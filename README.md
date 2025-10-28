# 22689661-NguyenDienThinh-EProject

🛍️ Giới thiệu
**Thực hiện bởi: Nguyễn Điền Thịnh – MSSV: 22689661
**Đây là một hệ thống thương mại điện tử được phát triển dựa trên mô hình kiến trúc Microservices.
Mục tiêu của dự án là mô phỏng quy trình hoạt động của một hệ thống bán hàng trực tuyến có khả năng mở rộng linh hoạt, dễ bảo trì và triển khai bằng Docker.


💻 Công nghệ & Công cụ sử dụng
****Node.js & Express.js – Nền tảng xây dựng backend cho từng microservice
****MongoDB – Cơ sở dữ liệu chính
****RabbitMQ – Hỗ trợ truyền thông giữa các dịch vụ
****Docker & Docker Compose – Đóng gói và triển khai toàn bộ hệ thống
****Nginx / HTTP Proxy – Làm cổng giao tiếp trung gian cho API Gateway
****JWT & API Key – Xác thực và phân quyền người dùng


⚙️ Thành phần chính của hệ thống
****API Gateway: Đóng vai trò là điểm truy cập duy nhất của client, chịu trách nhiệm định tuyến request đến các dịch vụ tương ứng.
****Auth Service: Cung cấp chức năng đăng ký, đăng nhập và quản lý xác thực người dùng thông qua JWT.
****Product Service: Xử lý các nghiệp vụ liên quan đến sản phẩm như tạo mới, chỉnh sửa, hiển thị danh sách sản phẩm.
****Order Service: Quản lý đơn hàng của khách hàng, kết nối với các dịch vụ khác để đảm bảo luồng xử lý đơn được đồng bộ.
****MongoDB: Hệ quản trị cơ sở dữ liệu NoSQL lưu trữ thông tin sản phẩm, người dùng và đơn hàng.
****RabbitMQ: Hệ thống message broker giúp các microservice giao tiếp với nhau theo mô hình bất đồng bộ.
