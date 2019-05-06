FinalProject
# Project - Shopku

#github username

นาย ธนกฤต พลสุเจริญ >> smthtk1997

นาย กฤษมาส ด่านขจร >> kitkitsamas

นางสาว ยศวดี ปัญญานิมิตร >> yotsawadee97

นาย สมัชญ์ พูนขวัญ >> khanend

# สมาชิก
| รหัสนิสิต  | ชื่อ  |
| ------------ | ------------ |
| 5810450733 | นาย ธนกฤต พลสุเจริญ |
| 5910450042 | นาย กฤษมาส ด่านขจร |
| 5910451189 | นางสาว ยศวดี ปัญญานิมิตร |
| 5910451227 | นาย สมัชญ์ พูนขวัญ |

# สรุป
เว็บ `shop ku` จัดทำเพื่อเป็นการศึกษาและพัฒนาในรูปแบบงานโปรเจคของรายวิชา Web-tech
[Link Shop-ku](http://www.shop-ku.esy.es)

# การทำงาน
`Adimin` 
- ดูภาพรวมระบบได้ อาทิเช่น จำนวน user, จำนวนสินค้าในระบบ,orderทั้งหมด,จำนวนแอดมิน order ล่าสุดที่ทำการซื้อขายในระบบ

- จัดการสินค้าได้ อาทิเช่น อนุญาติให้ผู้ใช้ขายสินค้า ลบสินค้า
โดยมีสถานะ active ,suspend(ไม่ผ่านให้ผู้ใช้แก้ไข)


- จัดการผู้ใช้ ให้สามารถเข้าใช้ หรือ ไม่ให้เข้าใช้ได้
  โดยจัดการสถานะ เป็น active และ suspend(เข้าระบบไมไ่ด้)

- สามารถเพิ่ม adminคนอื่นๆได้ ดูรายชื่อแอดมินด้วยกันได้

๊`User`
- ผู้ใช้สามารถขายและซื้อสินค้าได้ใน user เดียวกัน
- ผู้ใช้ต้อง login ทุกครั้งก่อนสั่งซื้อสินค้า,ขายสินค้า
- ผู้ใช้ดูรายละเอียดสินค้าได้ ,จัดการสินค้าใน orderได้
- สามารถซ่อนสินค้าได้ ลบสินค้าได้ 
- ดูชื่อผู้ขาย,ติดต่อผู้ขายได้
- สามารถสั่งซื้อสินค้าได้
- แก้ไขข้อมูลส่วนตัวได้
- ดูประวัติการสั่งซื้อได้ ,รหัสสั่งซื้อ


# Api reference
- facebook api 
- api การซื้อ-ขายของ

# License
- Apache,laragon,xampp