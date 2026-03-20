# CÁC MÔ HÌNH PHÁT TRIỂN PHẦN MỀM

## 📌 Tổng quan

### Phát triển phần mềm gồm 6 công đoạn chính:

- Yêu cầu (Requirements)

- Thiết kế (Design)

- Lập trình (Coding)

- Kiểm thử (Testing)

- Triển khai (Deployment)

- Vận hành & Bảo trì (Maintenance)

=> Tùy dự án → các công đoạn được tổ chức thành các mô hình phát triển phần mềm khác nhau

---

## 📊 Các mô hình chính

### 1. Mô hình Thác nước (Waterfall)

🔹 Tuần tự, tuyến tính, không quay lại

🔹 Mỗi giai đoạn phải hoàn thành rồi mới sang bước tiếp

🔹 Phù hợp: yêu cầu rõ ràng, ổn định

👉 Nhược điểm: khó thay đổi

### 2. Mô hình chữ V (V-Model)

🔹 Mở rộng từ Waterfall

🔹 Kiểm thử song song với phát triển

🔹 Mỗi giai đoạn dev ↔ một giai đoạn test

👉 Phù hợp: hệ thống cần độ tin cậy cao

### 3. Mô hình lặp (Iterative)

🔹 Phát triển theo nhiều vòng lặp nhỏ

🔹 Mỗi vòng tạo ra phiên bản chạy được

🔹 Liên tục cải tiến dựa trên phản hồi

👉 Phù hợp: yêu cầu chưa rõ ràng

### 4. Agile / Scrum

🔹 Chia thành các Sprint (1–4 tuần)

🔹 Làm việc linh hoạt, thích ứng thay đổi

🔹 Có các khái niệm chính:

Product Backlog: danh sách chức năng

Sprint Backlog: việc trong 1 sprint

👉 Phù hợp: dự án thay đổi thường xuyên

---

## ⚙️ Mô hình Thác nước – công việc chính

### 1. Yêu cầu

Thu thập, phân tích, viết SRS

Công cụ: Word, Google Docs

### 2. Thiết kế

Kiến trúc, database, UML

Công cụ: Enterprise Architect, Figma

### 3. Lập trình

Viết code theo chuẩn (SOLID, DRY, KISS)

Công cụ: VS Code, Git

### 4. Kiểm thử

Unit, Integration, System, Acceptance

Công cụ: Selenium, Postman

### 5. Triển khai

CI/CD, đóng gói, cloud

Công cụ: Docker, Jenkins

### 6. Bảo trì

Sửa lỗi, nâng cấp, monitoring

Công cụ: Grafana, Prometheus

---

## ❗ Ý quan trọng cần nhớ (dễ thi)

### Waterfall:

✔ Tuần tự, không quay lại

✔ Phù hợp yêu cầu rõ ràng

### V-Model:

✔ Dev đi đôi với Test

### Iterative:

✔ Làm nhiều phiên bản nhỏ

### Scrum:

✔ Sprint = 1–4 tuần

✔ Linh hoạt, thích nghi

---

## 2.5 Bài tập và câu hỏi

### Bài tập 2a. Vẽ lại sơ đồ các mô hình: Thác nước, chữ V, Tăng trưởng lặp và Agile/Scrum. 

### Bài tập 2b. Mô tả công việc của mỗi công đoạn, công cụ sử dụng của mô hình Thác nước

### Câu hỏi 2.1 Về mô hình Thác nước. Phát biểu nào không đúng?

A. Mỗi giai đoạn phải được hoàn thành trước khi chuyển sang giai đoạn tiếp theo và không có sự quay lại

(B.) Không phù hợp với các dự án có yêu cầu ổn định, đã được xác định rõ ràng ngay từ đầu và không có khả năng thay đổi

C. Đây là mô hình tuần tự, các giai đoạn phát triển diễn ra theo một trình tự tuyến tính, từ trên xuống dưới như một dòng thác

D. Phù hợp với các dự án có yêu cầu ổn định, đã được xác định rõ ràng ngay từ đầu và không có khả năng thay đổi

### Câu hỏi 2.2 Trong mô hình chữ V có đề cập tới 4 loại kiểm thử. Loại kiểm thử nào sau đây không đúng?

A. Acceptance Testing

(B.) Coding Testing

C. System Testing

D. Integration Testing

### Câu hỏi 2.3 Mô hình tiếp cận lặp gồm các công đoạn sau. Phát biểu nào không đúng?

A. Requirements

(B.) Integration

C. Design & Development

D. Testing

### Câu hỏi 2.4 Trong mô hình Agile/Scrum. Phát biểu nào sau đây không đúng?

(A.) Scope: xác định phạm vi của biến

B. Sprint: một chu kỳ phát triển ngắn, thường là 1 tới 4 tuần

C. Product backlog: danh mục các chức năng của sản phẩm

D. Sprint backlog: danh mục các chức năng của một sprint
