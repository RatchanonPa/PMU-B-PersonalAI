# **𝗣𝗠𝗨-𝗕 𝗣𝗲𝗿𝘀𝗼𝗻𝗮𝗹𝗔𝗜 🤖**

## **🔎 WORK COLLECTIONS**  
### **Overview of AI-powered Applications and Innovations**  
**Class** | **Name** | **Workshop** | **Lecture**
--- | --- | --- | ---
1 | xPore: An AI-Powered App for Bioinformaticians | [Gaussian mixture model](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/GMM.ipynb) | [Lecture1](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Lecture/xPore.pdf)
2 | Learning from Biosignal | [1D CNN for brain signal](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/model.py) | [Lecture2](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Lecture/Biosignals.pdf)
3 | AI for detecting code plagiarism | [Code2Vec to detect code clone](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/PMU_B_CodingAI_CodeCloneDetection_Workshop.ipynb) | [Lecture3](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Lecture/Code%20plagiarism%20.pdf)
4 | Mental disorder detection from social media data | [NLP classifcation](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Workshop_NLPclassifcation.ipynb) | [Lecture4](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Lecture/Mental%20disorder.pdf)
5 | BiTNet: AI for diagnosing ultrasound image | [EffcientNet: Image Classifcaiton](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Workshop_PMUB_Personal_AI_Image_classification_EfficientNetB5.ipynb) | [Lecture5](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Lecture/BitNet.pdf)
6 | AI for arresting criminals | [Yolo Detection // Face recognition](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Train_Yolov8_Object_Detection_on_Custom_Dataset.ipynb) | [Lecture6](https://github.com/RatchanonPa/PMU-B-PersonalAI/blob/main/Lecture/ObjectDetection.pdf)

---
## **🚀 COURSE HIGHLIGHTS**  

### **COURSE 1: xPore: An AI-Powered App for Bioinformaticians🧬**  
**xPore** เป็นซอฟต์แวร์ที่ช่วยเปรียบเทียบตำแหน่งและลักษณะของ **RNA Modifications** บนลำดับเบสของ RNA ระหว่างตัวอย่าง เช่น ผู้ป่วยมะเร็งกับคนปกติ โดยใช้ข้อมูลจาก **Nanopore Sequencer** ซึ่งสามารถตรวจสอบลำดับ RNA ได้โดยตรง ซอฟต์แวร์นี้ช่วยนักชีวสารสนเทศในการวิเคราะห์ตำแหน่งที่แตกต่างกันของ RNA เพื่อสนับสนุนงานวิจัยในด้านการวินิจฉัยโรค การพัฒนายา วัคซีน และการจำแนกไวรัส  

**ข้อดี**  
- ช่วยลดเวลาทดลองในห้องแล็บจากหลายวันเหลือเพียงไม่กี่ชั่วโมง  
- ประหยัดต้นทุนและทรัพยากร  
- มีความน่าเชื่อถือและรวดเร็ว  

**สถานะปัจจุบัน**  
xPore เป็น Python Package เปิดให้ใช้ฟรีตั้งแต่ปี 2021 (v1.0) และพัฒนาถึงเวอร์ชัน 2.1 โดยมียอดดาวน์โหลดกว่า 27,000 ครั้ง

---

### **COURSE 2: Learning from Biosignal 🧠**  
**TinySleepNet** เป็นแบบจำลองการเรียนรู้เชิงลึก (Deep Learning Model) สำหรับวิเคราะห์ **Sleep Stage Scoring** โดยใช้คลื่นสัญญาณสมอง (EEG) ซึ่งพัฒนาขึ้นภายใต้โครงการ **Learning from Biosignals**  

**วัตถุประสงค์**  
1. **เพิ่มประสิทธิภาพ** ในการสกัดคุณลักษณะจากคลื่นสมองเพื่อวิเคราะห์การนอนอย่างแม่นยำ  
2. **สร้างต้นแบบ** แบบจำลองที่สามารถติดตั้งในอุปกรณ์พกพา เพื่อใช้วิเคราะห์การนอนของผู้ป่วยที่บ้าน  
3. **ลดภาระงาน** ของผู้เชี่ยวชาญในการให้คะแนนการนอน  

**สถานะปัจจุบัน**  
- งานวิจัยจาก TinySleepNet ถูกอ้างอิงมากกว่า 100 ครั้งโดยนักวิจัยทั่วโลก  
- เผยแพร่เป็น Open Source บน GitHub 

---

### **COURSE 3: AI for detecting code plagiarism 💻**   
**Code Clone Detector** เป็นระบบ AI สำหรับตรวจจับความเหมือนของโค้ดและการคัดลอกโค้ด (**Plagiarism Detection**)  

**วัตถุประสงค์**  
1. ช่วยนักพัฒนาซอฟต์แวร์ค้นหาโค้ดที่ซ้ำกัน เพื่อปรับปรุงคุณภาพซอฟต์แวร์  
2. ช่วยครู/อาจารย์ตรวจจับการลอกงานของนักเรียน/นักศึกษาได้อย่างรวดเร็วและแม่นยำ แม้โค้ดจะถูกแก้ไขบางส่วน  

**จุดเด่น**  
- ใช้ AI ในการตรวจจับ ทำให้ค้นหาโค้ดที่คล้ายกันได้อย่างมีประสิทธิภาพ  
- ลดภาระงานของผู้ใช้งาน  

**สถานะปัจจุบัน**  
ระบบ **Merry** เปิดให้ทดลองใช้งานได้ฟรี 

---

### **COURSE 4: Mental Disorder detection from Social Media Data 📝**   
**Predicting Mental Health Disorders from Social Media Data** เป็นโครงการวิจัยที่ใช้ข้อมูลจากสื่อสังคมออนไลน์ เช่น Facebook, Twitter, Instagram เพื่อทำนายโรคซึมเศร้า  

**วัตถุประสงค์**  
1. รวบรวมและวิเคราะห์โพสต์ที่แสดงถึงความรู้สึกและสถานะจิตใจของผู้ใช้งาน  
2. ทำนายโรคซึมเศร้าด้วยความแม่นยำ  
3. ใช้ข้อมูลที่ได้เพื่อระบุผู้ที่มีความเสี่ยงและให้การสนับสนุนที่เหมาะสม  

**ความสำคัญ**  
- ช่วยป้องกันและลดผลกระทบจากโรคซึมเศร้าผ่านการใช้เทคโนโลยี  
- สนับสนุนการดูแลสุขภาพจิตในวงกว้าง    

---

### **COURSE 5: BiTNet AI for diagnosing ultrasound image 📷**  
**BitNet** เป็นระบบ AI ที่ช่วยคัดกรองความผิดปกติในช่องท้องส่วนบนจากภาพถ่ายอัลตราซาวน์  

**วัตถุประสงค์**  
1. ลดภาระงานของรังสีแพทย์ในการวินิจฉัยภาพถ่ายอัลตราซาวน์จากแพทย์เวชปฏิบัติที่คัดกรองผู้ป่วยมะเร็งท่อน้ำดี  
2. เพิ่มความมั่นใจในการวินิจฉัยของแพทย์เวชปฏิบัติ  

**จุดเด่น**  
- วินิจฉัยความผิดปกติได้กว่า **25 ชนิด** เช่น ไขมันพอกตับ, ตับแข็ง, นิ่วในถุงน้ำดี เป็นต้น  
- ถูกใช้งานจริงในโรงพยาบาลเครือข่ายกว่า **200 แห่ง** ทั้งในภาคอีสาน, ภาคเหนือ และ สปป.ลาว  
---

### **COURSE 6: AI for arresting criminals 👮‍♂️💻**
**Real-Time Object Detection** เป็นโครงการที่พัฒนาเทคโนโลยีปัญญาประดิษฐ์เพื่อช่วยตำรวจในการติดตามและจับกุมผู้ต้องสงสัยคนร้าย  

**วัตถุประสงค์**  
1. **เพิ่มประสิทธิภาพ** การจัดเก็บและตรวจสอบข้อมูลอาชญากรรมด้วย AI  
2. **สร้างความปลอดภัย** สร้างความเชื่อมั่นให้ประชาชน 

---

## **Presentation Video🎤👋​**
> https://youtu.be/eoZC8IFJMWk?si=KKTJTWiFxJoLZ2A0
