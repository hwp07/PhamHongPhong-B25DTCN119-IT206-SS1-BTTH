1. ## **Lý do chọn Agile**

- Với Waterfall, yêu cầu được chốt tương đối cứng từ đầu và sản phẩm thường chỉ được khách hàng xem ở cuối dự án. Khi khách thay đổi yêu cầu giữa chừng, nhóm phải sửa thiết kế, mã nguồn và kiểm thử đã thực hiện, dẫn đến tốn thời gian, tăng chi phí và phát hiện sai lệch muộn  
- Dự án GreenMart đang mở rộng từ hệ thống bán hàng truyền thống sang bán hàng đa kênh, vì vậy yêu cầu có khả năng thay đổi trong quá trình phát triển  
- Agile khắc phục:  
+ Chia dự án thành các sprint nhỏ  
+ Liên tục tạo Increment để kiểm tra  
+ Khách hàng có thể xem và phản hồi thường xuyên  
+ Product Backlog có thể thay đổi theo nhu cầu thực tế  
+ Ưu tiên những chức năng có giá trị kinh doanh cao trước  
- Kết luận: Agile đem lại hiệu quả tốt hơn vì yêu cầu kênh bán hàng có khả năng thay đổi cao, giúp nhóm nhận phản hồi sớm, điều chỉnh nhanh và giảm rủi ro làm sai sản phẩm

2. ## **Nguyên tắc làm việc theo 4 giá trị Agile**

| Thói quen hiện tại | Giá trị Agile bị đi ngược | Cách làm mới |
| ----- | ----- | ----- |
| Cả đội chỉ trao đổi qua bình luận trên phần mềm, gần như không họp trực tiếp | Cá nhân và tương tác hơn quy trình và công cụ | Tổ chức Daily Scrum ngắn hằng ngày; các vấn đề quan trọng được trao đổi trực tiếp thay vì chỉ bình luận trên phần mềm |
| Viết tài liệu đặc tả rất chi tiết trước, chỉ trình diễn sản phẩm một lần ở cuối dự án | Phần mềm chạy được hơn tài liệu đầy đủ | Chỉ duy trì tài liệu cần thiết, ưu tiên phát triển Increment chạy được và Review thường xuyên sau mỗi Sprint |
| Hợp đồng tính phí và bắt chờ 2 tuần phê duyệt mỗi khi khách muốn đổi yêu cầu | Hợp tác với khách hàng hơn đàm phán hợp đồng | PO tiếp nhận và đánh giá yêu cầu mới; thay đổi được đưa vào Product Backlog và sắp xếp lại ưu tiên |
| Khi thực tế khác với kế hoạch, đội vẫn làm đúng kế hoạch ban đầu | Đáp ứng thay đổi hơn bám theo kế hoạch | Kiểm tra kết quả sau mỗi Sprint, cập nhật Product Backlog và điều chỉnh kế hoạch cho Sprint tiếp theo |

3. ## **Khung Scrum**

- Sprint cố định: 2 tuần  
- Vì:   
+ Dự án có thời lượng ngắn (6 tuần) \-\> có thể tổ chức 3 sprint liên tiếp  
+ 2 tuần là thời gian vừa đủ để phát hiện sai lệch sớm đồng thời có đủ thời gian để nhóm phân tích, lập trình, kiểm thử và tạo increment  
+ Khách hàng có cơ hội phản hồi thường xuyên hơn   
- 3 trụ cột Scrum:  
+ Minh bạch:   
* product backlog được công khai cho đội và khách hàng  
* sprint rõ ràng  
* trạng thái công việc được cập nhật trên Scrum Board  
+ Thanh tra:  
* Daily Scrum: kiểm tra tiến độ hằng ngày  
* Sprint Review: kiểm tra Increment với GreenMart  
* Sprint Retrospective: kiểm tra cách nhóm đang làm việc  
+ Thích nghi:  
* Product Backlog được điều chỉnh dựa trên phản hồi  
* Ưu tiên có thể thay đổi giữa các Sprint  
* Nhóm cải thiện cách làm việc sau mỗi Retrospective  
- Chọn Scrum thay Waterfall vì:  
+ phù hợp hơn với sự linh hoạt thay đổi của GreenMart  
+ Scrum cho phép nhóm phát triển từng phần, nhận phản hồi sớm và điều chỉnh ưu tiên liên tục 

4. ## **Phân vai Scrum Team**

   ### **Long – Product Owner**

   **Được quyết định:**  
* Product Backlog.  
* Thứ tự ưu tiên.  
* Product Goal.  
* Những chức năng mang lại giá trị cao hơn cho GreenMart.  
  **Không được quyết định:**  
* Cách Developers thực hiện kỹ thuật.  
* Phân công công việc chi tiết cho từng Developer.  
* Tự ý thay đổi Sprint Backlog của Developers.

### **Hoa – Scrum Master**

**Được quyết định:**

* Cách hỗ trợ nhóm áp dụng Scrum hiệu quả.  
* Tổ chức và tạo điều kiện cho Scrum Events.  
* Hỗ trợ loại bỏ impediment.  
  **Không được quyết định:**  
* Ưu tiên Product Backlog thay PO.  
* Tự quyết định chức năng sản phẩm.  
* Ra lệnh cho Developers cách lập trình.

### **Developers: An, Bình, Chi, Dung**

**Được quyết định:**

* Cách thực hiện công việc kỹ thuật.  
* Cách phân chia công việc trong nhóm.  
* Sprint Backlog cần làm thế nào để đạt Sprint Goal.  
* Cách tạo Increment đáp ứng Definition of Done.  
  **Không được quyết định:**  
* Thay đổi Product Goal.  
* Tự thay đổi thứ tự ưu tiên Product Backlog.  
* Cam kết những yêu cầu sản phẩm mới thay cho PO.

5. ## **Artifacts & lịch sự kiện**

- Product Backlog

| Ưu tiên | Hạng mục | Mô tả |
| :---: | ----- | ----- |
| 1 | Tìm kiếm sản phẩm | Khách hàng tìm sản phẩm theo tên, mã hoặc từ khóa |
| 2 | Xem thông tin sản phẩm | Hiển thị tên, giá, tồn kho và thông tin cơ bản |
| 3 | Giỏ hàng | Thêm, sửa số lượng và xóa sản phẩm |
| 4 | Đặt hàng online | Khách tạo đơn hàng từ giỏ hàng |
| 5 | Thanh toán | Xử lý phương thức thanh toán cho đơn hàng |
| 6 | Theo dõi đơn hàng | Theo dõi trạng thái đơn hàng online |
| 7 | Quản lý tồn kho | Theo dõi số lượng hàng tồn |
| 8 | Báo cáo bán hàng | Thống kê doanh thu và tình hình bán hàng |

- Sprint 1:  
+ Tạo được luồng cơ bản giúp khách hàng tìm kiếm và chuẩn bị sản phẩm để đặt hàng online  
+ Sprint backlog:  
* Thiết kế giao diện tìm kiếm \- An  
* Xây dựng API/chức năng tìm kiếm \- Bình  
* Xây dựng hiển thị thông tin sản phẩm \- Chi  
* Xây dựng dỏ hàng cơ bản \- An \+ Bình  
* Kiểm thử tính năng tìm kiếm và giỏ hàng \- Dung  
* Tích hợp và sửa lỗi \- All  
- Increments: Tìm kiếm sản phẩm \-\> Xem thông tin sản phẩm \-\> Thêm sản phẩm vào giỏ hàng \-\> Thay đổi số lượng/xóa sản phẩm  
- Sự kiện:

| Sự kiện | Thời điểm | Mục đích |
| ----- | ----- | ----- |
| **Sprint Planning** | Ngày 1 | Xác định Sprint Goal và chọn Product Backlog Items cho Sprint |
| **Daily Scrum** | Mỗi ngày, 15 phút | Kiểm tra tiến độ và điều chỉnh kế hoạch trong ngày |
| **Development Work** | Trong suốt 2 tuần | Phân tích, thiết kế, lập trình, kiểm thử và tích hợp Increment |
| **Sprint Review** | Cuối ngày 10 | Trình diễn Increment cho GreenMart và thu thập phản hồi |
| **Sprint Retrospective** | Sau Sprint Review | Đánh giá cách làm việc và xác định cải tiến cho Sprint tiếp theo |

6. ## **Xử lý tình huống**

- TH1: Nhóm không lập tức dừng Sprint và thay đổi Sprint Backlog hiện tại, thay vào đó quy trình sẽ có sự thay đổi: **GreenMart gửi yêu cầu \-\> PO tiếp nhận \-\> PO đánh giá giá trị và mức độ ưu tiên \-\> đưa yêu cầu vào Product Backlog \-\> sắp xếp lại Product Backlog \-\> đưa vào Sprint tiếp theo**. Sau khi Sprint kết thúc, yêu cầu đặt hàng online sẽ được uu tiên cao hơn và có thể được chọn vào sprint tiếp theo  
- TH2:   
+ Trực tiếp thông báo đến khách hàng và tuyệt đối không trình bày tính năng chưa hoàn thành  
+ Không đưa phần chưa đạt vào Increment hoàn thành  
+ Chỉ trình bày những phần đã hoàn thành  
+ PO cập nhật lại Product Backlog dựa trên tình trạng thực tế  
+ Nhóm phân tích nguyên nhân chưa hoàn thành trong Retrospective để tránh lặp lại