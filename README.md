# th-digital-survival 🇹🇭🇹🇭🇹🇭

โครงการนี้มุ่งรวบรวมคู่มือและแนวทางปฏิบัติสำหรับการสื่อสารและการรับรู้ข่าวสารด้วยวิธีที่ปลอดภัย หลีกเลี่ยงและลดโอกาสได้รับผลกระทบจากภัยคุกคามต่างๆ ซึ่งรวมถึงการคุกคามโดยมิจฉาชีพ กลุ่มอันธพาล หรือเจ้าหน้าที่รัฐที่ปฏิบัติหน้าที่นอกขอบเขตที่กฎหมายอนุญาต และการดำเนินการใดๆ ที่ไม่สอดคล้องกับปฏิญญาสากลว่าด้วยสิทธิมนุษยชน (ที่ประเทศไทยได้ลงนาม)

ในเมื่อหน้าต่าง ประตูในบ้าน ไม่ได้มีไว้เพื่อให้ทำสิ่งที่ผิดกฎหมาย ทางเราเชื่อว่าการใช้อุปกรณ์ดิจิทัลทั้งหลายควรได้รับการป้องกันเสมือนหน้าต่าง ประตู ด้วยเช่นเดียวกัน

*สิ่งที่โครงการนี้จะไม่ทำคือชี้วิธีการในการฝ่าฝืนกฎหมาย อำนาจศาล หรืออำนาจที่ชอบธรรมของเจ้าหน้าที่รัฐในการทำงาน*

## แนวทาง

การพัฒนาข้อมูลชุดนี้จะทำในที่เปิดเผย ผ่าน GitHub และการสื่อสารหลักสำหรับระยะแรกจะทำผ่าน Issues tracker กับแอป Telegram (กดลิงก์โหลดแอป และกดลิงก์อีกครั้งเพื่อเข้าห้องได้เลยครับ https://t.me/joinchat/AgGs0ho9O29vjYsB0WvFig) ทุกคนสามารถเป็นอาสาสมัครมีส่วนร่วมและเสนอความคิดเห็นได้ หากคุณสนใจ แม้คิดว่าตัวเองไม่มีประสบการณ์หรือความเชี่ยวชาญพอ ไม่เป็นไรครับ เรายินดีต้อนรับ

## โปรเจกต์ต้องการอาสาสมัครดังนี้

* ผู้เชี่ยวชาญด้านความมั่นคงปลอดภัยทางดิจิทัล
* นักเขียน สำหรับคู่มือ
* นักแปล สำหรับ คู่มือ แอป บทความต่างๆ จากภาษาอังกฤษเป็นภาษาไทย
* คนทำกราฟฟิก อัดวีดีโอ ทำ voiceover เพื่อให้เข้าใจง่าย
* คนที่จะช่วยทดสอบและยืนยันความถูกต้องของคู่มือ
* คนที่ช่วยด้านการประชาสัมพันธ์

## ข้อมูลเบื้องต้น

![xkcd-crypto-th](https://user-images.githubusercontent.com/3682634/75450354-39a5df00-59a1-11ea-8c72-59ec66ec6133.png)\
ที่มา: [xkcd: Security](https://www.xkcd.com/538/)

ภาพแรก เราจะเห็นว่าในจินตนาการของนักต่อสู้ ผู้ร้ายสองคนกำลังคุยกัน เขาได้จับตัวประกันมาและจะถอดรหัสลับที่ปกป้องคอมพิวเตอร์ของตัวประกัน แต่ทำไม่ได้เพราะใช้รหัสแบบ 4096 บิต ตัวประกันปลอดภัย ภาพสอง เอาเข้าจริงๆ ถ้าเจอคอมพิวเตอร์ที่เข้ารหัสลับไว้ ผู้ร้ายจะเอาประแจมาทุบหัวจนกว่าตัวประกันจะบอกรหัสผ่าน

อย่าลืมนะครับว่าถ้าคุณหรือเพื่อนๆ กำลังจะเผชิญกับคนที่ยินดีที่จะใช้ความรุนแรง คุณต้องตัดสินใจเอาเองว่าสิ่งที่คุณกำลังจะทำอยู่นั้น คุ้มกับการเจ็บตัวหรือไม่

### ที่อยู่ไอพี (IP Address)

คอมพิวเตอร์ทุกเครื่องในอินเทอร์เน็ตจะมีที่อยู่ไอพี (IP address) ประจำเครื่อง ซึ่งจำเป็นในการรับส่งข้อมูล
- ที่อยู่ไอพีนี้เปรียบเหมือนเลขที่บ้าน เราส่งจดหมายหากันไม่ได้ ถ้าไม่ทราบที่อยู่ และระบบไปรษณีย์จะสับสน ถ้ามีบ้าน 2 หลังมีบ้านเลขที่เดียวกันบนถนนเดียวกัน ที่อยู่ไอพีก็เช่นกัน ที่โดยหลักการแล้วคอมพิวเตอร์ทุกเครื่อง อุปกรณ์ทุกตัว ที่เชื่อมกับอินเทอร์เน็ต จะมีที่อยู่ไอพีเฉพาะของตัวเอง ไม่ซ้ำกัน หรือมีวิธีที่ทำให้จำแนกได้ว่าเครื่องไหนเป็นเครื่องไหน
- ถ้าอยากเห็นว่า ที่อยู่ไอพีของเครื่องที่เราใช้อยู่ตอนนี้คืออะไร ให้ลองเข้าไปที่ https://whatismyipaddress.com/
  - เห็นตัวเลข IPV6 กับ IPV4 ไหมครับ เช่น IPv6: 4321:4321:bc81:3a0f:74be:fbbd:8c35:4821 IPv4: 184.22.234.55
  - ลองเปิดหน้านี้จากอุปกรณ์หลายตัวกับการเชื่อมต่อหลายประเภทดูครับ (เช่น wifi หรือ 4G ฯลฯ) แล้วคุณจะเห็นที่อยู่ของตัวเองในอินเทอร์เน็ต
- ส่วนถ้าอยากเห็นว่า เว็บไซต์หรือบริการที่เราใช้ มีที่อยู่ไอพีอะไร ให้ลองไปที่ https://www.dnslookup.com แล้วใส่ www.google.com จะเห็นที่อยู่ไอพีของบริการเหล่านั้น
- เวลาคอมพิวเตอร์ของเรากับคอมพิวเตอร์ปลายทางสื่อสารกัน ก็จะใช้ที่อยู่ไอพีเหล่านี้ เพื่อระบุว่า ใครหรือที่อยู่ไอพีไหนขอข้อมูลเข้ามา จะได้ส่งข้อมูลกลับไปได้ถูกที่ที่อยู่ดังกล่าว

ที่อยู่ไอพี คือร่องรอยหนึ่งในการสื่อสาร
- ผู้ให้บริการอินเทอร์เน็ตทั้งหลาย รวมถึงร้านกาแฟ โรงเรียน ห้างสรรพสินค้า หน่วยงาน ฯลฯ จะมีการเก็บข้อมูลว่าที่ไอพีไหน ใครใช้ เมื่อเวลาใด
- กระทั่งในการส่งอีเมลก็จะมีข้อมูลที่อยู่ไอพีพ่วงอยู่ในหีบห่อของอีเมล
- ถ้าคุณได้รับข้อความเข้ามาในกลุ่มไลน์ แล้วข้อความนั้นมีลิงก์ และคุณเปิดลิงก์ดังกล่าว เจ้าของเว็บไซต์ก็จะรู้ว่ามีใครจากที่อยู่ไอพีอะไร เข้ามาทำธุรกรรม หรือเข้าไปอ่านหน้าอะไรกันแน่

### ข้อมูลที่ส่งบนเน็ตก็เหมือนโปสการ์ด

อินเทอร์เน็ตที่เราใช้อยู่ทุกวันนี้ อยู่บนฐานของเทคโนโลยีจากหลายสิบปีที่แล้ว ในสมัยที่ผู้ใช้อินเทอร์เน็ตยังมีไม่มากและการเชื่อมต่ออินเทอร์เน็ตยังไม่ได้แพร่หลายทั่วไปเท่าทุกวันนี้ 
- การจะใช้อินเทอร์เน็ตได้จะต้องเป็นเจ้าหน้าที่หรือพนักงานขององค์กรรัฐ ศูนย์วิจัย หรือสถานศึกษา และต้องขอให้ผู้ดูแลระบบช่วยสร้างบัญชีให้ ดังนั้น เราพอจะกล่าวได้ว่า เราพอจะตามตัวกันได้ว่าใครเป็นใครบนอินเทอร์เน็ต
- และสิ่งที่ส่งหากันบนอินเทอร์เน็ตในสมัยนั้น ก็มักเป็นการแลกเปลี่ยนความคิดเห็นเชิงสาธารณะ (ทำนองเว็บบอร์ด) หรือเอกสารงานวิจัย ที่มีจุดประสงค์ปลายทางเพื่อเผยแพร่สู่สาธารณะอยู่แล้ว การทำธุรกรรมซื้อของจ่ายเงินต่างๆ ยังไม่เกิดขึ้น หรือยังคิดไปไม่ถึง
- นอกจากนี้ การออกแบบเทคโนโลยีรับส่งข้อมูลในยุคนั้นก็มีข้อจำกัดด้านความเร็วการส่งข้อมูลที่ช้ากว่าปัจจุบันมาก รวมถึงราคาของอุปกรณ์จัดเก็บช้อมูลที่ยังมีราคาแพงมาก ทำให้ความสามารถด้านความปลอดภัย เช่น การเข้ารหัสลับ เป็นสิ่งที่ฟุ่มเฟือยเกินความจำเป็นในขณะนั้น
- บริบทเหล่านี้ เป็นสมมติฐานและข้อจำกัดส่วนหนึ่งของการออกแบบอินเทอร์เน็ต ทำให้วิธีการรับส่งข้อมูลบนอินเทอร์เน็ตในตอนเริ่มแรกไม่ได้คำนึงถึงความปลอดภัยมากนัก ความเชื่อใจในตัวระบบอินเทอร์เน็ตมาจากความเชื่อใจในระบบกรองคนของตัวองค์กรต่างๆ ไม่ได้มีความปลอดภัยตัวด้วยตัวเทคโนโลยีเอง

การส่งข้อมูลบนอินเทอร์เน็ตเทียบได้กับการส่งไปรษณียบัตรหรือโปสการ์ด ที่เราเขียนที่อยู่และเนื้อความลงบนกระดาษแผ่นเดียวกัน และไม่ได้ใส่ซอง 
- เพราะในตอนที่ออกแบบอินเทอร์เน็ตสมัยนั้น ซองเป็นสิ่งไม่จำเป็นหรือไม่คุ้มค่า เมื่อเทียบกับราคาในการจัดหาซองและค่าใช้จ่ายที่เพิ่มขึ้นจากน้ำหนักของซอง
- ทุกในระบบไปรษณีย์สามารถอ่านเนื้อความบนโปสการ์ดได้ ตั้งแต่คนไขตู้ คนที่ที่ทำการไปรษณีย์ต้นทาง คนและเครื่องที่ศูนย์คัดแยก คนที่ที่ทำการไปรษณีย์ปลายทาง พนักงานไปรษณีย์ที่ทำโปสการ์ดไปส่งที่บ้าน กระทั่งเมื่อถึงบ้านแล้ว ถ้าในบ้านนั้นมีคนอยู่กันหลายคน ทุกคนในบ้านก็อ่านเนื้อความได้หมด ไม่เฉพาะคนที่มีชื่ออยู่บนจ่าหน้า
- กล่าวคือ ไม่ใช่เพียงคนเขียนต้นทาง และคนรับปลายทางเท่านั้น ที่จะรู้ได้ว่าเนื้อความเป็นอะไร แต่ทุกคนที่อยู่ระหว่างทางก็รู้ได้หมด

สมมติฐานที่เราเคยใช้ออกแบบอินเทอร์เน็ตนั้น อาจจะเคยจริง แต่มันไม่ได้จริงอีกต่อไปแล้ว
- ทุกวันนี้ใครๆ ก็เข้าถึงอินเทอร์เน็ตได้ โดยไม่ต้องขออนุญาตใครหรือองค์กรใด ซึ่งก็รวมถึงคนที่มีเจตนาร้ายด้วย
- เราใช้อินเทอร์เน็ตกับเรื่องส่วนตัวมากขึ้น ทั้งเพื่อเรื่องการศึกษา ความก้าวหน้าในอาชีพการงาน ความบันเทิง การจับจ่ายใช้สอย ไปจนถึงการหาคู่
- ข้อมูลที่เราส่งบนอินเทอร์เน็ต ซึ่งรวมถึงข้อมูลพฤติกรรมที่เราอาจจะไม่ตั้งใจส่งหรือไม่รู้ตัวด้วยซ้ำว่ากำลังส่งอยู่ ที่เป็นข้อมูลส่วนบุคคลหรือไม่ควรเปิดเผยกับสาธารณะมีจำนวนมากขึ้นเรื่อยๆ
- จากการเก็บข้อมูลการจราจรเพียงอย่างเดียว ผู้ให้บริการอินเทอร์เน็ตสามารถรู้พฤติกรรมเราได้ เช่น หากในช่วงนี้เรากำลังเข้าเว็บไซต์เกี่ยวกับการคุมกำเนิด ยาคุมฉุกเฉิน หรือการทำแท้ง อย่างซ้ำๆ หรือเข้าเว็บไซต์คะแนนสอบเข้ามหาวิทยาลัยย้อนหลัง เว็บไซต์เตรียมสอบอย่างสม่ำเสมอ ผู้ให้บริการอินเทอร์เน็ตสามารถจำแนกได้ว่าเรากำลังทำอะไรหรือกังวลเรื่องอะไร ยิ่งถ้าเว็บไซต์ดังกล่าวเป็นเว็บไซต์ของที่ทำงาน ที่คนรู้จักไม่มาก (เช่นเป็นเว็บไซต์ให้พนักงานล็อกอินเข้าไปทำงาน) ผู้ให้บริการอินเทอร์เน็ตอาจถึงขนาดรู้ได้ว่าเราทำงานอะไร หรือขยันทำงานแค่ไหน

การเข้ารหัสลับข้อมูล คือการนำโปสการ์ดเหล่านั้นมาใส่ซอง เพื่อให้มีเฉพาะผู้รับที่ผู้ส่งตั้งใจจะให้อ่านอ่านได้คนเดียวเท่านั้น
- ในกรณีของการใช้เว็บไซต์ การเข้ารหัสลับแบบ HTTPS ที่เว็บไซต์หลักๆ ในปัจจุบันใช้กันแพร่หลาย ช่วยเพิ่มความปลอดภัยของข้อมูลได้ โดยคนที่อยู่ระหว่างทาง (เข่นผู้ให้บริการในการเชื่อมต่ออินเทอร์เน็ต) จะไม่สามารถรู้ได้ว่าเนื้อหาในหน้าเว็บคืออะไร โดยจะรู้ได้เพียงว่าผู้ใช้เข้าไปที่เว็บไซต์ชื่อโดเมนอะไร
  - อย่างไรก็ตาม ชื่อโดเมนของบางเว็บไซต์ก็อาจจะบอกอะไรบางอย่างในตัวมันเอง โดยไม่จำเป็นต้องเห็นข้อมูลในหน้าเว็บเลย
- ในกรณีของอีเมลแบบเข้ารหัสลับ ผู้ให้บริการอินเทอร์เน็ตจะยังสามารถเห็นสิ่งที่อยู่บนซองได้ ทั้งที่อยู่ผู้ส่ง ที่อยู่ผู้รับ และสิ่งอื่นๆ เช่น "วงเล็บมุมซอง" ข้อมูลบนซองเหล่านี้เป็นสิ่งที่การเข้ารหัสลับอีเมลไม่สามารถช่วยปกปิดได้
  - ช่อง "subject" ในอีเมล เทียบได้กับ "วงเล็บมุมซอง" ดังนั้นในการส่งอีเมลเข้ารหัสลับ ในช่อง subject นี้ไม่ควรเขียนเรื่องที่ไม่ต้องการเปิดเผย
- ปัจจุบันมีแอปสื่อสารที่ช่วยเข้ารหัสลับข้อความให้เราแบบง่ายๆ มากมาย ลองดูในส่วน "รายการเครื่องมือ"


## รายการเครื่องมือ

### Chat
* [Signal](https://signal.org/) คล้าย LINE / WhatsApp ที่มีการเข้ารหัสลับในการสื่อสาร แต่มีการออกแบบที่คำนึงถึงความปลอดภัยมากกว่า โดยใช้หมายเลขโทรศัพท์แทนชื่อผู้ใช้
* [Ricochet](https://ricochet.im/) ด้วยการใช้เครือข่าย Tor และการสร้างบริการ Onion Service ซึ่งปกปิดตำแหน่งที่ตั้ง Ricochet เป็นแอปรับส่งข้อความด่วนที่อนุญาตให้คุณแชตได้โดยยังคุ้มครองความเป็นส่วนตัวและยังคงความเป็นนิรนามของคุณอยู่ เนื่องจากมันจะไม่เปิดเผยที่ตั้งหรือที่อยู่ไอพีของคุณ คุณจะไม่รู้สึกแตกต่างจากการแชตที่ไม่ปลอดภัย นอกจากการที่คุณจะใช้ที่อยู่ที่ไม่ซ้ำใครชุดหนึ่ง แทนที่จะใช้หมายเลขโทรศัพท์ อีเมล หรือชื่อผู้ใช้
* [Briar](https://briarproject.org/) ใช้กับ Android เท่านั้น ความปลอดภัยสูงมาก สามารถสื่อสารระหว่างอุปกรณ์ได้โดยตรง ไม่ต้องใช้อินเทอร์เน็ต (เหมาะกับกรณีที่เน็ตถูกตัด)

### คู่มือ
* 🇹🇭[คู่มือพลเมืองเน็ต: เข้าใจเน็ต และใช้เน็ตให้ปลอดภัย](https://thainetizen.org/docs/netizen-handbook-safe-internet/)
* 🇹🇭🇺🇸[การป้องกันตัวเองจากการถูกสอดส่อง: เคล็ดลับ เครื่องมือ และวิธีการติดต่อสื่อสารทางออนไลน์อย่างปลอดภัยยิ่งขึ้น](https://ssd.eff.org/th)
* 🇹🇭🇺🇸[อุปกรณ์และกลวิธีการรักษาความปลอดภัยทางดิจิตอล](https://securityinabox.org/th/) เก่าหน่อยแต่เขียนได้ดี
* 🇺🇸[Umbrella](https://secfirst.org/umbrella/) (ต้องการอาสาสมัครมาช่วยแปล)
* 🇺🇸[Digital Security Resources](https://www.frontlinedefenders.org/en/digital-security-resources) รวมลิงก์คู่มือต่างๆ เกี่ยวกับความปลอดภัยดิจิทัล
