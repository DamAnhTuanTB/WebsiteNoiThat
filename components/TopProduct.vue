<template>
    <div style="border: 1.5px solid rgb(212, 212, 212); padding: 10px 20px; border-radius: 10px; width: 96%; box-shadow: 0px 0px 1px 0.3px rgb(212, 212, 212)">
        <div class="row">
            <div class="col-12 p-1">
                <img class="w-100" :src="result" alt="">
            </div>
        </div>
      <div class="row">
          <div class="col-4 p-1" v-for="(link, index) in top" >
              <img :alt="index" @click="handleClick" class="img-fluid" :src="link" :class="{'active': activeKey == index}">
          </div>
      </div>
     <div style="font-family: 'Roboto Condensed'; letter-spacing:0.5px; display: flex; justify-content: center; align-items: center; font-size: 16px; border-bottom: 1.5px solid rgb(212, 212, 212); height: 60px; text-align: justify; text-shadow: 0px 0px 0px gray">{{title}}</div>
     <div class="d-flex justify-content-between align-items-center" style="padding: 5px 0px">
         <div class="d-flex flex-column">
             <span style="font-weight: bold">{{priceSale}} VNĐ</span>
             <span style="font-size: 14px; color: gray; text-decoration: line-through">{{priceOrigin}} VNĐ</span>
         </div>
         <span>
             <img :src="ncc" alt="">
         </span>
     </div>
    </div>
</template>

<script>
export default {
    props: {
        result: {
            type: String
        },
        top: {
            type: Array
        },
        ncc: {
            type: String
        },
        priceSale: {
            type: String
        },
        priceOrigin: {
            type: String
        },
        title: {
            type: String
        }
    },
    data(){
        return {
          activeKey: "",
        }
    },
    methods: {
        handleClick(event){
            this.result = event.target.attributes.src.value;
            this.activeKey = event.target.attributes.alt.value;
            console.log(this.activeKey);
           
        }
    }
}
</script>

<style scoped>
.active{
    border: 1.5px solid rgb(105, 105, 105);
    border-radius: 5px;
    box-shadow: 0px 0px 2px 0.2px gray;
}
.col-4{
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>