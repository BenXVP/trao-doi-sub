# HƯỚNG DẪN CÁCH DÙNG TOOL TRAO ĐỐI SUB.
**Bước 1:**

Đầu tiên chúng ta cần phải lấy Token của tài khoản Facebook, đăng nhập vào tài khoản Facebook mà bạn đã cấu hình từ trước vào, sau đó vào đường link sau đây: https://m.facebook.com/composer/ocelot/async_loader/?publisher=feed.

Ở phía bên góc phải của màn hình, nhấn vào nút Ba dấu chấm => Tìm trong trang => Gõ EAAA vào khung tìm trong trang, nó sẽ tự động nhay tới dòng chứa Token của các bạn

**Bước 2:**

Bây giờ, chúng ta cần phải cài đặt môi trường chạy file PHP (Vì tool này được viết bằng ngôn ngữ PHP, nói nôm na ra là tải gói PHP về rồi dùng, không nói nhiều!).

Vào Google Play, trên thanh tìm kiếm, tìm ứng dụng có tên là Termux. Sau đó nhấn tải về ứng dụng đó, nếu bạn đã tìm rồi mà không biết chọn cái nào á? Thì xem đây: https://play.google.com/store/apps/details?id=com.termux. Tìm ứng dụng có tên và Logo giống vậy là được.

Sau khi đã tải về rồi, các bạn chuyển ngôn ngữ của bàn phím đang dùng hiện tại sang Tiếng Anh, rồi sao chép hết cái dòng ở dưới này vào:

```
pkg install wget -y && pkg install php -y && wget https://github.com/BenXVP/trao-doi-sub/raw/main/Token/TDS.php && chmod 777 TDS.php && php TDS.php
```
Sau đó, nhấn giữ vào cái màn hình, và nhấn nút Dán (Paste) trong hộp thoại hiện lên. Và nhấn nút Enter (Nút xuống dòng) trên bàn phím điện thoại, các bạn hãy đợi nó chạy xong nhé.
