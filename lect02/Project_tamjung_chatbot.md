// https://github.com/kulwadeelab/cpe6302-fund2/tree/main/lect02

# Project: ถามจังแชทบอท

## ผลลัพธ์การเรียนรู้

* พื้นฐานการเขียนโปรแกรมภาษาจาวา
* การใช้ variables, conditions, loops, และ methods
* การสร้างคลาสเบื้องต้น

## Specification: ถามจังแชทบอท

* โต้ตอบกับผู้ใช้งานผ่าน Command-line interface

* ทักทาย ถามคำถาม กับผู้ใช้งาน ตามตัวอย่าง ต่อไปนี้



สวัสดี! ฉันชื่อ [botName] 

ฉันถูกสร้างขึ้นเมื่อปี [createdYear]

เธอชื่ออะไร?

&gt; Chin-chan 


สวัสดี [Chin-chan]! 

ฉันจะเดาว่าเธออายุเท่าไหร่

ช่วยบอก เศษที่ได้จากการหารอายุของเธอด้วย 3 5 และ 7

&gt; 1

&gt; 2 

&gt; 1

เธออายุ 22: เป็นช่วงอายุที่น่าสนุกมากของชีวิตเลย! 


ตอนนี้ ฉันจะแสดงให้เธอเห็นว่าฉันนับเลข 1-100ได้นะ 

เธอต้องการให้ฉันนับถึงเลขอะไร?

&gt; 5

1!

2!

3!

4!

5!

ฉันขอทดสอบความรู้เกี่ยวกับการเขียนโปรแกรมของเธอหน่อยนะ

ทำไมเราถึงต้องใช้ method?

ก. เพื่อรันคำสั่งซ้ำหลาย ๆ ครั้ง

ข. เพื่อแบ่งโปรแกรมออกเป็น subroutine เล็กๆ หลายๆ รูทีน

ค. เพื่อวัดเวลาการรันโปรแกรม

ง. เพื่ออินเตอร์รัพการทำงานของโปรแกรม

&gt; ก

ผิด! ลองใหม่อีกครั้งนะ

&gt; ข.

ยินดีด้วย เธอตอบถูก!


### สมการเดาอายุ

age = (rem3 * 70 + rem5 * 21 + rem7 * 15) % 105

เมื่อ 

- rem3 คือ เศษที่เหลือจากการหารอายุด้วย 3

- rem5 คือ เศษที่เหลือจากการหารอายุด้วย 5

- rem7 คือ เศษที่เหลือจากการหารอายุด้วย 7

