# Bùi Tuấn Dũng — Digital Profile

Website CV cá nhân: giới thiệu, kinh nghiệm, học vấn, kỹ năng, 9 dự án và liên hệ. Giữ chân dung áo sơ mi, hiệu ứng soi robot theo con trỏ và các icon công nghệ chuyển động.

## Chạy dự án

Không cần cài thư viện hay build. Chạy trong thư mục dự án:

```bash
python3 -m http.server 8000
```

Mở http://localhost:8000. Hosting tĩnh có thể phục vụ trực tiếp thư mục gốc.

## Tệp chính

- `index.html`: cấu trúc và nội dung hồ sơ.
- `style.css`: giao diện, responsive và hoạt ảnh.
- `app.js`: tương tác soi robot, bộ lọc, chi tiết dự án, menu và liên hệ.
- `projects.js`: dữ liệu 9 dự án.
- `Bui-Tuan-Dung-CV.pdf`: CV 2 trang tải về.
- Hai tệp WebP: chân dung và lớp robot; giữ cùng kích thước khi thay ảnh.

Trên điện thoại, có thể chạm để soi hoặc dùng nút **Hiện người máy**. Hiệu ứng nền giảm khi bật chế độ giảm chuyển động và tạm dừng khi ra khỏi màn hình. Video demo có nút phát; không tự phát.

## Kiểm tra đã thực hiện

Kiểm tra cú pháp JavaScript, tệp và liên kết nội bộ; thử bộ lọc, cửa sổ chi tiết, phát video; kiểm tra menu và tràn ngang trong khung 390px; render kiểm tra PDF hai trang. Chưa kiểm tra trên điện thoại vật lý.
