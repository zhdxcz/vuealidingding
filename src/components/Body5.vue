<template>
	<div class="body5_main">
		<div class="body5_div1">
			钉钉正在为企业解决办公协同问题
		</div>
		<div class="body5_div2">
			<div class="body5_div2_head">
				<p class="body5_div2_head_left">企业问题</p>
				<p class="body5_div2_head_right">解决方案</p>
			</div>
			<ul class="body5_ul1">
				<li class="body5_li1">
					<div class="body5_li_div1" @mouseenter="body5show">
						【规则制度不清晰】公司重要规章制度没地方展示，通知不到位
					</div>
					<div class="body5_li_div2">
						<div class="body5_li_div2_head">公告通知信息必达</div>
						<p class="body5_li_div2_p1">
							【融腾集团】公司公告通知、重要规范制度全部使用钉钉公告发送，
							谁看谁没看一目了然，没看再DING一下，保证所有人都收到
							<a href="#" class="body5_li_div2_a1">  查看具体案例></a>
						</p>
						<img src="../assets/image/one1.png" class="body5_li_div2_im1">
					</div>
				</li>
				<li class="body5_li1">
					<div class="body5_li_div1 body5_li_div12" @mouseenter="body5show">
						【规则制度不清晰】公司重要规章制度没地方展示，通知不到位
					</div>
					<div class="body5_li_div2">
						<div class="body5_li_div2_head">2s内找到任一同事手机号</div>
						<p class="body5_li_div2_p1">
							【融腾集团】公司公告通知、重要规范制度全部使用钉钉公告发送，
							谁看谁没看一目了然，没看再DING一下，保证所有人都收到
							<a href="#" class="body5_li_div2_a1">  查看具体案例></a>
						</p>
						<img src="../assets/image/one2.png" class="body5_li_div2_im1">
					</div>
				</li>
				<li class="body5_li1">
					<div class="body5_li_div1 body5_li_div13" @mouseenter="body5show">
						【规则制度不清晰】公司重要规章制度没地方展示，通知不到位
					</div>
					<div class="body5_li_div2">
						<div class="body5_li_div2_head">客户资料统一管理</div>
						<p class="body5_li_div2_p1">
							【融腾集团】公司公告通知、重要规范制度全部使用钉钉公告发送，
							谁看谁没看一目了然，没看再DING一下，保证所有人都收到
							<a href="#" class="body5_li_div2_a1">  查看具体案例></a>
						</p>
						<img src="../assets/image/one3.png" class="body5_li_div2_im1">
					</div>
				</li>
				<li class="body5_li1">
					<div class="body5_li_div1 body5_li_div14" @mouseenter="body5show">
						【规则制度不清晰】公司重要规章制度没地方展示，通知不到位
					</div>
					<div class="body5_li_div2">
						<div class="body5_li_div2_head">办公应用全套免费</div>
						<p class="body5_li_div2_p1">
							【融腾集团】公司公告通知、重要规范制度全部使用钉钉公告发送，
							谁看谁没看一目了然，没看再DING一下，保证所有人都收到
							<a href="#" class="body5_li_div2_a1">  查看具体案例></a>
						</p>
						<img src="../assets/image/one4.png" class="body5_li_div2_im1">
					</div>
				</li>
				<li class="more11">
					<a class="more11_a" href="javascript:;">查看其他问题</a>
				</li>
			</ul>
		</div>
	</div>	
</template>

<script>
	export default{
		name:"Body5",
		data(){
			return {
				
			}
		},
		methods:{
			body5show(e){
				for(var i = 0;i<4;i++){
				document.querySelectorAll(".body5_li_div1")[i].style.background = "#fafafa";
				document.querySelectorAll(".body5_li_div2")[i].style.display = "none";
				document.querySelectorAll(".body5_li_div2")[i].style.zIndex = 3;
				}
				e.target.style.background = "#fff";
				e.target.nextElementSibling.style.display = "block";
				e.target.nextElementSibling.style.zIndex = 10;
			}
		}
	}
</script>

<style>
	.more11_a{
		color: #2180E0;
	}
	.more11{
		width: 380px;
		height: 51px;
		position: absolute;
		top: 440px;
		text-align: center;
		line-height: 51px;
		border: 1px solid #eceef3;
		background:#fafafa ;
	}
	.body5_li_div14{
		top: 330px;
	}
	.body5_li_div13{
		top: 220px;
	}
	.body5_li_div12{
		top: 110px;
    	z-index: 10;
	}
	.body5_li_div2_im1{
		width: 800px;
		height: 340px;
		margin-top: 20px;
	}
	.body5_li_div2_a1{
	
    	color: #58adfb;
    	text-decoration: none;
    	font-size: 16px;
	}
	.body5_li_div2_p1{
		width: 100%;
		text-align: center;
		padding: 0 110px;
    	box-sizing: border-box;
    	font-size: 16px;
	}
	.body5_li_div2_head{
		width: 800px;
		height: 42px;
		text-align: center;
		font-size: 28px;
		margin-top: 30px;
		font-weight: bold;
		
	}
	.body5_li_div2{
		width: 800px;
		height: 490px;
		position: absolute;
		right: 0px;
	}
	.body5_li_div1{
		width: 380px;
		height: 110px;
		position: absolute;
		/*border: 1px solid white;*/
    	/*background: red;*/

    	padding: 30px 40px 0 30px;
    	box-sizing: border-box;
    	background: #fafafa;
    	border: 1px solid #eceef3;
    	font-size: 18px;
    	z-index: 10;
	}
	.body5_li1{
		position: absolute;
		width: 1180px;
		height: 490px;
	}
	.body5_ul1{
		width: 1180px;
		height: 490px;
		position: absolute;
		
	}
	.body5_div2_head_right{
		width: 800px;
		height: 30px;
		float: left;
	}
	.body5_div2_head_left{
		float: left;
    	width: 380px;
    	height: 30px;
    	border-right: solid 1px #69b1e8;
    	box-sizing: border-box;
	}
	.body5_div2_head{
		width: 1180px;
		height: 50px;
    	padding: 10px 0;
    	box-sizing: border-box;
    	background: #439de2;
    	text-align: center;
    	line-height: 30px;
    	font-size: 16px;
    	color: #fff;
	}
	.body5_div2{
		width: 1180px;
		height: 540px;
		margin: auto;
		overflow: hidden;
	}
	.body5_div1{
		width: 100%;
		height: 60px;
		text-align: center;
		font-size: 40px;
    	color: #333;
    	font-weight: bold;
	}
	.body5_main{
		width: 100%;
		height: 750px;
		position: absolute;
		top: 3200px;
		padding: ;
		box-sizing: border-box;
		padding: 100px 0 77px;
		background: #fff;
	}
</style>