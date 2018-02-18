<template>
  <div id="app">
    <Header></Header>
    <Swiper></Swiper>
    <Body1></Body1>
    <Body2 />
    <Body3 />
    <Body4 />
    <Body5 />
  </div>
</template>

<script>
import  Header from './components/Header.vue'
import  Swiper from './components/Swiper.vue'
import  Body1 from './components/Body1.vue'
import  Body2 from './components/Body2.vue'
import  Body3 from './components/Body3.vue'
import  Body4 from './components/Body4.vue'
import  Body5 from './components/Body5.vue'
export default {
  name: 'app',
  data () {
    return {
      
    }
  },
  components:{
  	Header,
  	Swiper,
  	Body1,
  	Body2,
  	Body3,
  	Body4,
  	Body5
  }
}
</script>

<style>
	body{
		background: #F5F5F5;
		font-family: "微软雅黑";
	}
	a{
		text-decoration: none;
		color: #000000;
	}
</style>
