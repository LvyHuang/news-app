<template>
  <div id="app">
    <div style="width: 1080px;margin: 0 auto">
      <Banner :banners="banners"/>
    </div>

  </div>
</template>


<script>
  import Banner from "./components/Banner";
  export default {
    components:{
      Banner,
    },
    data(){
      return {
        banners:[
          {url:require("./assets/banner/banner1.jpeg"), link:"https://baidu.com"},
          {url:require("./assets/banner/banner2.jpeg"), link:"https://zhihu.com"},
          {url:require("./assets/banner/banner3.jpeg"), link:"https://sougou.com"},
        ]
      }
    }
  };
</script>

