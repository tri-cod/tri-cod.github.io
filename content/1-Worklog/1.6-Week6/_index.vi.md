---
title: "Week 6 Worklog"
date: 2026-10-26
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

- Tìm hiểu các kiến thức cơ bản về Elastic Load Balancing (ELB) trên nền tảng AWS.
- Hiểu được vai trò của Amazon EC2 Auto Scaling trong việc nâng cao khả năng sẵn sàng và mở rộng của ứng dụng.
- Thực hành triển khai Application Load Balancer và cấu hình Auto Scaling Group.
- Tìm hiểu cách xây dựng kiến trúc ứng dụng có khả năng mở rộng và duy trì tính sẵn sàng cao trên AWS.

### Các công việc cần thực hiện trong tuần:

| Ngày | Công việc                                                                                                                                                                                                                | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo                                                              |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------ | --------------- | ------------------------------------------------------------------------------- |
| 2    | - Ôn tập lại những kiến thức về Amazon RDS đã học trong tuần trước.<br>- Tìm hiểu nguyên lý hoạt động của Elastic Load Balancing (ELB) và các loại Load Balancer được AWS cung cấp.                                      | 26/10/2026   | 26/10/2026      | [Giới thiệu ELB](https://000058.awsstudygroup.com/en/1-introduce/)              |
| 3    | - Nghiên cứu cách thức hoạt động của Application Load Balancer (ALB).<br>- Thực hành tạo Target Group và thiết lập Health Checks để kiểm tra trạng thái của các EC2 Instance.                                            | 27/10/2026   | 27/10/2026      | [Các bước chuẩn bị](https://000058.awsstudygroup.com/en/2-prerequiste/)         |
| 4    | - Tiến hành triển khai Application Load Balancer.<br>- Đăng ký nhiều EC2 Instance vào cùng một Target Group.<br>- Kiểm tra khả năng phân phối lưu lượng truy cập đến các EC2 Instance đã đăng ký.                        | 28/10/2026   | 28/10/2026      | [Tạo ALB](https://000058.awsstudygroup.com/en/3-createalb/)                     |
| 5    | - Tìm hiểu những khái niệm nền tảng của Amazon EC2 Auto Scaling.<br>- Tạo Launch Template và thiết lập Auto Scaling Group.<br>- Cấu hình Scaling Policies dựa trên mức độ sử dụng CPU.                                   | 29/10/2026   | 29/10/2026      | [Tạo ASG](https://000058.awsstudygroup.com/en/4-createasg/)                     |
| 6    | - Kiểm tra hoạt động của Load Balancer và Auto Scaling Group.<br>- Mô phỏng lưu lượng truy cập ứng dụng để quan sát quá trình Scale Out và Scale In.<br>- Ôn tập nội dung đã học và hoàn thành bài thực hành trong tuần. | 30/10/2026   | 30/10/2026      | [Dọn dẹp tài nguyên ELB và ASG](https://000058.awsstudygroup.com/en/5-cleanup/) |

### Kết quả đạt được trong tuần 6:

- Hiểu được mục đích của Elastic Load Balancing (ELB) và cách dịch vụ này phân phối lưu lượng truy cập đến nhiều EC2 Instance.
- Nắm được những thành phần quan trọng của Elastic Load Balancing, bao gồm:
  - Application Load Balancer (ALB)
  - Target Group
  - Listener
  - Health Check
- Triển khai thành công Application Load Balancer và thiết lập Target Group để quản lý nhiều EC2 Instance.
- Hiểu được cơ chế hoạt động của Health Checks, đồng thời biết cách theo dõi tình trạng hoạt động của các EC2 Instance thông qua Load Balancer.
- Nắm được kiến thức cơ bản về Amazon EC2 Auto Scaling và cách dịch vụ này tự động điều chỉnh số lượng EC2 Instance dựa trên nhu cầu sử dụng của ứng dụng.
- Hoàn thành việc tạo và cấu hình các tài nguyên sau:
  - Launch Template
  - Auto Scaling Group
  - Scaling Policy
- Thực hành mô phỏng sự thay đổi về tải của ứng dụng và quan sát các sự kiện Scale Out, Scale In, từ đó hiểu rõ hơn cách AWS điều chỉnh tài nguyên để duy trì hiệu suất và tính sẵn sàng của hệ thống.
- Hoàn thành các bài thực hành về Elastic Load Balancing và Auto Scaling trong lộ trình Cloud Journey.
- Xây dựng nền tảng kiến thức về thiết kế ứng dụng trên AWS với khả năng mở rộng linh hoạt, tính sẵn sàng cao và khả năng chịu lỗi tốt.
