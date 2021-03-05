HTML

1. HTML là gì và tại sao phải sử dụng HTML
- Là ngôn ngữ siêu văn bản được dùng để trình bày và lên cấu trúc (bộ khung) cho 1 trang web

- HTML là ngôn ngữ duy nhất mà trình duyệt có thể biên dịch được
Cho dù trang web được xây dựng bằng ngôn ngữ nào thì đầu ra cuối cùng vẫn phải là HTML

2. Định nghĩa trang HTML

- cú pháp: tên_file.html
- Cấu trúc của 1 trang HTML

    <html>
        <head> code html </head>
        <body> code html </body>
    </html>

- Cấu trúc và quy luật của thẻ HTML
    + Thông thường 1 thẻ HTML sẽ luôn có 2 thẻ đóng và mở. Và tên thẻ giống nhau ở thẻ đóng và mở

    + Đối với 1 số thẻ đặc biệt sẽ không ko có thẻ đóng. Dấu đóng thẻ nằm trên chính nó

    + Một thẻ html có thể có hoặc không có thuộc tính hoặc có nhiều thuộc tính 

Cách định nghĩa 1 thẻ HTML
    <tagName attributeName="value" .... ></tagName>

3. Phân loại các thẻ HTML
    - None: không hiển thị
    - Block: Full màn hình
    - Inline: Độ rộng bằng nội dung

4. Các thẻ HTML thường sử dụng
* Nhóm các thẻ tiêu đề H
    <h1>Nội dung</h1>
    <h2>Nội dung</h2>
    <h3>Nội dung</h3>
    <h4>Nội dung</h4>
    <h5>Nội dung</h5>
    <h6>Nội dung</h6>

* Các thẻ thể hiện văn bản của trang web
- <strong>Nội dung</strong> In đậm văn bản
- <b>Nội dung</b> In đậm văn bản
    => strong: Tốt cho SEO
- <font color='value' size='number'>Nội dung</font> Qui định cỡ chữ và màu chữ
- <p>Nội dung</p> Trình bày văn bản theo đoạn văn
- <i>Nội dung</i> In nghiêng văn bản
- <u>Nội dung</u> Gạch chân văn bản
- <del>Nội dung</del> Xóa văn bản
- <small>Nội dung</small> Hiển thị nội dung nhỏ lại

* Thẻ thể hiện liên kết

    <a href="" title="" target="__blank">Nội dung</a>
    Liên kết đến một trang nào đó

    href: Trang cần liên kết
    title: Mô tả cho liên kết
    target: qui định cách mở trình duyệt

* Thẻ danh sách
- Danh sách tuần tự
    <ol>
        <li>Nội dung 1</li>
        <li>Nội dung 2</li>
        <li>Nội dung 3</li>
    </ol>

- Danh sách bất tuần tự
    <ul>
        <li>Nội dung 1</li>
        <li>Nội dung 2</li>
        <li>Nội dung 3</li>
    </ul>

* Thẻ hình ảnh
    <img src="" alt="" width="" height="" />

    src: đường dẫn của ảnh
    alt: Mô tả cho ảnh
    width: độ rộng của ảnh
    height: độ cao của ảnh

    Chú ý: Không được set width và height cùng 1 lúc

* Các thẻ Form
    - Ý nghĩa của Form: Giúp người sử dụng giao tiếp được với hệ thống (bằng cách gửi thông tin đi)

    <form action="" method="">
        Các thẻ con
        <input type="" name="" placeholder="" size="" />
        type: 
            - text
            - password
            - number
            - email
            - file
            - checkbox
            - radio
    </form>
