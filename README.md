# ใบงานที่ 3 ทำงานกับ git clients

## แนะนำใบงาน

ใบงานนี้จะพานักศึกษามาทำความรู้จักกับ git clients ซึ่งจะใช้ระบบปฏิบัติการ Windows 10-11 เป็นหลัก นักศึกษาที่ใช้ OS อื่นๆ สามารถนำแนวทางไปใช้ได้ตามลักษณะเฉพาะของ OS นั้นๆ

เนื่องจาก git เป็นโปรแกรมควบคุมรุ่นที่ยิยมใช้อย่างแพร่หลาย จึงมี git client ให้เลือกใข้ได้หลายตัว  ทั้งชนิดที่เป็น stand alone เช่น  git bash, Github Desktop และชนิดที่ integrated เข้ากับ IDE ต่างๆ เช่น Visual studio, Visual Studio Code, Eclipse based IDEs เป็นต้น

### 1. Git Clients แบบ stand alone

#### 1.1 Git bash

<img src="https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png" width="120"/>

Git bash เป็นโปรแกรม GNU Bash ตัวหนึ่งที่มีลักษณะเป็น Terminal ที่รองรับคำสั่ง git command line interface มีให้ใช้ทั้งบน Windows, macOS และ Linux/Unix  ดูรายละเอียดได้จาก <https://git-scm.com/>

<img src="Pictures/pic-01.png"/>


#### 1.2 Git GUI Clients

เมื่อเราติดตั้ง gitbash จะมีโปรแกรมอีกตัวที่เป็น GUI ติดมาด้วย (ชื่อว่า Git GUI) โดยจะมีส่วนติดต่อผู้ใช้แบบกราฟฟิกส์ สำหรับการ commit, push, pull และอื่น ๆ  

__ตัวอย่างโปรแกรม git GUI__
1. เรียกโปรแกรม git GUI และเปิด repository ที่เคยได้ clone ไว้ใน harddisk

<img src="Pictures/pic-02.png"/>

2. ลักษณะของโปรแกรม git GUI ที่มาพร้อมกับ git bash

<img src="Pictures/pic-03.png"/>

นอกจาก git GUI แล้วยังมีโปรแกรม git GUI Clients อีกหลายตัว ทั้งชนิดที่ฟรีและมีค่าใช้จ่ายสำหรับหารซื้อ License (ดูรายละเอียดได้ที่ https://git-scm.com/downloads/guis และ https://git.wiki.kernel.org/index.php/InterfacesFrontendsAndTools)

#### 1.3 Github Desktop

Github Desktop เป็น git GUI ที่พัฒนาโดย Github สามารถทำงานกับ repository ได้เทียบเท่ากับ git bash ไม่ว่าจะเป็นการ push, pull, clone, commit, pull request เป็นต้น (แต่การแก้ปัญหาที่ซับซ้อนบางอย่างยังจำเป็นต้องใช้ command line interface อยู่)  ดูรายละเอียดได้ที่ <https://desktop.github.com>  

<img src="https://desktop.github.com/images/github-desktop-screenshot-windows.png"/>

### 2. Git ที่ Intergrated ร่วมกับ IDE อื่น ๆ

#### 2.1 Git สำหรับ Visual studio

Git สำหรับ Visual studio เป็น extension ที่ติดตั้งบน Microsoft Visual Studio ที่ช่วยอำนวยความสะดวกในการทำงานกับ git ได้อย่างราบรื่นและรวดเร็ว สามารถศึกษาเพิ่มเติมได้จาก <https://learn.microsoft.com/en-us/visualstudio/version-control/git-with-visual-studio?view=vs-2022> หรือ <https://visualstudio.microsoft.com/vs/github/>

<img src="https://visualstudio.microsoft.com/wp-content/uploads/2021/08/image4.jpg">

