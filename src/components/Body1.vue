<template>
	<div class="body1_div">
		<div class="body1_main">
			<div class="body_logo">
			</div>
			<div class="body_scroll1">
				<a href="#" class="body_scroll1_a">
					2015/1/11 | 阿里巴巴钉钉“寻找教育行业酷公司”论坛：教育企业如何成为新物种
				</a>
				<a href="#" class="body_scroll1_a">
					2015/1/11 | 左手写代码 右手修电脑 一个小学校长的钉钉攻略
				</a>
				<a href="#" class="body_scroll1_a">
					2015/1/11 | 拥抱新零售，大润发高效沟通从钉钉开始
				</a>
			</div>
			<a href="#" class="body_scroll1_a2">查看更多></a>
		</div>
		<div class="body1_main2">
			<ul class="body1_ul1">
				<li class="body1_li1">
					<a href="#" class="body1_li1_a1" @mouseenter="bianda">
						<span class="body1_li1_span1">
							酷公司“0元购机计划”第2季
						</span>
						<span class="body1_li1_span1">
							钉钉多款智能硬件全额返现
						</span>
					</a>
				</li>
				<li class="body1_li1">
					<a href="#" class="body1_li1_a1" @mouseenter="bianda">
						<span class="body1_li1_span1">
							酷公司“0元购机计划”第2季
						</span>
						<span class="body1_li1_span1">
							钉钉多款智能硬件全额返现
						</span>
					</a>
				</li>
				<li class="body1_li1">
					<a href="#" class="body1_li1_a1" @mouseenter="bianda">
						<span class="body1_li1_span1">
							酷公司“0元购机计划”第2季
						</span>
						<span class="body1_li1_span1">
							钉钉多款智能硬件全额返现
						</span>
					</a>
				</li>
				<li class="body1_li1">
					<a href="#" class="body1_li1_a1" @mouseenter="bianda">
						<span class="body1_li1_span1">
							酷公司“0元购机计划”第2季
						</span>
						<span class="body1_li1_span1">
							钉钉多款智能硬件全额返现
						</span>
					</a>
				</li>
			</ul>
		</div>
	</div>
</template>

<script>
	export default {
  name: 'Body1',
  data () {
    return {
      num:0
    }
  },
  methods:{
  	bianda(e){
  		//alert(e.target.style.marginTop)
  		//e.target.style.marginTop ="-30px"
  	}
  },
  mounted(){
  	var num = 0;
  	function scro1(){
  		
  		//console.log();
  		switch(num){
  			case 0:
  				console.log("case0");
  				for(var i =0;i<3;i++){
  					document.querySelectorAll(".body_scroll1_a")[i].className="body_scroll1_a anima"
  				}
				
  				break;
  			
  			case 1:
				console.log("case1");
				for(var i =0;i<3;i++){
  					document.querySelectorAll(".body_scroll1_a")[i].className="body_scroll1_a anima1"
  				}
  				break;
  			
  			case 2:
  				console.log("case2");
				for(var i =0;i<3;i++){
  					document.querySelectorAll(".body_scroll1_a")[i].className="body_scroll1_a anima2"
  				}
  				break;
  			
  		}
  		num++;
  		if(num == 3){
  			num=0
  		}
  		
  	}
  	function inter(){
  		var i = setInterval(scro1,4100);
  		
  	}
  	inter();
  }
}
</script>

<style>
	.body1_li1_span1{
		display: inline-block;
		width: 100%;
		text-align: center;
		font-size: 18px;
		margin: 10px 0px;
	}
	.body1_li1_a1{
		border: 1px solid #eaebec;
		width: 100%;
		height: 221px;
		box-sizing: border-box;
		float: left;
		background: url(../assets/image/li_a.png);
		background-size: 100% 100%;
		transition: margin-top 0.5s;
	}
	.body1_li1_a1:hover{
		box-shadow:0 15px 30px rgba(0,0,0,.1);
		margin-top: -10px;
	}
	.body1_li1{
		
		width: 25%;
		height: 221px;
		box-sizing: border-box;
		float: left;
		
		position: relative;
	}
	.body1_ul1{
		width: 1180px;
		height: 221px;
		/*overflow: hidden;*/
		margin: auto;
	}
	.body1_main2{
		width: 100%;
		height: 221px;
		padding: 20px 0px 40px 0px;
	}
	.body_scroll1_a2{
		float: right;
	}
	@keyframes scrollinterval{
	0%   {transform:  translateY(-0px) rotateX(-0deg)}
	50%  {transform:  translateY(-10px) rotateX(-5deg)}
	75%  {transform:  translateY(-20px) rotateX(-15deg)}
	100% {transform: translateY(-30px) rotateX(-20deg)}
}
	@keyframes scrollinterval1{
	0%   {transform:  translateY(-30px) rotateX(-20deg)}
	50%  {transform:  translateY(-40px) rotateX(-25deg)}
	75%  {transform:  translateY(-50px) rotateX(-35deg)}
	100% {transform: translateY(-60px) rotateX(-40deg)}
}
	@keyframes scrollinterval2{
	0%   {transform:  translateY(-60px) rotateX(-40deg)}
	50%  {transform:  translateY(-70px) rotateX(-45deg)}
	75%  {transform:  translateY(-80px) rotateX(-55deg)}
	100% {transform: translateY(-90px) rotateX(-60deg)}
}
	.body1_div{
		width: 100%;
		height: 57px;
		position: absolute;
		top: 580px;
	}
	.body1_main{
		width: 1180px;
		height: 57px;
		padding-top: 25px;
		box-sizing: border-box;
		margin: auto;
		
	}
	.body_logo{
		width: 87px;
		height: 30px;
		background: url(../assets/image/newlogo.png);
		background-size:100% 100% ;
		float: left;
	}
	.body_scroll1{
		width: 649px;
		height: 30px;
		line-height: 30px;
		margin-left:30px;
		float: left;
		overflow: hidden;
		
		/*transform-style: preserve-3d;*/
	}
	.body_scroll1_a{
		text-decoration: none;
    	color: #000;
    	font-size: 16px;
    	
    	display: block;
	}
	.anima{
		animation: scrollinterval linear 3s forwards ;
	}
	.anima1{
		animation: scrollinterval1 linear 3s forwards ;
	}
	.anima2{
		animation: scrollinterval2 linear 3s forwards ;
	}
</style>