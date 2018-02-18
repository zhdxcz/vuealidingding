<template>
	<div class="div_zong">
	<div class="body2_1">
		<div class="span1">
		    超过500万家企业组织正在使用盯盯
		</div>
		<div class="span2">
			钉钉正在共享各行各业优秀的工作方式，帮助中国企业进入智能移动办公时代。<br>
			让工作更简单、高效、安全
		</div>
		<div class="circle_bg">
			<div class="circle_a" id="circle1">
				
			</div>
			<div class="circle_a" id="circle2">
				
			</div>
			<div class="circle_a" id="circle3">
				
			</div>
		</div>
		<ul class="body2_ul">
			<li class="body2_ul_li">
				<a class="body2_a" href="#">
					
				
				<p class="body2_li_p">
					90万+
				</p>
				<p class="body2_li_p2">
					IT互联网企业
				</p>
				<a href="#" class="body2_li_a1">
					查看优秀案例>
				</a>
				</a>
			</li>
			<li class="body2_ul_li">
				<a class="body2_a" href="#">
					
				
				<p class="body2_li_p">
					90万+
				</p>
				<p class="body2_li_p2">
					IT互联网企业
				</p>
				<a href="#" class="body2_li_a1">
					查看优秀案例>
				</a>
				</a>
			</li>
			<li class="body2_ul_li">
				<a class="body2_a" href="#">
					
				
				<p class="body2_li_p">
					90万+
				</p>
				<p class="body2_li_p2">
					IT互联网企业
				</p>
				<a href="#" class="body2_li_a1">
					查看优秀案例>
				</a>
				</a>
			</li>
			<li class="body2_ul_li2">
				<a class="body2_a" href="#">
					
				
				<p class="body2_li_p">
					90万+
				</p>
				<p class="body2_li_p2">
					IT互联网企业
				</p>
				<a href="#" class="body2_li_a1">
					查看优秀案例>
				</a>
				</a>
			</li>
		</ul>
		<a href="#" class="body2_a3">
			查看更多行业案例>
		</a>
	</div>
	</div>
</template>

<script>
	export default{
		name:"Body2",
		data(){
			return {
				
			}
		},
		mounted(){
			var cir1 = document.getElementById("circle1");
			var cir2 = document.getElementById("circle2");
			var cir3 = document.getElementById("circle3");
			cir1.classList.add("circle_an1");
			cir2.classList.add("circle_an2");
			cir3.classList.add("circle_an3");
		}
	}
</script>

<style>
	.body2_a3{
		width: 144px;
		height: 44px;
		text-align: center;
		line-height: 44px;
		border: 1px solid #58adfb;
		color: #58adfb;
		position: absolute;
		border-radius: 5px;
		left: 50%;
		margin-left: -72px;
		top:680px;
	}
	.body2_ul_li2{
		width: 200px;
		height: 200px;
		float: left;
    	box-sizing: border-box;
   	 	padding: 14px 0 0 27px;
    	list-style: none;
    	border: 2px solid #fcd37c;
    	transition: margin-top 0.5s;
	}
	.body2_li_a1{
		display: inline-block;
		float: left;
		margin-top: 35px;
	}
	.body2_li_p2{
		font-size: 20px;
		margin-top: 10px;
		float: left;
	}
	.body2_a{
		width: 100%;
		height: 100%;
		display: inline-block;
	}
	.body2_li_p{
		width: 169px;
		font-size: 40px;
		font-weight: bold;
		float: right;
		text-align: left;
	}
	.body2_ul_li{
		width: 200px;
		height: 200px;
		float: left;
    	box-sizing: border-box;
   	 	padding: 14px 0 0 27px;
    	list-style: none;
    	margin-right: 50px;
    	border: 2px solid #44e2ba;
    	transition: margin-top 0.5s;
	}
	.body2_ul_li:hover,.body2_ul_li2:hover{
		box-shadow:0 15px 30px rgba(0,0,0,.1);
		margin-top: -10px;
	}
	.body2_ul{
		width: 950px;
    	height: 200px;
    	/*overflow: hidden;*/
    	position: absolute;
    	top: 450px;
    	left: 50%;
    	margin-left: -475px;
	}
	.circle_a{
		position: absolute;
    	width: 100%;
    	height: 100%;
    	background: url(../assets/image/circle.png);
    	background-size:100% 100% ;
    	opacity: 0.5;
    	transition: all 0.5s ;
	}
	@keyframes circleintervalAll{
	0%   {transform:  scale(0.0,0.0);opacity: 1;}
	50%  {transform:  scale(0.6,0.4);opacity: 0.8;}
	75%  {transform:  scale(1.2,1.0);opacity: 0.4;}
	100% {transform: scale(1.8,1.6);opacity: 0.2;}
	}
	.circle_an1{
		animation:circleintervalAll 3.5s linear infinite forwards;
	}
	.circle_an2{
		animation:circleintervalAll 3.5s linear 1.5s infinite forwards;
	}
	.circle_an3{
		animation:circleintervalAll 3.5s linear 2.5s infinite forwards;
	}
	.circle_bg{
		width: 600px;
		height: 400px;
		background: url(../assets/image/circle_bg.png) no-repeat center center;
		position: absolute;
		left: 50%;
		margin-left: -300px;
	}
	.span2{
		text-align: center;
		margin-top: 50px;
		font-size: 16px;
		line-height: 26px;
	}
	.div_zong{
		width: 100%;
		height: 750px;
		position: absolute;
		top: 920px;
		background: #fff;
	}
	.span1{
		width: 100%;
		height: 40px;
		line-height: 40px;
		text-align: center;
		font-size: 40px;
		font-weight: bold;
		display: inline-block;
		margin-top: 80px;
	}
	.body2_1{
		width: 1180px;
		height: 750px;
		position: absolute;
		left: 50%;
		margin-left: -590px;
		overflow: hidden;
    	background: url(../assets/image/8.png);
    	background-size:100% 100% ;
	}
</style>