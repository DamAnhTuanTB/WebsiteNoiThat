<template>
<div class="container-fluid">
    <div class="container">
        <div class="row">
            <div class="col-6 col-sm-3 mb-sm-0 mb-3">
                <h5>FININ</h5>
                <div>Giới thiệu</div>
                <div>Tuyển dụng</div>
                <div>Hoạt động xã hội</div>
                <div>Liên hệ quảng cáo</div>
            </div>
            <div class="col-6 col-sm-3 mb-sm-0 mb-3">
                <h5>ĐIỀU KHOẢN SỬ DỤNG</h5>
                <div>Điều khoản chung</div>
                <div>Điều khoản giao dịch</div>
                <div>Chính sách thanh toán</div>
                <div>Chính sách bảo mật</div>
            </div>
            <div class="col-6 col-sm-3 mb-sm-0 mb-3">
                <h5>KẾT NỐI VỚI CHÚNG TÔI</h5>
                <div class="d-flex">
                     <div>
                    <img class="img-fluid" src="https://c7.uihere.com/files/353/468/986/menlo-park-facebook-social-media-computer-icons-social-networking-service-facebook-new-logo-png-thumb.jpg" alt="">
                </div>
                <div>
                     <img class="img-fluid" src="https://cdn4.iconfinder.com/data/icons/social-messaging-ui-color-shapes-2-free/128/social-instagram-new-square1-512.png" alt="">
                </div>
                <div>
                    <img class="img-fluid" src="https://municipalidadlongavi.cl/wp-content/uploads/2016/05/youtube_001.jpg" alt="">
                </div>
                <div>
                    <img class="img-fluid" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSy2cdwFne0BX1J7iaxzvAc4IlZE2P6T05zyh0pI1IG6AIQogII&usqp=CAU" alt="">
                </div>
                <div>
                     <img class="img-fluid" src="https://lh3.googleusercontent.com/rFIOt4fDSCgJh_FkHU2qP8YiZUUhfVoKoNfQFbPEM-Wl8zuyuwn7vzkEx_XMh5B6FfO3" alt="">
                </div>
                </div>
            </div>
            <div class="col-6 col-sm-3 mb-sm-0 mb-3">
                <h5>LIÊN HỆ</h5>
                <div>CÔNG TY CỔ PHẦN FITIN VIỆT NAM</div>
                <div>Chăm sóc khách hàng: 19008198</div>
                <div>Tòa nhà FITIN - Số 8, đường Phạm Hùng, quận Nam Từ Liêm, Hà Nội</div>
                <div>Email hỗ trợ: fitinvn@gmail.com</div>
            </div>
       </div>
    </div>
    <div class="copyright">Copyright ©2021 All rights reserved</div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.container{
    padding: 50px 0px;
}
.container div{
    font-family: 'Roboto Condensed';
    letter-spacing: 0.5px;
    color: white
}
.container-fluid{
    background: #1E1F29 !important;
    border-top: 3px solid rgb(0, 132, 255);
}
h5{
    display: inline-block;
    border-bottom: 3px solid white;
}
.d-flex div{
    height: 40px;
    width: 40px;
    padding: 2px;
    transition: 0.2s;
}
.d-flex div img{
    border-radius: 3px;
}
.d-flex div:hover{
    transform: scale(0.9);
}

.container > div > div > div{
    transition: 0.2s;
    cursor: pointer;
}

.container > div > div > div:hover{
    color: rgb(0, 132, 255)
}

.container > div > div:nth-child(4) > div:hover{
     color: white;
}
.copyright{
    height: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-family: 'Roboto Condensed';
    background: #494a4d;
}
</style>