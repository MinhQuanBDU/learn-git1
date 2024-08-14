Step 1: Git init 
Step 2 : git checkout -b Develop
- Tạo nhánh mới có tên là develop
Step3 : Commit code 
- Git add file -> add từng file 1
- Git add . -> add all file
- git commit -m "Message"

Step 4 : Add remote
- git remote add origin 

Step 5: Push Code
-git push origin

-> Làm xong task
Login task

Các câu lệnh git cơ bản : 
- git branch -d tên_nhánh -> Xóa nhánh
- git checkout -b tên_nhánh -> tạo mới 1 nhánh và chuyển sang nhánh đó 
- git branch -> Xem danh sách nhánh
- git check out tên_nhánh -> chuyển nhánh
- git commit -m "Nội dung message" -> Commit code (Note : Để commit code thì phải add trước )
- git push origin tên_nhánh -> đẩy code lên nhánh (origin là tên remote mà chúng ta đặt)
- git pull orgin tên_nhánh -> Pull code (kéo code) mới nhất của nhánh đó về local
- git add . -> add nhiều file cùng 1 lúc
- git add fileName -> add một file
- git remote add tên_nhánh link_remote -> Thêm mới một remote