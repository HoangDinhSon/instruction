cài đặt boostrap (CSS+JS) 3 cách .
cài iquery (thư viện của JS)
phan tích cau truc instruction cyber  (Header , cyberCarousel, ...., footer)
cài font chữ work sans cho index.html 
cài font chu work sans cho index.CSS
cài font size : nếu không cài thì mặc định 16 px 
cài font awesome cài thông qua cdn (cdn giống như một thư viện đám mây )
xử lí phần header top  (backgroud color , cho hai hàng trên 1 dòng dùng thư viện chương 2boostrap d-flex chỉnh hướng , chỉnh cách sắp xếp các item con )
    các class dùng của boostrap : .d-flex , .align-item-center , .text-white ,
    text-decoration , 
    margin là khoảng cách giữa các thẻ , padding là nội bộ khoảng cách giữa nội dung và viền 
    cách căn nội dung theo chiều ngang : text-align 
    căn theo chiều dọc : line-height , hoặc dùng flex .
  xử lý phần nav bar : 
    dùng đến phần compoent của boostrap : copy code 
    cấu trúc : 3 phần : navbar-brand ,button(responsive), collapse > dropdown
    cách gọi đến thẻ con 
    tranform : skew ( cho quyển sách nghiêng )
    đẩy nội dung sang phải thường sẽ dùng padding right nhưng nếu dùng margin auto ok 
    xu lí phần gạch chân khi bị hover vào . dùng after , before 
    xử lí margin căn đều 2 bên dùng container , container-fluid 
    vấn đề nếu người dùng đang ở trang nào thì mục đó phải sáng ??? dùng kĩ thuật đè code 
    code sau có giá trị selector hơn code trước 
      b1 : gắn 1 thẻ active cho thẻ li (Home )
      b2 : gọi các thuộc tính mà muốn giữ nguyên cho nó . 
    -chỉnh màu cho dropdown menu (rgba 0,0,0, 0.6 ), màu chữ black 
    - chỉnh hover và focus cho dropdown menu , màu chữ thành hồng , backgroud transparent 
# chương 3 : Carousel
  -cài đặt code của thư viện boostrap cho html( chọn cái muc caption = mô tả chính )
  -tạo ảnh trước trong đó , alt là mô tả muc đích tốt cho SEO 
  - Carousel-Caption : muốn căn giua các khối mà có posion thì cần dùng margin không dùng được flex , top:50%, , right:50%  và dùng tranform: translate(50%, 50%)
# chuong 4 : Welcome 
  -phan tích : 2  thẻ con trực tiếp , thấy có class heading dùng chung khai báo lên đầu tiên trong css
  -khi ta dùng after set các kiểu mà không hiện nguyên nhân là thẻ inlien không set được chiều cao và chiều rộng vậy cần chuyển về display: block;
  - biết cách tạo một class có các tính chất để dùng chung .(section, class heading )
  -boostrap :Grid System quy ước kích thước màn hình 12 cột . (áp dụng cho tất cả màn hình )
    span 1, span1 , span1 ...span1 ;  vậy ta cần gom cột. ---> 
    khi ghi span4 : = 4 cột gom lại với nhau .
# chương 5 our starts 
  - cho ảnh làm background có 2 cách 
    c1: thêm ảnh trong file html và sau đó CSS
    C2: thêm ảnh trong CSS và chỉnh trong CSS luôn 
    cần phân biệt ảnh làm back ground khác với ảnh được cho vào để làm gì đó 
# chương 6 offer 
# chương 7 : feedback 
  -cài owl carousel , tải về và cài Css sau đó cài js (trong đó is có 2 file ).làm sao biết file nào mà cài đặt. 
  -thiết lập layout bằng html xem cho demo trong trang wep owl carousel để thiết la html và JS 
    + nhìn html và nhìn setup 
    + dùng display flex(nếu không ghi gì thì khả năng mặc định các item nằm ngang với nhau ) : thì thuộc tính align-item dùng để căn theo chiểu dọc 
# chương 8: news
  b1: dàn layout dùng boostrap 
     - dàn layout lúc chứa ảnh : dùng thư viện của boostrap .img-fluid , 
     - bộ selector khi chọn thẻ P thứ 3/10 
     
# chương 9:MODAL
- muốn làm boostrap để tạo nút modal thì đầu tiên phải cài đúng phiên bản. phiên bản boostrap cài bản nào thì phải dùng modal của bản đó modal 5.3 ==> boos trap cũng phải 5.3 
-đổi id example modal---> modalInstruction
- ôn lại 8 cách selector
# chương 10 :footer
- section.footer -div.footer__content- div.footer__top  -3xfooter__item
                                      -div.footer__botom
                                      -div.coppyring 


                 



