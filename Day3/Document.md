1. CSS & Các khái niệm cơ bản

* Khai báo
    - Trực tiếp
    - Nội tuyến (khai báo trong trang)
        <style>
            ....
        </style>
    - Khai báo ngoại (tạo file css ở bên ngoài)
        <link rel="stylesheet" type="text/css" href="đường dẫn file css" />

* Độ ưu tiên
    - Important có độ ưu tiên cao nhất
    - Khai báo cuối có độ ưu tiên cao nhất

* Selector
    - tagName ex: div {  ... }
    - attributeName ex: span[name='test'] {  ... }
    - class: ex .className { .... }
    - id: ex: #test {  ...  }
    - first-chill
    - last-child

Lưu ý:
    Trên cùng 1 trang không được phép có ID trùng tên nhau

* Cấu trúc và cách định CSS cho 1 thẻ HTML

    selector {
        css attribute1: value1;
        ............
        css attribute2: value2;
    }

    Ex:
        div {
            color: red;
        }

        #demo {
            background: red;
        }

2. Các thuộc tính CSS cơ bản
* Thuộc tính background (qui định màu/ảnh nền)
    background: color url(image path) repeat position attachment

    background-color: value;
    background-image: url(đường dẫn ảnh)
    background-repeat: no-repeat | repeat-x | repeat-y
    backgroun-position: ?px ?px | right bottom | right top | left top | left bottom | center
    background-size: contain | cover

* Thuộc tính border (Qui định đường viền của thẻ)
    border: width type color;

    border-width: ?px;
    border-color: value;
    border-type: solid | dashed | dotted | thin | ....
    border-radius: ?px | ?%
    border-top-left-radius: ?px
    border-bottom-left-radius: ?px
    border-top-right-radius: ?px
    border-bottom-right-radius: ?px

* Nhóm các thuộc tính liên quan đến văn bản
    font-family: (Qui định kiểu loại)
    font-size: ?px | ?% | %rem | %em; (Qui định kích cỡ chữ)
    font-style: italic; (Qui định kiểu chữ)
    font-weight: bold | number
    text-decoration: underline | line-throug | overline;
    text-transform: uppercase | lowercase | capitalize
    letter-spacing: ?px; (Qui định khoảng cách giữa các từ với nhau)
    line-height: 36px; (Tạo khoảng cách dòng)

* Thuộc tính width height & max-width & max-height & min-width & min-height
    div {
        width: 1000px;
        height: 200px;
        min-height: 300px;
        border: 1px solid #ccc;
        max-width: 400px;
    }

* margin & padding
    margin: qui định khoảng các giữa 2 hay nhiều thẻ HTML nằm ngoài nhau
    
    padding: qui định khoảng cách từ đường viền của thẻ đến những nội dung bên 
    trong nó

    margin: top right bottom left;
    padding: top right bottom left;

