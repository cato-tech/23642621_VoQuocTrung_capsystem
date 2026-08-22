## Các vấn đề/yếu điểm của hệ thống hiện tại và câu hỏi cần làm rõ

### 1. Phân công tài xế còn thủ công
- Hệ thống hiện tại đang phân công tài xế như thế nào?
- Những khó khăn lớn nhất của việc phân công tài xế thủ công là gì?

### 2. Khách hàng khó theo dõi trạng thái chuyến đi
- Hiện tại khách hàng có thể theo dõi những thông tin nào về chuyến đi?
- Hệ thống mới cần cung cấp những trạng thái nào cho khách hàng?

### 3. Thông tin thanh toán chưa được quản lý tập trung
- Hiện tại doanh nghiệp đang quản lý thông tin và lịch sử thanh toán như thế nào?
- Những vấn đề thường xảy ra trong quá trình quản lý thanh toán là gì?

### 4. Khó mở rộng hệ thống
- Hệ thống hiện tại gặp vấn đề gì khi số lượng khách hàng và tài xế tăng cao?
- Doanh nghiệp dự kiến hệ thống mới phải phục vụ bao nhiêu khách hàng và tài xế?

### 5. Chưa xác định rõ tiêu chí phân công tài xế
- Hệ thống sẽ ưu tiên tài xế dựa trên những tiêu chí nào?
- Khi có nhiều tài xế cùng phù hợp thì hệ thống sẽ lựa chọn tài xế nào?

### 6. Chưa xác định thời gian tài xế phản hồi
- Tài xế có bao nhiêu thời gian để chấp nhận hoặc từ chối chuyến?
- Nếu tài xế không phản hồi thì hệ thống sẽ xử lý như thế nào?

### 7. Chưa xác định chính sách hủy chuyến
- Khách hàng và tài xế được phép hủy chuyến trong những trường hợp nào?
- Hủy chuyến có phát sinh phí hay không?
- Nếu tài xế hủy chuyến thì hệ thống có tự động tìm tài xế khác không?

### 8. Chưa xác định cách tính cước
- Giá chuyến xe được tính dựa trên những yếu tố nào?
- Có áp dụng giá cao điểm hoặc phụ phí trong một số trường hợp không?

### 9. Chưa xác định cách xử lý khi mất kết nối
- Nếu khách hàng hoặc tài xế mất kết nối trong quá trình thực hiện chuyến thì hệ thống xử lý như thế nào?
- Nếu mất kết nối trong lúc thanh toán thì trạng thái giao dịch được xử lý ra sao?

### 10. Chưa xác định thời gian lưu trữ dữ liệu
- Dữ liệu khách hàng, tài xế, vị trí và giao dịch cần được lưu trữ trong bao lâu?
- Những dữ liệu nào cần được lưu lâu dài để phục vụ báo cáo và kiểm tra?
## Mục tiêu của nghiệp vụ

* Đáp ứng nhu cầu **đặt xe của số lượng lớn khách hàng**.
* Tự động hóa quá trình **tìm kiếm và phân công tài xế**, giảm sự phụ thuộc vào thao tác thủ công.
* Hỗ trợ khách hàng **đặt xe, theo dõi trạng thái chuyến đi và xem thông tin tài xế**.
* Hỗ trợ **thanh toán bằng hai hình thức: tiền mặt và thanh toán điện tử**.
* Quản lý tập trung thông tin **khách hàng, tài xế, phương tiện, chuyến đi và giao dịch**.
* Hỗ trợ nhân viên vận hành **theo dõi, quản lý và xử lý các vấn đề phát sinh trong chuyến đi**.
* Cung cấp dữ liệu và báo cáo để **đánh giá hiệu quả hoạt động và doanh thu**.
* Đảm bảo hệ thống **ổn định, bảo mật và có khả năng mở rộng** khi số lượng người dùng tăng.
* Tạo nền tảng linh hoạt để **bổ sung dịch vụ, phương thức thanh toán và kênh thông báo mới trong tương lai**.

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

## Phạm vi dự án trong 7 tuần

Dự án **CAB System** được thực hiện trong **7 tuần**, tập trung xây dựng phiên bản **MVP (Minimum Viable Product)** cho nền tảng đặt xe. Phạm vi ưu tiên các chức năng cốt lõi phục vụ quy trình từ khi khách hàng đặt xe đến khi chuyến đi hoàn thành và thanh toán.

### Trong phạm vi

* **Khách hàng:** Đăng ký, đăng nhập, cập nhật thông tin, đặt xe, theo dõi chuyến đi, xem lịch sử chuyến, hủy chuyến, thanh toán và đánh giá tài xế.
* **Tài xế:** Quản lý thông tin cá nhân và phương tiện, cập nhật trạng thái sẵn sàng, nhận hoặc từ chối chuyến, cập nhật trạng thái và hoàn thành chuyến.
* **Đặt xe và phân công:** Tiếp nhận yêu cầu đặt xe, nhập điểm đón và điểm đến, lựa chọn loại xe, tìm tài xế phù hợp và tiếp tục tìm tài xế khác nếu tài xế từ chối hoặc không phản hồi.
* **Quản lý chuyến đi:** Quản lý toàn bộ vòng đời chuyến đi từ lúc tạo yêu cầu, tìm tài xế, nhận chuyến, thực hiện, hoàn thành hoặc hủy chuyến.
* **Thanh toán:** Tính cước và hỗ trợ hai hình thức thanh toán gồm **tiền mặt và thanh toán điện tử** thông qua nhà cung cấp bên ngoài.
* **Thông báo:** Gửi thông báo về đặt xe, nhận chuyến, tài xế đến điểm đón, hoàn thành chuyến và kết quả thanh toán.
* **Quản lý vận hành:** Cho phép nhân viên vận hành quản lý khách hàng, tài xế, phương tiện, chuyến đi và xử lý các sự cố phát sinh.
* **Báo cáo:** Thống kê số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế.
* **Bảo mật:** Xác thực người dùng, phân quyền, bảo vệ dữ liệu và ghi nhận các thao tác quan trọng.

### Ngoài phạm vi

Các chức năng sau chưa được triển khai trong phiên bản MVP của dự án:

* Định giá động bằng AI/Machine Learning.
* Voucher, khuyến mãi và tích điểm.
* Chat trực tiếp giữa khách hàng và tài xế.
* Tự xây dựng hệ thống bản đồ/GPS riêng.
* Tích hợp nhiều nhà cung cấp thanh toán cùng lúc.
* Tích hợp nhiều nhà cung cấp SMS, Email hoặc Push Notification cùng lúc.
* Các dịch vụ vận tải khác ngoài dịch vụ đặt xe cơ bản.

### Kế hoạch thực hiện trong 7 tuần

| Tuần       | Nội dung                                                                |
| ---------- | ----------------------------------------------------------------------- |
| **Tuần 1** | Khảo sát hiện trạng, xác định vấn đề, stakeholder và mục tiêu nghiệp vụ |
| **Tuần 2** | Phân tích nghiệp vụ và xây dựng Business Requirements                   |
| **Tuần 3** | Phân rã Functional Requirements và xây dựng Use Case                    |
| **Tuần 4** | Đặc tả Use Case và mô hình hóa Business Process                         |
| **Tuần 5** | Thiết kế cơ sở dữ liệu và kiến trúc hệ thống                            |
| **Tuần 6** | Phát triển và tích hợp các chức năng cốt lõi                            |
| **Tuần 7** | Kiểm thử, sửa lỗi, hoàn thiện tài liệu và chuẩn bị demo                 |

### Quy trình nghiệp vụ cốt lõi

**Đặt xe → Tìm tài xế → Phân công tài xế → Nhận chuyến → Thực hiện chuyến → Hoàn thành → Tính cước → Thanh toán → Đánh giá**

Mục tiêu cuối cùng của phạm vi 7 tuần là hoàn thành một phiên bản **MVP** có thể vận hành được quy trình đặt xe cơ bản và làm nền tảng để phát triển thêm các chức năng trong tương lai.


## Business Requirements – Yêu cầu nghiệp vụ

| ID | Yêu cầu nghiệp vụ | Mô tả |
|---|---|---|
| **BR01** | Hỗ trợ đặt xe trực tuyến | Cho phép khách hàng tạo và quản lý yêu cầu đặt xe, nhập điểm đón, điểm đến và lựa chọn loại xe. |
| **BR02** | Tự động tìm kiếm và phân công tài xế | Tự động tìm và phân công tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. |
| **BR03** | Tiếp tục tìm tài xế | Khi tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế khác mà không yêu cầu khách hàng đặt lại. |
| **BR04** | Theo dõi chuyến đi | Cho phép khách hàng theo dõi trạng thái và thông tin chuyến đi từ lúc đặt xe đến khi hoàn thành. |
| **BR05** | Quản lý tài xế và phương tiện | Hỗ trợ quản lý thông tin tài xế, phương tiện và trạng thái hoạt động của tài xế. |
| **BR06** | Quản lý chuyến đi | Quản lý toàn bộ vòng đời chuyến đi: tạo yêu cầu, tìm tài xế, nhận chuyến, thực hiện, hoàn thành hoặc hủy chuyến. |
| **BR07** | Tính cước và thanh toán | Xác định số tiền khách hàng cần thanh toán dựa trên loại dịch vụ và thông tin chuyến đi. |
| **BR08** | Hỗ trợ nhiều hình thức thanh toán | Hỗ trợ thanh toán bằng tiền mặt và thanh toán điện tử thông qua nhà cung cấp bên ngoài. |
| **BR09** | Quản lý thông báo | Gửi thông báo cho khách hàng và tài xế về các sự kiện quan trọng trong quá trình đặt và thực hiện chuyến đi. |
| **BR10** | Quản lý vận hành | Cung cấp giao diện quản trị để nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và chuyến đi. |
| **BR11** | Hỗ trợ xử lý sự cố | Cho phép nhân viên vận hành theo dõi và hỗ trợ xử lý các vấn đề liên quan đến chuyến đi hoặc giao dịch. |
| **BR12** | Báo cáo và theo dõi hoạt động | Cung cấp báo cáo về số chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |
| **BR13** | Đảm bảo bảo mật | Bảo vệ thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch. |
| **BR14** | Kiểm soát quyền truy cập | Phân quyền người dùng và nhân viên, đảm bảo các chức năng quản trị nhạy cảm chỉ được thực hiện bởi người có quyền. |
| **BR15** | Ghi nhận lịch sử hoạt động | Lưu vết các thao tác quan trọng để phục vụ kiểm tra, giám sát và xử lý sự cố. |
| **BR16** | Đảm bảo khả năng mở rộng | Có khả năng phục vụ số lượng lớn khách hàng và tài xế, đồng thời cho phép mở rộng độc lập các thành phần khi nhu cầu tăng. |
| **BR17** | Đảm bảo tính liên tục của dịch vụ | Hạn chế ảnh hưởng khi một thành phần như thanh toán hoặc thông báo gặp lỗi, tránh làm gián đoạn toàn bộ chức năng đặt xe. |
| **BR18** | Hỗ trợ phát triển trong tương lai | Cho phép bổ sung loại dịch vụ, phương thức thanh toán, nhà cung cấp thông báo và thay đổi thành phần kỹ thuật mà không cần xây dựng lại toàn bộ hệ thống. |

## Functional Requirements

| ID | Functional Requirement | Description |
|---|---|---|
| **FR01** | Đặt xe trực tuyến | Hệ thống cho phép khách hàng tạo và quản lý yêu cầu đặt xe, bao gồm điểm đón, điểm đến và loại xe. |
| **FR02** | Tìm kiếm và phân công tài xế | Hệ thống tự động tìm kiếm và phân công tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. |
| **FR03** | Tiếp tục tìm tài xế | Hệ thống tiếp tục tìm tài xế khác khi tài xế được đề xuất từ chối hoặc không phản hồi. |
| **FR04** | Theo dõi chuyến đi | Hệ thống cho phép khách hàng theo dõi trạng thái và thông tin chuyến đi từ khi đặt xe đến khi hoàn thành. |
| **FR05** | Quản lý tài xế và phương tiện | Hệ thống hỗ trợ quản lý thông tin tài xế, phương tiện và trạng thái hoạt động của tài xế. |
| **FR06** | Quản lý chuyến đi | Hệ thống quản lý toàn bộ vòng đời chuyến đi, từ tạo yêu cầu, tìm tài xế, nhận chuyến, thực hiện đến hoàn thành hoặc hủy chuyến. |
| **FR07** | Tính cước | Hệ thống xác định số tiền khách hàng cần thanh toán dựa trên loại dịch vụ và thông tin chuyến đi. |
| **FR08** | Xử lý thanh toán | Hệ thống hỗ trợ thanh toán bằng tiền mặt và thanh toán điện tử thông qua nhà cung cấp thanh toán bên ngoài. |
| **FR09** | Quản lý thông báo | Hệ thống gửi thông báo cho khách hàng và tài xế về các sự kiện quan trọng trong quá trình đặt và thực hiện chuyến đi. |
| **FR10** | Quản lý vận hành | Hệ thống cung cấp giao diện quản trị để nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và chuyến đi. |
| **FR11** | Xử lý sự cố | Hệ thống cho phép nhân viên vận hành theo dõi và hỗ trợ xử lý các trường hợp chuyến đi hoặc giao dịch gặp vấn đề. |
| **FR12** | Báo cáo và theo dõi hoạt động | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |

