# A.DEMOGRAPHICS  
[text] Registry ID: _________  
[text] HN (Health Number): _________  
[text] AN (Account Number): _________  
[text] Last Name: _________  
[text] First Name: _________  
[text] Middle Name: _________  
[dropdown][dd/mm/yyyy] Birth Date: ___ /___ /______  
[text][cal from current - BD] Age: _________ years  
[dropdown] Sex:   
- Female  
- Male  

[text] SSN (Social Security Number): _________  
[dropdown] Race:   
- White Black/African American   
- European   
- Arab   
- Asian  

[text + dropdown][Nationalities List] Nationality: _________  
[text] Is This Patient's Permanent Address: 
    Yes No → If Yes, [text] Zip Code: _________

---

# B.EPISODE OF CARE
[text] Hospital Name: _____________  
[radio] Admission Type:   
- Direct   
- Transfer If Transfer, form Healthcare Center: 
  -  BDMS Network: _____________ 
  -  Non BDMS_____________   

[text] Arrival Date/Time: ___ /___ /,:  
[text] Admitting Provider: _____________  
[text] Attending Provider: ____________  

[radio] Payment Source  
- [radioOption] Primary Payor   
- [radioOption] Secondary Payor  
    - [-] Self   
    - [-] Corporate   
    - [-] Embassy   
    - [-] Other  
    - [-] Comptroller General's Department  
    - [-] NHSO (Natonal Health Security Ofce)  
    - [-] SSO (Social Security Ofce)  
    - [-] UCEP (Universal Coverage Emergency Patent)  
    - [-] Private Health Insurance  
    - [-] Charitable care/Foundaton Funding  

[radio] Research Enrolled :  
- yes/no

---
# C.HISTORY AND RISK FACTORS
Hyperension (ความดันโลหิตสูง) : yes/no  

Diabees Mellitus (การเป็นโรคเบาหวาน): yes/no  

Dyslipidemia ( การมีโรคไขมันในเลือดผิดปกติ ): yes/no  

Prior MI (บุคคลเคยเจ็บหัวใจ): yes/no  
-> if yes Most Recent MI Date: __ /__ /____ (Date)  

Prior PCI ( เคยทำการรักษาด้วยการทำหัตถการทีอุบัติรายในหลอดเลือดในหัวใจ ): yes/no  
-> if yes Most Recent PCI Date: __ /__ /____ (Date)  

Left Main PCI ( ประวัติการรักษาของหลอดเลือดหลักทางซ้าย ): Unknown , Yes/No

Height: ____ cm    
Weight: ____ kg    
  
Currently on Dialysis (กำลังไดอาลิซิส): yes/no  

Family History of Premature CAD (ประวัติครอบครัวเป็นโรคหลอดเลือดหัวใจอุดตันเร็ว): yes/no  

Cerebrovascular Disease (โรคหลอดเลือดสมอง): yes/no  

Peripheral Arterial Disease (โรคหลอดเลือดแดนรอบ): yes/no  

Chronic Lung Disease (โรคปอดเรื้อรัง): yes/no  

Prior CABG (ประวัติผ่าตัดหลอดเลือดหัวใจ): yes/no  
-> if yes Most Recent CABG Date : __ /__ /____ (Date)  

---

Tobacco Use (การใช้ยาสูบ):  
- [radio] Never (ไม่เคย)  
- [radio] Current - Some Days (ใช้ในบางวัน)  
- [radio] Former (เคยใช้แต่เลิก)  
- [radio] Current - Every Day (ใช้ทุกวัน)  
- [radio] Smoker, Current Status Unknown (สูบบุหรี่ สถานะปัจจุบันไม่ทราบ)  
- [radio] Unknown if ever Smoked (ไม่ทราบว่าเคยสูบหรือไม่)  

if any current 
Tobacco Type (ประเภทของยาสูบ):
- [checkbox] Cigarettes (บุหรี่)
- [checkbox] Cigars (ซิการ์)
- [checkbox] Pipe (หลอด)
- [checkbox] Smokeless (ยาสูบแบบไม่ไหว)

if Current - Every Day 
 - [radio] Light tobacco use (<10/day) (การใช้ยาสูบเบา: น้อยกว่า 10 มวนต่อวัน)
 - [radio] Heavy tobacco use (>=10/day) (การใช้ยาสูบหนัก: 10 มวนหรือมากกว่าต่อวัน)

---
Cardiac Arrest Out of Healthcare Facility: Yes/No  
(อัตราการเกิดหัวใจหยุดการทำงานของหน่วยบริการด้านการแพทย์)

If Yes, Arrest Witnessed: Yes/No  
(มีคนพบเห็น)

If Yes, Arrest after Arrival of EMS: Yes/No  
(การเจ็บหัวใจหยุดหลังจากที่รถอาชีพกู้ชีพมาถึง)

If Yes, First Cardiac Arrest Rhythm: Yes/No  
(จำนวนครั้งที่หัวใจหยุดการทำงานครั้งแรก)
- Shockable
- Not Shockable
- Unknown

Cardiac Arrest at Transferring Healthcare Facility: Yes/No


[Dropdown][scale color with number and text label]
CSHA Clinical Frailty Scale (See in Appendix):  
(ลักษณะความโอบอาจทางการแพทย์ CSHA) ?  
- 1: Very Fit  
- 2: Well  
- 3: Managing Well  
- 4: Vulnerable  
- 5: Mildly Frail  
- 6: Moderately Frail  
- 7: Severely Frail  
- 8: Very Severely Frail  

---
# D. PRE-PROCEDURE INFORMATION 

Heart Failure (ความล้มเหลวของหัวใจ) : Yes/No 
NYHA Class (ระดับความรู้สึกต่อการมีความล้มเหลวของหัวใจ) :
- [dropdown] class I 
- [dropdown] class II
- [dropdown] class III
- [dropdown] class IV  
  
Newly Diagnosed (การวินิจฉัยครั้งแรก) : Yes/No  


Heart Failure Type (ประเภทของความล้มเหลวของหัวใจ) : 
 - Diastolic 
 - Systolic 
 - Unknown   

---

Electrocardiac Assessment Method
(ข้อมูลเกี่ยวกับวิธีการประเมินคลื่นไฟฟ้าในหัวใจ) 
- ECG (Electrocardiogram) - บันทึกคลื่นไฟฟ้าในหัวใจด้วยการใช้ ECG  
- Telemetry Monitor - บันทึกคลื่นไฟฟ้าในหัวใจโดยใช้อุปกรณ์ Telemetry Monitor  
- Holter Monitor - บันทึกคลื่นไฟฟ้าในหัวใจโดยใช้ Holter Monitor  
- Other - วิธีการอื่น ๆ ที่ไม่ได้ระบุไว้ข้างต้น  
?(หากเลือกช้อยนี้ต้องมีช่องให้ใส่วิธีอื่นๆมั้ย)
- None - ไม่มีการใช้วิธีการใด ๆ ในการประเมินคลื่นไฟฟ้าในหัวใจ  

[**checkbox**] if any methods -> Results   
- Normal (ปกติ)  
- Abnormal (ผิดปกติ)  
- Uninterpretable (ไม่สามารถตีความได้)

 If Abnormal, New Antarrhythmic Therapy Initated Prior to Cath Lab : Yes / No  
 (รักษาด้วยยาชนิดต้านจัยสรีรวิท (Antarrhythmic Therapy) ไหม ก่อนไปห้องการทำหัตหะ (Cath Lab))

 [**checkbox**] Electrocardiac Abnormality Type 
 (ประเภทของคลื่นไฟฟ้าในหัวใจที่ผิดปกติ)

- Ventricular Fibrillation (VF)  
- Sustained VT (Ventricular Tachycardia)  
- Non-Sustained VT  
- Exercise Induced VT  
- T wave inversions  
- ST deviation >= 0.5 mm  
- New Left Bundle Branch Block  
- New Onset Atrial Fibrillation  
- New Onset Atrial Flutter  
- PVC – Frequent (Premature Ventricular Contraction)  
- PVC – Infrequent  
- 2nd Degree AV Heart Block Type 1  
- 2nd Degree AV Heart Block Type 2  
- 3rd Degree AV Heart Block  
- Symptomatic Bradyarrhythmia  
- คลื่นไฟฟ้าในหัวใจผิดปกติอื่น ๆ  

[**number**] → If New Onset Atrial Fib, Heart Rate : _____________ bpm  
(หากมีคลื่นไฟฟ้าในหัวใจประเภท New Onset Atrial Fib)  

 → [**checkbox**] If Non Sustained VT, Type: (Select all that apply) 
 (หากคลื่นไฟฟ้าในหัวใจประเภท Non Sustained VT)
 -  Symptomatc 
 -  Newly Diagnosed 
 -  Other

Stress Test (การทดสอบความเค้น) : Yes/No  
-> if Test Type Performed
- Stress Echocardiogram (ทดสอบความเค้นด้วยเอโคคาร์ดิออกรัม)
- Stress Nuclear (ทดสอบความเค้นด้วยนิวเคลียร์)
- Exercise Stress Test (w/o imaging)(ทดสอบความเค้นด้วยการออกกำลังกายโดยไม่มีการทำภาพถ่าย)
- Stress Imaging w/CMR (ทดสอบความเค้นด้วยการภาพถ่ายและการรู้สึกต่อแม่เหล็ก)

-> if yes, Most recent Date : dd/mm/yyyy  

-> if yes, Test Result : 
- ลบ (Negative)
- บวก (Positive)
- ไม่แน่ใจ (Indeterminate)
- ไม่สามารถใช้ (Unavailable)  
  
    -> if Positive , Risk/Extent of Ischemia :   
    (หากผลการทดสอบเป็น "Positive" (บวก), คุณจะต้องระบุความเสี่ยง/ขอบเขตของภาวะขาดเลือดในหัวใจ )
    - ต่ำ (Low)
    - กลาง (Intermediate)
    - สูง (High)
    - ไม่สามารถใช้ (Unavailable)

---
Agatston Coronary Calcium Score : Yes/No  
( การประเมินคะแนนแคลเซียมในหลอดเลือดหัวใจตามวิธี Agatston )  

[**number**] → If Yes, Agatston Coronary Calcium Score ___ 
                → if any value Most Recent Calcium Score Date: ___ /___ /______

EF (LVEF - Left Ventricular Ejection Fraction) : Yes/No  
(การตรวจวัดหรือประเมินอัตราเต้นของหัวใจทางรายการ LVEF)  
[**number**] → if yes Most Recent LVE ___ %

Prior Dx Coronary Angiography Procedure: (without interventon) Yes/No  
(ประวัติการทำกระบวนการสำรวจหลอดเลือดหัวใจ (ไม่มีการทำการแก้ไข))  

→ If Yes, Most Recent Procedure Date: ___ /___ /______  
    [**dropdown**]→ If Yes, Results:   
    - Obstructve CAD  
    - Non-Obstructve CAD  
    - Unclear Severity  
    - No CAD  
    - Structural Disease  
    - Unknown  

## PRE-PROCEDURE MEDICATIONS

| Medicaton                     | Meaning                           | Administered  |
|-------------------------------|-----------------------------------|---------------|
| Antplatelet ASA               | ยาต้านการเกาะติดเม็ดเลือด              |  No , Yes Contrai      |   
| Beta Blockers (Any)           | ยาบีตาบล็อกเกอร์                     |  No , Yes  Contrai    |   
| Ca Channel Blockers (Any)     | ยาบล็อกเกอร์ช่องไคลเซียม              |  No , Yes  Contrai    |
| Antarrhythmic Agent Other     | ยาป้องกันหรือรักษาอาการหัวใจเต้นผิดรูป    |  No , Yes  Contrai    |  
| Long Actng Nitrates (Any)     | ยานาไตรตระคันยาวดี                  |  No , Yes  Contrai   |   
| Ranolazine                    | ยาราโนเลซีน                        |  No , Yes  Contrai   |   
| Statn (Any)                   | ยาสตาติน                           |  No , Yes  Contrai    |   
| Non-Statn (Any)               | ยาสตาตินที่ไม่ใช่สตาติน                 |  No , Yes  Contrai    |   
| PCSK9 Inhibitors              | ยากำจัด PCSK9                       |  No , Yes  Contrai    |   
---

# E. PROCEDURE INFORMATION

Procedure Start Date/Time: ___ /___ /______,___:___   
Procedure End Date/Time: ___ /___ /______,___:___  

Diagnostc Coronary Angiography Procedure: Yes/No  
(กระบวนการสำรวจหลอดเลือดหัวใจ)  
 [text][dropdown if possible] → If Yes, Diagnostc Cath Operator: _____________  
 (ชื่อผู้ดำเนินการสำรวจหลอดเลือดหัวใจ)  

Percutaneous Coronary Interventon - PCI : Yes/No  
( ข้อมูลเกี่ยวกับกระบวนการติดต่อหลอดเลือดหัวใจแบบทางผิว )  

→ If Yes, PCI Operator:   
( ชื่อผู้ดำเนินการ PCI )  
    [**text**][dropdown if possible] 1ˢᵗ Operator - _____________   
    [**text**][dropdown if possible] 2ⁿᵈ Operator - _____________  

Diagnostc Lef Heart Cath : Yes/No   
(กระบวนการสำรวจหัวใจซ้าย)

→ If Yes,  
LVEF (Left Ventricular Ejection Fraction): _____________ %   
LVEDP (Left Ventricular End-Diastolic Pressure) : _____________ mmHg

Concomitant Procedures Performed : Yes/No
( ข้อมูลเกี่ยวกับกระบวนการที่ทำพร้อมกัน )   
→ If Yes,   
[**checkbox**] Procedure Type(s)  
- Structural Repair: การซ่อมแซมโครงสร้างในหัวใจ
- Lef Atrial Appendage Occlusion: การปิดปิดส่วนเส้นผมของลิ้นปลอด
- Parachute Device Placement: การติดตั้งอุปกรณ์ Parachute
- Mitral Clip Procedure: กระบวนการ Mitral Clip
- Transcatheter Aortc Valve Replacement (TAVR): การสิ่งสร้างหางใจคาด (TAVR)
- Thoracic Endovascular Aortc Repair (TEVAR): การซ่อมแซมหลอดลมในปอด (TEVAR)
- Endovascular Aortc Repair (EVAR): การซ่อมแซมหลอดลม
- Right Heart Cath: การสำรวจหัวใจด้านขวา
- EP Study: การศึกษาการทำงานของหัวใจ
- Cardioversion: การแปลงลมหัวใจ
- Temporary Pacemaker Placement: การใส่เครื่องช่วยเติมพลังชั่วคราว
- Permanent Pacemaker Placement: การใส่เครื่องช่วยเติมพลังถาวร
- LIMA (Natve Positon) Angiography: การสำรวจหลอดลม LIMA ในตำแหน่งปกติ
- Aortography: การสำรวจหลอดลมหัวใจ
- Renal Angiography: การสำรวจหลอดโตและไต
- Peripheral Interventon: กระบวนการแทรกซึมในส่วนรอบแขนหรือขา
- Peripheral Angiography: การสำรวจหลอดลมรอบแขนหรือขา
- Biopsy of heart: การตรวจสุภาพของหัวใจ
- Procedure Type Not Listed: ประเภทของกระบวนการที่ไม่ได้ระบุในรายการข้างต้น

---
[**radio**] Arterial Access Site ( ข้อมูลเกี่ยวกับสถานที่เข้าถึงเส้นเลือด )
- Right Femoral: การเข้าถึงเส้นเลือดด้านขวาที่ช่วงอัตราเลือด
- Lef Femoral: การเข้าถึงเส้นเลือดด้านซ้ายที่ช่วงอัตราเลือด
- Right Brachial: การเข้าถึงเส้นเลือดด้านขวาที่แขนบน
- Lef Brachial: การเข้าถึงเส้นเลือดด้านซ้ายที่แขนบน
- Right Radial: การเข้าถึงเส้นเลือดด้านขวาที่ข้อมือ
- Lef Radial: การเข้าถึงเส้นเลือดด้านซ้ายที่ข้อมือ
- Other: สถานที่เข้าถึงเส้นเลือดอื่นๆ

[**radio**] Access Site - Closure Method (วิธีการปิดสถานที่เข้าถึงเส้นเลือด)

- Manual Compression: การกดด้วยมือ
- Compression Device: ใช้เครื่องมือที่มีฟังก์ชันการกด
- Sealing technique: การปิดด้วยเทคนิคการปิด
- Suturing technique: การปิดด้วยเทคนิคการเย็บ

---
[**radio**] Arterial Cross Over (การครอสโอเวอร์ของเส้นเลือด)
- Right Femoral: การเข้าถึงเส้นเลือดด้านขวาที่ช่วงอัตราเลือด
- Lef Femoral: การเข้าถึงเส้นเลือดด้านซ้ายที่ช่วงอัตราเลือด
- Right Brachial: การเข้าถึงเส้นเลือดด้านขวาที่แขนบน
- Lef Brachial: การเข้าถึงเส้นเลือดด้านซ้ายที่แขนบน
- Right Radial: การเข้าถึงเส้นเลือดด้านขวาที่ข้อมือ
- Lef Radial: การเข้าถึงเส้นเลือดด้านซ้ายที่ข้อมือ
- No: ไม่มีการเข้าถึงเส้นเลือดอีกข้าง
  
[**radio**] → If not No, Cross Over - Closure Method: 
- Manual Compression
- Compression Device
- Sealing technique
- Suturing technique
---

[**radio**] Arterial Simultaneous (การเข้าถึงเส้นเลือดแบบพร้อมกัน)  
- Right Femoral: การเข้าถึงเส้นเลือดด้านขวาที่ช่วงอัตราเลือด
- Lef Femoral: การเข้าถึงเส้นเลือดด้านซ้ายที่ช่วงอัตราเลือด
- Right Brachial: การเข้าถึงเส้นเลือดด้านขวาที่แขนบน
- Lef Brachial: การเข้าถึงเส้นเลือดด้านซ้ายที่แขนบน
- Right Radial: การเข้าถึงเส้นเลือดด้านขวาที่ข้อมือ
- Lef Radial: การเข้าถึงเส้นเลือดด้านซ้ายที่ข้อมือ
- No: ไม่มีการเข้าถึงเส้นเลือดอีกข้าง

[**radio**] → If not No, Simultaneous - Closure Method - Closure Method: 
- Manual Compression
- Compression Device
- Sealing technique
- Suturing technique


Venous Access: Yes/No
[**radio**] → If not No, Venous - Closure Method: 
- Manual Compression
- Compression Device
- Sealing technique
- Suturing technique

[**number**] Systolic BP (ความดันเลือดซิสโทลิค): _____________ mmHg
Cardiac Arrest at this facility ( อุบัติการหัวใจที่สถานที่รักษา ): Yes/No

RADIATION EXPOSURE AND CONTRAST 
(การรังสีและสาร Contrast)

Fluoro Time : _____________ นาที (minutes)   - ระยะเวลาที่ใช้ในการถ่ายภาพรังสี 
Contrast Volume : _____________ มิลลิลิตร (ml) - ปริมาณสาร Kontrastที่ใช้
Cumulative Air Kerma : _____________ mGy    - ความเผา (dose) ของรังสีที่ได้รับ
Dose Area Product : _____________ mGy/cm²   - พื้นที่ของการรังสีที่ได้รับ

---

# F. LABS  
PRE-PROCEDURE (value closest to the procedure)  
[radio - text] hsTroponin I : Drawn _____________ ng/L  
[radio - text] hsTroponin T :  Drawn _____________ ng/L  
[radio - text] Creatnine: Drawn _____________ mg/dL  
[radio - text] Hemoglobin : Drawn _____________ g/dL  
[radio - text] Total Cholesterol: Drawn _____________ mg/dL    
[radio - text] HDL: Drawn _____________ mg/dL  

POST-PROCEDURE
[radio - text] hsTroponin I  Drawn _____________ ng/L
[radio - text] hsTroponin T:  Drawn _____________ ng/L
[radio - text] Creatnine: (peak)  Drawn _____________ mg/dL
[radio - text] Hemoglobin:  Drawn _____________ g/dL


# G. CATH LAB VISIT 
(การเข้ารับบริการในห้อง CATH LAB)

- ACS <= 24 hrs  
- ACS > 24 hrs  
- New Onset Angina <= 2 months  
- Worsening Angina  
- Resuscitated Cardiac Arrest  
- Heart Failure  
- Stable Known CAD  
- Suspected CAD  
- Valvular Disease  
- Pericardial Disease  
- Cardiac Arrhythmia  
- Cardiomyopathy  
- LV Dysfuncton  
- Syncope  
- Post Cardiac Transplant  
- Pre-operatve Evaluaton  
- Evaluaton for Exercise Clearance  
- Other  








