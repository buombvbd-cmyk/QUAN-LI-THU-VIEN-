# QUẢN LÍ THƯ VIỆN + VĂN HÓA ĐỌC

Bộ code hoàn chỉnh để đưa lên GitHub/Render.

## Chạy trên máy
1. Cài Python 3.11+.
2. Mở CMD tại thư mục dự án.
3. Chạy `pip install -r requirements.txt`.
4. Chạy `python app.py` hoặc `run.bat`.
5. Mở http://127.0.0.1:5000

Tài khoản mặc định: admin / admin123

## Database
- Nếu có biến môi trường `DATABASE_URL`, ứng dụng dùng PostgreSQL.
- Nếu không có, ứng dụng dùng SQLite `library.db` và tự tạo khi chạy lần đầu.

## Tính năng Văn hóa Đọc
- Hồ sơ đọc sách
- 20 điểm cho mỗi lượt trả sách thành công
- Hoạt động cảm nhận/giới thiệu/video/sân khấu hóa
- Huy hiệu theo số lượt đọc: 1, 5, 10, 20, 50
- Khen thưởng
- Bảng xếp hạng theo lớp/toàn trường
