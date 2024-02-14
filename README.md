# chomchob_test_ggds

Section 1 - Manual Testing Skill and Testing Knowledge

1. หากต้องการ Design Test-case มี Technique อะไรบ้างที่สามารถช่วยให้การ Design Test-case เพื่อทดสอบระบบได้ครอบคลุม
  - Positive testing: ทดสอบข้อมูลหรือระบบที่ถูกต้อง
  - Negative testing: ทดสอบข้อมูลหรือระบบที่ไม่ถูกต้อง
  - Boundary Testing: ทดสอบข้อมูลที่อยู่ในขอบเขตค่าสูงสุด ต่ำสุด และค่ากลาง
  - Regression Testing: ทดสอบเพื่อหลังจากการแก้ไขซอฟแวร์ ว่าไม่ได้ส่งผลกระทบต่อฟังก์ชั่นอื่นๆ
  - Smoke Testing: ทดสอบระบบโดยการเน้นไปที่ฟังก์ชั่นหลักเพื่อตรวจสอบว่าทำงานได้ถูกต้อง
  - End-to-End testing: ทดสอบระบบทั้งหมดตั้งแต่เริ่มต้น จนจบการทำงาน
</br>
</br>
2. Design Test-case จากโจทย์ต่อไปนี้อย่างน้อย 5 Case พร้อมระบุ Technique ที่ใช้ข้อนั้น
</br>&nbsp;&nbsp;&nbsp;&nbsp;[โจทย์] : ผู้ใช้ต้องการโอน Point จากบัญชีตัวเอง ไปยังบัญชีปลายทาง โดยเงื่อนไขคือ
</br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ขั้นต่ำในการโอน Point คือ 100 / การทำรายการ
</br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;สูงสุดในการโอน Point คือ 3,000 / การทำรายการ
</br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;หากโอน < ขั้นต่ำ ระบบคิดค่า Fee 8 Point โดยบวกเพิ่มจากค่าที่กรอก
</br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ต้องกรอก Passcode 4 หลัก ให้ถูกต้องจึงทำรายการสำเร็จ
</br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;บัญชีปลายทางต้องถูกต้อง จึงจะสามารถกรอก Passcode ได้

  - Please refer to [Point_transfer_system_Test_case.xlsx](/Point_transfer_system_Test_case.xlsx)

</br>
</br>
3. หากทีมต้องการทดสอบ Feature ในข้อ 2 จะต้องมี Test Plan อย่างไร?

  - Please refer to [Point_transfer_system_Test_plan.docx](/Point_transfer_system_Test_plan.docx)

</br>
</br>

4. Software Testing มีความสำคัญอย่างไรในการพัฒนาระบบ
  - เป็นกระบวนการที่ทำให้ระบบที่สร้างขึ้นมามีประสิทธิภาพ มีคุณภาพ ช่วยตรวจสอบการทำงานของระบบว่าถูกต้องตามความต้องการลูกค้า ลดโอกาศในการเกิดข้อผิดพลาดที่อาจจะเกิดขึ้นในระบบ

</br>
</br>

หมายเหตุ ต้องขออภัยสำหรับ Section 2 และ 3 ครับ จุดนี้ต้องไปศึกษา automate test เพิ่มเติม
