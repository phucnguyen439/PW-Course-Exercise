# Version Control System
 - VCS (Version Control
System): Hệ thống quản lý
các phiên bản
## Type of Version Control System
- Local: lưu ở máy cá nhân
- Centralize: lưu ở một máy chủ tập trung
- Distributed: lưu ở nhiều máy khác nhau
# Git
## Git - three states 
- Working Directory
- Staging Area
- Repository
## Git - key takeaways
1. Khởi tạo: git init
2. Cấu hình cho 1 repo
- git config user.name “name”
- git config user.email “email”
3. Cấu hình cho toàn bộ máy tính
- git config --global user.name
“user”
- git config --global user.email
“email”
4. Thêm file vào vùng staging:
- Thêm 1 file: git add <file_name>
- Thêm toàn bộ: git add .
5. Xem trạng thái file: git status
6. Commit: git commit -m”message”
7. Kiểm tra lịch sử commit: git log
## Git - commit convention
- convention: <type>: <short_description>
- type: loại commit
* chore: sửa nhỏ lẻ, chính tả, xóa file không dùng tới,...
* feat: thêm tính năng mới, test case mới
* fix: sửa lỗi 1 test trước đó
- short_description: mô tả ngắn gọn (50 kí tự), tiếng Anh hoặc tiếng Việt không dấu.
# Javascript basic
## Variable
1. Variable = biến, dùng để lưu trữ giá trị, có thể thay đổi giá trị được.
2. Cách khai báo:
- var <ten_bien> = <gia tri>;
- let <ten_bien> = <gia tri>;
3. Phạm vi của biến
-  var: phạm vi toàn cục (global)
-  let: phạm vi trong cặp ngoặc {}
## Constant
1. Constant = hằng số. Dùng để khai báo các giá trị không thể thay đổi.
2. Cách khai báo
-  const <name> = <value>
## Data types
1. Data type = kiểu dữ liệu.
2. Có 8 loại kiểu dữ liệu: String, Number, Bigint, Boolean, Undefined, Null, Symbol, Object.
## Comparison operator
1. Comparison operator = toán tử so sánh.
2. Dùng để so sánh giá trị giữa 2 biến với nhau. Kết quả sẽ trả về Boolean (true hoặc false).
3. Các toán tử so sánh:
- So sánh hơn kém: >, <
- So sánh bằng: ==, ===,!=, !==, >=, <=
## Unary operator = toán tử một ngôi.
1. Dùng để tăng hoặc giảm giá trị
2. Cách sử dụng:
-  i++ bằng với i=i+1
-  i-- bằng với i=i-1
## Arithmetic operator
1. Arithmetic operator = toán tử số học.
2. Cách sử dụng:
- Dùng tính toán giá trị biểu thức
- Các phép toán: +, -, *, /
## Conditional
1. Conditional = điều kiện, dùng để kiểm tra có nên thực hiện một đoạn logic không
2. Cú pháp: if (<điều kiện>) { // code }. Nếu điều kiện đúng, sẽ chạy đoạn code
## Loops
1. Loops = vòng lặp, Dùng để thực hiện một đoạn logic một số lần nhất định
2. Cú pháp: for(<khởi tạo>; <điều kiện dừng>; <điều kiện tăng>) { // code}
## Format code
- Mac: Option + Shift + F
- Window: Alt + Shift + F
