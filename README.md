# Portfolio cá nhân – Dương Ngọc Trọng

## 1. Mô tả dự án

Website Portfolio cá nhân giới thiệu Dương Ngọc Trọng, định hướng Developer, AI Enthusiast và Product Builder.

Website được xây dựng bằng HTML5 và CSS3, tập trung vào việc giới thiệu thông tin cá nhân, kỹ năng công nghệ, các sản phẩm đã tham gia phát triển và thông tin liên hệ.

Portfolio thể hiện quá trình học tập, nghiên cứu và phát triển sản phẩm trong các lĩnh vực Web Development, Artificial Intelligence và Web3.

## 2. Chức năng

- Giới thiệu thông tin cá nhân và định hướng phát triển công nghệ.
- Trình bày các kỹ năng và công nghệ sử dụng.
- Hiển thị 3 dự án tiêu biểu dưới dạng thẻ (Project Cards), bao gồm hình ảnh, mô tả và công nghệ liên quan.
- Điều hướng nhanh tới các khu vực Giới thiệu, Kỹ năng, Dự án và Liên hệ.
- Cung cấp email và liên kết GitHub cá nhân.
- Hỗ trợ điều hướng quay lại đầu trang.
- Giao diện responsive, phù hợp với máy tính, máy tính bảng và điện thoại.

### Các dự án được giới thiệu

**1. đihát.online**

Nền tảng KTV trực tuyến với không gian 3D, hệ thống nhân vật chibi, phòng giải trí và tính năng tương tác nhiều người chơi theo thời gian thực.

Công nghệ liên quan:
- Next.js
- TypeScript
- Three.js
- Colyseus

Repository: [github.com/trongkekiwi-lang/dihat-online](https://github.com/trongkekiwi-lang/dihat-online)

**2. Kim Chi App**

Ứng dụng Kim Chi thuộc hệ sinh thái sản phẩm cá nhân, được giới thiệu trong portfolio như một dự án phát triển ứng dụng và trải nghiệm người dùng.

**3. Devil Pepe**

Dự án memecoin trên blockchain Solana với chủ đề Halloween, tập trung vào xây dựng website, nhận diện thương hiệu, hình ảnh truyền thông và phát triển cộng đồng Web3.

Công nghệ và lĩnh vực liên quan:
- Solana
- Web3
- Website Development
- Branding

## 3. Công nghệ sử dụng

Website Portfolio sử dụng các công nghệ:

- **HTML5:** Xây dựng cấu trúc và nội dung website.
- **CSS3:** Thiết kế giao diện và định dạng các thành phần.
- **CSS Flexbox:** Xây dựng bố cục điều hướng và các thành phần giao diện.
- **CSS Grid:** Hiển thị danh sách dự án theo dạng lưới.
- **CSS Responsive:** Hỗ trợ hiển thị trên nhiều kích thước màn hình.
- **CSS Custom Properties:** Quản lý các biến và thuộc tính giao diện.
- **Git & GitHub:** Quản lý mã nguồn và lưu trữ dự án.

Dự án Portfolio hiện tại sử dụng HTML và CSS thuần, không yêu cầu framework JavaScript, trình quản lý gói hoặc backend.

## 4. Cấu trúc thư mục

```text
My-CV-main/
│
├── .vscode/
│   └── settings.json
│
├── assets/
│   ├── css/
│   │   └── styles.css
│   │
│   └── img/
│       ├── 86c7dc2a695caefb6dba5aef5bdd90bb.jpg
│       ├── dihat.png
│       ├── images.png
│       ├── devilpepe.png
│    
│     
│
├── docs/
│   ├── responsive-desktop.png
│   ├── responsive-mobile.png
│   └── responsive-tablet.png
│
├── index.html
├── BAOCAO-A2.1.docx
├── README.md
├── RELEASENOTE.md
└── test_report.md
```

## 5. Yêu cầu môi trường

### Chỉ xem trang web

- Trình duyệt hiện đại như Google Chrome, Microsoft Edge, Firefox hoặc Safari.
- Visual Studio Code (khuyến nghị).
- Có thể sử dụng tiện ích Live Server để chạy website trên máy tính cá nhân.

### Chạy máy chủ web cục bộ

Có thể sử dụng một trong các môi trường sau:

- Python 3.
- Visual Studio Code với tiện ích Live Server.
- Docker Desktop hoặc Docker Engine nếu muốn chạy bằng Docker.

Dự án không yêu cầu cài đặt thư viện hoặc dependency bổ sung.

## 6. Cài đặt

1. Tải hoặc sao chép toàn bộ mã nguồn dự án về máy tính.
2. Giải nén thư mục dự án nếu tải dưới dạng ZIP.
3. Mở thư mục dự án bằng Visual Studio Code.
4. Kiểm tra các thư mục `assets`, `docs` và tệp `index.html`.
5. Không cần cài đặt thêm dependency để chạy phiên bản hiện tại.

Nếu sử dụng Git:

```bash
git clone <URL-repository>
cd My-CV-main
```

Thay `<URL-repository>` bằng địa chỉ repository GitHub thực tế.

## 7. Cấu hình

Dự án hiện không yêu cầu:

- Tệp cấu hình `.env`.
- Cơ sở dữ liệu.
- API Key.
- Backend.
- Quy trình build hoặc bundler.

Các thành phần chính:

- Nội dung website được khai báo trong `index.html`.
- Giao diện và bố cục được định dạng trong `assets/css/styles.css`.
- Hình ảnh được lưu trữ trong `assets/img/`.
- Ảnh minh họa responsive được lưu trong `docs/`.

Khi muốn cập nhật nội dung, có thể chỉnh sửa trực tiếp trong `index.html`.

Khi muốn thay đổi giao diện, màu sắc, font chữ hoặc bố cục, chỉnh sửa tệp `assets/css/styles.css`.

Trước khi công bố website, cần kiểm tra các đường dẫn hình ảnh, email, GitHub và các liên kết dự án.

## 8. Chạy thử dự án

### Cách 1: Sử dụng Visual Studio Code

1. Mở thư mục dự án trong Visual Studio Code.
2. Cài đặt tiện ích Live Server nếu chưa có.
3. Mở tệp `index.html`.
4. Nhấn chuột phải và chọn **Open with Live Server**.
5. Website sẽ được mở trên trình duyệt.

Địa chỉ mặc định thường có dạng:

```text
http://127.0.0.1:5500/index.html
```

Cổng có thể thay đổi tùy theo cấu hình Live Server.

### Cách 2: Sử dụng Python

Tại thư mục gốc dự án, mở Terminal hoặc PowerShell.

**Windows:**

```powershell
py -m http.server 8000
```

Nếu lệnh `py` không hoạt động:

```powershell
python -m http.server 8000
```

**macOS / Linux:**

```bash
python3 -m http.server 8000
```

Sau đó mở trình duyệt tại:

[http://localhost:8000](http://localhost:8000)

Để dừng máy chủ, nhấn `Ctrl + C` trong Terminal.

## 9. Chạy bằng Docker

Dự án hiện không đi kèm Dockerfile hoặc docker-compose.yml.

Có thể sử dụng Nginx để phục vụ website tĩnh thông qua Docker.

Yêu cầu:
- Docker Desktop hoặc Docker Engine.
- Thư mục dự án đã được tải về máy.

### Windows (PowerShell)

Chạy lệnh tại thư mục gốc dự án:

```powershell
docker run --rm -d --name portfolio -p 8080:80 -v "$($PWD.Path):/usr/share/nginx/html:ro" nginx:alpine
```

Mở trình duyệt tại:

[http://localhost:8080](http://localhost:8080)

Dừng container:

```powershell
docker stop portfolio
```

### macOS và Linux

Chạy lệnh:

```bash
docker run --rm -d --name portfolio -p 8080:80 -v "$(pwd):/usr/share/nginx/html:ro" nginx:alpine
```

Mở trình duyệt tại:

[http://localhost:8080](http://localhost:8080)

Dừng container:

```bash
docker stop portfolio
```

Lưu ý: Docker có thể cần tải image `nginx:alpine` trong lần chạy đầu tiên.

## 10. Kiểm tra trước khi bàn giao

Các nội dung cần kiểm tra:

- Kiểm tra website trên máy tính để bàn.
- Kiểm tra giao diện trên máy tính bảng.
- Kiểm tra giao diện trên điện thoại.
- Kiểm tra các liên kết điều hướng.
- Kiểm tra hình ảnh đại diện và hình ảnh dự án.
- Kiểm tra nội dung giới thiệu cá nhân.
- Kiểm tra thông tin email và GitHub.
- Kiểm tra bố cục CSS Grid và Flexbox.
- Đảm bảo website không bị lỗi hiển thị khi thay đổi kích thước màn hình.

Tài liệu kiểm tra chi tiết được trình bày trong tệp [test_report.md](./test_report.md).

Tài liệu cập nhật phiên bản được lưu trong [RELEASENOTE.md](./RELEASENOTE.md).

Ảnh minh họa giao diện responsive được lưu trong thư mục `docs/`.

## 11. Thông tin liên hệ

- **Họ và tên:** Dương Ngọc Trọng
- **Email:** [trongkekiwi@gmail.com](mailto:trongkekiwi@gmail.com)
- **GitHub:** [github.com/trongkekiwi-lang](https://github.com/trongkekiwi-lang)
- **Địa điểm:** Việt Nam
- **Định hướng:** Web Development, Artificial Intelligence và Web3.

---

**© 2026 Dương Ngọc Trọng**

*Build Ideas. Create Products. Keep Learning.*