Giới Thiệu

Dự án này là hệ thống truyền tin nhắn và tệp tin bảo mật sử dụng WebSocket và TCP, được thiết kế để đảm bảo an toàn dữ liệu từ đầu đến cuối. Hệ thống tích hợp các thuật toán mã hóa mạnh như DES3 và RSA để bảo vệ thông tin trong quá trình truyền tải. Với khả năng hoạt động thời gian thực, hệ thống cung cấp trải nghiệm liền mạch cho người dùng, đồng thời duy trì tính bảo mật cao.

Chức Năng Cơ Bản

Hệ thống hỗ trợ gửi tin nhắn và tệp tin qua WebSocket với tốc độ cao. Các tệp tin được mã hóa bằng DES3 và xác thực bằng chữ ký RSA trước khi truyền đi. Người dùng có thể theo dõi trạng thái gửi/nhận tin nhắn và tệp tin trong thời gian thực. Hệ thống cũng cung cấp tính năng lưu trữ tệp tin an toàn trên máy chủ, cho phép tải xuống khi cần thiết.

Kỹ Thuật & Công Nghệ Sử Dụng

Backend sử dụng Flask và Flask-SocketIO để xử lý kết nối WebSocket và HTTP. Quá trình mã hóa dựa trên DES3 cho mã hóa dữ liệu và RSA cho chữ ký số. Giao diện người dùng được xây dựng bằng HTML, CSS và JavaScript, đảm bảo tương thích với nhiều thiết bị. Hệ thống còn tích hợp Socket TCP để truyền tải dữ liệu ổn định và hiệu quả.

Giao Diện Người Dùng

Giao diện được thiết kế đơn giản, tập trung vào trải nghiệm người dùng. Người dùng có thể dễ dàng nhập tin nhắn, chọn tệp tin để gửi và theo dõi các thông báo trạng thái. Giao diện hiển thị rõ ràng các tin nhắn và tệp tin đã gửi/nhận, cùng với thông tin về trạng thái mã hóa, giúp người dùng yên tâm về tính bảo mật của hệ thống.
![image](https://github.com/user-attachments/assets/49abf13c-d080-466b-a3f8-5c7167879182)
![image](https://github.com/user-attachments/assets/4260b201-9329-4560-af03-aa0029db3046)
![image](https://github.com/user-attachments/assets/045f08d1-3fab-4b63-b605-3123bfbedbf2)
![image](https://github.com/user-attachments/assets/ecf5defa-f9a3-4e61-92aa-6a1e7486bb76)
