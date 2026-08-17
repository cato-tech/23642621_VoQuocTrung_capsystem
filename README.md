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

# Stakeholder matrix
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

## Phạm vi dự án

Dự án CAB System được triển khai trong **7 tuần**, tập trung xây dựng các chức năng cốt lõi của nền tảng đặt xe và đảm bảo quy trình từ đặt xe đến hoàn thành chuyến.

### 1. Trong phạm vi

* **Khách hàng:** Đăng ký, đăng nhập, cập nhật thông tin, đặt xe, theo dõi chuyến, xem lịch sử, thanh toán và đánh giá tài xế.
* **Tài xế:** Quản lý hồ sơ và phương tiện, cập nhật trạng thái sẵn sàng, nhận/từ chối chuyến và cập nhật trạng thái chuyến.
* **Nhân viên vận hành:** Quản lý khách hàng, tài xế, phương tiện, chuyến đi và hỗ trợ xử lý sự cố.
* **Đặt xe và phân công:** Tiếp nhận yêu cầu, tìm tài xế phù hợp, ưu tiên tài xế gần khách hàng và tự động tìm tài xế khác khi tài xế từ chối hoặc không phản hồi.
* **Thanh toán:** Tính cước và hỗ trợ thanh toán bằng **tiền mặt hoặc thanh toán điện tử** thông qua nhà cung cấp bên ngoài.
* **Thông báo:** Gửi thông báo về yêu cầu đặt xe, tài xế nhận chuyến, tài xế đến điểm đón, hoàn thành chuyến và kết quả thanh toán.
* **Báo cáo:** Thống kê số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế.
* **Bảo mật:** Xác thực người dùng, phân quyền nhân viên, bảo vệ dữ liệu và ghi log các thao tác quan trọng.

### 2. Ngoài phạm vi

Các chức năng sau chưa được ưu tiên trong giai đoạn 7 tuần:

* Định giá động bằng AI/Machine Learning.
* Hệ thống khuyến mãi, voucher và tích điểm.
* Chat trực tiếp giữa khách hàng và tài xế.
* Xây dựng hệ thống bản đồ/GPS riêng.
* Tích hợp nhiều nhà cung cấp thanh toán cùng lúc.
* Tích hợp nhiều nhà cung cấp thông báo cùng lúc.
* Các dịch vụ khác ngoài dịch vụ đặt xe cơ bản.

### 3. Quy trình nghiệp vụ cốt lõi

**Đặt xe → Tìm tài xế → Phân công tài xế → Thực hiện chuyến → Hoàn thành chuyến → Tính cước → Thanh toán → Đánh giá → Kết thúc**

### 4. Mục tiêu phạm vi trong 7 tuần

Hoàn thành một phiên bản **MVP** có thể vận hành được toàn bộ quy trình đặt xe cơ bản, đồng thời có kiến trúc đủ linh hoạt để phát triển thêm các chức năng trong các giai đoạn tiếp theo.
