# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Nguyễn Khánh Đức
- **Mã số sinh viên:** 24810320072
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.6: HỆ THỐNG QUẢN LÝ MƯỢN TRẢ SÁCH THƯ VIỆN
(LIBRARY MANAGEMENT SYSTEM)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="881" height="562" alt="Screenshot 2026-11-13 180759" src="https://github.com/user-attachments/assets/a326565f-b6f8-4f06-8d38-7141f6cf36c1" />

- Giao diện khi thêm đầu sách
<img width="885" height="559" alt="Screenshot 2026-11-13 180829" src="https://github.com/user-attachments/assets/8c44df54-7e65-4c2d-af1e-4d37897f4a2c" />

- Giao diện quản lí độc giả
<img width="871" height="563" alt="Screenshot 2026-11-13 180839" src="https://github.com/user-attachments/assets/15d1c132-24ed-4eef-83ec-7bb5de2b8a94" />

- Giao diện quản lí mượn/trả sách
<img width="880" height="561" alt="Screenshot 2026-11-13 180842" src="https://github.com/user-attachments/assets/708e6c1d-89c7-4c81-899a-1b58e32d3645" />

- Giao diện quản lí cảnh báo quá hạn
<img width="874" height="553" alt="Screenshot 2026-11-13 180847" src="https://github.com/user-attachments/assets/79b42d68-2c1f-482c-a9f8-9c94595d9672" />

## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `LibraryDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `DbConnection.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
