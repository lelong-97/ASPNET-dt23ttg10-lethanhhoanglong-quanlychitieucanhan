# 💸 ASP.NET Web Project – Quản Lý Chi Tiêu Cá Nhân

## 👨‍🎓 Thông tin sinh viên

- **Họ tên:** Lê Thành Hoàng Long  
- **Lớp:** DT23TTG10  
- **Mã học phần:** 220064 – Chuyên đề ASP.NET  
- **Giảng viên hướng dẫn:** ThS. Đoàn Phước Miền  

---

## 🎯 Mục tiêu của dự án

Dự án xây dựng một website giúp người dùng:

- Quản lý toàn bộ quá trình chi tiêu cá nhân một cách trực quan.
- Theo dõi và phân tích tài chính qua biểu đồ và bảng thống kê.
- Tối ưu hóa ngân sách thông qua các công cụ gợi ý thông minh.
- Lưu trữ dữ liệu về thu nhập, chi tiêu và danh mục tài chính.

---

## 🛠️ Công nghệ sử dụng

- **Ngôn ngữ lập trình:** C#  
- **Framework:** ASP.NET Core 6.0 (Web Application)  
- **IDE:** Visual Studio 2022  
- **Cơ sở dữ liệu:** SQL Server

### Thư viện / SDK sử dụng:

| Tên thư viện                | Chức năng                                         |
|----------------------------|----------------------------------------------------|
| Bootstrap 4.6              | Giao diện responsive, dễ sử dụng                   |
| FontAwesome                | Biểu tượng giao diện hiện đại                      |
| Chart.js                   | Hiển thị biểu đồ thống kê                          |
| Newtonsoft.Json            | Xử lý JSON từ API                                  |
| CloudinaryDotNet           | Upload hình ảnh lên Cloudinary                     |


### API tích hợp:

- **Cloudinary API** – lưu trữ hình ảnh trực tuyến

---

## 📁 Cấu trúc thư mục

QUANLYCHITIEU_ASPNET/
│
├── Controllers/ # Điều hướng và xử lý logic
├── Models/ # Các lớp mô hình dữ liệu (Entity)
├── Views/ # Giao diện người dùng (Razor Pages)
├── wwwroot/ # Tài nguyên tĩnh (CSS, JS, hình ảnh)
├── Services/ # Xử lý API, Excel, Cloudinary...
├── Migrations/ # Thư mục quản lý dữ liệu Entity Framework
├── appsettings.json # Chuỗi kết nối CSDL, cấu hình API
├── Program.cs, Startup.cs # Cấu hình ứng dụng ASP.NET Core
├── setup/ # Tài liệu hướng dẫn cài đặt, dữ liệu mẫu
│ └── InstallationGuide.pdf
└── README.md # File hướng dẫn tổng quan



---

## 🚀 Hướng dẫn cài đặt & chạy dự án

### ✅ Chạy bằng Visual Studio

1. Mở file `*.sln` trong Visual Studio 2022.
2. Kiểm tra chuỗi kết nối SQL Server trong `appsettings.json`.
3. Khởi tạo CSDL (nếu cần):  
dotnet ef database update

less
Sao chép
Chỉnh sửa
4. Nhấn **Start** hoặc **F5** để chạy ứng dụng trên trình duyệt.

> **Lưu ý:** Đảm bảo máy đã cài đặt .NET 6.0 SDK.

---

## 📊 Tính năng chính của hệ thống

- **Dashboard:** Tổng quan tình hình tài chính cá nhân.
- **Quản lý giao dịch:** Thêm, sửa, xóa khoản thu/chi.
- **Quản lý danh mục:** Tạo nhóm chi tiêu, phân loại thu nhập.
- **Ngân sách:** Đặt và theo dõi ngân sách theo tháng.
- **Thống kê:** Biểu đồ phân tích theo tháng/năm.

---

## 📬 Thông tin liên hệ

- **Họ tên:** Lê Thành Hoàng Long  
- **Email:** lelong9730@gmail.com  
- **Số điện thoại:** 0584765228
