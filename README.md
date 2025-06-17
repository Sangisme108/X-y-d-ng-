# 📱 Website Bán Thiết Bị Điện Tử

## 📌 Mục tiêu dự án
Xây dựng một website thương mại điện tử cho phép người dùng mua các thiết bị điện tử như điện thoại, laptop, tai nghe,... Giao diện thân thiện, dễ sử dụng và hỗ trợ đặt hàng trực tuyến.

---

## 🛠️ Các chức năng chính (Yêu cầu chức năng)

### Người dùng:
- Đăng ký, đăng nhập, đăng xuất
- Xem danh sách sản phẩm theo danh mục
- Xem chi tiết sản phẩm
- Thêm sản phẩm vào giỏ hàng
- Đặt hàng và theo dõi đơn hàng
- Tìm kiếm sản phẩm

### Quản trị viên:
- Đăng nhập admin
- Thêm/sửa/xóa sản phẩm
- Quản lý đơn hàng
- Quản lý người dùng
- Quản lý danh mục sản phẩm

---

## 🔒 Yêu cầu phi chức năng

- Hệ thống dễ mở rộng (modular, có thể thêm nhiều loại sản phẩm mới)
- Tốc độ tải trang nhanh (dưới 3 giây)
- Responsive – chạy tốt trên điện thoại, máy tính bảng, laptop
- Giao diện người dùng dễ sử dụng, thân thiện

---

## 💻 Công nghệ sử dụng

- **Frontend:**
  - HTML, CSS, JavaScript
  - Bootstrap
  - Vue.js 

- **Backend:**
  - Laravel (PHP Framework)
  - MySQL

- **Khác:**
  - Git & GitHub để quản lý phiên bản
  - XAMPP hoặc Laravel Valet để chạy cục bộ
 

---

## 🚀 Hướng dẫn chạy dự án

```bash
# Clone project
git clone https://github.com/your-username/ten-du-an.git
cd ten-du-an

# Cài đặt các package
composer install
npm install && npm run dev

# Cấu hình môi trường
cp .env.example .env
php artisan key:generate

# Tạo database
php artisan migrate --seed

# Chạy server
php artisan serve
