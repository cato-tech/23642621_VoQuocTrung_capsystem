
# CAB System - API Documentation

Tài liệu đặc tả các giao diện lập trình ứng dụng (API) cho nền tảng đặt xe trực tuyến CAB System, phục vụ 3 nhóm tác nhân chính: **Khách hàng (Customer)**, **Tài xế (Driver)** và **Nhân viên vận hành (Admin/Operator)**.

---

## 1. Quy ước chung (General Conventions)

* **Base URL:** `https://github.com/cato-tech/23642621_VoQuocTrung_capsystem/blob/main/openapi.json`
* **Content-Type:** `application/json`
* **Xác thực (Authentication):** Sử dụng chuẩn **JWT Bearer Token** truyền trong Header của các request yêu cầu bảo mật:
  ```http
  Authorization: Bearer <access_token>
