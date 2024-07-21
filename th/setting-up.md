---
คำอธิบาย: อ่านวิธีการตั้งค่าด้วย
---

# 🛠️ ตั้งค่าการใช้งาน

ถ้าคุณเจอปัญหาอะไรก็ตาม, เช็คที่ [คำถามที่พบบ่อย](faq.md).

ก่อนที่จะเริ่มตั้งค่าเช็กให้แน่ใจว่าคุณมี Discord แค่อันเดียวที่เปิดอยู่ (**ไม่ใช่ในเบราว์เซอร์**)
และ เปิด "สถานะกิจกรรม" ในการตั้งค่าของ Discord แล้ว:

![image](.gitbook/assets/1.PNG)

## ขั้นตอนเริ่มต้น

* เข้าเว็ป [Discord Developer portal](https://discord.com/developers/applications).
* กด **New Application** ทางด้านขวาบน.

![](https://user-images.githubusercontent.com/2225711/161050202-c796103d-6712-401e-be96-3f3712512375.png)

* ใส่ชื่อที่จะต้องการให้โชว์, ชื่อจะโชว์ข้างล่างสถานะ "กำลังเล่น". กด **Create**.
* กดคัดลอก **Application ID** และ วางในฟิล์ด **ID**, แล้วก็กด **เชื่อมต่อ**.&#x20;

![](https://user-images.githubusercontent.com/2225711/161050341-8169af53-5d3f-44d6-b745-cc711e8d1476.png)

* ถ้าทำถูกต้อง, สถานะใน Discord ควรขึ้นว่า "กำลังเล่นเกม **\[ตามด้วยชื่อที่ใส่ตอนแรก]**". ถ้าเจอปัญหา, เช็กที่ [คำถามที่พบบ่อย](faq.md).
  * สถานะจะไม่โชว์ถ้าอยู่ใน โหมดไม่ระบุ. 
  * ถ้าคุณมีสถานะที่กำหนดเองอยู่แล้ว(อันที่ตั้งอีโมจิได้), มันจะเป็นอันแรกที่ถูกโชว์ แทนที่จะเป็น CustomRP. สถานะของ Custom RP ยังสามารถเช็คได้ในโปรไฟล์ถ้ามีสถานะที่กำหนดเองอยู่แล้ว.
* ถึงขั้นตอนนี้คุณสามารถกรอกฟิล์ดอื่นได้แล้ว (สามารถกรอกอะไรก็ได้ตามที่คุณต้องการ):
  * **Details**: บรรทัดแรกที่จะโชว์ในสถานะ ข้างล่างชื่อที่ใส่ใน Application.
  * **State**: บรรทัดสองที่จะโชว์ในสถานะ. จะกลายเป็นบรรทัดแรกถ้า Details ไม่ได้กรอกอะไร.
  * **Party**: โชว์ตัวเลข `(X of Y)` ข้างหลังบรรทัด State. ถ้า Party ไม่ได้ใส่อะไร, Party จะไม่โชว์ขึ้นมา.
  * **Timestamp**: ตัวจับเวลาที่จะนับตามรูปแบบ Timestamp ที่เลือก. จะโชว์เวลาข้างล่าง Details และ State" `xx:xx:xx ผ่านไป` หรือ `xx:xx:xx เหลืออยู่`. สามารถโชว์เวลาถึงแค่ `23:59:59` ก่อนที่จะเริ่มนับใหม่ที่ `00:00`.
  * **ภาพขนาดใหญ่ และ เล็ก**: เป็นรูปภาพที่จะโชว์ทางด้านซ้ายของสถานะ. ถ้าทั้งสองภาพถูกตั้งค่าให้โชว์, ภาพเล็กจะย่อขนาดอยู่ด้านขวาล่างของภาพใหญ่.
    * **Key**: จะเป็นช่องกรอก URL ที่ใช้ให้รูปภาพโชว์ (แนะนำ, เนื่องจากคุณสามารถใช้ GIFs ได้ด้วย) หรือ จะเป็นชื่อ Asset ภาพที่จะใช้ก็ได้.

      * _ถ้าเลือกใช้ URL:_ ถ้ารูปภาพที่จะใช้อยู่ในอินเตอร์เน็ตแล้ว, วาง **ลิ้งค์โดยตรง** ในฟิล์ด
      (โดยปกติคัดลอกลิ้งค์โดยตรง โดย กดคลิกขวา และ เลือก "คัดลอกลิ้งค์รูปภาพ"). ถ้ารูปภาพของคุณอยู่ในคอมพิวเตอร์ยังไม่ได้อัปโหลดไปที่อินเตอร์เน็ต, ให้ใช้เว็ปไซต์ที่สามารถอัปโหลดไฟล์รูปภาพได้ เช่น (Imgur, ImageShack, อื่น ๆ). ไม่ **แนะนำ** ให้ใช้ภาพที่อัปโหลดใน Discord หรือ ช่อง Discord, ลิ้งค์ของรูปภาพจะหมดอายุใน 2 สัปดาห์.
        * ถ้าการเชื่อมต่อค้างที่ "กำลังอัพเดทสถานะ...", อาจจะเป็นเพราะว่า URL ที่กรอกในฟิล์ดนั้นยาวเกินไป หรือ มันไม่ใช่ลิ้งค์โดยตรง. ถ้าคุณแน่ใจว่าเป็นลิ้งค์โดยตรงแน่นอน, ให้ใช้ URL Shortner หรือ ย่อ URL.
      * _ถ้าเลือกใช้ Art Asset:_ ที่หน้าเว็ปของที่ตั้งชื่อ application ตอนแรก กดเข้าไปที่ application ที่ตั้ง,เลือก Rich Presence ตามด้วย Art Assets และ อัปโหลดสัก 1 รูปภาพข้างล่าง Rich Presence Assets. ใน CustomRP, ให้มองหา **อัปโหลด Assets** ใน หน้าต่างไฟล์ (สามารถกด Ctrl+U แทนได้) หลังจากกดจะเปิดหน้าเว็ปให้อัปโหลดรูปภาพ(ถ้าช่อง ID กรอกแล้ว) ทำตามขั้นตอนข้างบน.
        * โน้ต 1: แม้ว่าโดยปกติแล้วภาพจะสามารถใช้งานได้ทันที, แต่ในบางกรณีอาจจะต้องรอหลายชั่วโมงถึงจะใช้งานได้.
        * โน้ต 2: คุณสามารถตั้งชื่อ Asset ได้มากกว่า 999 ตัวอักษร,แต่แอปจะซัพพอร์ตแค่ 256 ตัวอักษรเท่านั้น.
    * **Text**: ตัวหนังสือที่จะโชว์ขึ้นเมื่อเอาเคอร์เซอร์เม้าส์ ไปชี้ที่รูปภาพ (หรือ กดค้างที่ภาพ ถ้าเป็นมือถือ).
  * **Buttons**:
    * **Text**: A text displayed on the button.
    * **URL**: A URL that the button will open upon clicking.
* Hit **Update Presence** (or **Connect** if you aren't already connected).
* Congratulations, you're wonderful!

### I use more than one Discord client, what do I do?

If you have more than one Discord client and you wish your presence to show up on a different account from the one app chose automatically, please press **Disconnect**, then hold Ctrl+Shift keys on your keyboard and press **Connect**. A window with a number input will pop up, put a number 1, close the window, and press **Connect** again, without Ctrl+Shift. In case it's a wrong account again, try number 0, then 2 and so on up until 9.

Please note that if you have multiple Discord clients run on startup, pipe number assigned to each client might not be persistent from boot to boot and can change depending on which client started first. To prevent that, you can either start additional clients manually, or use Windows Task Scheduler to delay the startup of the clients.

If you have 2 accounts that you use at the same time and want for each of them to have a different presence, then follow these steps:

* Set up your main account first with the instructions above.
* Grab the latest **portable (.zip)** version of CustomRP (either from [website](https://www.customrp.xyz) or [GitHub releases page](https://github.com/maximmax42/Discord-CustomRP/releases/latest)) and unpack it anywhere.
  * This only works with versions 1.16 and newer.
* Open `Start Second Instance.bat` or create a shortcut to CustomRP.exe with an argument `--second-instance` (or `-2`).
* Set up the program the same way you did your main instance.
  * Tip: If you already have a preset you would want to use with your second instance, you can edit the bat file or the shortcut to include the path to the preset. Example: `CustomRP.exe -2 "C:\Some Folder\preset.crp"` (quotation marks around the path are necessary if the path has spaces in it).
* Before connecting, change the pipe as described earlier and connect.

If you use 3 or more accounts at the same time, then... why? But also if enough of you will nag me, I'll add support for using more instances.

## Notes

* If you don't want to set up small or large image, leave all related fields in the program blank.
* If large image is not set, small image settings will be ignored.
