# **𝗣𝗠𝗨-𝗕 𝗣𝗲𝗿𝘀𝗼𝗻𝗮𝗹𝗔𝗜 🤖**

## **🔎 WORK COLLECTIONS**  
### **Overview of AI-powered Applications and Innovations**  
**Class** | **Name** | **Workshop** | **Lecture**
--- | --- | --- | ---
1 | xPore: An AI-Powered App for Bioinformaticians | [Gaussian mixture model](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Workshop_GMM.ipynb) | [Lecture1](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Lecture/Lecture_Xpore%20.pdf)
2 | Learning from Biosignal | [1D CNN for brain signal](https://github.com/punramon/PMU-B-PersonalAI/blob/main/model.py) | [Lecture2](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Lecture/Lecture_learning_from_biosignals.pdf)
3 | AI for detecting code plagiarism | [Code2Vec to detect code clone](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Workshop_CodeCloneDetection.ipynb) | [Lecture3](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Lecture/Lecture_CodeClone.pdf)
4 | Mental disorder detection from social media data | [NLP classifcation](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Workshop_NLPclassifcation.ipynb) | [Lecture4](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Lecture/Lecture_AI%20for%20Detecting%20Users%20with%20Mental%20Disorders%20from%20Social%20media.pdf)
5 | BiTNet: AI for diagnosing ultrasound image | [EffcientNet: Image Classifcaiton](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Workshop_PMUB_Personal_AI_Image_classification_EfficientNetB5.ipynb) | [Lecture5](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Lecture/Lecture_BitNet.pdf)
6 | AI for arresting criminals | [Yolo Detection // Face recognition](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Workshop_Train_Yolov8_Object_Detection_on_Custom_Dataset.ipynb) | [Lecture6](https://github.com/punramon/PMU-B-PersonalAI/blob/main/Lecture/Lecture_ObjectDetection.pdf)

---
## **🚀 COURSE HIGHLIGHTS**  

### **COURSE 1: xPore: An AI-Powered App for Bioinformaticians🧬**  
**ชื่อโครงการ:** **xPore**  
**วัตถุประสงค์:**  
พัฒนาเป็นซอฟต์แวร์เพื่อเปรียบเทียบลำดับBaseของ RNA ระหว่างเซลล์ชนิดต่าง ๆ เช่น เซลล์ของผู้ป่วยมะเร็งกับคนปกติ โดยโครงการนี้มุ่งเน้นการตรวจจับความแตกต่างระดับโมเลกุลในตำแหน่ง RNA เฉพาะ โดยใช้ข้อมูลจาก **Nanopore Sequencers** ซึ่งเป็นเครื่องมือเดียวที่สามารถจัดลำดับ RNA ได้โดยตรงอย่างมีประสิทธิภาพ  

**การนำไปใช้:**  
1. ช่วยนักชีวสารสนเทศศาสตร์ในการตรวจจับการดัดแปลง RNA ในระดับฐานของลำดับพันธุกรรม  
2. วัดระดับการดัดแปลง RNA ซึ่งเป็นกุญแจสำคัญในการเข้าใจพฤติกรรมของเซลล์  

**เทคโนโลยีหลักที่ใช้:**  
- Gaussian Mixture Model สำหรับการวิเคราะห์สัญญาณ  

**ไฟล์อ้างอิง:**  
- **Workshop:** [Gaussian Mixture Model](WorkShop/WorkShop1_xPore.ipynb)  
- **Lecture:** [PDF การนำเสนอ](Lecture/Lecture1_xPore.pdf)  
- **เอกสารเพิ่มเติม:** [ข้อมูลสนับสนุน](https://drive.google.com/drive/folders/1WzSEFgym7sDo-3A9etN1a210a0IYmDi_)

---

### **COURSE 2: การเรียนรู้จากสัญญาณชีวภาพ 🧠**  
**ชื่อโครงการ:** **Learning from Biosignals**  
**วัตถุประสงค์:**  
ใช้ **1D CNN Models** ในการวิเคราะห์และแปลความหมายของสัญญาณสมอง เพื่อเพิ่มความเข้าใจเกี่ยวกับรูปแบบกิจกรรมทางประสาท  

**การนำไปใช้:**  
1. ใช้ประโยชน์จากข้อมูลคลื่นสมองในงานด้านการแพทย์  
2. ช่วยพัฒนาโมเดล AI ที่สามารถตรวจจับและวิเคราะห์สัญญาณชีวภาพได้อย่างมีประสิทธิภาพ  

**เทคโนโลยีหลักที่ใช้:**  
- 1D Convolutional Neural Networks (CNNs)  

**ไฟล์อ้างอิง:**  
- **Workshop:** [1D CNN for Brain Signals](WorkShop/WorkShop2_BiosignalModel.py)  
- **Lecture:** [PDF การนำเสนอ](Lecture/Lecture2_Biosignal.pdf)  
- **เอกสารเพิ่มเติม:** [ข้อมูลสนับสนุน](https://drive.google.com/drive/folders/1ZWYsgQaMztE_KxHUUT7dp-Z51vSp1Z6q)

---

### **COURSE 3: AI สำหรับตรวจจับการลอกโค้ด 💻**  
**ชื่อโครงการ:** **AI for Code Plagiarism Detection**  
**วัตถุประสงค์:**  
พัฒนาโมเดล **Code2Vec** เพื่อช่วยตรวจจับการลอกเลียนแบบในโค้ด โดยโฟกัสที่การวิเคราะห์โครงสร้างและพฤติกรรมของโค้ดอย่างละเอียด  

**การนำไปใช้:**  
1. ป้องกันการลอกเลียนแบบในงานเขียนโปรแกรม  
2. สนับสนุนการเรียนการสอนในวิชาคอมพิวเตอร์  

**เทคโนโลยีหลักที่ใช้:**  
- Code2Vec Model  

**ไฟล์อ้างอิง:**  
- **Workshop:** [Code2Vec for Clone Detection](WorkShop/WorkShop3_CodeClone.ipynb)  
- **Lecture:** [PDF การนำเสนอ](Lecture/Lecture3_CodePlagiarism.pdf)  
- **เอกสารเพิ่มเติม:** [ข้อมูลสนับสนุน](https://drive.google.com/drive/folders/1t-RL2SHrjztbW630o4VjY02a9II0tMsQ)

---

### **COURSE 4: การตรวจจับความผิดปกติทางจิตใจจากโซเชียลมีเดีย 📝**  
**ชื่อโครงการ:** **Mental Disorder Detection via Social Media**  
**วัตถุประสงค์:**  
ใช้เทคนิค NLP เพื่อวิเคราะห์ข้อความจากโซเชียลมีเดียในการตรวจจับรูปแบบหรือสัญญาณที่บ่งบอกถึงปัญหาสุขภาพจิต  

**การนำไปใช้:**  
1. ช่วยนักจิตวิทยาในการวินิจฉัยความผิดปกติจากข้อความออนไลน์  
2. ปรับปรุงการเฝ้าระวังปัญหาสุขภาพจิตในกลุ่มผู้ใช้อินเทอร์เน็ต  

**เทคโนโลยีหลักที่ใช้:**  
- Natural Language Processing (NLP)  

**ไฟล์อ้างอิง:**  
- **Workshop:** [NLP Classification](WorkShop/WorkShop4_NLPClassification.ipynb)  
- **Lecture:** [PDF การนำเสนอ](Lecture/Lecture4_MentalDisorderfromSocialMedia.pdf)  
- **เอกสารเพิ่มเติม:** [ข้อมูลสนับสนุน](https://drive.google.com/drive/folders/1XYuuqvKlfR0BlUyOTZjtUeFr-Tq5sf44)

---

### **COURSE 5: BiTNet AI for diagnosing ultrasound image 📷**  
**วัตถุประสงค์:**  
พัฒนาโมเดล **EfficientNet** เพื่อการจำแนกภาพทางการแพทย์ โดยเฉพาะการตรวจจับโรคจากภาพอัลตราซาวด์  

**การนำไปใช้:**  
1. ช่วยแพทย์ในการวินิจฉัยโรคด้วยความแม่นยำสูง  
2. ลดเวลาการตรวจและเพิ่มความสะดวกในงานด้านการแพทย์  
---
แน่นอนครับ! นี่คือการปรับใหม่โดยใช้ **emoji** อื่น ๆ เพื่อเพิ่มความน่าสนใจให้กับเนื้อหา:

---

### **COURSE 6: AI AI for arresting criminals 👮‍♂️💻**

**โครงการ:** **การวิจัยและพัฒนาระบบการติดตามสำหรับการจับกุมอาชญากรโดยใช้ปัญญาประดิษฐ์**  
โครงการนี้ได้รับการพัฒนาขึ้นมาเพื่อ:

- เพิ่มประสิทธิภาพของเจ้าหน้าที่ตำรวจในการจัดเก็บและตรวจสอบข้อมูลอาชญากรรมผ่านระบบการติดตามจับกุมคนร้ายด้วยเทคโนโลยีปัญญาประดิษฐ์ 🤖🔍
- สร้างความเชื่อมั่นและรักษาความปลอดภัยให้กับประชาชน โดยใช้เทคโนโลยีกล้องวงจรปิด (CCTV) เพื่อช่วยเจ้าหน้าที่ตำรวจในการเฝ้าระวังการกระทำความผิดและบันทึกหลักฐาน 🎥🚨
- พัฒนาระบบแจ้งเตือน ตรวจจับ ติดตาม และรู้จำบุคคลหรือรถต้องสงสัยด้วยเทคโนโลยีปัญญาประดิษฐ์ 🛑👤🚗

**Workshop:**  
- **งาน:** แยกวิดีโอออกเป็นเฟรมและติดป้ายประเภทให้แต่ละเฟรมใน 4 หมวดหมู่ ได้แก่ รถบัส, แท็กซี่, รถยนต์, และคนเดินเท้า จากนั้นสร้างโมเดลเพื่อจำแนกประเภททั้ง 4 ด้วย YOLOv8 🎬🚍🚖🚗🚶‍♂️
- **ปัญหา:** โมเดลมักทำนาย pedestrian มากเกินไป  
  - ปัญหานี้อาจเกิดจากการที่ Bounding Boxes ซ้อนทับกันมากเกินไป ทำให้แยกไม่ออก
  - ข้อมูลชุด (Dataset) ที่มีไม่เพียงพอ ทำให้ประสิทธิภาพของโมเดลไม่ดี ควรเพิ่มข้อมูลชุด (เช่น การดึงเฟรมจากวิดีโอ 17 วินาที หรือการลดระยะเวลาของวิดีโอเพื่อให้ได้จำนวนภาพมากขึ้น)

---
