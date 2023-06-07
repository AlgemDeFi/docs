# ⚠ Riการบริหารความเสี่ยง

ก่อนใช้ Algem [โปรดอ่านข้อกำหนดและเงื่อนไขการใช้งานของเราและรับทราบถึงความเสี่ยง](https://www.algem.io/terms-of-use).

* ความเสี่ยงของสัญญาอัจฉริยะ\
  \
  โปรโตคอล Algem[ ได้รับการตรวจสอบโดย](https://github.com/AlgemDeFi/audits/blob/main/AlgemQuantstampCertifacate.png) [Quantstamp ](https://quantstamp.com/)ผู้นำด้านความปลอดภัย Web3.0. โปรดทราบว่าการตรวจสอบความปลอดภัยไม่ได้รับประกันความผิดพลาดทั้งหมดของโปรโตคอล. ความเสี่ยงสามารถเกิดขึ้นได้เสมอ. อย่าฝากสินทรัพย์ที่คุณไม่สามารถจะเสียได้บน Algem.\

* ASTR สูญเสียหมุด(depeg) \
  \
  บนโปรโตคอล Algem จะมีอัตราส่วน 1:1 เสมอสำหรับการสร้างโทเค็น nASTR และเบิร์น. ม่ว่าอัตราส่วนของคู่ nASTR/ASTR ในตลาดจะเป็นอย่างไร. ผู้ใช้สามารถถอน ASTR จากโทเค็น nASTR ในจำนวนที่เท่ากันได้เสมอ. อย่างไรก็ตาม หากผู้ถือ nASTR ใช้โทเค็นของตนใน DEXs เพื่อให้มีสภาพคล่อง พวกเขาอาจเผชิญกับความเป็นไปได้ของการสูญเสียที่ไม่แน่นอน (IL) และ depeg เช่นเดียวกับการทำฟาร์มใน DEXs.\
  \
  เพื่อลดความเสี่ยงนี้ ผู้ใช้สามารถดำเนินกลยุทธ์การเก็งกำไรระหว่าง DEX และโปรโตคอล Algem โดยใช้ฟังก์ชัน swap, stake และ unstake. ด้วยวิธีนี้ ผู้ใช้มีแรงจูงใจทางการเงินในการรักษาหมุด ASTR/nASTR และทำให้ระบบนิเวศมีเสถียรภาพ. [ดูส่วนอัตราส่วน nASTR:ASTR](dnts.md).\

*   การสูญเสียอนิจจังบน DEX (IL)\
    \
    โดยพื้นฐานแล้ว การสูญเสียอนิจจังคือการสูญเสียเงินทุนชั่วคราวที่เกิดขึ้นเมื่อจัดหาสภาพคล่อง. บ่อยครั้งที่มีการอธิบายว่าเป็นความแตกต่างระหว่างการถือครองสินทรัพย์กับการให้สภาพคล่องในสินทรัพย์นั้น. การสูญเสียอนิจจัง (IL) มักพบในกลุ่มสภาพคล่องมาตรฐานซึ่งผู้ให้บริการสภาพคล่อง (LP) ต้องจัดหาสินทรัพย์ทั้งสองในอัตราส่วนที่ถูกต้อง และหนึ่งในสินทรัพย์มีความผันผวนเมื่อเทียบกับอีกสินทรัพย์หนึ่ง. (ตัวอย่างเช่น ใน Liquidity Pool ของ Arthswap ASTR/WETH 50/50).\


    หาก WETH มีมูลค่าเพิ่มขึ้น Pool จะต้องพึ่งพานักอนุญาโตตุลาการอย่างต่อเนื่องเพื่อให้มั่นใจว่าราคา Pool สะท้อนราคาในโลกแห่งความเป็นจริงเพื่อรักษามูลค่าของโทเค็นทั้งสองใน Pool ให้เท่ากัน. โดยทั่วไปจะนำไปสู่สถานการณ์ที่กำไรจากโทเคนที่มีมูลค่าเพิ่มขึ้นจะถูกพรากไปจากผู้ให้บริการสภาพคล่อง. ณ จุดนี้ หาก LP ตัดสินใจถอนสภาพคล่อง การสูญเสียอนิจจังกลายเป็นถาวร". ดู "[การสูญเสียอนิจจัง(IL)คืออะไร? DEFI อธิบาย](https://finematics.com/impermanent-loss-explained/)" จาก Finematics สำหรับข้อมูลเพิ่มเติม.

สำหรับความเสี่ยงที่เกี่ยวข้องกับการใช้ nASTR บนโปรโตคอลอื่น โปรดดูส่วนที่เกี่ยวข้อง:

* [ความเสี่ยงของ Sirius Finance](../undefined/how-to-use-algems-nastr-farming/sirius-finance.md)
* [ความเสี่ยงของ Kagla Finance](../undefined/how-to-use-algems-nastr-farming/kagla-finance.md)
* [ความเสี่ยงของ Arthswap](../undefined/how-to-use-algems-nastr-farming/arthswap.md)