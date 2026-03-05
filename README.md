# Docker-for-Developer
# # Git Version Control
# # Git First time setup 
# # ก าหนดข้อมูลผู ้ใช้
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

# # ค าสั ่งเช็คข้อมูลที่ก าหนดไว
git config  --list
git config  --global --list




# # Set Default branch “main”

# # ตั ้งค่าให้ branch หลักชื่อ “main”
git config --global init.defaultBranch main

# # ตรวจสอบหลังตั ้งค่า
git config  --list

# # ตรวจสอบหลังตั ้งค่า
 git config --list --show-origin
## A add สำเร็จ U ยังไม่ได้ add
 git add file.txt
 git status

 git commit -m "main:fix login error:release 1"

 git log
