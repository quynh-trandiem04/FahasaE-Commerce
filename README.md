# 📚 Fahasa Bookstore Website

Dự án giao diện website bán sách Fahasa được phát triển bằng HTML, CSS và JavaScript thuần. Website bao gồm các trang chính như trang chủ, giỏ hàng, tài khoản người dùng và danh mục sản phẩm.

## 🌟 Tính năng chính

### 📖 Trang chủ (index.html)

- **Banner quảng cáo**: Hiển thị các chương trình khuyến mãi
- **Flash Sale**: Khu vực giảm giá có đồng hồ đếm ngược
- **Danh mục sản phẩm**: 10 danh mục sách phổ biến
- **Bảng xếp hạng Manga**: Hiển thị top người chơi
- **Bảng xếp hạng bán chạy**: Sách bán chạy theo từng thể loại
- **Gợi ý sách**: Grid layout hiển thị sách đề xuất
- **Tìm kiếm thông minh**: Autocomplete với gợi ý theo danh mục

### 🛒 Giỏ hàng (cart.html)

- **Trạng thái giỏ trống**: Hoạt hình xe đẩy ngủ với hiệu ứng Z
- **Giao diện thân thiện**: Nút "Mua sắm ngay" để quay về trang chủ
- **Responsive design**: Tối ưu cho mọi thiết bị

### 👤 Tài khoản (account.html)

- **Dashboard cá nhân**: Thống kê với biểu tượng cú mèo
- **Thông tin hồ sơ**: Form chỉnh sửa thông tin cá nhân
- **Layout ngang**: Form được bố trí theo chiều ngang hiện đại
- **Dropdown sinh nhật**: Đầy đủ ngày, tháng, năm

### 📂 Danh mục (category.html)

- **Hiển thị sản phẩm**: Layout grid cho các sản phẩm
- **Bộ lọc**: Lọc theo giá, thể loại, tác giả
- **Phân trang**: Điều hướng trang dễ dàng

## 🚀 Cách sử dụng

### Yêu cầu hệ thống

- Trình duyệt web hiện đại (Chrome, Firefox, Safari, Edge)
- Không cần server backend (chạy trực tiếp với file HTML)

### Cài đặt và chạy

1. **Clone repository**

   ```bash
   git clone https://github.com/quynh-trandiem04/GiaoDienFahasa.git
   cd GiaoDienFahasa
   ```

2. **Mở trực tiếp bằng trình duyệt**

   - Cách 1: Double-click vào file `index.html`
   - Cách 2: Chuột phải → "Open with" → Chọn trình duyệt
   - Cách 3: Kéo thả file vào trình duyệt

3. **Sử dụng Live Server (khuyên dùng)**

   ```bash
   # Cài đặt Live Server (nếu dùng VS Code)
   # Extension: Live Server by Ritwick Dey

   # Hoặc dùng Python
   python -m http.server 8000

   # Hoặc dùng Node.js
   npx live-server
   ```

### Điều hướng website

#### 🏠 Trang chủ (index.html)

- **URL**: `/index.html` hoặc `/`
- **Mô tả**: Trang chủ chính với đầy đủ tính năng
- **Tính năng**:
  - Tìm kiếm sách với gợi ý thông minh
  - Xem flash sale và sản phẩm khuyến mãi
  - Duyệt danh mục sản phẩm
  - Xem bảng xếp hạng

#### 🛒 Giỏ hàng (cart.html)

- **URL**: `/cart.html`
- **Mô tả**: Trang giỏ hàng với trạng thái trống
- **Tính năng**:
  - Hiển thị hoạt hình xe đẩy ngủ
  - Nút quay về mua sắm

#### 👤 Tài khoản (account.html)

- **URL**: `/account.html`
- **Mô tả**: Trang quản lý tài khoản cá nhân
- **Tính năng**:
  - Dashboard thống kê
  - Chỉnh sửa thông tin cá nhân
  - Form sinh nhật với dropdown

#### 📂 Danh mục (category.html)

- **URL**: `/category.html`
- **Mô tả**: Trang danh mục sản phẩm
- **Tính năng**:
  - Hiển thị sản phẩm theo grid
  - Bộ lọc và tìm kiếm

## 📁 Cấu trúc thư mục

```
Fahasa/
├── 📄 index.html          # Trang chủ
├── 📄 cart.html           # Trang giỏ hàng
├── 📄 account.html        # Trang tài khoản
├── 📄 category.html       # Trang danh mục
├── 📄 README.md           # File hướng dẫn này
└── 📁 assets/
    ├── 📁 css/
    │   ├──  main.css        # CSS chính cho trang chủ
    │   ├──  cart.css        # CSS cho trang giỏ hàng
    │   ├──  account.css     # CSS cho trang tài khoản
    │   ├──  category.css    # CSS cho trang danh mục
    │   ├──  base.css        # CSS cơ bản, biến CSS
    │   └──  reset.css       # CSS reset browser
    ├── 📁 img/
    │   └──  [Hình ảnh local]   # Các hình ảnh cục bộ
    └── 📁 fonts/
        └──  [Font files]      # Các file font tùy chỉnh
```
