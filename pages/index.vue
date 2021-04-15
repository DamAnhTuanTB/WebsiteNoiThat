<template>
  <div class="container-fluid">

    <div id="banner" class="row">
       <div class="col-sm-6" id="text-header">
          <div class="first-text">WELCOME TO</div>
          <div class="second-text">FITINVN</div>
          <div class="third-text">- Love begins at home, Love lives in home -</div>
       </div>
       <div class="col-sm-6">
           <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="~/assets/banner1.jpg" class="d-block w-100" alt="">
                       
                    </div>
                    <div class="carousel-item">
                        <img src="~/assets/banner2.jpg" class="d-block w-100" alt="">
                        
                    </div>
                    <div class="carousel-item">
                        <img src="~/assets/banner3.jpg" class="d-block w-100" alt="">
                      
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
          </div>

        
       </div>
    </div>

    <div class="parent-marketing row">
       <h1 class="wow bounce">OUR ADVANTAGES</h1>
       <div class="marketing">
 
            <div class="col-lg-4 mb-3 mb-lg-0  wow bounceInLeft">
                <div class="circle"> <i class="far fa-star fa-5x text-white"></i> </div>
                <h2>Đa dạng</h2>
                <p>Rất nhiều mẫu mã, màu sắc, kích thước phù hợp với mọi căn nhà.</p>
            </div>

            <div class="col-lg-4 mb-3 mb-lg-0  wow bounceInUp">
                <div class="circle"> <i class="far fa-check-circle fa-5x text-white"></i> </div>
                <h2>Chất lượng </h2>
                <p>Đảm bảo quy trình sản xuất hiện đại và tốt nhất Việt Nam.</p>
            </div>

            <div class="col-lg-4 mb-3 mb-lg-0  wow bounceInRight">
                <div class="circle"> <i class="fa fa-heartbeat fa-5x text-white"></i> </div>
                <h2>Bảo hành tận tâm</h2>
                <p>Đội ngũ thiết kế luôn lắng nghe và sẵn sàng sữa chữa giúp bạn.</p>
            </div>

       </div>
    </div>

    <div class="info-admin row">
      
        <div class="row">
            <div class="col-sm-3" id="introduce-admin">
                  <h1 class="">OUR TEAM</h1>
                  <h3 class="">FITINVN</h3>
                  <p class="">Chúng tôi là một đội ngũ chuyên gia thiết kế nội thất tận tâm và chuyên nghiệp. Chúng tôi luôn đặt chất lượng sản phẩm và sự hài lòng khách hàng lên hàng đầu. Sologan của chúng tôi: "Love begins at home, Love lives in home".</p>
                  <div>
                      <div class="square"><i class="far fa-envelope fa-2x"></i></div>
                      <div class="square"><i class="fas fa-arrow-left fa-2x"></i></div>
                      <div class="square"><i class="fas fa-arrow-right fa-2x"></i></div>
                  </div>
            </div>
            <div class="col-sm-9">
                <div class="row" id="row1-image">
                    <div class="col-sm-4 p-5 hover">
                        <img style="" class="img-fluid" src="~/assets/nam.jpg" alt="">
                        <div>Nguyễn Đăng Nam</div>
                    </div>
                    <div class="col-sm-4 p-5 hover">
                        <img class="img-fluid" src="~/assets/tuan.jpg" alt="">
                         <div>Đàm Anh Tuấn</div>
                    </div>
                    <div class="col-sm-4 p-5 hover">
                        <img class="img-fluid" src="~/assets/tuan.jpg" alt="">
                        <div >Đàm Anh Tuấn</div>
                    </div>
                </div>

                <div class="row" id="row2-image">
                    <div class="col-sm-2" ></div>
                    <div class="col-sm-4 p-5 hover">
                        <img class="img-fluid" src="~/assets/son.jpg" alt="">
                        <div style="transform: rotate(0deg)">Vương Tuấn Sơn</div>
                    </div>
                    <div class="col-sm-4 p-5 hover">
                        <img class="img-fluid" src="~/assets/tuan.jpg" alt="">
                        <div style="transform: rotate(0deg)">Đàm Anh Tuấn</div>
                    </div>
                    <div class="col-sm-2"></div>
                </div>
            </div>
        </div>
     </div>
     <div>
    </div>

    <div class="container category">
      <h1>CATEGORY</h1>
      <div class="row">
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/ban.jpg" alt="">
          <div>Bàn</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/ghe.jpg" alt="">
          <div>Ghế</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/ke.jpg" alt="">
          <div>Kệ</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/tu.jpg" alt="">
           <div>Tủ</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/sofa.jpg" alt="">
          <div>Sofa</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/giuong.jpg" alt="">
          <div>Giường</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/dogiadung.jpg" alt="">
          <div>Đồ gia dụng</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/den.jpg" alt="">
          <div>Đèn</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/lotrangtri.jpg" alt="">
          <div>Lọ trang trí</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/guong.jpg" alt="">
          <div>Gương</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/thungrac.jpg" alt="">
          <div>Thùng rác</div>
        </div>
        <div class="col-4 col-sm-2 p-sm-4">
          <img class="img-fluid" src="~/assets/bosanpham.jpg" alt="">
          <div>Bộ sản phẩm</div>
        </div>
      </div>
    </div>
  


    <div id="top-sell" class="container carousel slide" data-bs-ride="carousel" >
        <h1>TOP SELLING PRODUCTS</h1>
        
          <div class="carousel-inner">
              <div class="carousel-item active">
                 <div class="row">
                   <div class="col-sm-3" v-for="pd in topSellProducts.slice(0,4)">
                      <top-product :title="pd.title" :result="pd.result" :top="pd.top" :ncc="pd.ncc" :priceSale="pd.priceSale" :priceOrigin="pd.priceOrigin"/>
                   </div>
          
                 </div>
                  
              </div>
              <div class="carousel-item">
                 <div class="row">
                   <div class="col-sm-3" v-for="pd in topSellProducts.slice(4,8)">
                      <top-product :title="pd.title" :result="pd.result" :top="pd.top" :ncc="pd.ncc" :priceSale="pd.priceSale" :priceOrigin="pd.priceOrigin"/>
                   </div>
                 </div>
                  
              </div>
              
          </div>

          <button class="carousel-control-prev" type="button" data-bs-target="#top-sell" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"><i class="fas fa-angle-left"></i></span>
              <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#top-sell" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"><i class="fas fa-angle-right"></i></span>
              <span class="visually-hidden">Next</span>
          </button>
    </div>


    <div id="new-product" class="container carousel slide" data-bs-ride="carousel">
        <h1>NEW PRODUCTS</h1>
        
          <div class="carousel-inner">
              <div class="carousel-item active">
                 <div class="row">
                   <div class="col-sm-3" v-for="pd in topSellProducts.slice(4,8)">
                      <top-product :title="pd.title" :result="pd.result" :top="pd.top" :ncc="pd.ncc" :priceSale="pd.priceSale" :priceOrigin="pd.priceOrigin"/>
                   </div>
          
                 </div>
                  
              </div>
              <div class="carousel-item">
                 <div class="row">
                   <div class="col-sm-3" v-for="pd in topSellProducts.slice(0,4)">
                      <top-product :title="pd.title" :result="pd.result" :top="pd.top" :ncc="pd.ncc" :priceSale="pd.priceSale" :priceOrigin="pd.priceOrigin"/>
                   </div>
                 </div>
                  
              </div>
              
          </div>

          <button class="carousel-control-prev" type="button" data-bs-target="#new-product" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"><i class="fas fa-angle-left"></i></span>
              <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#new-product" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"><i class="fas fa-angle-right"></i></span>
              <span class="visually-hidden">Next</span>
          </button>
    </div>


  


  </div>
</template>

<script>

import TopProduct from '~/components/TopProduct.vue'

import {mapState} from 'vuex';









export default {
  components: { TopProduct },
  computed: {
    ...mapState(['topSellProducts'])
  },
  head: {
    title: "Trang chủ",
  },
  layout(context){
    return "home"
  },
  mounted(){
   


  }
}
</script>

<style>
.category{
  padding: 50px 20px !important;
  border-bottom: 3px solid rgb(160, 156, 168);
}
.category .col-4 > div{
  font-family: 'Roboto Condensed';
  letter-spacing: 0.7px;
  text-align: center;
  font-size: 20px;
}
.category h1{
  text-align: center;
  font-family: Oswald;
  word-spacing: 3px;
  letter-spacing: 4px;
  color:  #070404;
  text-shadow: 0px 1px 4px white;
  margin-bottom: 20px;
}
.category .col-4{
  transition: 0.2s;
  cursor: pointer;
}

.category .col-4:hover{
  transform: translateY(-3px);
  box-shadow: 1px 1px 2px 1px rgb(214, 205, 205);
}



#top-sell .fa-angle-left{
  border-radius: 50%;
  padding: 0px 4px;
  background: rgb(156, 155, 155);
  color: white;
}

#top-sell{
  padding: 50px 20px;
}

#top-sell h1{
  text-align: center;
  font-family: Oswald;
  word-spacing: 3px;
  letter-spacing: 4px;
  color:  #070404;
  text-shadow: 0px 1px 4px white;
  margin-bottom: 20px;
}
#top-sell .fa-angle-right{
  border-radius: 50%;
  padding: 0px 4px;
  background:  rgb(156, 155, 155);
  color: white;
  
}

#top-sell .col-sm-3{
   cursor: pointer;
   transition: 0.2s;
}
#top-sell .col-sm-3:hover{
  transform: scale(0.98);
}

.carousel-control-next,.carousel-control-prev {
    position: absolute;
    top: 50%;
    bottom: 40%;
    z-index: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 5%;
    padding: 0;
    color: #fff;
    text-align: center;
    background: 0 0;
    border: 0;
    opacity: .5;
    transition: opacity .15s ease;
}

#top-sell .carousel-control-prev-icon {
    display: inline-block;
    width: 2rem;
    height: 2rem;
    background:transparent;
    /* border: 1px solid black; */
    color: black !important; 
    transform: scale(3);
 

}
#top-sell .carousel-control-next-icon{
    display: inline-block;
    width: 2rem;
    height: 2rem;
     background:transparent;
    /* border: 1px solid black; */
    color: black !important; 
    transform: scale(3);
 

}



#new-product .fa-angle-left{
  border-radius: 50%;
  padding: 0px 4px;
  background: rgb(156, 155, 155);
  color: white;
}

#new-product{
  padding: 50px 20px;
  border-top: 3px solid rgb(160, 156, 168);
}

#new-product h1{
  text-align: center;
  font-family: Oswald;
  word-spacing: 3px;
  letter-spacing: 4px;
  color:  #070404;
  text-shadow: 0px 1px 4px white;
  margin-bottom: 20px;
}
#new-product .fa-angle-right{
  border-radius: 50%;
  padding: 0px 4px;
  background:  rgb(156, 155, 155);
  color: white;
  
}


#new-product .col-sm-3{
   cursor: pointer;
   transition: 0.2s;
}
#new-product .col-sm-3:hover{
  transform: scale(0.98);
}

#new-product .carousel-control-prev-icon {
    display: inline-block;
    width: 2rem;
    height: 2rem;
    background:transparent;
    /* border: 1px solid black; */
    color: black !important; 
    transform: scale(3);
 

}
#new-product .carousel-control-next-icon{
    display: inline-block;
    width: 2rem;
    height: 2rem;
     background:transparent;
    /* border: 1px solid black; */
    color: black !important; 
    transform: scale(3);
 

}








.container{
    padding: 0px 20px;
}
#text-header{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-image: url('~/assets/bannergif.gif');
    background-position: center;
    background-repeat: none;
    background-size: cover;
}
.first-text{
  font-family: 'Bungee Inline';
  font-size: 30px;
  text-shadow: 0px 1px 4px white;
}

.second-text{
  font-family: 'Bungee Inline';
  font-size: 70px;
  text-shadow: 0px 1px 4px white;
  
}

.third-text{
    font-family: VT323;
    font-size: 35px;
    text-shadow: 0px 1px 4px white;
}
.col-sm-6{
    padding: 0px !important;
}

/* info admin */
#row1-image div:nth-child(1){
   transform: rotate(-4deg)
}

#row1-image div:nth-child(3){
   transform: rotate(4deg)
}

#row2-image div:nth-child(2){
   transform: rotate(-3deg)
}

#row2-image div:nth-child(3){
   transform: rotate(3deg)
}

.info-admin{
  padding: 10px 0px;
  background-image: url('~/assets/bg3.jpg');
  background-size: cover;
  box-shadow: 0px 5px 5px 5px rgb(253, 253, 253);

}
.info-admin img {
    border: 1px solid white;
    outline: 6px solid rgb(82, 82, 94);
    border-radius: 4px;
    width: 90%;
}

.info-admin .col-sm-4{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    transition: 0.2s;
    cursor: pointer;
}

.hover:hover{
    transform: scale(1.1) !important;
}

.info-admin .col-sm-4 div{
    font-family: Oswald;
    letter-spacing: 5px;
    font-size: 20px;
    word-spacing: -5px;
    padding: 5px;
    font-weight: bold;
}

#introduce-admin{
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-left: 60px;
    text-align: justify;
    
}

#introduce-admin h1{
  font-family: Oswald;
  word-spacing: 3px;
  letter-spacing: 4px;
  color:  #070404;
  text-shadow: 0px 1px 4px white;
}

#introduce-admin h3{
    text-shadow: 0px 1px 4px white;
    font-family: 'Bungee Inline';
}

#introduce-admin p{
    font-size: 20px;
    text-shadow: 0px 1px 4px white;
    font-family: 'Roboto Condensed';
    letter-spacing: 0.7px;
}

.info-admin .square{
    display: inline-block;
    border: 3px solid  #070404;
    padding: 10px 12px;
    border-radius: 4px;
    transition: 0.2s;
    cursor: pointer;

}

.info-admin .square:hover{
    border: 3px solid  rgb(39, 121, 245);
}

.info-admin .square i{
    transition: 0.2s;

}

.info-admin .square i:hover{
    transform: scale(1.1);

}



/* Marketting start */
#total-like{
  white-space: nowrap;
}
.marketing .col-lg-4 {
  text-align: center;
  
}
.marketing h2 {
  font-weight: 400;
}

.marketing .col-lg-4 p {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.parent-marketing{
  padding: 50px 20px;
  background-image: url('~/assets/bg12.jpg');
  background-position: center;
  background-size: cover;
  box-shadow: 0px 5px 5px 5px rgb(253, 253, 253);
}

.parent-marketing h1{
  font-family: Oswald;
  text-align: center;
  word-spacing: 3px;
  letter-spacing: 4px;
  color:  #070404;
  text-shadow: 0px 1px 4px white;
}

.marketing{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 50px
}
.marketing .circle{
  width: 8em;
  height: 8em;
  border-radius: 50%;
  background: rgb(72, 75, 83);
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  box-shadow: 0px 0px 2px 3px rgb(228, 228, 228);
  border: 2px solid white;
  
}
.marketing h2{
  font-family: 'Roboto Condensed';
  letter-spacing: 1px;
  color:  #070404;
  text-shadow: 0px 1px 4px white;
  font-size: 28px;
  margin-top: 10px;
}

.marketing p{
  font-size: 20px;
  text-shadow: 0px 1px 4px white;
  font-family: 'Roboto Condensed';
  letter-spacing: 0.5px;
}

/* Marketting end */

</style>