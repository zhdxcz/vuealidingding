<template>
	<div class="body3_main">
		<div class="body3_div">
			钉钉正在为各行各业提供专业解决方案
		</div>
		<div class="body3_div2">
			<div class="body3_div3">
				
			
			<ul class="ul1">
				<li class="ul1_li">
					<a href="#" class="ul1_li_a">
						<img class="li_img" src="../assets/image/9.jpg">
						<div class="ul_div1">
							<p class="ul_p">
								<span class="ul_p_span">制造业</span>
								<span class="ul_p_span">杭州朝阳香蕉有限公司</span>
								<a href="#" class="ul_li_a2">传统生产企业的信息化升级</a>
								<p class="ul_li_p">
									信息化和工业化的“两化融合”中，钉钉起到了不可替代的作用。
								</p>
								<p class="ul_li_p1">
									1000人以上 审批流程电子化、沟通信息安全
								</p>
							</p>
						</div>
					</a>
				</li>
				<li class="ul1_li">
					<a href="#" class="ul1_li_a">
						<img class="li_img" src="../assets/image/9.jpg">
						<div class="ul_div1">
							<p class="ul_p">
								<span class="ul_p_span">制造业</span>
								<span class="ul_p_span">杭州朝阳香蕉有限公司</span>
								<a href="#" class="ul_li_a2">传统生产企业的信息化升级</a>
								<p class="ul_li_p">
									信息化和工业化的“两化融合”中，钉钉起到了不可替代的作用。
								</p>
								<p class="ul_li_p1">
									1000人以上 审批流程电子化、沟通信息安全
								</p>
							</p>
						</div>
					</a>
				</li>
				<li class="ul1_li">
					<a href="#" class="ul1_li_a">
						<img class="li_img" src="../assets/image/9.jpg">
						<div class="ul_div1">
							<p class="ul_p">
								<span class="ul_p_span">制造业</span>
								<span class="ul_p_span">杭州朝阳香蕉有限公司</span>
								<a href="#" class="ul_li_a2">传统生产企业的信息化升级</a>
								<p class="ul_li_p">
									信息化和工业化的“两化融合”中，钉钉起到了不可替代的作用。
								</p>
								<p class="ul_li_p1">
									1000人以上 审批流程电子化、沟通信息安全
								</p>
							</p>
						</div>
					</a>
				</li>
				<li class="ul1_li">
					<a href="#" class="ul1_li_a">
						<img class="li_img" src="../assets/image/9.jpg">
						<div class="ul_div1">
							<p class="ul_p">
								<span class="ul_p_span">制造业</span>
								<span class="ul_p_span">杭州朝阳香蕉有限公司</span>
								<a href="#" class="ul_li_a2">传统生产企业的信息化升级</a>
								<p class="ul_li_p">
									信息化和工业化的“两化融合”中，钉钉起到了不可替代的作用。
								</p>
								<p class="ul_li_p1">
									1000人以上 审批流程电子化、沟通信息安全
								</p>
							</p>
						</div>
					</a>
				</li>
				<li class="ul1_li">
					<a href="#" class="ul1_li_a">
						<img class="li_img" src="../assets/image/9.jpg">
						<div class="ul_div1">
							<p class="ul_p">
								<span class="ul_p_span">制造业</span>
								<span class="ul_p_span">杭州朝阳香蕉有限公司</span>
								<a href="#" class="ul_li_a2">传统生产企业的信息化升级</a>
								<p class="ul_li_p">
									信息化和工业化的“两化融合”中，钉钉起到了不可替代的作用。
								</p>
								<p class="ul_li_p1">
									1000人以上 审批流程电子化、沟通信息安全
								</p>
							</p>
						</div>
					</a>
				</li>
				<li class="ul1_li">
					<a href="#" class="ul1_li_a">
						<img class="li_img" src="../assets/image/9.jpg">
						<div class="ul_div1">
							<p class="ul_p">
								<span class="ul_p_span">制造业</span>
								<span class="ul_p_span">杭州朝阳香蕉有限公司</span>
								<a href="#" class="ul_li_a2">传统生产企业的信息化升级</a>
								<p class="ul_li_p">
									信息化和工业化的“两化融合”中，钉钉起到了不可替代的作用。
								</p>
								<p class="ul_li_p1">
									1000人以上 审批流程电子化、沟通信息安全
								</p>
							</p>
						</div>
					</a>
				</li>
			</ul>
			</div>
			<div class="body3_tab_left" @click="goLeft">
				<
			</div>
			<div class="body3_tab_right">
				>
			</div>
			<div class="body_logoList">
				<ul class="body_list_ul">
					<li class="body_list_ul_li">
						
					</li>
					<li class="body_list_ul_li">
						
					</li>
					<li class="body_list_ul_li">
						
					</li>
					<li class="body_list_ul_li">
						
					</li>
					<li class="body_list_ul_li">
						
					</li>
					<li class="body_list_ul_li">
						
					</li>
				</ul>
			</div>
			<a href="#" class="body3_a3">
			查看更多行业案例>
			</a>
		</div>
		
	</div>
</template>

<script>
	export default{
		name:"Body3",
		data(){
			return {
				
			}
		},
		mounted(){
			var i ;
			var y ;
			var marlef = 0;
			function marleffun(){
			marlef -=1180;
			if(marlef<-2000){
				marlef = 0;
				$(".ul1").animate({"margin-left":"0px"},100);
			}
			$(".ul1").animate({"margin-left":marlef+"px"},2500);
			clearInterval(i);
			y = setTimeout(seinter,1500);
			}
			function seinter(){
				i = setInterval(marleffun,3000);	
			}
			seinter();
			
			
		}
	}
</script>

<style>
	.body3_a3{
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
		top:540px;
	}
	.body_list_ul_li{
		float: left;
		width: 180px;
		height: 70px;
		background: url(../assets/image/liantong.png);
		background-size:100% 100% ;
		margin-right: 10px;
	}
	.body_list_ul{
		float: left;
	}
	.body_logoList{
		width: 1180px;
		height: 70px;
		position: absolute;
		top: 440px;
	}
	.body3_tab_right{
		width: 40px;
		height: 60px;
		position: absolute;
		top: 160px;
		font-size: 40px;
		cursor: pointer;
		right:-60px;
	}
	.body3_tab_left{
		width: 40px;
		height: 60px;
		position: absolute;
		top: 160px;
		font-size: 40px;
		cursor: pointer;
		left:-30px;
	}
	.ul_li_p1{
		width: 100%;
		margin: 15px 0px 0px 10px;
		color: #999;
	}
	.ul_li_p{
		width: 100%;
		height: 51px;
		margin: 15px 0px 0px 10px;
		color: #999;
		border-bottom: solid 1px #ebeef3;
	}
	.ul_li_a2{
		display: block;
		margin: 15px 0px 0px 10px;
		font-size: 20px;
	}
	.ul_p_span{
		padding: 0px 10px;
		border-right: solid 1px #ebeef3;
	}
	.ul_p{
		font-size: 14px;
	}
	.ul_div1{
		width: 380px;
		height: 174px;
		box-sizing: border-box;
    	padding: 17px 20px;
	}
	.li_img{
		width: 380px;
		height: 200px;
	}
	.ul1_li_a{
		width: 100%;
		height: 100%;
		float: left;
	}
	.ul1_li{
		width: 388px;
		height: 376px;
		float: left;
		box-sizing: border-box;
    	border: solid 1px #eff1f5;
    	transition: margin-top 0.5s;
	}
	.ul1_li:hover{
		box-shadow:0 15px 30px rgba(0,0,0,.1);
		margin-top: -10px;
	}
	.ul1{
		width: 2400px;
		height: 376px;
		float: left;
	}
	.body3_div3{
		width: 100%;
		height: 100%;
		overflow: hidden;
	}
	.body3_div2{
		width: 1180px;
		height: 615px;
		margin-top: 50px;
		position: absolute;
		left: 50%;
		margin-left: -590px;
}
.body3_div{
	width: 1180px;
	height: 40px;
	margin: auto;
	text-align: center;
	font-size: 40px;
	font-weight: bold;
	margin-top: 50px;
}
.body3_main{
	width: 100%;
	height: 750px;
	position: absolute;
	top: 1680px;
	background: #fff;
}
</style>