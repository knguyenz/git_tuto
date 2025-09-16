# GIT TUTORIAL

## TẠO GIT REPO
a. Tạo repo trên Github
- Nhấn nút New repository
- Điền thông tin ()

b. Clone về máy 
- chọn vị trí trên máy tính để clone 
- git clone https//....

## THÊM NGƯỜI DÙNG VÀO DỰ ÁN 
- Vào repo trên Github
- Setting -> Collaborators
- Add people -> nhập username
## CÁC BƯỚC ĐỂ ĐẨY FILE LÊN (DÀNH CHO PROJECT NHỎ)
1. Clone code về máy (nếu chưa clone)
- git clone https... 
2. Thêm file
- git add . (thêm tất cả các thư mục đã thay đổi)
- git add <file> (chỉ thêm file cụ thể)
3. Mô tả thay đổi 
- git commit -m "Mô tả thay đổi" (thường viết là "[UPDATE]....")
4. push file 
- git push -u origin main 
## TRONG PROJECT LỚN
1. Pull code về
- git clone ....
2. Tạo branch mới để làm việc tránh làm hỏng nhánh main
- git branch : kiểm tra branch hiện tại 
- git checkout -b tenbranch : tạo branch mới
- git branch : kiểm tra lại 
- git add . 
- git commit - m "......"
- git push -u origin tenbranch
3. Merge code (sau khi check lỗi không có vấn đề gì)
- git checkout main
- git pull origin main: kéo code mới nhất về 
- git merge tenbranch
- git push -u origin main
4. Xóa branch sau khi merge code (nếu cần)
- git branch -d tenbranch