## **1\. Kiểm tra Increment Sprint 14**

| Mã | Kết quả | Trạng thái |
| :---: | ----- | :---: |
| SC-61 | 80/80 đạt, không lỗi cao | Done |
| SC-62 | 70/78 đạt, còn 8 lỗi | Chưa Done |
| SC-63 | 74/80 đạt, còn lỗi cao | Chưa Done |
| SC-64 | 60/60 đạt, chờ kiểm tra che SĐT | Chưa Done |
| SC-65 | 42/42 đạt, quyền riêng tư đạt | Done |

Done khi đáp ứng đủ DoD: staging, kiểm thử quan trọng đạt, không lỗi cao, đạt kiểm tra quyền riêng tư.

Sai sót Review cũ:

* Gọi tất cả hạng mục Done dù chưa đạt DoD.  
* Biến Review thành nghiệm thu, thiếu trao đổi hai chiều.  
* Hứa thực hiện mọi Feedback, gây cam kết thiếu căn cứ.

## **2\. Sprint Review – 60 phút**

| Thời gian | Nội dung |
| :---: | ----- |
| 5 phút | Nhắc Sprint Goal |
| 10 phút | Kiểm tra DoD |
| 20 phút | Demo Increment |
| 15 phút | Trao đổi Feedback |
| 10 phút | Tổng hợp, điều chỉnh Backlog |

Vai trò: PO xem xét ưu tiên; Developers demo sản phẩm; Scrum Master hỗ trợ sự kiện.

### **Feedback Log**

| Mã | Feedback | Hướng xử lý |
| ----- | ----- | ----- |
| F-01 | Tự động hóa 90% | Làm rõ cách tính, kiểm tra dữ liệu |
| F-02 | Chuyển sớm | Xác định điều kiện chuyển |
| F-03 | Còn lộ SĐT | Kiểm tra quyền riêng tư |
| F-04 | Thiếu lịch sử đa kênh | Làm rõ phạm vi lịch sử |
| F-05 | P95 bị lệch | Thu thập số liệu và xác định ngưỡng |

Feedback chưa phải cam kết; PO xem xét giá trị và ưu tiên trước khi cập nhật Product Backlog.

## **3\. Sprint Retrospective – 60 phút**

| Thời gian | Hoạt động |
| ----- | ----- |
| 5 phút | Thống nhất nguyên tắc không đổ lỗi |
| 15 phút | Data: xem dữ liệu Sprint |
| 15 phút | Insight: tìm nguyên nhân |
| 15 phút | Action: chọn cải tiến |
| 10 phút | Follow-up: thống nhất cách đo |

Dữ liệu: Đổi quy tắc qua tin nhắn, staging Ngày 4, Integration Test Ngày 8, an toàn tâm lý 2,8/5.

### **Action Item**

| Mã | Hành động | Theo dõi và bằng chứng |
| :---: | ----- | ----- |
| A-01 | Ghi nhận và thống nhất thay đổi tại nơi làm việc chung | Scrum Master theo dõi; kiểm tra nhật ký cuối Sprint |
| A-02 | Tích hợp và kiểm thử sớm từ Ngày 1 | Developers thực hiện; kiểm tra nhật ký tích hợp và lỗi phát hiện sớm |

## **4\. So sánh kỹ thuật Retro**

| Tiêu chí | Start-Stop-Continue | 4Ls |
| ----- | :---: | ----- |
| An toàn | Khá | Tốt |
| Tìm nguyên nhân | Trung bình | Khá |
| Tạo hành động | Dễ | Cần bước bổ sung |
| Thời lượng | 45–60 phút | 60 phút |
| Người ít nói | Nên viết trước | Có thể viết ẩn danh |

Lựa chọn: Dùng 4Ls vì mức an toàn chỉ 2,8/5; sau đó dùng Start-Stop-Continue để chốt tối đa 2 Action Item.

## **5\. Chu trình Inspect and Adapt**

Truy vết:

* F-04: Làm rõ nhu cầu lịch sử đa kênh; đo bằng tỷ lệ tình huống kiểm tra đạt yêu cầu.  
* A-02: Tích hợp sớm; đo thời điểm tích hợp, số lỗi phát hiện sớm và lỗi tồn đọng cuối Sprint.

Xử lý ngoại lệ: Thiếu dữ liệu thì ghi rõ và xác minh; phát hiện lỗi cao hoặc chưa đạt quyền riêng tư thì không công bố Done.

