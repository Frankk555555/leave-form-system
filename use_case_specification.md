# ตารางคำอธิบาย Use Case (Use Case Specification)

อ้างอิงจากแบบจำลอง Use Case Diagram ระบบบริหารจัดการการลาบุคลากร กรณีศึกษา มหาวิทยาลัยราชภัฏบุรีรัมย์

<br>

**ตารางที่ 3.1 การเข้าสู่ระบบ**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> เข้าสู่ระบบ (Login)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-01</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> บุคลากร, ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> บุคลากร, ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. ผู้ใช้งานเข้าสู่หน้าเว็บไซต์ของระบบ<br>
      2. ผู้ใช้งานกรอกชื่อผู้ใช้ (Username) และรหัสผ่าน (Password) ลงในฟอร์ม<br>
      3. ระบบตรวจสอบความถูกต้องของข้อมูลกับการตั้งค่าในฐานข้อมูล<br>
      4. หากข้อมูลถูกต้อง ระบบจะนำเข้าสู่หน้าหลักตามสิทธิ์การใช้งาน (หน้าหลักบุคลากร หรือ หน้าหลักผู้ดูแลระบบ)
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.2 การดูสารสนเทศระเบียบการลา**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> ดูสารสนเทศระเบียบการลา (View Leave Regulations)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-02</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. บุคลากรเลือกเมนู "ระเบียบการลา"<br>
      2. ระบบแสดงข้อมูล กฎระเบียบ และเงื่อนไขการลาประเภทต่างๆ (ตามกรมบัญชีกลาง กระทรวงการคลัง)<br>
      3. บุคลากรอ่านและทำความเข้าใจเงื่อนไขก่อนยื่นใบลา
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.3 การยื่นใบลา**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> ยื่นใบลา (Submit Leave Request)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-03</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. บุคลากรเลือกเมนู "ยื่นใบลา"<br>
      2. ผู้ใช้งานระบุประเภทการลา ช่วงเวลาที่ต้องการลา และเหตุผลการลา<br>
      3. ผู้ใช้งานแนบไฟล์หลักฐานประกอบการลา (เช่น ใบรับรองแพทย์เป็นไฟล์ PDF หรือรูปภาพ) ถ้ามี<br>
      4. บุคลากรกดยืนยันการส่งใบลา<br>
      5. ระบบบันทึกข้อมูล บันทึกประวัติการลา และแสดงข้อความแจ้งเตือนผลการบันทึก
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.4 การติดตามและดูประวัติการลา**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> ติดตามและดูประวัติการลา (View Leave History)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-04</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. บุคลากรเลือกเมนู "ประวัติการลา"<br>
      2. ระบบดึงข้อมูลและแสดงรายการการลาที่ผ่านมา พร้อมแสดงสถานะการอนุมัติปัจจุบัน<br>
      3. บุคลากรสามารถคลิกดูรายละเอียดของรายการลาแต่ละครั้งได้
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.5 การดูแดชบอร์ดสรุปวันลา**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> ดูแดชบอร์ดสรุปวันลา (View Dashboard)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-05</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. บุคลากรเปิดเข้าสู่หน้าหลัก (Dashboard) ของระบบบุคลากร<br>
      2. ระบบแสดงกราฟหน้าปัดหรือข้อมูลสรุปจำนวนวันลาที่ได้ใช้งานไปแล้ว เพื่อให้เห็นภาพรวม
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.6 การแก้ไขข้อมูลส่วนตัวและเปลี่ยนรหัสผ่าน**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> แก้ไขข้อมูลส่วนตัวและเปลี่ยนรหัสผ่าน (Manage Profile)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-06</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. บุคลากรเลือกเมนู "ข้อมูลส่วนตัว"<br>
      2. ระบบแสดงข้อมูลส่วนตัวปัจจุบัน<br>
      3. บุคลากรทำการแก้ไขข้อมูลพื้นฐาน หรือทำการกำหนดรหัสผ่านใหม่<br>
      4. บุคลากรกดยืนยันการเปลี่ยนแปลง<br>
      5. ระบบอัปเดตข้อมูลลงฐานข้อมูลและแสดงข้อความทำรายการสำเร็จ
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.7 การตรวจสอบสิทธิ์วันลาคงเหลือ**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> ตรวจสอบสิทธิ์วันลาคงเหลือ (Check Leave Quota)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-07</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. บุคลากรเลือกเมนู "สิทธิ์วันลา"<br>
      2. ระบบประมวลผลคำนวณวันลาที่ใช้ไป หักลบกับโควตาประจำปีของบุคลากรท่านนั้น<br>
      3. ระบบแสดงจำนวนวันลาคงเหลือแยกตามประเภทการลาอย่างชัดเจน
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.8 การพิมพ์ใบลา**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> พิมพ์ใบลา (Print Leave Form)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-08</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> บุคลากร</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. บุคลากรเลือกรายการลาจากตารางประวัติการลา<br>
      2. บุคลากรกดปุ่ม "พิมพ์ใบลา"<br>
      3. ระบบจัดการสร้างเอกสารใบลาในรูปแบบไฟล์ PDF พร้อมข้อมูลที่กรอกไว้<br>
      4. บุคลากรสามารถดาวน์โหลดหรือสั่งพิมพ์ทางเครื่องพิมพ์ เพื่อนำไปส่งให้ผู้บังคับบัญชาอนุมัติ
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.9 การจัดการบัญชีผู้ใช้และบุคลากร**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> จัดการบัญชีผู้ใช้และบุคลากร (Manage Users)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-09</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. ผู้ดูแลระบบเลือกเมนู "จัดการบุคลากร"<br>
      2. ระบบแสดงรายชื่อบัญชีผู้ใช้ในระบบทั้งหมด<br>
      3. ผู้ดูแลระบบสามารถใช้ฟังก์ชัน เพิ่มรายบุคคล, นำเข้าจากไฟล์ (CSV/Excel), แก้ไขข้อมูล, ลบข้อมูล หรือรีเซ็ตรหัสผ่าน<br>
      4. ระบบประมวลผลและอัปเดตข้อมูลผู้ใช้ในระบบ
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.10 การจัดการข้อมูลพื้นฐาน (Dashboard และ กำหนดโควตา)**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> จัดการข้อมูลพื้นฐาน (Manage Basic Information)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-10</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. ผู้ดูแลระบบเข้าสู่ส่วนการจัดการข้อมูลพื้นฐานและ Dashboard ของระบบ<br>
      2. ระบบแสดงสถิติภาพรวมการลา แยกตามประเภทและสังกัดหน่วยงาน เพื่อดูข้อมูลเชิงลึก<br>
      3. ผู้ดูแลระบบสามารถเข้าไปตั้งค่า กำหนดตัวเลขโควตาวันลาประจำปีให้กับบุคลากรแต่ละประเภทได้<br>
      4. ระบบบันทึกการตั้งค่าโควตาเพื่อใช้เป็นเกณฑ์ในการตรวจสอบสิทธิ์การลา
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.11 การส่งออกรายงานการลา**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> ส่งออกรายงานการลา (Export Report)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-11</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. ผู้ดูแลระบบเลือกเมนู "รายงานการลา"<br>
      2. ผู้ดูแลระบบกำหนดเงื่อนไขการออกรายงาน เช่น ช่วงเวลา ประเภท สังกัด<br>
      3. ผู้ดูแลระบบกดปุ่มดาวน์โหลดรายงาน<br>
      4. ระบบสร้างและส่งออกไฟล์ตามรูปแบบที่กำหนด (เช่น ไฟล์ Excel) สรุปชื่อ สังกัด และจำนวนวันลา
    </td>
  </tr>
</table>

<br>

**ตารางที่ 3.12 การตั้งค่าระบบการลา (วันหยุดและประเภทการลา)**
<table border="1" width="100%" style="border-collapse: collapse;">
  <tr>
    <td width="50%" style="padding: 8px;"><b>Use Case Title:</b> ตั้งค่าระบบการลา (System Leave Settings)</td>
    <td width="50%" style="padding: 8px;"><b>Use Case Id:</b> UC-12</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Primary Actor:</b> ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Stakeholder Actor:</b> ผู้ดูแลระบบ</td>
  </tr>
  <tr>
    <td colspan="2" style="padding: 8px;"><b>Main Flow:</b><br>
      1. ผู้ดูแลระบบเลือกเมนู "ตั้งค่าระบบ"<br>
      2. ผู้ดูแลระบบทำการจัดการวันหยุดประจำปี (เช่น เพิ่ม ลด แก้ไขปฏิทินวันหยุดเพื่อยกเว้นการคำนวณวันลา)<br>
      3. ผู้ดูแลระบบทำการจัดการตั้งค่าประเภทการลา (เช่น เพิ่ม ลด แก้ไขชื่อหรือคุณลักษณะการลาประเภทต่างๆ)<br>
      4. ระบบบันทึกข้อมูลการตั้งค่าเข้าสู่ระบบเพื่อใช้คำนวณเงื่อนไขและวันลาให้กับบุคลากรทั้งหมด
    </td>
  </tr>
</table>
