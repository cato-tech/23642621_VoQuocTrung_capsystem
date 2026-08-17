# CAB System – Các vấn đề cần làm rõ

## 1. Tính cước

* Cước chuyến xe được tính dựa trên những yếu tố nào?
* Giá cước có thay đổi theo loại xe, khoảng cách, thời gian hoặc khu vực không?
* Có áp dụng phụ phí vào giờ cao điểm, ngày lễ hoặc khi nhu cầu tăng cao không?
* Khi giá cước thay đổi trong lúc chuyến đang diễn ra thì hệ thống áp dụng mức giá nào?

## 2. Phân công tài xế

* Tiêu chí nào được dùng để xác định tài xế phù hợp?
* Hệ thống ưu tiên khoảng cách gần, thời gian đến dự kiến hay kinh nghiệm tài xế?
* Nếu nhiều tài xế cùng phù hợp thì hệ thống chọn tài xế nào?
* Tài xế có bao nhiêu thời gian để phản hồi yêu cầu chuyến?
* Nếu tài xế từ chối hoặc không phản hồi thì hệ thống sẽ tìm tài xế tiếp theo như thế nào?

## 3. Hủy chuyến

* Khách hàng có thể hủy chuyến ở những trạng thái nào?
* Tài xế có được phép hủy chuyến không?
* Khi hủy chuyến có phát sinh phí hay không?
* Trường hợp tài xế hủy chuyến thì hệ thống xử lý như thế nào?
* Có giới hạn số lần hủy hoặc quy định xử lý khách hàng/tài xế hủy nhiều lần không?

## 4. Thanh toán

* Doanh nghiệp muốn tích hợp với nhà cung cấp thanh toán nào?
* Những phương thức thanh toán điện tử nào được hỗ trợ?
* Khi thanh toán thất bại, khách hàng được phép thử lại bao nhiêu lần?
* Nếu thanh toán thất bại nhưng tiền đã bị trừ thì hệ thống xử lý như thế nào?
* Khi nào giao dịch được xác định là thành công hoặc thất bại?

## 5. Mất kết nối và lỗi hệ thống

* Nếu khách hàng hoặc tài xế mất kết nối mạng trong lúc đang thực hiện chuyến thì hệ thống xử lý như thế nào?
* Nếu tài xế mất kết nối trong khi đang di chuyển, trạng thái chuyến được cập nhật ra sao?
* Nếu hệ thống không thể gửi thông báo thì có cơ chế gửi lại không?
* Nếu dịch vụ thanh toán hoặc thông báo bên ngoài bị lỗi, hệ thống CAB có tiếp tục hoạt động không?

## 6. Thông báo

* Hệ thống hiện cần hỗ trợ những kênh thông báo nào?
* Khi nào khách hàng và tài xế bắt buộc phải nhận thông báo?
* Nếu người dùng không nhận được thông báo thì hệ thống có gửi lại không?
* Doanh nghiệp có muốn bổ sung SMS, Email, Push Notification hoặc các kênh khác trong tương lai không?

## 7. Quản lý vị trí tài xế

* Hệ thống cập nhật vị trí tài xế với tần suất bao lâu?
* Vị trí của tài xế được lưu trong bao lâu?
* Ai được phép xem dữ liệu vị trí tài xế?

## Stakeholders

| Stakeholder | Vai trò / trách nhiệm |
|---|---|
| **Ban Giám đốc** | Định hướng, phê duyệt và đưa ra các quyết định quan trọng của dự án |
| **Quản lý vận hành** | Quản lý hoạt động đặt xe, tài xế và xử lý các vấn đề phát sinh |
| **Nhân viên vận hành** | Quản lý khách hàng, tài xế, phương tiện và chuyến đi |
| **Khách hàng** | Đăng ký, đặt xe, theo dõi chuyến, thanh toán và đánh giá tài xế |
| **Tài xế** | Nhận chuyến, cập nhật trạng thái, vị trí và hoàn thành chuyến |
| **Nhà cung cấp thanh toán** | Cung cấp dịch vụ thanh toán điện tử |
| **Cơ quan quản lý** | Giám sát việc tuân thủ các quy định liên quan |
| **Nhà cung cấp hạ tầng công nghệ** | Cung cấp và duy trì hạ tầng hệ thống |
| **Nhà cung cấp dịch vụ thông báo** | Cung cấp các kênh SMS, Email và Push Notification |

#Stakeholder matrix
<table>
<tr>
<td align="center" width="50%">

### HIGH POWER – LOW INTEREST
**Keep Satisfied**

- Government / Regulatory
- Payment Provider

</td>
<td align="center" width="50%">

### HIGH POWER – HIGH INTEREST
**Manage Closely**

- Senior Management
- Operations Manager

</td>
</tr>

<tr>
<td align="center" width="50%">

### LOW POWER – LOW INTEREST
**Monitor**

- Potential Customers
- Tech / Infrastructure
- Advertising Partners

</td>
<td align="center" width="50%">

### LOW POWER – HIGH INTEREST
**Keep Informed**

- Operations Staff
- Customers / Riders
- Drivers

</td>
</tr>
</table>

# Phạm vi dự án CAB System trong 7 tuần
1. Trong phạm vi dự án
Khách hàng
Đăng ký, đăng nhập.
Cập nhật thông tin cá nhân.
Nhập điểm đón và điểm đến.
Lựa chọn loại xe.
Tạo yêu cầu đặt xe.
Theo dõi trạng thái chuyến đi.
Xem thông tin tài xế.
Xem lịch sử chuyến đi.
Xem số tiền phải trả.
Đánh giá tài xế sau chuyến.
Tài xế
Đăng nhập.
Cập nhật hồ sơ và thông tin phương tiện.
Bật/tắt trạng thái sẵn sàng nhận chuyến.
Nhận thông báo chuyến mới.
Chấp nhận hoặc từ chối chuyến.
Cập nhật trạng thái chuyến:
Đã đến điểm đón.
Đã đón khách.
Đang di chuyển.
Hoàn thành chuyến.
Cập nhật vị trí để hỗ trợ tìm tài xế gần khách hàng.
Nhân viên vận hành
Quản lý khách hàng.
Quản lý tài xế.
Quản lý phương tiện.
Theo dõi các chuyến đang diễn ra.
Theo dõi trạng thái tài xế.
Hỗ trợ xử lý chuyến bị lỗi.
Tra cứu lịch sử giao dịch.
Phân quyền nhân viên.
Đặt xe và phân công tài xế
Tiếp nhận yêu cầu đặt xe.
Tìm tài xế dựa trên vị trí và trạng thái sẵn sàng.
Ưu tiên tài xế phù hợp/gần khách hàng.
Nếu tài xế từ chối hoặc không phản hồi → tìm tài xế khác.
Nếu không tìm được tài xế → thông báo cho khách hàng.
Thanh toán
Tính cước chuyến đi.
Hỗ trợ tiền mặt và thanh toán điện tử.
Tích hợp với một nhà cung cấp thanh toán bên ngoài.
Không lưu thông tin nhạy cảm của thẻ/tài khoản.
Xử lý trường hợp thanh toán thất bại.
Thông báo
Thông báo khi yêu cầu đặt xe được tiếp nhận.
Thông báo khi có tài xế nhận chuyến.
Thông báo khi tài xế đến điểm đón.
Thông báo khi chuyến hoàn thành.
Thông báo kết quả thanh toán.
Thông báo chuyến mới cho tài xế.
Báo cáo cơ bản
Số lượng chuyến.
Doanh thu.
Tỷ lệ chuyến hoàn thành.
Tỷ lệ hủy.
Hiệu quả hoạt động của tài xế.
2. Ngoài phạm vi trong 7 tuần
Để tránh phạm vi quá lớn, các chức năng sau không ưu tiên triển khai trong phiên bản đầu tiên:
Nhiều nhà cung cấp thanh toán cùng lúc.
Nhiều nhà cung cấp SMS/Email/Push cùng lúc.
Hệ thống khuyến mãi, voucher, mã giảm giá phức tạp.
Chương trình thành viên/tích điểm.
Định giá động nâng cao bằng AI/Machine Learning.
Dự đoán nhu cầu bằng AI.
Chat trực tiếp giữa khách hàng và tài xế.
Hệ thống bản đồ/GPS tự xây dựng.
Ứng dụng riêng cho từng nền tảng nếu vượt quá khả năng của nhóm.
Các loại dịch vụ mới ngoài dịch vụ đặt xe cơ bản.
3. Phạm vi cốt lõi
Có thể tóm tắt phạm vi 7 tuần bằng chuỗi:
