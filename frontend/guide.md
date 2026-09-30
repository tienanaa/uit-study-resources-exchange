# Frontend Guide

## 1. HTML

- Các file HTML trong `pages/` đã được tạo sẵn làm khung.
- Không tự ý đổi tên hoặc xóa file.
- Chỉnh sửa trực tiếp file được phân công.
- Nếu cần thêm trang mới, trao đổi với nhóm trước.

## 2. CSS

- CSS dùng chung: `css/global.css`, `css/components.css`
- CSS riêng từng trang: `css/pages/`
- Nếu style có thể dùng cho nhiều trang, đặt vào CSS dùng chung thay vì tạo lại.

## 3. JavaScript

- JavaScript dùng chung: `js/`
- JavaScript riêng từng trang: `js/pages/`
- Gọi API backend thông qua `js/api.js`.

## 4. Assets

- Hình ảnh và tài nguyên frontend đặt trong `assets/`.
- Không để file tài nguyên ở ngoài thư mục này.

## 5. Git

Trước khi làm:

```bash
git pull
```

Sau khi làm xong:

```bash
git add .
git commit -m "mô tả thay đổi"
git push
```

- Commit rõ nội dung thay đổi.
- Không commit file `.env`.
- Không tự ý xóa hoặc thay đổi code của người khác.
- Nếu thay đổi ảnh hưởng đến cấu trúc chung, trao đổi với nhóm trước.
