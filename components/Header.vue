<template>
    <div class="container">
        <div id="logo"><img class="img-fluid" src="~/assets/logo.png" alt=""></div>

        <div id="search">
            <input class="font" type="text" name="" id="" placeholder="Tìm kiếm">
            <i class="fa fa-search"></i>
        </div>

        <div id="account">
            <i class="fa fa-user-circle icon-account"></i>
            <div class="login-register">
                <nuxt-link to="/login" class="login font">Đăng nhập</nuxt-link>
                <span>/</span>
                <nuxt-link to="/register" class="register font">Đăng ký</nuxt-link>
            </div>
        </div>

        <div id="cart">
            <i class="fa fa-shopping-cart"></i>
            <span class="font">Giỏ hàng</span>
            <i class="fa fa-caret-down"></i>
        </div>
    </div>

</template>

<script>
export default {
    
}
</script>

<style scoped>
    .font{
        font-family: 'Roboto Condensed';
        letter-spacing: 1px;
    }
    .container{
  
        padding: 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    #logo{
        width: 10%;
    }

    #account{
        display: flex;
        align-items: center;
    }
    #account i{
        font-size: 45px;
    }
    #account .login-register{
        margin-left: 10px;
    }
    .login,.register{
        text-decoration: none;
        font-weight: bold;
        color: #070404
    }

    #cart{
       display: flex;
       align-items: center;
       font-weight: bold;
       border: 1px solid #070404;
       padding: 8px;
       border-radius: 4px;
       cursor: pointer;
    }
    #cart i:first-child{
        font-size: 30px;
    }
    #cart span{
        margin: 0px 7px;
    }

    #search{
        width: 25%;
        border: 1px solid #070404;
        padding: 7px 10px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        border-radius: 4px; 
    }
    #search input{
        width: 100%;
    }
    input{
        border: none;
    }
    input:focus{
        outline: none;
    }



   



</style>