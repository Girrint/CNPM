# (Git) HỆ THỐNG QUẢN LÝ PHIÊN BẢN

---

## 1. Khái niệm chính

### Phiên bản (Version)

Là các trạng thái khác nhau của dự án theo thời gian

Giúp:

Xem lại lịch sử

Khôi phục trạng thái cũ

### Hệ thống quản lý phiên bản (VCS)

Là phần mềm giúp:

Lưu lại mọi thay đổi mã nguồn

Theo dõi ai sửa gì

So sánh các phiên bản

Khôi phục dữ liệu bị mất

=> Ứng dụng: không chỉ code mà còn thiết kế, tài liệu,...

## 2.3 loại hệ thống VCS
 
### 1. Cục bộ (Local VCS)

- Lưu version trên máy cá nhân

- Có thể làm thủ công (đổi tên folder)

- Có công cụ hỗ trợ: RCS

=> Nhược điểm:

- Không hỗ trợ làm việc nhóm

- Khó quản lý khi nhiều version

### 2. Tập trung (Centralized VCS - CVCS)

- Có 1 server trung tâm

- Client:

  - tải về

  - sửa

  - gửi lại server

=> Ưu:

Hỗ trợ làm việc nhóm

=> Nhược:

Server lỗi → tê liệt toàn bộ

Mất server → có thể mất dữ liệu

Ví dụ:

- CVS

- SVN

### 3. Phân tán (Distributed VCS - DVCS)

- Mỗi máy client chứa:

  - toàn bộ repo

  - lịch sử version

 => ✔ Ưu:

- Không cần mạng vẫn commit được

- Server hỏng vẫn khôi phục được

- Làm việc với nhiều repo

=> Ví dụ:

- Git

- Mercurial

- Darcs

|Loại|Lưu ở đâu|Làm việc nhóm|Phụ thuộc server|
|----|---------|-------------|----------------|
|Cục bộ|Máy|cá nhân|❌|❌|
|Tập trung|Server|✔|✔ (rất phụ thuộc)|
|Phân tán|Mọi máy|✔|❌|

---

## 1.6 Bài tập

### Câu 1.1 Các đặc điểm của hệ thống quản lý phiên bản cục bộ. Phát biểu nào không đúng?

A. Có thể thực hiện thủ công

B. Không hỗ trợ trong môi trường cộng tác nhiều người

C. Có thể dùng phần mềm để quản lý phiên bản kiểu cục bộ

(D.) Các phiên bản của dự án được lưu tập trung trên một máy server 

### Câu 1.2 Các đặc điểm của hệ thống quản lý phiên bản tập trung. Phát biểu nào không đúng?

A. Các phiên bản của dự án được lưu tập trung trên máy server

(B.) Các máy client sẽ chứa tất cả các phiên bản của thư mục dự án cùng với lịch sử thay đổi  

C. Máy client không thể tải phiên bản của dự án về, khi máy server không hoạt động

D. Hỗ trợ làm việc cộng tác nhiều người

### Câu 1.3 Các đặc điểm của hệ thống quản lý phiên bản phân tán. Phát biểu nào không đúng?

A. Các máy client sẽ chứa toàn bộ các phiên bản của dự án, cùng lịch sử thay đổi

B. Hỗ trợ làm việc cộng tác nhiều người

C. Các phiên bản của dự án được lưu trên máy server

(D.) Bạn không thể tạo và lưu phiên bản khi không có kết nối mạng tới máy server

### Câu 1.4 Tìm trang chủ của các phần mềm quản lý phiên bản.

|Tên phần mềm|Trang chủ|
|------------|---------|
|RCS|https://www.gnu.org/software/rcs/|
|CVS|https://www.nongnu.org/cvs/|
|SVN|https://subversion.apache.org/|
|Git|https://git-scm.com/|
|Mercurial|https://www.mercurial-scm.org/|
|Darcs|http://darcs.net/|
