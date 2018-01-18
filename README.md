# HOMEWORK
<b>อธิบายคำสั่งเบื้องต้นต่างๆ โดยใช้ GITHUB</b>
  <br>ก่อนจะเริ่มต้นการลงมือ ให้ทำตามขั้นตอนดังนี้ก่อน
  <br> 1. (ใช้ระบบปฏิิบัติการ LINUX) เปิดโปรแกรม <b>TERMINAL</b> ขึ้นมาเพื่อทำการเขียน Command ต่างๆ
  <br> 2. สร้างโฟลเดอร์ขึ้นมา 1 โฟลเดอร์ โดยใช้คำสั่ง <b><i>mkdir</i></b> แล้วตั้งชื่อโฟลเดอร์
  <br> 3. เข้าไปยังโฟลเดอร์ใหม่ที่สร้างขึ้นมา โดยใช้คำสั่ง <b><i>cd</i></b> ตามด้วยชื่อโฟลเดอร์ที่ตั้งเอาไว้
  <br> <strong>คำสั่ง</strong>
1. <b><i>echo</i></b> "# HOMEWORK" >> README.md <br>
  <b><i>echo</i></b> เป็นคำสั่งที่ใช้สำหรับการเขียนข้อความ ซึ่งในคำสั่งนี้เป็นการเขียนข้อความลงไปในไฟล์ที่ชื่อว่า README.md วิธีการสั่งให้บันทึกข้อความลงไปในไฟล์ จะตามหลังด้วยเครื่องหมาย >>
2.  <b><i>git init</i></b>
  <br> เป็นคำสั่งสำหรับสร้าง git repository ซึ่งมีนามสกุลเป็น .git
3.  <b><i>git add</i></b> README.md
  <br>เป็นคำสั่งที่ใช้ในการ track ไฟล์ โดย git สำหรับดูการเปลี่ยนแปลงต่างๆ
4.  <b><i>git status</i></b>
  <br>เป็นคำสั่งตรวจสอบสถานะของไฟล์นั่น ซึ่งสถานะมี 4 สถานะ คือ <br><b>Staged</b> : สถานะที่ไฟล์พร้อมจะ commit <br><b>unstaged</b> : ไฟล์ที่ถูกแก้ไขแต่ว่ายังไม่ได้เตรียม commit <br><b>untracked</b> : ไฟล์ที่ยังไม่ถูก track โดย Git <br><b>deleted</b> : ไฟล์ที่ถูกลบไปแล้ว
5.  <b><i>git config --global user.email "5835512011@psu.ac.th"</i></b>
  <br>เป็นคำสั่งที่ใช้เข้าใช้อีเมล์ของเรา เป็นการ setup ค่าของผู้ใช้
6.  <b><i>git config --global user.name "DanudetPanbo"</i></b>
  <br>เป็นคำสั่งที่ใช้เข้าใช้ชื่อของเรา เป็นการ setup ค่าของผู้ใช้เช่นกัน
7.  <b><i>git commit -m "first commit" git commit -m</i></b>
  <br>เป็นคำสั่งบันทึกการเปลี่ยนแปลงของไฟล์และค่า setup ต่างๆ
8. <b><i>git remote add origin https://github.com/DanudetPanbo/homeworkWEEK1.git </i></b>
  <br> เป็นคำสั่งชี้ที่อยู่ url ของ repository
9.  <b><i>git remote -v</i></b>
  <br> เป็นคำสั่งแสดง remote repository
10.  <b><i>git push -u origin master</i></b>
 <br> เป็นคำสั่งที่ใช้ในการส่งการเปลี่ยนแปลงไฟล์ไปที่ Github
 
 <pre><b>จัดทำโดย</b> นายดนุเดช ปานโบ </pre>
