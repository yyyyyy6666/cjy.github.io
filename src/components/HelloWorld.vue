<template>
  <div class="hello">
    <header>
    	<div>前端知识汇总大全------2020向前冲鸭！！！！</div>
    
    </header>
    <!--banner部分-->
    <section class="banner">
    	<h1>真正的努力，从来都不动声色</h1>
    	<div>
    		<p>Study up, Day Day Up.</p>
    	</div>
    	<!-- <nav>
    	<ul class="clearfix">
    		<li><a href="#">Sign Up</a></li>
    		<li><a href="#">Learn More</a></li>
    	</ul>
    </nav> -->
    </section>
    <!--第一部分icon-->
    <section class="icon">
    	<div class="inner">
    		<ul class="clearfix">
    			<li class="">
    				<span class="fa fa-calendar-minus-o" id="vueTz"></span>
    				<h2>VUE</h2>
    			</li>
    			<li>
    				<span class="fa fa-calendar-minus-o" id="JavaScriptTz"></span>
    				<h2>JavaScript</h2>
    			</li>
    			<li>
    				<span class="fa fa-calendar-minus-o" id="JavaScriptTz"></span>
    				<h2>小程序</h2>
    			</li>
    			<li>
    				<span class="fa fa-calendar-minus-o" id="AppletTz"></span>
    				<h2>uniapp</h2>
    			</li>
    		</ul>
    	</div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	 @import 'https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css';
body{font-size:10px;font-family: arial;}
header{background: #eeeef3;position:relative;position:fixed;width:100%;
	box-shadow:0 1px 2px #C5C6C8;opacity:0.9;height:50px;text-align: center;line-height: 50px;font-size:20px}
header img{display:block;margin:0 auto;padding:26px 0;}
header nav{position:absolute;right:0;top:0;}
header nav a{
	font-size: 1.5em;
	display:block;
	height:4.6666em;/*70/15*/
	line-height:4.6666em;
	padding:0 2.0666em;/*31/15*/
	margin-left:0.8em;/*12/15*/
	color:#43464c;
}
.clearfix{
	display: flex;
}
header nav li:first-child a{border-top: 2px solid #f5756c;transition:background 0.3s,color 0.3s;}
header nav li:first-child a:hover{background: #f5756c;color:#fff;}
header nav li:last-child a{border-top: 2px solid #6585ed;transition:background 0.3s,color 0.3s;}
header nav li:last-child a:hover{background: #6585ed;color:#fff;}
.banner{
	background: url(../../static/images/banner.jpg) no-repeat;
	background-size: cover;
	background-origin: border-box;
	-webkit-background-origin: border-box;
	background-clip: border-box;
	-webkit-background-clip: border-box;
	-moz-background-clip: border-box;
	background-position: center center;
	padding:7.2em 0;/*72/10*/
	
}
.banner h1{
	font-family:myFont;
	font-size: 3em;
	font-weight: normal;
	color:#fff;
	text-align:center;
	padding-top:2.58181em;/*142/55*/
}
.banner div{
	width:100%;
	padding:1em 0 12.5em 0;/*68/10*//*125/10*/
}
.banner p{
	width:37.8169%;
	color:#b1b2be;
	font-size: 1.5em;
	text-align:center;
	line-height:2.2666em;/*34/15*/
	margin:0 auto;
	
}
.banner nav ul{
	padding:6.7em 0 6.7em 33.4507%;/*67/10*//*475/1420*/
	border-top:1px solid #403f53;
	border-bottom:1px solid #161521;
	}
.banner nav li a{
	display:block;
	color:#fff;

}
.banner nav li:first-child a{
	/*box-shadow: 0 1px 0 #fbbab5 inset,0 2px 2px #1f1d2c;*/
	display:block;
	font-size:2.8em;
	height:3.0357em;
	line-height: 3.0357em;/*85/28*/
	padding:0 2.1071em;/*59/28*/
	background: #f66f65;
	text-shadow:0 -1px 0px #b8524b;
	border-radius:5px;
	transition:box-shadow 1s;
}
.banner nav li:first-child a:hover{
	box-shadow:2px 2px 20px 5px #f66f65;
}
.banner nav li:last-child a{
	height:4.4736em;
	line-height:4.4736em;/*85/19*/
	font-size:1.9em;
	padding:0 2em;/*38/19*/
	text-shadow:-1px -1px 0 #292940;
}
.icon .inner,.icon3 .inner,{
	width:84.5070%;/*1200/1240*/
}
.icon,.icon3{background: #edf1f8;}
.icon .inner li,.icon3 .inner li{
	width:24.9999%;/*25%*/
	padding:8em 0;/*80/10*/

}
.icon .inner li span,.icon3 .inner li span{
	font-size:54px;
	display:block;
	width:2.2222em;/*120/54*/
	height: 2.2222em;
	line-height: 2.2222em;
	text-align:center;
	background:#fff;
	margin:0 auto;
	border-radius:0.6111em;/*33/54*/
	border:1px solid #e2e6eb;
	color:#6585ed;
}
.icon .inner li h2,.icon3 .inner li h2{
	padding: 1.5789em 0 0.5263em 0;/*30/19*//*10/19*/
}
.icon .inner li p,.icon3 p{
	width:70%;/*291/289*/
}
.icon2 i{
	display:block;
	width:1.02em;
	height:1.02em;/*102/100*/
	margin:0 auto;
	font-size: 10em;/*100/10*/
	opacity:0.5;
}
.icon2 p{color:#fff;
	padding:0 0 9.2307em 0;/*120/13*/}
.icon2 li{
	width:33.3333%;
	padding:12em 0 0 0;/*120/10*/}
.icon2 li:nth-child(1){
	background-image:-moz-linear-gradient(top,#5ed8ad,#2ad4e8);
	background-image:-webkit-linear-gradient(top,#5ed8ad,#2ad4e8);
	background-image:-ms-linear-gradient(top,#5ed8ad,#2ad4e8);
	background-image:-o-linear-gradient(top,#5ed8ad,#2ad4e8);
}
.icon2 li:nth-child(2){
	background-image:-moz-linear-gradient(top,#f5746c,#fc547f);
	background-image:-webkit-linear-gradient(top,#f5746c,#fc547f);
	background-image:-ms-linear-gradient(top,#f5746c,#fc547f);
	background-image:-o-linear-gradient(top,#f5746c,#fc547f);
}
.icon2 li:nth-child(3){
	background-image:-moz-linear-gradient(top,#6485ed,#349bfe);
	background-image:-webkit-linear-gradient(top,#6485ed,#349bfe);
	background-image:-ms-linear-gradient(top,#6485ed,#349bfe);
	background-image:-o-linear-gradient(top,#6485ed,#349bfe);
}
.icon2 h2{
	padding:31px 0 22px 0;
}
.icon2 p{
	width:67.5105%;/*320/474*/
}

@media screen and (){

}
@media screen and (max-width: 800px){
	body{font-size: 8px;}
	.payMe section, .blue section{float:none;}
	.payMe section:first-child, .blue section:first-child{width:100%;}
	.payMe section:last-child, .blue section:last-child{display: none;}
	.banner p{width:100%;}
}
@media screen and (max-width: 900px){
	.icon2 li{
		float:none;
		width:100%;
	}
	.icon .inner li, .icon3 .inner li{
		width:50%;
		padding:4em 0;
	}
}
</style>
