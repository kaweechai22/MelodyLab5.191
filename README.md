# MelodyLab v5.93 Speed of Sound Matched Template

ปรับหน้า Displacement and Pressure ให้กราฟกินพื้นที่แนวตั้งเต็มขึ้นบนจอมือถือ
- เพิ่มความสูง canvas สำหรับหน้า Displacement and Pressure / Longitudinal
- ขยายความสูงของกราฟบน-ล่างให้ใช้พื้นที่เกือบเต็ม slot
- ลดช่องว่างใต้กราฟล่าง
- คงพฤติกรรมความถี่, แอมพลิจูด, อัตราเร็วคลื่น, เฟส และความต่างเฟส

## v5.93 Speed of Sound Matched Template
- เลื่อน badge “Phase Difference: Δφ = ...°” ลงมาอยู่ในกรอบกราฟการกระจัด
- แก้ไม่ให้ข้อความ Phase Difference ซ้อนทับกับลูกศรทิศทางการเคลื่อนที่ของคลื่น
- คงการขยายกราฟแนวตั้งและการปรับความถี่ f จาก v5.88

## v5.93 Speed of Sound Matched Template
- ปรับกราฟ Longitudinal Wave ให้อนุภาคสั่นซ้าย–ขวารอบตำแหน่งสมดุล
- เพิ่มจุดสมดุลสีจางและจุดจริงของอนุภาค เพื่อให้เห็นว่าอนุภาคไม่ได้ไหลไปกับคลื่น
- แสดงส่วนอัด–ส่วนขยายจากความหนาแน่นของอนุภาค
- เพิ่มลูกศร “การสั่นของอนุภาค” ที่จุดสังเกต
- แก้ให้ f และ v ส่งผลต่อความยาวคลื่นของหน้า Longitudinal Wave ผ่าน λ = v/f
- คงหน้า Displacement and Pressure จาก v5.89


## v5.93 Speed of Sound Matched Template
- ลบหัวข้อ Longitudinal / Transverse ออกจากเมนู Wave Visualizer
- เพิ่มหัวข้อใหม่ Speed of Sound (อัตราเร็วเสียง)
- ภาพจำลองใหม่แสดงแหล่งกำเนิดเสียง ไมโครโฟน ระยะทาง d เวลาที่เสียงเดินทาง Δt และอัตราเร็วเสียง v
- ใช้ความสัมพันธ์ v = d / Δt และ v ≈ 331 + 0.6T
- เพิ่มการส่งออกข้อมูลของหัวข้อ Speed of Sound Matched Template ตามชื่อหัวข้อ

## v5.93 Speed of Sound Matched Template
- ปรับหน้า Speed of Sound เป็นสื่อการสอนฟิสิกส์ชัดเจน
- แสดงแหล่งกำเนิดเสียง ไมโครโฟน พัลส์เสียง เส้นระยะทาง d ค่า Δt และสูตร v = d/Δt
- เพิ่มตัวควบคุม Distance d, Temperature T, Time Speed และแสดงค่า v, Δt อัตโนมัติ
- คงการลบหัวข้อ Longitudinal / Transverse ออกจากเมนู Wave Visualizer

## v5.93 Speed of Sound Matched Template
- ปรับหน้า Speed of Sound ให้ใช้รูปแบบเดียวกับ Longitudinal, Pressure, Displacement and Pressure
- ใช้ class ชุด visualizerTemplatePage / longitudinalFocusPage / longitudinalFocusGrid / longitudinalMainViz / neonControlViz
- ใช้ปุ่มเล่น หยุด รีเซ็ต และปุ่มส่งออกแบบเดียวกับสามหน้าหลัก
- ใช้รูปแบบพารามิเตอร์แบบ neonParamRow เดียวกัน
- คงภาพจำลองอัตราเร็วเสียงและสมการ v = d/Δt, v = 331 + 0.6T
