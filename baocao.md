## Cơ chế hoạt động của internet và WWW.
***Cơ chế hoạt động của internet***
 * Internet được thực hiện thông qua các thiết bị định tuyến (router)
 * Các phương tiện truyền dẫn như cáp quang, vệ tinh, sóng vô tuyến, dây đồng trục.
 * Tín hiệu điện tử đi qua các thiết bị định tuyến và các mạng truyền dẫn này để đạt đến điểm đích cuối.
 * TCP/IP là giao thức truyền tải dữ liệu cơ bản cho phép các thiết bị trên Internet giao tiếp và xác định đường đi tối ưu nhất để truyền dữ liệu.
>Link tham khảo:
[https://techcare.vn/tin-cong-nghe/internet-la-gi-internet-hoat-dong-nhu-the-nao/](https://techcare.vn/tin-cong-nghe/internet-la-gi-internet-hoat-dong-nhu-the-nao/)

***Cơ chế hoạt động của WWW***

  ![Cách thức hoạt động của WWW](https://st.quantrimang.com/photos/image/2021/04/17/www-la-gi-2.jpg)
  * WWW hoạt động theo định dạng client-server
  * Server lưu trữ và chuyển các trang web hoặc thông tin đến máy tính của người dùng trên mạng khi người dùng yêu cầu.
  * Khi nhập URL vào thanh địa chỉ hoặc tìm kiếm thứ gì đó trên Google, WWW sẽ bắt đầu hoạt động.
  * Có ba công nghệ chính liên quan đến việc truyền thông tin
    - Hypertext Markup Language (HTML)
    - Hypertext Transfer Protocol (HTTP)
    - Các trình duyệt web.
>Link tham khảo:
[https://quantrimang.com/cong-nghe/www-la-gi-180585](https://quantrimang.com/cong-nghe/www-la-gi-180585)
## Protocol của HTTP/HTTPS/FTP/SMTP/POP3.
***Protocol của HTTP***
  * Hypertext Transfer Protocol (HTTP) là nền tảng giao tiếp dữ liệu cho WWW.
  * Cho phép trao đổi thông tin (chủ yếu ở dạng siêu văn bản) qua Internet.
  * Cổng mặc định là 80 và 443

***Protocol của HTTPS***
  * Hypertext Transfer Protocol over SSL/TLS (HTTPS) cung cấp các dịch vụ tương tự HTTP.
  * Kết nối bảo mật được cung cấp bởi SSL hoặc TLS.
  * Cổng mặc định là 443.

***Protocol của FTP***
  * FTP (File Transfer Protocol) cho phép trao đổi tập tin qua Internet.
  * Có ít nhất hai máy tính để FTP hoạt động
    - FTP server
    - FTP Client
  * Cổng mặc định là 21
  
***Protocol của SMTP***
  * SMTP (Simple Mail Transfer Protocol) cho phép gởi các thông điệp thư điện tử (e-mail) qua Internet.
  * Cổng mặc định 25.

***Protocol của POP3***
  * POP3 (Post Office Protocol, phiên bản 3) cho phép nhận các thông điệp thư điện tử qua Internet.
  * Thông qua kết nối TCP/IP.
  * Cổng mặc định 110
>Link tham khảo:
[https://bkaii.com.vn/tin-tuc/621-nhung-giao-thuc-mang-ban-nen-biet](https://bkaii.com.vn/tin-tuc/621-nhung-giao-thuc-mang-ban-nen-biet)
## Cơ chế hoạt động của browser và sự khác nhau giữa các browser.
***Cơ chế hoạt động của browser***

\- Trình duyệt web lấy thông tin từ các phần khác của web và hiển thị trên máy tính hoặc thiết bị di động.Thông tin được truyền bằng HTTP. 

\- Khi trình duyệt web tìm nạp dữ liệu từ một máy chủ được kết nối internet. Nó sử dụng một phần mềm được gọi là công cụ kết xuất để dịch dữ liệu đó thành văn bản và hình ảnh. Dữ liệu này được viết bằng HTML

\- Hyperlink cho phép người dùng đi theo đường dẫn đến các trang hoặc trang web khác trên web.
>Link tham khảo:
[https://www.mozilla.org/vi/firefox/browsers/what-is-a-browser/](https://www.mozilla.org/vi/firefox/browsers/what-is-a-browser/)

***sự khác nhau giữa các browser***

\- Các browser không sử dụng bộ sử lý Rendering Engine (Layout engine) giống nhau nên các trang web không hiển thị giống nhau trên các trình duyệt
* Firefox: Gecko Engine
* Safari: WebKit
* Opera: Presto
* Chrome: Blink
>Link tham khảo:
[https://topdev.vn/blog/hieu-ve-trinh-duyet-how-browsers-work-2/](https://topdev.vn/blog/hieu-ve-trinh-duyet-how-browsers-work-2/)

## Cơ chế hoạt động của địa chỉ IP, DNS, domain.
***Cơ chế hoạt động của địa chỉ IP***

\- Khi truy cập vào 1 trang web. Máy tính sẽ gửi yêu cầu đến địa chỉ IP của trang web. Traffic đó được gửi từ máy tính đến router và router sẽ chuyển tiếp yêu cầu tới máy chủ của trang web. Máy chủ gửi đúng thông tin tới router, sau đó chuyển thông tin về thiết bị đã yêu cầu.
>Link tham khảo:
[https://quantrimang.com/cong-nghe/cach-thuc-hoat-dong-cua-dia-chi-ip-147253](https://quantrimang.com/cong-nghe/cach-thuc-hoat-dong-cua-dia-chi-ip-147253)

***Cơ chế hoạt động của DNS***

\- Khi truy cập vào 1 trang web. Người dùng gửi yêu cầu tìm kiếm địa chỉ IP ứng với tên miền tới Name Server cục bộ. Máy chủ domain cục bộ sẽ tìm kiếm trong kho dữ liệu xem có cơ sở dữ liệu chuyển đổi từ tên miền sang địa chỉ IP của tên miền mà người dùng yêu cầu hay không. Việc tìm kiếm có thể dẫn tới một trong hai kết quả:
 * Không thấy thông tin -> DNS tiếp tục tìm kiếm tại bộ nhớ cache.
 * Không nhận được bất cứ thông tin nào -> DNS hiển thị mã lỗi.
>Link tham khảo:
[https://kinhtedothi.vn/domain-name-system-la-gi-cach-thuc-hoat-dong-cua-dns.html](https://kinhtedothi.vn/domain-name-system-la-gi-cach-thuc-hoat-dong-cua-dns.html)

***Cơ chế hoạt động của domain***

\- Khi nhập một domain name vào thanh URL của trình duyệt web, lúc này nó sẽ gửi yêu cầu truy cập đến một mạng lưới máy chủ toàn cầu hình thành nên hệ thống domain (DNS). Sau đó các máy chủ toàn cầu này sẽ tìm kiếm các máy chủ có tên được liên kết với domain và chuyển tiếp yêu cầu đến các máy chủ tên đó.
>Link tham khảo:
[https://vietmoz.edu.vn/domain-la-gi/](https://vietmoz.edu.vn/domain-la-gi/)
## Giải thích về hosting server.
  * Hosting là một dịch vụ online giúp bạn đăng tải dữ liệu, xuất bản website hoặc ứng dụng web lên Internet.
  * Nhà cung cấp Web Hosting chịu trách nhiệm cho việc giữ server hoạt động liên tục, chống tấn công bởi mã độc, và xử lý dữ liệu (văn bản, nội dung, hình ảnh, files) từ hosting đến trình duyệt người dùng.
  * Người thuê hosting chỉ việc upload các files lên hosting và cấu hình hoạt động cho chúng. Người dùng có thể truy cập hosting từ các thiết bị kết nối internet, thông qua việc gửi request đến domain name (tên miền) hoặc địa chỉ IP của hosting.
  * Hosting sẽ trả về các tập tin được yêu cầu tương ứng. Trong quá trình sử dụng, nếu có nhu cầu mở rộng gói hosting, người dùng phải liên hệ với nhà cung cấp để được thực hiện.
  * Có 4 loại Hosting phổ biến nhất hiện nay:
    - Shared hosting.
    - Dedicated hosting
    - Cloud hosting
    - WordPress hosting
>Link tham khảo:
[https://www.hostinger.vn/huong-dan/hosting-la-gi-giai-thich-web-hosting-cho-nguoi-moi-bat-dau](https://www.hostinger.vn/huong-dan/hosting-la-gi-giai-thich-web-hosting-cho-nguoi-moi-bat-dau)

















