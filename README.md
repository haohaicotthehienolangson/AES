1. Giới thiệu 
AES là một mã phổ biến được dùng cho mã hóa và giải mã dữ liệu. Và dưới đây là một đoạn code đơn giản để miêu tả chức năng và cách hoạt động của nó. 
2. Chức năng cơ bản
Trang web được phát triển với các chức năng như: 
+ Cho phép người dùng nhập bằng tay hoặc tải file lên từ máy 
+ Yêu cầu người dùng nhập khóa và chọn mã hóa hoặc giải mã 
+ In ra kết quả khi đã mã hóa hoặc giải mã và lưu lại file 
3. Kỹ thuật, công nghệ 
Đoạn code trên sử dụng các công nghệ như HTML5, JavaScript, CSS nhằm định hình trang web cũng như tăng độ bắt mắt của giao diện. Đặc biệt đối với JavaScript:
  + CryptoJS: Đây là thư viện JavaScript cho phép mã hóa và giải mã dữ liệu bằng nhiều thuật toán, bao gồm AES.
  + Hàm encryptText(): Lấy khóa và văn bản từ người dùng.
  + Sử dụng CryptoJS.AES.encrypt để mã hóa văn bản. Kết quả được lưu vào resultContent.
  + Cập nhật văn bản kết quả hiển thị và cho phép tải về tệp.
  + Hàm decryptText(): Tương tự như hàm mã hóa, nhưng sử dụng CryptoJS.AES.decrypt để giải mã văn bản.
    Kết quả được lưu vào resultContent và cập nhật giao diện.
  + Hàm downloadFile(): Tạo một đối tượng Blob từ resultContent, cho phép tạo tệp từ dữ liệu.
  + Tạo một URL cho Blob và tạo một liên kết ẩn để người dùng có thể tải về tệp.
  4. Hình ảnh minh họa
    ![image](https://github.com/user-attachments/assets/7e8bdad3-0cde-4c45-b6af-30ae224e9ca3)

