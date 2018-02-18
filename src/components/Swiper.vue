<template>
	<div class="swiper" id="swiper1">
		<div class="scroll_1 scrol">
		<div class="scroll_1_div2">
     			<div class="scroll_2_div1">
				<p class="scroll_p2">酷公司，用钉钉</p>
				<p class="scroll_p3">
					世界上的公司分两种，第一种是“酷公司”，而除此以外的我们只能称之为“其它公司”
				</p>
				<p class="dow1"><a href="#" class="down">下载盯盯</a><a href="#" class="down1">观看完整视频</a></p>
			</div>
     		</div>
			<video class="video1" preload="auto" autoPlay muted 
				poster="" width="100%"  height="500">
			<source src="../assets/image/video.mp4" type="video/mp4"/>
			<span>
			Your browser does not support the video tag
			</span>
     		</video>
		</div>
		<div class="scroll_2 scrol">
			<div class="scroll_2_divv1">
				<div class="scroll_2_divv2">
					<p class="scroll2_p2">酷公司“0元购机计划”第2季</p>
				<p class="scroll2_p3">
					助力中国企业，跨入智能移动办公时代！
				</p>
				<a href="#" class="down">立即参与</a>
				</div>
			</div>
		</div>
		<div class="scroll_3 scrol">
			<div class="scroll_2_divv1">
				<div class="scroll_2_divv2">
					<p class="scroll2_p2 col1">钉钉云 · 安全 稳定 赋能</p>
				<p class="scroll2_p3 col1">
					为钉钉开发者量身打造的一站式云服务解决方案
				</p>
				<a href="#" class="down">查看详情</a>
				</div>
			</div>
		</div>
		<div class="scroll_4 scrol">
			<div class="scroll_2_divv1">
				<div class="scroll_2_divv2">
					<p class="scroll2_p2 col1">钉钉云 · 安全 稳定 赋能</p>
				<p class="scroll2_p3 col1">
					为钉钉开发者量身打造的一站式云服务解决方案
				</p>
				<a href="#" class="down">查看详情</a>
				</div>
			</div>
		</div>
		<div class="scroll_5 scrol">
			<div class="scroll_2_divv1">
				<div class="scroll_2_divv2">
					<p class="scroll2_p2 col1">钉钉云 · 安全 稳定 赋能</p>
				<p class="scroll2_p3 col1">
					为钉钉开发者量身打造的一站式云服务解决方案
				</p>
				<a href="#" class="down">查看详情</a>
				</div>
			</div>
		</div>
		<div class="scroll_6 scrol">
			<div class="scroll_2_divv1">
				<div class="scroll_2_divv2">
					<p class="scroll2_p2 col1">钉钉云 · 安全 稳定 赋能</p>
				<p class="scroll2_p3 col1">
					为钉钉开发者量身打造的一站式云服务解决方案
				</p>
				<a href="#" class="down">查看详情</a>
				</div>
			</div>
		</div>
		<div class="scroll_7 scrol">
			<div class="scroll_2_divv1">
				<div class="scroll_2_divv2">
					<p class="scroll2_p2 col1">钉钉云 · 安全 稳定 赋能</p>
				<p class="scroll2_p3 col1">
					为钉钉开发者量身打造的一站式云服务解决方案
				</p>
				<a href="#" class="down">查看详情</a>
				</div>
			</div>
		</div>
		<ul class="dotList">
			<li class="dot">
				
			</li>
			<li class="dot dot1">
				
			</li>
			<li class="dot dot2">
				
			</li>
			<li class="dot dot3">
				
			</li>
			<li class="dot dot4">
				
			</li>
			<li class="dot dot5">
				
			</li>
			<li class="dot dot6">
				
			</li>
		</ul>
		<div class="tab_left">
			<
		</div>
		<div class="tab_right">
			>
		</div>
	</div>
</template>

<script>
export default {
  name: 'Swiper',
  data () {
    return {
      
    }
  },
  methods:{
  	
  },
  mounted(){
  	var  winww;
    window.onresize=r;
    function r(){
    winww=window.innerWidth;
    //document.getElementsByTagName("html")[0].style.fontSize=winww*0.05207+"px";
//  alert(winw*0.15625+"px");
	};
	r();
  	$(document).ready(function(){
    // var winw = winww-21;
    var winw = winww;
    // alert(winw);
    var wei = 0;
    swi(wei);
    var i;
    var p;
    // alert(wei);
    $(".scrol").css("left",-winw).eq(wei).css("left","0px");
    function up(){
       wei++;
       if(wei>6){
        wei = 0;
       }
       lunbo();   
    }
    function down(){
        
        wei--;
        if(wei==-1){
            wei = 6;
        }
        lunbo1();
        
    }
    function lunbo(){
        clearTimeout(p);
    	window.clearInterval(i);
//      console.log(i);
    	$(".scrol").eq(wei-1).stop(true,true);
    	$(".scrol").eq(wei).stop(true,true);
        $(".scrol").eq(wei-1).animate({"left":-winw},500);
        $(".scrol").eq(wei).css("left",winw);
        $(".scrol").eq(wei).animate({"left":"0px"},500
               ,function(){
//             window.setTimeout(tim,2000);
           }
        );
        $(".scrol").eq(wei+1).animate({"left":winw},1);
        swi(wei);
        p=setTimeout(tim,1500);
    }
    function lunbo1(){
    	clearTimeout(p);
    	window.clearInterval(i);
        if(wei==6){
        $(".scrol").eq(wei).animate({"left":-winw},1);
        $(".scrol").eq(wei).animate({"left":"0px"},500);
        $(".scrol").eq(0).animate({"left":winw},500);
        }
        else{
        $(".scrol").eq(wei).animate({"left":-winw},1);
        $(".scrol").eq(wei).animate({"left":"0px"},500);
        $(".scrol").eq(wei+1).animate({"left":winw},500);   
        }
        swi(wei);
        p=setTimeout(tim,1500);
    }
    function tim(){
      i = window.setInterval(up,2000);
//    console.log(i);
    }
    tim();
    
    function swi(wei1){
        $(".dot").eq(wei1).css("background","#f00").siblings().css("background","#fe0");
    }
    $(".dot").click(function(){
    	clearTimeout(p);
        clearInterval(i);
        var inde=$(this).index(".dot");
        if(inde>wei){
            $(".scrol").eq(wei).animate({"left":-winw},500);
            wei=inde;
            $(".scrol").eq(wei).css("left",winw);
            $(".scrol").eq(wei).animate({"left":"0px"},500);

        }
        if(inde==wei){
        }
        else{
            $(".scrol").eq(wei).animate({"left":winw},500);
            wei=inde;
            $(".scrol").eq(wei).css("left",-winw);
            $(".scrol").eq(wei).animate({"left":"0px"},500);
        }
        swi(inde);
        p=setTimeout(tim,1500);
    })
    $(".tab_left").click(down);
    $(".tab_right").click(up);
})
  }
  
}
</script>

<style>
	.scroll_6{
		width: 100%;
		height: 500px;
		background: url(../assets/image/6.png);
		background-size:100% 100% ;
		position: absolute;
	}
	.scroll_7{
		width: 100%;
		height: 500px;
		background: url(../assets/image/7.jpg);
		background-size:100% 100% ;
		position: absolute;
	}
	.scroll_5{
		width: 100%;
		height: 500px;
		background: url(../assets/image/5.jpg);
		background-size:100% 100% ;
		position: absolute;
	}
	.scroll_4{
		width: 100%;
		height: 500px;
		background: url(../assets/image/4.jpg);
		background-size:100% 100% ;
		position: absolute;
	}
	.scrol{
		
	}
	.swiper{
		width: 100%;
		height: 500px;
		position: relative;
		top: 81px;
		/*background: #42B983;*/
		overflow-x: hidden;
	}
	.scroll_1{
		width: 100%;
		height: 500px;
		position: absolute;
		/*display: none;*/
		z-index: 10;
	}
	.video1{
		height: 500px;
		width: 100%;
		object-fit:fill ;
		position: absolute;
	}
	.scroll_2{
		width: 100%;
		height: 500px;
		background: url(../assets/image/1.jpg);
		background-size:100% 100% ;
		position: absolute;
		z-index: 9;
		/*display: none;*/
	}
	.scroll_1_div2{
		width: 660px;
		height: 294px;
		margin: auto;
		position: absolute;
		top: 125px;
		left: 50%;
		margin-left: -330px;
		z-index: 4;
	}
	.scroll_p2{
		width: 100%;
		height: 60px;
		text-align: center;
		font-size: 40px;
		font-weight: bold;
		color: #fff;
	}
	.scroll_p3{
		width: 100%;
		height: 60px;
		text-align: center;
		font-size: 20px;
		color: #fff;
	}
	.dow1{
		width: 100%;
		height: 55px;
		line-height: 55px;
		text-align: center;
	}
	.down{
		width: 150px;
		height: 55px;
		line-height: 55px;
		text-align: center;
		display: inline-block;
		background: #3296fa;
		border-radius: 5px;
		box-sizing: border-box;
		color: #fff;
		margin: 0px 20px;
		font-size: 20px;
	}
	.down1{
		width: 150px;
		height: 55px;
		line-height: 55px;
		text-align: center;
		display: inline-block;
		background: transparent;
		border-radius: 5px;
		box-sizing: border-box;
		border: 1px solid #fff;
		color: #333;
		font-size: 20px;
		margin: 0px 20px;
	}
	.scroll_2_divv1{
		width: 1100px;
		height: 300px;
		margin: auto;
	}
	.scroll_2_divv2{
		width: 600px;
		padding: 30px;
		height: 264px;
		box-sizing: border-box;
		position: absolute;
		top: 170px;
	}
	.scroll2_p2{
		width: 100%;
		height: 60px;
		text-align: left;
		font-size: 40px;
		font-weight: bold;
		color: #000;
	}
	.scroll2_p3{
		width: 100%;
		height: 60px;
		text-align: left;
		font-size: 20px;
		color: #333;
		float: left;
		margin: 50px 0xp;
	}
	.scroll_3{
		width: 100%;
		height: 500px;
		background: url(../assets/image/3.png);
		background-size:100% 100% ;
		position: absolute;
		z-index: 8;
	}
	.col1{
		color: #fff;
	}
	.dotList{
		width: 154px;
		height: 12px;
		text-align: center;
		position: absolute;
		z-index: 101;
		left: 50%;
		margin-left: -77px;
		top: 484px;
		
	}
	.dot{
		width: 12px;
		height: 12px;
		position: absolute;
    	padding: 0;
    	/*bottom: 15px;
    	left: 45%;*/
    	stroke:rgba(255,0,0,1);
    	cursor: pointer;
    	border-radius: 50%;
    	background: #2180E0;
	}
	.dot1{
		left: 15px;
	}
	.dot2{
		left: 30px;
	}
	.dot3{
		left: 45px;
	}
	.dot4{
		left: 60px;
	}
	.dot5{
		left: 75px;
	}
	.dot6{
		left: 90px;
	}
	.tab_left{
		width: 40px;
		height: 140px;
		font-size: 35px;
		color: #fff;
		font-weight: bold;
		position: absolute;
		top: 170px;
		cursor: pointer;
		line-height: 140px;
		z-index: 101;
	}
	.tab_right{
		width: 40px;
		height: 140px;
		font-size: 35px;
		color: #fff;
		font-weight: bold;
		position: absolute;
		top: 170px;
		right: 0px;
		cursor: pointer;
		z-index: 101;
		line-height: 140px;
	}
	/*@keyframes toLeft{
		0%{
			left:0%;
			opacity: 1;
		}
		25%{
			opacity: 0.75;
			left:-25%;
		}
		50%{
			opacity: 0.5;
			left:-50%;
		}
		75%{
			opacity: 0.25;
			left:-75%;
		}
		100%{
			opacity: 0;
			left:-100%;
		}
	}
	@keyframes toLeft2{
		0%{
			opacity: 0;
			left:100%;
		}
		25%{
			opacity: 0.25;
			left:75%;
		}
		50%{
			opacity: 0.5;
			left:50%;
		}
		75%{
			opacity: 0.75;
			left:25%;
		}
		100%{
			opacity: 1;
			left:0%;
		}
	}
	.toLeft1{
		animation: toLeft 600ms linear forwards;
	}
	.toLeft2{
		animation: toLeft2 600ms linear;
	}*/
</style>