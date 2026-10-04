# QUẢN LÍ THƯ VIỆN + VĂN HÓA ĐỌC — GIAI ĐOẠN 1

Bản nâng cấp hoàn chỉnh từ bộ V2 đang chạy.

## Có sẵn
- Quản lý sách: thêm/sửa/xóa, ảnh bìa, tìm kiếm, QR, nhập/xuất Excel
- Bạn đọc: thêm/sửa/xóa, QR, thẻ bạn đọc, hồ sơ đọc
- Mượn/trả, mượn nhanh, trả nhanh, giới hạn 5 sách đang mượn
- Kệ sách, lớp học, báo cáo, xuất Excel
- Văn hóa Đọc: điểm, hoạt động, huy hiệu, khen thưởng, bảng xếp hạng

## Tài khoản mặc định
- admin / admin123

## Chạy local
```bash
pip install -r requirements.txt
python app.py
```

Không đưa file database cũ vào bộ code này. Khi chạy local, SQLite sẽ tạo `library.db` cạnh `app.py`. Trên Render, dùng `DATABASE_URL` nếu đã cấu hình PostgreSQL.
