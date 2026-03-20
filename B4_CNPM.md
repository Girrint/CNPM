# TỔNG QUAN VỀ GIT

---

## 1. Git là gì?

Git là hệ thống quản lý phiên bản phân tán (DVCS)

Dùng để:

Theo dõi thay đổi mã nguồn

Làm việc nhóm hiệu quả

## 2. Tính năng chính của Git

- Lưu lịch sử chi tiết → quay lại phiên bản cũ

- Làm việc nhóm → nhiều người cùng code

- Phân nhánh (branch) → phát triển độc lập

- Hợp nhất (merge) → gộp code

- Bảo mật → commit không bị thay đổi

- Phân tán → mỗi máy có full repo, làm offline được

## 3. Cài đặt Git

Cách cài:

Tải tại: https://git-scm.com/

Cài như phần mềm bình thường

Kiểm tra:

```bash
git --version
# hoặc
git -v
```

=> Hiện version → đã cài thành công

 ## 4. Nhúng Git vào dự án
 
Bước chính:

Tạo thư mục dự án (vd: TeoShop)

Mở CMD → di chuyển vào thư mục:

```bash
cd TenThuMuc
```

Khởi tạo Git:

```bash
git init
```

=> Kết quả:

Xuất hiện thư mục ẩn .git

## 5. Khái niệm quan trọng

- Repository (Repo)

Là kho chứa toàn bộ lịch sử dự án

Thực chất là thư mục .git

=> Chứa:

Lịch sử commit

Thông tin phiên bản

- Ý cần nhớ (rất dễ thi)

```git init``` → khởi tạo Git

```git --version``` hoặc ```git -v``` → kiểm tra Git

```.git``` → nơi Git lưu dữ liệu

Repo = thư mục đã có Git

---

## 2.4 Bài tập

### Bài tập 2.1 Thực hành các cài đặt trong bài học.

### 2.2 Lệnh nào được sử dụng để nhúng Git vào thư mục dự án?

(A.) git init

B. git --init

C. git initialize

D. git embed

### 2.3 Lệnh nào sử dụng để kiểm tra trên máy tính đã có phần mềm Git
hay chưa?

A. git ver

B. git version

(C.) git -v

D. git --ver

### 2.4 Trong Git, kho lưu trữ (repo, repository) là gì?

A. Là thư mục dự án

B. Là thư mục dự án đã được nhúng Git

C. Là thư mục cài đặt phần mềm Git

(D.) Là thư mục .git (trong thư mục dự án)
