# AppServer1


1. Các thư viện chính (Dependencies)
•express: Framework tạo server web và API.
•mysql2: Driver kết nối và làm việc với cơ sở dữ liệu MySQL.
•cors: Xử lý vấn đề chia sẻ tài nguyên chéo nguồn (Cross-Origin Resource Sharing), giúp App Android (hoặc trình duyệt) gọi được API từ IP khác.
•bcrypt: Mã hóa mật khẩu người dùng để bảo mật.
•jsonwebtoken: Tạo và xác thực Token (JWT) cho chức năng đăng nhập/đăng ký.
•multer: Xử lý upload file (như ảnh món ăn) từ form multipart/form-data.
•dotenv: Đọc các biến môi trường từ file .env (như cấu hình DB, Secret Key).

2. Lệnh cài đặt

   npm install express mysql2 cors bcrypt jsonwebtoken multer dotenv


3. Chạy server

  node server.js
