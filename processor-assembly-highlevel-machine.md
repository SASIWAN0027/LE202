# ภาษาเครื่อง(Machine  Language)
- เป็นภาษาโปรแกรมที่สั่งให้คอมพิวเตอร์ทำงานได้โดยตรง องค์ประกอบของภาษาเครื่องจะประกอบด้วยเลข 0และ1 หรือระบบเลขฐานสอง เมื่อส่งให้คอมพิวเตอร์ คอมพิวเตอร์สามารถเข้าใจได้ โปรแกรมที่ได้จากภาษานี้จึงเป็นกลุ่มรหัสคำสั่งของตัวเลขล้วนๆ ที่เรียงต่อกันดังนั้นโปรแกรมภาษาเครื่องจึงมีความยุ่งยากเป็นอย่างยิ่งเนื่องจากอยู่ในรูปแบบหรือสัญลักษณ์ที่เราไม่คุ้นเคย   
# ภาษาระดับต่ำหรือภาษาแอสเซมบลี(Low level language) 
- ภาษาระดับต่ำเพียงภาษาเดียวคือภาษาแอสเซมบลี ใช้สัญลักษณ์แทนการใช้รหัสตัวเลขที่ใช้ในภาษาเครื่องทำให้การเขียนโปรแกรมมีความสะดวก ทำงานได้เร็วและเข้าใจง่ายกว่าภาษาเครื่อง แต่คอมพิวเตอร์เข้าใจเพียงภาษาเครื่องเท่านั้น จึงต้องทำการแปลจากภาษาแอสเซมบลีให้เป็นภาษาเครื่องก่อน จึงจะสามารถนำไปใช้ควบคุมคำสั่งการให้เครื่องทำงานได้  โดยใช้ระบบโปรแกรมแปลภาษาซึ่งเรียกว่า  Translator Program โปรแกรมแปลภาษาของแอสเซมบลีจะมีชื่อเฉพาะของมันว่า แอสเซมเบลอร์(ASSEMBLER)   
# ภาษาระดับสูง(High level language)
- เป็นภาษาที่มีลักษณะใกล้เคียงกับสัญลักษณ์ต่างๆที่มนุษย์คุ้นเคย เช่นคำในภาษาอังกฤษและสัญลักษณ์ทางคณิตศาสตร์ จึงทำให้สะดวกต่อการใช้งานมากขึ้น เป็นภาษาที่นิยมใช้อย่างกว้างขวางในปัจจุบัน ข้อดีของภาษาระดับสูงคือเป็นภาษาที่ไม่ผูกพันหรือขึ้นตรงกับตัวเครื่อง ดังนั้นผู้เขียนโปรแกรมสามารถเขียนได้อย่างอิสระภายใต้กฎเกณฑ์ของภาษานั้น ๆ โดยไม่จำเป็นต้องมีความรู้ทางฮาร์ดแวร์ ก็สามารถใช้ประโยชน์ได้  เมื่อจะนำไปใช้ควบคุมสั่งการเครื่องก็ต้องนำไปแปลเป็นภาษาเครื่องก่อนโปรแกรมที่ใช้แปลภาษาระดับสูงให้เป็นภาษาเครื่องคือ คอมไพเลอร์ (Compiler)หรืออินเตอร์พริทเตอร์ (Interpreter) ภาษาระดับสูงเช่น ภาษาปาสคาล (PASCAL)  ภาษาซี (C) ภาษาโคบอล (COBOL) ภาษาเบสิก(BASIC)
# โปรเซสเซอร์(Processor) 
- เป็นองค์ประกอบที่สำคัญส่วนหนึ่งของเครื่องคอมพิวเตอร์ทุกประเภทในโลก เปรียบเสมือนกับเป็นมันสมองให้กับคอมพิวเตอร์นั่นเอง ประกอบไปด้วยวงจรทางไฟฟ้ามากมาย ที่อยู่บนแผ่นซิลิกอนซิป ซึ่งมีขนาดเล็กมาก ๆ
- ไมโครคอนโทรลเลอร์คือ อุปกรณ์ควบคุมขนาดเล็ก ซึ่งบรรจุความสามารถท่ีคล้ายคลึงกับระบบคอมพิวเตอร์ โดยในไมโครคอนโทรลเลอร์ได้รวมเอาซีพียู, หน่วยความจำและพอร์ตซึ่งเป็นส่วนประกอบหลักสำคัญของระบบคอมพิวเตอร์เข้าไว้ด้วยกัน โดยการบรรจุเข้าไว้ในตัวถังเดียวกัน
# เปรียบเทียบความสัมพันธ์
- ตัวอย่างที่1 High level language คือ ภาษาซี(C) , Processor คือ RISC-V rv64gc clang 12.0.0 จะได้
assembly คือ
![image](https://user-images.githubusercontent.com/98944081/161817761-687e260d-b6f8-4e86-b845-8113c046bfc1.jpeg)
Machine language คือ
![image](https://user-images.githubusercontent.com/98944081/161818081-d7703b92-babc-4cbe-acb9-26370b660049.jpeg)
- ตัวอย่างที่2 High level language คือ ภาษาซีพลัสพลัส(C++) , Processor คือ mips64 gcc 5.4 จะได้
assembly คือ
![image](https://user-images.githubusercontent.com/98944081/161818463-196d70b7-087a-4b6b-bfc3-d67d657a1461.jpeg)
Machine language คือ
![image](https://user-images.githubusercontent.com/98944081/161818673-d0cc7b33-7f4c-4e86-bd27-376f414291f0.jpeg)



  
