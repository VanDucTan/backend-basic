Backend, Server, Cookie, Session, Database, HTTP Protocol và Mô hình Client-Server: Giải thích chi tiết
1. Backend, Server, Cookie, Session, Database:
Backend: Là các công việc liên quan đến dữ liệu, logic phía sau frontend, giúp trang web hoạt động trơn tru nhất. Ví dụ như xử lý database, logic kinh doanh, quản lý tài khoản người dùng, v.v.
Server: Là một máy tính giúp đưa ra các response cho các request từ các máy agent (như trình duyệt web, ứng dụng di động). Server có thể lưu trữ dữ liệu, xử lý logic và trả về kết quả cho người dùng.
Cookie: Là một đoạn mã mà server gửi cho user khi họ truy cập một trang web. Cookie lưu trữ thông tin về người dùng, chẳng hạn như lịch sử truy cập, thông tin đăng nhập, v.v., giúp cho việc truy cập trang web sau này nhanh hơn và tiện lợi hơn.
Session: Là một bộ nhớ tạm trong RAM của server nhằm tiết kiệm dung lượng cho database. Session lưu trữ thông tin về người dùng trong một phiên làm việc (session), ví dụ như giỏ hàng trong một trang web mua sắm.
Database: Là một kho chứa tất cả dữ liệu của user truy cập và phân biệt các user. Database có thể lưu trữ nhiều loại dữ liệu khác nhau, chẳng hạn như thông tin người dùng, sản phẩm, đơn hàng, v.v.
2. HTTP Protocol:
HTTP (Hypertext Transfer Protocol) là giao thức truyền tải siêu văn bản, là nền tảng cho sự tương tác giữa trình duyệt web và server. Khi bạn truy cập một trang web, trình duyệt web của bạn sẽ gửi một request HTTP đến server. Server sẽ xử lý request và trả về một response HTTP, bao gồm nội dung của trang web.
Request URL: Địa chỉ của trang web mà bạn muốn truy cập.
Request method: Phương thức gửi request (ví dụ: GET, POST, PUT, DELETE).
Status: Báo trạng thái request đã được xử lý thành công hay chưa.
Remote address: Địa chỉ IP của máy tính đang gửi request.
Response header: Thông tin bổ sung về response, chẳng hạn như loại nội dung, kích thước, v.v.
Request header: Thông tin về request, chẳng hạn như loại trình duyệt web, ngôn ngữ, v.v.
Có nhiều loại status code HTTP khác nhau, được chia thành các nhóm sau:
Mã 1xx: Mã thông tin.
Mã 2xx: Thành công.
Mã 3xx: Chuyển hướng lại.
Mã 4xx: Lỗi client.
Mã 5xx: Lỗi server.
3. Mô hình Client-Server:
Mô hình client-server là một mô hình mạng máy tính trong đó các máy tính được chia thành hai nhóm: client và server. Client là máy tính yêu cầu dịch vụ từ server, và server là máy tính cung cấp dịch vụ cho client.
Client: Là máy khách, nơi người dùng tương tác với trang web. Client có thể là trình duyệt web, ứng dụng di động, hoặc bất kỳ chương trình nào khác có thể gửi request HTTP đến server.
Server: Là máy chủ, nơi lưu trữ dữ liệu và xử lý logic của trang web. Server có thể là một máy tính duy nhất hoặc một nhóm máy tính được kết nối với nhau.
Mô hình client-server là mô hình mạng phổ biến nhất hiện nay, được sử dụng cho hầu hết các trang web và ứng dụng web.
Tóm lại:
Backend, server, cookie, session, database là những thành phần quan trọng của một trang web, giúp trang web hoạt động hiệu quả và an toàn.
HTTP protocol là giao thức truyền tải siêu văn bản, là nền tảng cho sự tương tác giữa trình duyệt web và server.
Mô hình client-server là mô hình mạng máy tính trong đó các máy tính được chia thành hai nhóm: client và server.
Lưu ý:
Giải thích này chỉ bao gồm những thông tin cơ bản về backend, server, cookie, session, database, HTTP protocol và mô hình client-server. Để hiểu rõ hơn về các chủ đề này, bạn có thể tham khảo thêm các tài liệu chuyên sâu hơn.
Một số ví dụ về backend: WordPress, Django, Laravel, Ruby on Rails, Node.js.
Một số ví dụ về server: Apache, Nginx, IIS, Tomcat.
Một số ví dụ về database: MySQL, PostgreSQL, MongoDB, Oracle, SQL Server.


3.Mô hình Client-Server:
Rendering là đang xuất ra cái file 
SSR (server-side rendering) kiểu như là một cái respone cho cái request mà cái respone này có chứa các câu lệnh CSS và HTML gửi về để load ra trang web 
Còn CSR là nó tải từ HTML, Java, CSS từ SSR để load trang web 


4.API (application programing interface): 
Những cái mình tương tác trên các trang web chỉ là cái giao diện (frontend) thoi -> web API là trung gian từ giao diện tới database 
Có 2 dạng API: Web API & Framework 


