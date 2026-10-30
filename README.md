# baitap5.4
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI TẬP 5.4: HỆ THỐNG QUẢN LÝ TIỆN ÍCH DỊCH VỤ & KHÁCH SẠN(HOTEL MANAGEMENT SYSTEM)

---

## KẾT QUẢ THỰC HÀNH

- Giao diện chính
<img width="1289" height="794" alt="GD" src="https://github.com/user-attachments/assets/8164584a-bba4-4f2b-a4bc-9718c32eb8d3" />


- Xác nhận thông tin khách hàng chưa có trong hệ thống - khách hàng mới
<img width="1284" height="788" alt="CN1" src="https://github.com/user-attachments/assets/02572e2a-7eaf-4c92-b050-cf1f114d6671" />


- Xác nhận thông tin đặt phòng thành công
<img width="1283" height="792" alt="CN2" src="https://github.com/user-attachments/assets/a1e62566-e357-4705-a51a-a21eb4f2f432" />


- Xem số tiền tạm tính (tiền phòng + dịch vụ đã sử dụng)
<img width="1150" height="694" alt="CN3" src="https://github.com/user-attachments/assets/af14f7be-fa43-41e6-ac13-c974b8f175cd" />


- Xác nhận thanh toán thành công + trạng thái phòng chuyển sang dọn dẹp
<img width="1145" height="720" alt="CN4" src="https://github.com/user-attachments/assets/d250e674-5230-4f39-b846-133fe025afc2" />


- Giao diện chọn các loại phòng khác nhau
<img width="1154" height="710" alt="KQ" src="https://github.com/user-attachments/assets/2054e191-471a-42fe-862c-1072b39eabf4" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `HotelDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `DatabaseHelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
