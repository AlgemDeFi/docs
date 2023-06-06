# Unstaking nASTR

ในการรับ ASTR คืน, ผู้ถือ nASTR จะต้องแลกโทเค็นของตนบน Algem โดยใช้หนึ่งในสองตัวเลือก Unstake ที่มี:

### Unstaking ปกติ

ตัวเลือก unstake ปกติจะใช้ฟังก์ชันเดียวกันกับ dApps staking ของ Astar Network. เมื่อผู้ใช้ถอนโทเค็น nASTR ของเขาแล้ว, Algem จะเรียกใช้ unstaking บน Astar dApps staking. หลังจากหมดช่วง unstaking, Algem จะได้รับโทเค็น ASTR และแจกจ่ายไปยังกระเป๋าเงินของผู้ใช้โดยตรง.

### Unstaking ทันที

ในตัวเลือก unstaking ทันที, ผู้ใช้สามารถตัดสินใจถอน nASTR ของเขาและรับโทเค็น ASTR ของเขาโดยตรงโดยไม่ต้องรอ 10 eras, เช่นเดียวกับในกรณีของ unstaking ปกติ. ในทางกลับกัน, Algem คิดค่าธรรมเนียมเล็กน้อยสำหรับบริการ. [ข้อมูลเพิ่มเติมเกี่ยวกับค่าธรรมเนียมของเรา](../undefined.md).

ตัวเลือกนี้ยังขึ้นอยู่กับความจุของ unstaking pool. อาจมีโทเค็น ASTR บางส่วนใน pool. ระบบจะปฏิเสธธุรกรรมหากพูลว่างหรือมีโทเค็นไม่เพียงพอที่จะตอบสนองคำขอ unstaking ของผู้ใช้.

รายได้โปรโตคอลจัดหาให้กับ pool, กล่าวคือ, หากผู้ใช้ถอนโทเค็น nASTR ทันทีโดยใช้ unstaking pool, เขาจะได้รับโทเค็น ASTR โดยตรงจาก pool. ถึงกระนั้น Algem จะเปิดใช้ตัวเลือก unstaking ปกติใน dApps staking. หลังจาก 10 eras, โทเค็น ASTR จาก dApp staking จะถูกเพิ่มและเติม pool เพื่อให้ผู้ใช้รายอื่นยกเลิกการเดิมพันได้ทันที.

การดำเนินการจะเหมือนกันในทั้งสองตัวเลือก, แต่มีการเปลี่ยนแปลงเวลาและค่าธรรมเนียมเท่านั้น. ASTR ที่ได้รับหลังจาก unstaking ไม่ใช่เงินฝากเริ่มต้น, แต่เป็นจำนวน nASTR ที่ไม่ได้เดิมพัน.

กล่าวคือ, หากผู้ใช้ซื้อหรือขายโทเค็น nASTR นับตั้งแต่การฝากเงินครั้งแรกของเขาและได้ถอนยอดคงเหลือทั้งหมดของ nASTR, ออกไป เขาจะได้รับโทเค็น ASTR มากกว่าหรือน้อยกว่าเงินฝากเริ่มต้นของเขา.

### Q: ช่วง unstaking คืออะไร?

ระยะเวลา unstaking แตกต่างกันไปตั้งแต่ 10 ERAs ถึง 13 ERAs (ประมาณ 10-13 วัน).

### Q: ทำไมเป็นเช่นนั้น? ในระยะเวลา unstaking ของ Astar Network dApp staking คือ 10 ERAs.

DApp staking จำกัดการโทรแบบไม่ผูกมัด 4 ครั้ง/ผู้ใช้ในช่วง 10 วัน. เนื่องจากสัญญา liquid staking ของเรานั้นเป็นผู้ใช้โดยพื้นฐานแล้ว, Algem จึงจัดกลุ่มการโทร unstaking ทั้งหมดเป็นกลุ่มและส่งไปยัง dApp staking 4 ครั้งในช่วง 10 วัน. นั่นคือเหตุผลที่หากคุณถอน ASTR ในช่วงเริ่มต้นของรอบนี้ ระยะเวลา unstaking ของคุณจะเป็น 13 ERAs.