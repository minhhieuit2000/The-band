Những thành phần thường gặp trên website
1. Header
2. Navigation (điều hướng của trang)
3. Breadcrumb
4. Sidebar
5. Slider
6. Content
7. Footer

Phân tích Dự án The band
1. Header
2. Slider
3. Content
    + About
    + Tour
    + Contact
    + Img
4. Footer

Tạo thẻ nhanh
ul#nav>li*5>a
ctrl + shift
end 
mũi tên

Popup Buy tickets
Flex box
display: flex (align-item)
 <script>
        /* Biến const Btns lấy 3 nút, document(đại diện trang web), querySelectorAll(lấy tất cả class)*/ 
        const buyBtns = document.querySelectorAll('.js-buy-tickets')
        /* Lấy ra 1 thằng*/
        const modal = document.querySelector('.modal')

        function showBuyTickets(){
            modal.classList.add('open')
        }

        /*Tạo biến mới đại diện cho từng nút (vòng lặp for)*/ 
        for(const buyBtn of buyBtns){
            buyBtn.addEventListener('click', showBuyTickets)
        }
    </script>
    Khi click vào showBuyTickets sẽ gọi đoạn modal add thằng class open vào đoạn html
    