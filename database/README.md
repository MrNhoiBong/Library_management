# 📚 Hướng Dẫn Tạo Cơ Sở Dữ Liệu Thư Viện bằng MySQL Workbench

File `Libmanagement.sql` chứa các câu lệnh SQL dùng để khởi tạo cơ sở dữ liệu cho hệ thống quản lý thư viện. Hướng dẫn này sẽ giúp bạn import file này vào MySQL Workbench để tạo database.

## 🛠️ Yêu Cầu

- Đã cài đặt [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
- Đã cài đặt MySQL Server và có thể kết nối được

## 🚀 Các Bước Thực Hiện

### 1. Mở MySQL Workbench và kết nối đến server

- Khởi động MySQL Workbench
- Click vào kết nối (ví dụ: `Local instance MySQL`)
- Nhập mật khẩu nếu được yêu cầu

### 2. Import file SQL

- Vào menu **File** → **Open SQL Script**
- Chọn file `Libmanagement.sql` từ máy tính
- File sẽ mở ra trong một tab mới

### 3. Chạy script để tạo database

- Kiểm tra lại nội dung file nếu cần
- Nhấn nút ⚡ **Execute the selected portion of the script** hoặc nhấn `Ctrl + Shift + Enter`
- Chờ quá trình thực thi hoàn tất

### 4. Kiểm tra kết quả

- Vào tab **Schemas** bên trái
- Click nút refresh 🔄 nếu chưa thấy database mới
- Mở rộng database để xem các bảng đã được tạo

## ✅ Hoàn Tất

Sau khi thực hiện xong, bạn đã có một cơ sở dữ liệu thư viện sẵn sàng để sử dụng cho ứng dụng backend hoặc các truy vấn quản lý.

---

📌 *Lưu ý:* Nếu file có lỗi khi chạy, hãy kiểm tra lại cú pháp SQL hoặc đảm bảo rằng phiên bản MySQL của bạn tương thích với script. Và server database phải chạy ở cổng 3307

