# CÔNG NGHỆ PHẦN MỀM

## GIỚI THIỆU

### 1.1 Công nghệ phần mềm là gì?
Công nghệ phần mềm (Software Engineering) là một ngành kỹ thuật, liên quan đến tất cả các khía cạnh của sản xuất phần mềm, từ giai đoạn sơ khai (lấy và phân tích yêu cầu) cho đến giai đoạn sau cùng (vận hành và bảo trì).

#### Quá trình sản xuất phần mềm gồm các giai đoạn nào?

Các giai đoạn của quá trình sản xuất phần mềm được gọi là Vòng đời phát triển phần mềm (Software Development Life Cycle - SDLC), gồm 6 giai đoạn chính.

[image](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjB5_BBJ-k-wmhw9_3MrWgXNtcg4WMM9vPYxvog2kBmG2xXlVuYq2Ge8_gcyj7bOpbr0ZgRZUP356NdTGmUeAh0Xn3aRJfI0vFT3fCdUyGZcozjwZxyCWhUnT6XBagBomiw8YDHD19m0EL3A4EDW9GTDUDXxo_zwxYLkl-dksAUWBsG66560Mf_dodoVWM/s584/SDLC.jpg)

- Lấy và phân tích yêu cầu

- Thiết kế

- Lập trình

- Kiểm thử

- Triển khai

- Vận hành và Bảo trì

|Giai đoạn|Công việc chính|
|---------|---------------|
|Lấy & Phân tích yêu cầu (Analysis)|Làm việc với khách hàng để xác định phần mềm phải làm gì. Kết quả là tài liệu đặc tả yêu cầu về tính năng, giao diện và hiệu suất của phần mềm.|
|Thiết kế (Design)|Chuyển yêu cầu thành bản vẽ kỹ thuật. Thiết kế cơ sở dữ liệu, kiến trúc hệ thống, thuật toán và giao diện người dùng.|
|Lập trình (Implementation)|Các lập trình viên sử dụng các ngôn ngữ lập trình để viết mã dựa trên bản thiết kế đã có.|
|Kiểm thử (Testing)|Tìm và sửa lỗi. Đảm bảo phần mềm chạy đúng, ổn định và đáp ứng đúng yêu cầu ban đầu của khách hàng.|
|Triển khai (Deployment)|Cài đặt phần mềm vào môi trường thực tế, bàn giao cho khách hàng và hướng dẫn họ cách sử dụng sản phẩm.|
|Vận hành & Bảo trì (Maintenance)|Theo dõi hệ thống, sửa các lỗi phát sinh sau khi dùng, cập nhật tính năng mới hoặc nâng cấp để tương thích với công nghệ mới.|

### 1.2 Tại sao lập trình giỏi là chưa đủ?

- Tính quy mô (scalability): Một đoạn mã chạy tốt cho 10 người dùng có thể sập ngay lập tức khi có một triệu người dùng. Lập trình giỏi không cứu được tình huống này nếu kiến trúc hệ thống không tốt. Do đó, bạn cần phải có kiến thức chuyên sâu để lựa chọn và thiết kế kiến trúc hệ thống phù hợp.

- Tính dễ bảo trì (maintainability): Mã nguồn của bạn viết ra hôm nay, nhưng 3 năm sau người khác (hoặc chính bạn) phải đọc lại để nâng cấp. Nếu mã nguồn chỉ “chạy được” mà không dễ đọc, dễ hiểu, thì nó như một mớ bòng bong, một đống rác công nghệ. Điều này đòi hỏi bạn phải biết cách viết mã theo các tiêu chuẩn (SOLID, DRY, KISS), đặt tên theo chuẩn, viết chú thích đầy đủ, xây dựng hệ thống kiểm thử tự động (unit test). Bạn phải thay đổi tư duy từ “viết mã cho máy chạy được” sang “viết mã cho người hiểu được”.

- Làm việc nhóm (collaboration): Một sản phẩm phần mềm lớn cần hàng trăm người làm chung. Nếu bạn lập trình giỏi mà không tuân thủ quy trình, không viết tài liệu, không biết cách quản lý phiên bản (Git), bạn sẽ trở thành “vật cản” cho cả tập thể.

### 1.3 Thảo luận thêm về Khoa học máy tính và Công nghệ phần mềm

Khoa học máy tính (Computer Science) và Công nghệ phần mềm (Software Engineering) là 2 ngành khác nhau, nhưng nó có sự giao thoa rất lớn. Tuy nhiên, về bản chất, chúng tập trung vào những mục tiêu khác nhau.

|Đặc điểm|Khoa học máy tính|Công nghệ phần mềm|
|--------|-----------------|------------------|
|Trọng tâm|Lý thuyết, thuật toán, kiến trúc máy tính và cách dữ liệu được xử lý.|Quy trình xây dựng, vận hành và bảo trì hệ thống phần mềm thực tế.|
|Câu hỏi chính|Tại sao máy tính làm được điều này? hoặc Làm sao để giải bài toán này nhanh nhất?|Làm sao để xây dựng phần mềm này hiệu quả, ít lỗi và dễ mở rộng cho hàng triệu người dùng?|
|Công việc điển hình|Nghiên cứu AI, phát triển ngôn ngữ lập trình mới, tối ưu hóa thuật toán phức tạp.|Thiết kế hệ thống (System Design), quản lý dự án, kiểm thử (Testing), triển khai (DevOps).|
|Công cụ chính|Toán học rời rạc, cấu trúc dữ liệu, logic học.|Quy trình Agile/Scrum, Git, CI/CD, các công cụ quản trị dự án.|

### 1.4 Một số thách thức của các dự án CNPM

- Vượt quá ngân sách: Chi phí thực tế cao hơn rất nhiều so với dự tính ban đầu

- Trễ tiến độ: Dự án không thể bàn giao đúng hạn cho khách hàng

- Chất lượng kém: Phần mềm thường xuyên gặp lỗi, và không đáp ứng đúng yêu cầu người dùng

- Khó bảo trì: Mã nguồn viết ra khó đọc, khó sửa, tạo nên “đống rác công nghệ”

### 1.5 Đạo đức nghề nghiệp

Trong Công nghệ phần mềm, đạo đức nghề nghiệp là trách nhiệm đảm bảo an toàn và quyền lợi cho người dùng.

Các kỹ sư phần mềm thường tuân theo bộ quy tắc đạo đức của ACM/IEEE-CS.

- Tính an toàn và bảo mật (Security): Kỹ sư có trách nhiệm bảo vệ dữ liệu người dùng, tránh rò rỉ thông tin cá nhân

- Tính tin cậy (Efficiency & Reliability): Phần mềm trong các lĩnh vực như ngân hàng hay y tế phải chạy ổn định tuyệt đối, vì sai sót có thể gây mất mát tài sản hoặc sinh mạng

- Tính minh bạch: Không cài đặt các mã độc, phần mềm gián điệp hoặc các tính năng lén lút thu thập thông tin

### 1.6 Một phần mềm như thế nào là có chất lượng?

- Tính dễ bảo trì (maintainability):

  - Phần mềm phải dễ chỉnh sửa, dễ cập nhật khi yêu cầu của khách hàng thay đổi

  - Mã nguồn phải sạch, tuân thủ các chuẩn như SOLID, DRY, KISS

  - Có tài liệu hướng dẫn đầy đủ

- Tính bảo mật và tin cậy (security & reliability)

  - Bảo vệ dữ liệu người dùng và đảm bảo phần mềm hoạt động ổn định, không gây thiệt hại khi có sự cố

  - Cần bảo mật từ khâu thiết kế, có khả năng chống lại các cuộc tấn công và tự phục hồi sau lỗi

- Tính hiệu quả (efficiency)

  - Phần mềm không làm lãng phí tài nguyên hệ thống (CPU, RAM, đĩa cứng)

  - Tối ưu hóa thuật toán và tốc độ xử lý

- Tính dễ sử dụng (usability)

  - Phần mềm phải có giao diện thân thiện, dễ dùng và phù hợp với đối tượng người dùng

  - Có thiết kế giao diện (UI) và trải nghiệm (UX) tốt, có hướng dẫn sử dụng rõ ràng

### 1.7 Bài tập và câu hỏi

#### Bài tập 1. Bạn sẽ lựa chọn theo Công nghệ phần mềm hay Khoa học máy tính? Tại sao?

#### Câu hỏi 1.1 Dưới đây là các giai đoạn phát triển phần mềm. Phát biểu nào không đúng?

A. Lấy và phân tích yêu cầu; Thiết kế

B. Lập trình; Kiểm thử

(C.) Họp nhóm dự án

D. Triển khai; Vận hành và Bảo trì

#### Câu hỏi 1.2 Một số thách thức của các dự án CNPM. Phát biểu nào không đúng?

A. Vượt quá ngân sách

B. Trễ tiến độ

C. Chất lượng kém

(D.) Dễ bảo trì 

#### Câu hỏi 1.3 Một phần mềm như thế nào là có chất lượng? Phát biểu nào không đúng?

A. Tính hiệu quả (efficiency)

(B.) Tính khó bảo trì (non maintainability)

C. Tính bảo mật và tin cậy (security & reliability)

D. Tính dễ sử dụng (usability)
