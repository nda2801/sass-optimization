# Thực hành Tối ưu SCSS: Variables & Mixins

Dự án mẫu thực hành tách module SCSS theo mô hình chuẩn, sử dụng Sass variables và mixins để tối ưu hóa mã CSS.

## Cấu trúc thư mục
- `scss/abstracts/`: Chứa variables và mixins dùng chung.
- `scss/base/`: Typography và base styles.
- `scss/components/`: Styles cho các components riêng biệt (`button`, `card`).
- `scss/main.scss`: Entry file import toàn bộ styles.
- `index.html`: File HTML demo hiển thị kết quả.

## Hướng dẫn biên dịch SCSS
Chạy lệnh sau nếu có cài đặt Sass CLI:
```bash
npx sass scss/main.scss css/style.css
```
