*ĐỒ ÁN NHẬP MÔN LẬP TRÌNH WEB*

1. **TỔNG QUAN**
    - Tên đồ án: Trang web giới thiệu ẩm thực Cần Thơ
    - Nội dung:
        * Thức ăn, nước uống
        * Đặc sản vùng
        * Địa điểm ăn uống nổi tiếng
        * *Thêm nếu có...*

2.  **CHI TIẾT**
    - Trang web bao gồm:
        1. [Trang chủ](./src/resources/index.html);
        2. [Trang phản hồi](./src/resources/feedback.html);
        3. [Trang sản phẩm](./src/resources/products.html);
        4. [Trang đăng kí](./src/resources/register.html);
        5. [Trang đăng nhập](./src/resources/login.html);
        6. *Thêm nếu có...*
    - Các tài nguyên: 
        1. Nguồn ảnh được lấy từ internet hoặc dùng các công nghệ tạo ảnh
            [Ảnh được sử dụng](./src/img)
        2. CSS được viết thuần hoặc dùng các công nghệ
            [CSS thuần](./src/css/)
            [Boostrap](./vender/boostrap-5/)
            [Font chữ](./vender/fonts)
            [Icons](./vender/icons)
        3. Javascript được viết thuần hoặc dùng các thư viện có sẵn
            [Javascript thuần](./src/js/)
            [Jquery](./vender/jquery/jquery-3.7.1.js)
        4. Dữ liệu người dùng được sử dụng thông qua localStorage hoặc json
            [Dữ liệu json](./src/json/)

3. **CÁC CHỨC NĂNG**
    - Chức năng về form:
        1. Đăng kí []
            - validate thông tin đăng kí []
            - xác nhận nhập lại mật khẩu []
            - xác nhận người dùng đã tồn tại []
        2. Đăng nhập []
            - validate thông tin đăng nhập []
            - xác minh tài khoản và mật khẩu từ dữ liệu tại [Trang dữ liệu người dùng](./src/json/users.json) []
        3. Gửi mail cảm ơn phản hồi 
            - validate form phản hồi []
            - sau khi người dùng gửi phản hồi, gửi mail cảm ơn lại vào mail của người dùng []