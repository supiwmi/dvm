# Talk to Senior Division Manager

# การจัดการ Version Control System ด้วย Git
เราจะใช้ git ในการทำ  version control กับพวก source code หรือ documents ต่างๆได้
การที่จะทำแบบนั้นได้เราต้องมี 2
1. โปรแกรม git ที่คอยจัดการ version control system - ส่วนใหญ่จะใ้ช้เป็นแบบ local คือ install ที่เครื่อง Notebook/PC 
   ดูตัวอย่างได้ที่นี่ https://phoenixnap.com/kb/how-to-install-git-windows 
2. Remote version control system ซึ้งมีมากมายแล้วแต่ว่าใครจะอยากใช้แบบไหน มีทั้งแบบ ฟรีและเสียเงิน หรือ จะทำเป็นแบบ private server เช่น GitLab ก็ได้
  เราจะใช้ GitHUb ทีมี developer มากกว่า 65 ล้านคนใช้เพือ hosting for software development and version control using Git
  - ถ้ายังไม่เคยมี github account สมัครและใช้ฟรีได้ที่นี https://github.com/

**DevOps from Development to Deployment/Production นี้ ผู้เข้าอบรมจะได้ลงมือปฏิบัติอย่างจริงจัง โดยเริ่มตั้งแต่**

1. การจัดการ Version Control System ด้วย Git
2. การ deploy application แบบ container ด้วย Docker, Kubernetes และ Helm
3. การทํา CI/CD ด้วย Jenkins

โดย Workshop ทั้งหมดจะทําในรูปแบบของ step-by-step ด้วย Infrastructure as Code

# Recommend Tools ที่ควร install ที่เครื่อง Laptop/PC ถ้าเป็นไปได้

1. Install and Use Visual Studio Code on Windows 10

   - ตัวอย่างใน Youtube https://www.youtube.com/watch?v=MlIzFUI1QGA
   - ดูวิธีการติดตั้งได้ที่นี่ Setting up Visual Studio Code  https://code.visualstudio.com/docs/setup/setup-overview

2. ติดตั้ง Windows Subsystem for Linux เพื่อให้ใช้ คำสั่ง Windows และ Linux ได้ในเครื่องเดียวกัน

   - ดูวิธีการติดตั้งได้ที่นี่ https://docs.microsoft.com/en-us/windows/wsl/install-win10

3. ติดตั้ง Oracle VM VirtualBox ช่วยให้เรา develop และเรียกใช้ระบบปฏิบัติการหลายระบบ(Windows/Linux/ etc) ในอุปกรณ์เดียว
   เหมือนกับว่าเรามี local cloud ในเครื่อง PC เราเลย
   
   - ดูวิธีการติดตั้งได้ที่นี่  https://www.virtualbox.org/manual/ch01.html#intro-starting
