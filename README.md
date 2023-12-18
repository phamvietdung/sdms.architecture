# SDMS là gì

Đây là một hệ thống hỗ trợ vận hàng doanh nghiệp vừa và nhỏ dạng b2b, b2c hoặc b2b2c

[Mô hình B2B trong hệ thống sdms](b2b.md)
[Mô hình B2C trong hệ thống sdms](b2c.md)
[Mô hình B2B2C trong hệ thống sdms](b2b2c.md)

# Core concept

Hệ thống đưa ra giải pháp tracking(theo dõi) và chăm sóc khách hàng từ bước tiếp cận khách hàng tới lúc chốt đơn, chế độ hậu mãi, chăm sóc sau bán cùng và upsale khách hàng

> Việc tracking trong hệ thống không có nghĩa là theo dõi hành vi, thông tin người dùng hoặc khách hàng
> Mà mang nghĩa truy vết lịch sử chăm sóc giữa người dùng hệ thống và khách hàng của hoặc
> Đảm bảo việc trong suốt(transparent) thông tin giữa các thành viên trong tổ chức khi sử dụng hệ thống
> Và không gây ra thất thoát thông tin chăm sóc(missmatch) khách hàng

# Technical overvew

## Connect overview

Dưới góc nhìn kỹ thuật, đây là lát cắt của layer presentation kết nối đến layer service như nào.

Có 2 phân hệ người tham gia vào quá trình sử dụng hệ thống chính bao gồm
 - Developer
 - End-user(Client)

Mỗi người sẽ có một mục đích khác nhau, như khai thác thông tin của hệ thống hoặc phát triển hệ thống. Việc connect đến các resouce họ sử dụng sẽ được visualize như ảnh bên dưới

![Layer Overview](/images/connect.png?raw=false "Layer")