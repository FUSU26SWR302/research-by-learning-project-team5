[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/eQ0omQZ7)
#  Hệ Thống Kết Nối & Hỗ Trợ Nông Dân Bán Hàng Nông Sản

> Nền tảng số kết nối trực tiếp nông dân với người tiêu dùng — minh bạch, hiệu quả, bền vững.

---

## 👥 Thành Viên Nhóm

1   | Bùi Khắc Khoa           | DE190322
2   | Nguyễn Viết Bảo Hưng    | DE190327             
3   | Nguyễn Văn Trùng Khánh  |  DE190536    
4   | Dương Minh Toàn         |  DE190521    
5   | Nguyễn Đình Khôi        |  DE190992    

---

 Tên dự án: Hệ thống kết nối, hỗ trợ nông dân bán hàng nông sản

* Lý Do Hình Thành

Hiện nay, để các sản phẩm nông nghiệp đến tay người tiêu dùng, chúng phải đi qua nhiều tầng trung gian — thương lái, kho hàng, đại lý phân phối. Điều này dẫn đến hai hệ quả:

- *Người tiêu dùng phải mua nông sản với giá cao hơn giá thực tế tại nông trại.
- *Nông dân thu được lợi nhuận thấp hơn, không tương xứng với công sức sản xuất.

Hệ thống này đóng vai trò **bên thứ ba trung lập**, kết nối trực tiếp nông dân với người tiêu dùng, giúp giá nông sản ổn định và minh bạch hơn, không bị đội giá qua các thương lái hay kho trung gian.

### Mô Tả Hệ Thống

*Hệ thống Kết Nối Nông Sản** là một nền tảng web số cho phép:

- *Nông dân** đăng ký, đăng sản phẩm và quản lý đơn hàng trực tiếp.
- *Người tiêu dùng* tìm kiếm, đặt mua và theo dõi đơn hàng nông sản chất lượng.
- *Đơn vị vận chuyển** nhận và cập nhật trạng thái giao hàng.
- Quản trị viên** giám sát toàn bộ hoạt động của nền tảng.

**Mục tiêu:** Xây dựng chuỗi cung ứng nông sản **minh bạch – hiệu quả – bền vững**, giảm thiểu trung gian, tăng lợi nhuận cho nông dân và đảm bảo nguồn cung chất lượng cho người tiêu dùng.

## Phạm Vi Dự Án

- Áp dụng cho các loại nông sản trong nước: **rau, củ, quả, thịt, thủy sản**.
- Hệ thống hoạt động trên nền tảng **web**.
- Người dùng chính:

| Tác Nhân | Mô Tả |
|----------|-------|
|  Nông dân | Người sản xuất và cung cấp nông sản |
|  Khách hàng | Người tiêu dùng cá nhân hoặc doanh nghiệp |
|  Đơn vị vận chuyển | Đơn vị nhận vận chuyển và giao hàng |
|  Quản trị viên | Người quản lý, giám sát hệ thống |
|  Cơ quan chứng nhận | Đơn vị xác nhận chất lượng/nguồn gốc nông sản |

---

##  Tác Nhân & Chức Năng (Use Case)

###  Chức Năng Chung (Tất Cả Người Dùng)

- Đăng ký tài khoản
- Đăng nhập / Đăng xuất
- Xem & chỉnh sửa hồ sơ cá nhân
- Đổi mật khẩu / Quên mật khẩu
- Gửi yêu cầu hỗ trợ đến Admin

---

# Nông Dân

- Đăng sản phẩm nông sản
- Cập nhật số lượng tồn kho
- Thay đổi thông tin sản phẩm / Ngừng bán sản phẩm
- Xác nhận / Từ chối đơn hàng
- Chat với người mua
- Xem thống kê doanh thu
- Xem feedback từ khách hàng
- Xem lịch sử đơn hàng
- Mở phiên live bán hàng
- Tạo chương trình khuyến mãi / Giảm giá sản phẩm

---

# Khách Hàng

- Tìm kiếm & lọc sản phẩm
- Xem chi tiết sản phẩm
- Xem hồ sơ nông dân
- Đặt hàng / Huỷ đơn hàng
- Thanh toán đơn hàng
- Xem lịch sử mua hàng
- Chat với nông dân
- Đánh giá & gửi feedback
- Đặt trước theo mùa vụ

---

# Quản Trị Viên

- Khoá / Mở tài khoản người dùng
- Xem danh sách & tìm kiếm tài khoản
- Xem danh sách đơn hàng & theo dõi giao dịch
- Xử lý khiếu nại
- Xem báo cáo vi phạm
- Xem thống kê hệ thống
- Gửi thông báo hệ thống
- Duyệt sản phẩm trước khi hiển thị
- Quản lý danh mục sản phẩm

---

# Đơn Vị Vận Chuyển

- Nhận yêu cầu vận chuyển
- Cập nhật trạng thái đơn hàng
- Xác nhận giao hàng thành công
- Xem lịch sử vận chuyển
- Liên hệ khách hàng

---

# Hàm Lượng Nghiên Cứu (Tuần 1)

# Thuật Toán Nghiên Cứu

| # | Thuật Toán | Ứng Dụng Trong Dự Án |
|---|------------|----------------------|
| 1 | **Tìm kiếm Full-text Search** (Elasticsearch / PostgreSQL FTS) | Tìm kiếm sản phẩm nông sản theo tên, loại, vùng trồng |
| 2 | **Thuật toán lọc & xếp hạng** (Filtering + Scoring) | Lọc sản phẩm theo giá, loại, đánh giá, khoảng cách |
| 3 | **Gợi ý sản phẩm** (Collaborative Filtering / Content-based) | Đề xuất sản phẩm phù hợp với lịch sử mua hàng |
| 4 | **Thuật toán phân phối đơn hàng** (Nearest Neighbor / Greedy) | Tự động gán đơn vận chuyển phù hợp theo vùng |
| 5 | **Phân tích doanh thu** (Time-series Analysis) | Thống kê doanh thu theo ngày/tuần/tháng cho nông dân |
| 6 | **Phát hiện gian lận** (Anomaly Detection) | Phát hiện hành vi bất thường trong giao dịch |

---

### 💻 Công Nghệ Lập Trình Nghiên Cứu

| Hạng Mục | Công Nghệ | Lý Do Lựa Chọn |
|----------|-----------|----------------|
| **Frontend** | React.js / Next.js | SSR/SSG tốt cho SEO, hiệu năng cao |
| **Backend** | Node.js (Express) hoặc Java (Spring Boot) | Xử lý REST API, realtime tốt |
| **Database** | PostgreSQL + Redis | RDBMS cho dữ liệu cấu trúc; Redis cho cache & session |
| **Realtime / Chat** | WebSocket (Socket.IO) | Chat nông dân — khách hàng theo thời gian thực |
| **Live Stream** | WebRTC / HLS | Mở phiên live bán hàng |
| **Authentication** | JWT + OAuth2 | Bảo mật, hỗ trợ đăng nhập mạng xã hội |
| **Thanh toán** | VNPay / MoMo / ZaloPay API | Thanh toán nội địa phổ biến tại Việt Nam |
| **Lưu trữ file/ảnh** | AWS S3 / Cloudinary | Lưu ảnh sản phẩm, video live |
| **Tìm kiếm** | Elasticsearch | Full-text search hiệu suất cao |
| **Deployment** | Docker + CI/CD (GitHub Actions) | Triển khai nhất quán, tự động hóa |


# Kiến Trúc Hệ Thống Nghiên Cứu

# Kiến Trúc Tổng Quan

Hệ thống được thiết kế theo mô hình **3-tier Architecture** kết hợp các yếu tố của **Microservices** cho các module độc lập:

```
┌─────────────────────────────────────────────────────┐
│                   CLIENT LAYER                      │
│        Web Browser (React.js / Next.js)             │
└──────────────────────┬──────────────────────────────┘
                       │ HTTPS / WebSocket
┌──────────────────────▼──────────────────────────────┐
│                   API GATEWAY                       │
│         (Nginx Reverse Proxy / Load Balancer)       │
└──┬──────────┬──────────┬──────────┬─────────────────┘
   │          │          │          │
┌──▼──┐  ┌───▼──┐  ┌────▼──┐  ┌───▼──────────┐
│Auth │  │User  │  │Order  │  │ Notification │
│Svc  │  │& Farm│  │& Pay  │  │ & Chat Svc   │
│     │  │Svc   │  │Svc    │  │ (Socket.IO)  │
└──┬──┘  └───┬──┘  └────┬──┘  └───┬──────────┘
   └─────────┴──────────┴─────────┘
                    │
┌───────────────────▼────────────────────────────────┐
│              DATA LAYER                            │
│  PostgreSQL │ Redis (Cache) │ Elasticsearch        │
│  AWS S3 (Media) │ Message Queue (RabbitMQ)         │
└────────────────────────────────────────────────────┘
```

#### Các Module Chính

| Module | Chức Năng |
|--------|-----------|
| **Auth Service** | Đăng ký, đăng nhập, JWT, OAuth2, phân quyền RBAC |
| **User & Farm Service** | Quản lý hồ sơ nông dân, khách hàng, sản phẩm, tồn kho |
| **Order & Payment Service** | Đặt hàng, thanh toán, lịch sử giao dịch |
| **Delivery Service** | Quản lý đơn vận chuyển, cập nhật trạng thái |
| **Notification & Chat Service** | WebSocket chat realtime, thông báo push |
| **Live Stream Service** | Quản lý phiên live bán hàng qua WebRTC/HLS |
| **Admin Service** | Duyệt nội dung, báo cáo, thống kê hệ thống |
| **Search Service** | Elasticsearch full-text search, filter, ranking |



## 📅 Kế Hoạch Phát Triển (Tổng Quan)

| Tuần | Nội Dung |
|------|----------|
| 1 | Nghiên cứu công nghệ, thuật toán, kiến trúc hệ thống |
| 2 | Phân tích yêu cầu, thiết kế Use Case, ERD |
| 3–4 | Thiết kế UI/UX, prototype giao diện |
| 5–7 | Phát triển backend — Auth, User, Product |
| 8–10 | Phát triển Order, Payment, Delivery module |
| 11–12 | Tích hợp Chat, Live Stream, Notification |
| 13 | Kiểm thử (Unit Test, Integration Test) |
| 14 | Triển khai, hoàn thiện tài liệu |

---

https://zhi23072005.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog?selectedIssue=SCRUM-11
link figma: https://www.figma.com/design/yHUUvXJh8nd1KxBvqjzUml/Untitled?node-id=0-1&p=f&t=bFCoHRiAea1tX90S-0
link template: https://www.overleaf.com/read/jxnmkyvphqwg#f4e83e


