<template>
<div class="header-hde">
  <div class="header">
		<h1 class="header_logo"></h1>
		<a href="#" class="header_a1">产品</a>
        <a href="#" class="header_a2" @mouseenter="show1" @mouseleave="hide1">智能硬件</a>
        <a href="#" class="header_a6">客户案例</a>
        <a href="#" class="header_a3">服务</a>
        <a href="#" class="header_a2">DING峰会</a>
        <a href="#" class="header_a2">开放平台</a>
        <a href="#" class="header_a2">合作伙伴</a>
        <a href="#" class="header_a2">下载盯盯</a>
        <a href="javascript:;" class="header_a4">注册盯盯</a>
        <a href="javascript:;" class="header_a5">企业盯盯</a>
        <div  class="header_div" v-show="show1_data" @mouseenter="show1" @mouseleave="hide1">
        	
     
        <ul class="header_ul">
        	<li class="header_ul_li">
        		<a href="#" class="header_ul_a">
        			<p class="header_ul_p">新品</p>
        			<div class="header_ul_img">
        				
        			</div>
        			<p class="header_ul_p2">
        				 盯盯智能前台
        			</p>
        			<p class="header_ul_price">
        				1099元
        			</p>
        		</a>
        	</li>
        	<li class="header_ul_li">
        		<a href="#" class="header_ul_a">
        			<p class="header_ul_p">新品</p>
        			<div class="header_ul_img">
        				
        			</div>
        			<p class="header_ul_p2">
        				 盯盯智能前台
        			</p>
        			<p class="header_ul_price">
        				1099元
        			</p>
        		</a>
        	</li>
        	<li class="header_ul_li">
        		<a href="#" class="header_ul_a">
        			<p class="header_ul_p">新品</p>
        			<div class="header_ul_img">
        				
        			</div>
        			<p class="header_ul_p2">
        				 盯盯智能前台
        			</p>
        			<p class="header_ul_price">
        				1099元
        			</p>
        		</a>
        	</li>
        	<li class="header_ul_li">
        		<a href="#" class="header_ul_a">
        			<p class="header_ul_p">新品</p>
        			<div class="header_ul_img">
        				
        			</div>
        			<p class="header_ul_p2">
        				 盯盯智能前台
        			</p>
        			<p class="header_ul_price">
        				1099元
        			</p>
        		</a>
        	</li>
        	<li class="header_ul_li">
        		<a href="#" class="header_ul_a">
        			<p class="header_ul_p">新品</p>
        			<div class="header_ul_img">
        				
        			</div>
        			<p class="header_ul_p2">
        				 盯盯智能前台
        			</p>
        			<p class="header_ul_price">
        				1099元
        			</p>
        		</a>
        	</li>
        </ul>
        </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      show1_data:false
    }
  },
  methods:{
  	show1(){
  		this.show1_data = true;
  	},
  	hide1(){
  		this.show1_data = false;
  	}
  }
}
</script>
<style scoped>
	.header_ul_price{
		text-align: center;
    color: #3296fa;
    font-size: 12px;
    line-height: 20px;
    width: 180px;
    position: absolute;
    top: 171px;
	}
	.header_ul_p2{
		text-align: center;
    color: #333;
    font-size: 12px;
    line-height: 16px;
    width: 180px;
    position: absolute;
    top: 155px;
	}
	.header_ul_img{
		position: absolute;
    margin: 0 auto;
    top: 35px;

    width: 180px;
    box-sizing: border-box;
    height: 120px;
    padding: 0px 30px;
    border-right: 1px solid #ebeced;
    background: url(../assets/image/list_1.png);
    background-size:100% 100% ;
	}
	.header_ul_p{
		width: 30px;
    height: 30px;
    top: 0;
    left: 0;
    font-size: 12px;
    line-height: 30px;
    text-align: center;
    color: #fff;
    box-sizing: border-box;
    background-color: #3296fa;
	}
	.header_ul_a{
		float: left;
		width: 180px;
		height: 200px;
		font-size: 14px;
		box-sizing: border-box;
	}
	.header_ul_li{
		float: left;
	}
	.header_ul{
		position: absolute;
		width: 1180px;
		height: 200px;
		left: 50%;
		margin-left: -590px;
		background: #fff;
		border-top: 1px solid #ebeced;
		box-sizing: border-box;
		}
		.header_div{
		position: absolute;
		width: 100%;
		height: 200px;
		background: #fff;
		border-top: 1px solid #ebeced;
		left: 0px;
		top: 80px;
		}
	.header-hde{
		width: 100%;
		position: fixed;
		background: #fff;
		z-index: 9999;
	}
	.header{
		width: 1180px;
		height: 81px;
		margin: 0px auto;
		/*background: #42B983;*/
/*		box-sizing: border-box;*/
		display: flex;
		flex-flow:row nowrap;
		align-items: center;

	}
	.header_logo{
		width: 88px;
		height: 32px;
		background: url(../assets/image/logo.png);
		background-size: 100% 100%;
		float: left;
	}
	.header_a1{
		width: 33px;
		height: 80px;
		float: left;
		line-height: 80px;
		margin-left: 150px;
	}
	.header_a1:hover{
		color: #3296FA;
	}
	.header_a2:hover{
		color: #3296FA;
	}
	.header_a3:hover{
		color: #3296FA;
	}
	.header_a5:hover{
		color: #3296FA;
	}
	.header_a6:hover{
		color: #3296FA;
	}
	.header_a2{
		width: 75px;
		height: 80px;
		float: left;
		line-height: 80px;
		margin-left: 20px;
		text-align: center;
	}
	.header_a3{
		width: 33px;
		height: 80px;
		float: left;
		line-height: 80px;
		margin-left: 20px;
		text-align: center;
	}
	.header_a4{
		width: 80px;
		height: 80px;
		line-height: 80px;
		text-align: center;
		background: #2180e0;
		color: #fff;
		margin-left: 150px;
	}
	.header_a5{
		width: 80px;
		height: 80px;
		line-height: 80px;
		text-align: center;
		border-right:1px solid #eee ;
	}
	.header_a6{
		width: 80px;
		height: 80px;
		line-height: 80px;
		text-align: center;
		background: url(../assets/image/new.png) no-repeat left 20px;
	}
</style>
