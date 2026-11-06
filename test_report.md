# BÁO CÁO KIỂM THỬ (TEST REPORT)

## 1. Thông tin chung

- **Tên dự án:** Personal Portfolio – Dương Ngọc Trọng
- **Phiên bản:** 1.0.0
- **Ngày kiểm thử:** 06/11/2026
- **Người thực hiện:** Dương Ngọc Trọng
- **Loại dự án:** Website Portfolio cá nhân
- **Công nghệ:** HTML5, CSS3

## 2. Mục tiêu kiểm thử

Kiểm tra khả năng hoạt động, tính chính xác của nội dung, giao diện và khả năng tương thích của website trên các kích thước màn hình khác nhau.

Các mục tiêu chính:

- Đảm bảo các thành phần HTML hiển thị chính xác.
- Kiểm tra điều hướng giữa các khu vực.
- Kiểm tra hình ảnh và liên kết.
- Kiểm tra bố cục CSS Grid và Flexbox.
- Kiểm tra khả năng hiển thị responsive.
- Kiểm tra thông tin cá nhân và thông tin liên hệ.

## 3. Môi trường kiểm thử

| Thành phần | Môi trường |
|---|---|
| Hệ điều hành | Windows |
| Trình duyệt | Google Chrome |
| Trình soạn thảo | Visual Studio Code |
| Local Server | Live Server |
| Ngôn ngữ | HTML5, CSS3 |
| Địa chỉ kiểm thử | http://127.0.0.1:5502/index.html |

## 4. Danh sách kiểm thử

| STT | Hạng mục | Nội dung kiểm thử | Kết quả mong đợi |
|---|---|---|---|
| 1 | Header | Hiển thị tên và logo cá nhân | Hiển thị chính xác |
| 2 | Navigation | Chọn mục Giới thiệu | Chuyển đến About |
| 3 | Navigation | Chọn mục Kỹ năng | Chuyển đến Skills |
| 4 | Navigation | Chọn mục Dự án | Chuyển đến Projects |
| 5 | Navigation | Chọn mục Liên hệ | Chuyển đến Contact |
| 6 | About | Hiển thị tên và thông tin cá nhân | Nội dung chính xác |
| 7 | Avatar | Hiển thị ảnh đại diện | Ảnh hiển thị đầy đủ |
| 8 | Skills | Hiển thị danh sách kỹ năng | Hiển thị đầy đủ |
| 9 | Projects | Hiển thị đihát.online | Hiển thị đúng |
| 10 | Projects | Hiển thị Kim Chi App | Hiển thị đúng |
| 11 | Projects | Hiển thị Devil Pepe | Hiển thị đúng |
| 12 | Project Grid | Kiểm tra bố cục các thẻ dự án | Các thẻ sắp xếp hợp lý |
| 13 | Contact | Kiểm tra liên kết Email | Mở ứng dụng email |
| 14 | Contact | Kiểm tra liên kết GitHub | Mở trang GitHub |
| 15 | Footer | Kiểm tra nút quay lại đầu trang | Chuyển về đầu trang |
| 16 | Responsive | Kiểm tra trên máy tính | Bố cục phù hợp |
| 17 | Responsive | Kiểm tra trên máy tính bảng | Bố cục thích ứng |
| 18 | Responsive | Kiểm tra trên điện thoại | Nội dung không tràn màn hình |

## 5. Kết quả kiểm thử

Các hạng mục được đánh giá theo trạng thái:

- **PASS:** Kiểm thử thành công.
- **FAIL:** Kiểm thử không thành công.
- **PENDING:** Chưa thực hiện kiểm thử.

| Hạng mục | Trạng thái |
|---|---|
| Cấu trúc HTML | PASS |
| Hiển thị Header | PASS |
| Điều hướng Navigation | PASS |
| Khu vực About | PASS |
| Khu vực Skills | PASS |
| Danh sách 3 dự án | PASS |
| Bố cục Project Grid | PASS |
| Khu vực Contact | PENDING |
| Liên kết Email | PENDING |
| Liên kết GitHub | PENDING |
| Hiển thị Footer | PENDING |
| Responsive Desktop | PENDING |
| Responsive Tablet | PENDING |
| Responsive Mobile | PENDING |

*Lưu ý: Các trạng thái PASS là kết quả dự kiến theo cấu trúc và giao diện đã kiểm tra; các mục PENDING cần được kiểm thử trực tiếp trước khi xác nhận hoàn thành.*

## 6. Các lỗi cần chú ý

| STT | Vấn đề | Hướng xử lý |
|---|---|---|
| 1 | Hình ảnh dự án không hiển thị | Kiểm tra đường dẫn trong assets/img |
| 2 | Giao diện trên điện thoại bị tràn | Điều chỉnh CSS Media Queries |
| 3 | Liên kết không hoạt động | Kiểm tra thuộc tính href |
| 4 | Bố cục dự án không cân đối | Kiểm tra CSS Grid và Flexbox |

## 7. Đánh giá

Website đã xây dựng được các thành phần chính của một Portfolio cá nhân:

- Giới thiệu thông tin cá nhân.
- Trình bày kỹ năng và công nghệ.
- Giới thiệu 3 dự án tiêu biểu.
- Cung cấp thông tin liên hệ.
- Có cấu trúc HTML5 rõ ràng và sử dụng CSS riêng.

Cần tiếp tục kiểm tra các liên kết, hình ảnh và khả năng hiển thị trên thiết bị di động trước khi bàn giao chính thức.

## 8. Kết luận

Dự án Portfolio cá nhân đã hoàn thành phần cấu trúc và nội dung cơ bản.

Báo cáo này được sử dụng làm tài liệu theo dõi quá trình kiểm thử, phát hiện lỗi và hoàn thiện sản phẩm trước khi phát hành.

---

**Người thực hiện:** Dương Ngọc Trọng  
**Email:** trongkekiwi@gmail.com  
**GitHub:** https://github.com/trongkekiwi-lang

**© 2026 Dương Ngọc Trọng**