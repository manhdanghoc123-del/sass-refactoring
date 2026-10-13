# Dự Án Chuyển Đổi CSS Sang SASS/SCSS Chuẩn Cấu Trúc

Dự án thực hành refactor lại file CSS truyền thống sang SASS/SCSS nâng cao, áp dụng các kỹ thuật:
- **Variables**: Quản lý màu sắc, font chữ, hiệu ứng tập trung.
- **Mixins**: Tái sử dụng các đoạn CSS như style button, box-shadow.
- **Nesting & Partials**: Chia nhỏ mã nguồn thành các file `_filename.scss` giúp dễ bảo trì.
- **Cấu trúc thư mục**: Phân chia theo `abstracts`, `base`, `layout`, `components`.

## Lệnh Biên Dịch SASS CLI

```bash
# Biên dịch và tự động theo dõi thay đổi (Watch Mode)
sass scss/main.scss css/main.css --watch
