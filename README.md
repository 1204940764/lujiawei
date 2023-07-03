<!DOCTYPE html>
<html lang="en">
  <head>
      <meta charset="UTF-8">
      <title>i熊er网</title>
      <style>
          body{
              background:black;background: url(../images/bg1.jpg);background-size:cover;background-attachment:fixed;background-repeat:repeat-x;
              
          }
          p{color:black;text-shadow: 0px 0px 4px red}
          table{color:black;text-shadow: 0px 0px 4px red}
          h1{color:black;text-shadow: 0px 0px 4px red}
          h2{color:black;text-shadow: 0px 0px 4px red}
          h3{color:black;text-shadow: 0px 0px 4px red}
          h4{color:black;text-shadow: 0px 0px 4px red}
          h5{color:black;text-shadow: 0px 0px 4px red}
          h6{color:black;text-shadow: 0px 0px 4px red}
          li{color:black;}
          a{color:black;text-shadow: 5px 5px 4px red}
          .botton
          {
              width:300px;height: 150px;font-size: 30px;background-color:deepskyblue;border:10px solid gold;text-shadow: 0px 0px 4px red;
          }
          .main {
 display: flex;
 justify-content: center;
}
.btn {
 width: 200px;
 height: 100px;
 font-size: 30px;
 text-shadow: 0px 0px 4px red;
 background:deepskyblue;
 border-radius: 30px;
 color: #000;
 outline: none;
 cursor: pointer;
 transition: all 0.4s;
}
.btn:hover {
 box-shadow: inset 0 0 0 4px #ef476f, 
              inset 0 0 0 8px #ffd166, 
              inset 0 0 0 12px #06d6a0,
              inset 0 0 0 16px #118ab2;
 background: #073b4c;
 color: #fff;
}
.thetop
{
    color:#680000;
    letter-spacing: 20px;
    font-size:40px;
    position:sticky;
    top:0;
    text-shadow: 0px 0px 10px #3333FF;
}
.thetop:hover
{
    font-size:50px;
    text-shadow: 0px 0px 10px gold;
}
      </style>
      <script>
    function myFunction() {
        alert("i熊er的成员多了你一个\ni熊er一定会非常开心的!");
    }
    </script>
    <script>
	function clickCounter() {
		if(typeof(Storage)!=="undefined") {
			if (sessionStorage.clickcount) {
				sessionStorage.clickcount=Number(sessionStorage.clickcount)+1;
			}
			else {
				sessionStorage.clickcount=1;
			}
			document.getElementById("result").innerHTML=" 你已经i熊er " + sessionStorage.clickcount + " 下了 ";
		} else {
			document.getElementById("result").innerHTML="对不起，您的浏览器不支持 web 存储。";
		}
	}
</script>
  </head>
  <body>
        <center>
            <p class="thetop">你i熊er吗?&nbsp&nbsp&nbsp&nbsp你i熊er吗?&nbsp&nbsp&nbsp&nbsp你i熊er吗?</p>
          <p><button onclick="clickCounter()" type="button" class="btn">点我i个熊er1</button></p>
	<div id="result"></div>
	<p style="font-size: 30px;letter-spacing: 20px;color: :#680000;">点击该按钮查看i熊er的次数</p>
      <button type="button" style="border-radius:10px;width: 100%;height: 200px;border:10px double gold;background-color:rgba(0,255,255,0.5);"><a href="../images/bg.jpg"style="text-decoration:none"><big><p style="color::#680000;letter-spacing: 150px;font-size: 50px;"><b>i熊er</b>之家!</p></big></a></button>
  <form action="https://5b0988e595225.cdn.sohucs.com/images/20171208/2686429581ca4916bb4754307a9e68e5.jpeg">
  <fieldset style="height: 525px;color::#680000;border: 10px double gold;">
      <legend style="font-size: 30px;letter-spacing: 20px;text-shadow: 5px 5px 4px red"><b>i熊er之家的选择</b></legend>
      <p style="color: :#680000;font-size :40px;letter-spacing: 20px;">你i熊er吗?</p><br>
      <p style="color: :#680000;font-size :40px;">A.<input type="radio" name="sex" size="20">爱&nbsp&nbsp
      B.<input type="radio" name="sex" size="20">很爱&nbsp&nbsp
      C.<input type="radio" name="sex" size="20">超级爱&nbsp&nbsp
      D.<input type="radio" name="sex" size="20" checked="chected">宇宙第一爱</p><br><br>
      <input type="button" onclick="myFunction()" value="点击提交i个熊er" class="botton" >
      </fieldset>
  </form>
  <br>
  <video width="60%" style="border: 10px solid gold;" controls loop autoplay>
		<source src="//static.nowcoder.com/tutorial/web-examples/video/movie.mp4" type="video/mp4">
		你的浏览器太老啦!!!该更新了。
	</video>
  <hr color="red">
  <table border="10" style="border-color: gold;width: 100%;height: 300px;margin-top: 0;font-size: 40px;color: :#680000;border-spacing:10px">
    <tr>
        <td><center>超级i熊er</center></td>
        <td><center>超级i同er</center></td>
    </tr>
    <tr>
        <td><center>超级i贤er</center></td>
        <td><center>超级i俊er</center></td>
    </tr>
</table>
      <p id="demo"style="font-size:50px;letter-spacing:30px;color: :#680000;">点击按钮获取您当前坐标:</p>
	<button onclick="getLocation()"style="width: 200px;height: 100px;font-size:30px;background:none;color::#680000;border:3px solid gold">有种点我</button>
	<script>
		var x = document.getElementById("demo")
		function getLocation() {
			if (navigator.geolocation) {
				navigator.geolocation.getCurrentPosition(showPosition);
			} else {
				x.innerHTML = "该浏览器不支持获取地理位置。";
			}
		}

		function showPosition(position) {
			x.innerHTML = "纬度: " + position.coords.latitude +
				"<br>经度: " + position.coords.longitude;
		}
	</script>
      <hr color="orange">
      <a href="https://419d2e19-preview.lightly.teamcode.com/HTMLProject/js/ikun的诗.html?server=preview&dcsId=419d2e19&token=KiN9MfSYRt2N8-oBvLoAoQ"target="_blank"><p style="font-size:50px;color::#680000;letter-spacing: 30px;">点击阅读真i粉诗句</p></a>
      <hr color="yellow">
      <a href="https://corestudi0.github.io/newyear/#1673101386906"><big><p style="font-size:50px;letter-spacing:150px;color: :#680000;">新年快乐！</p></big></a>
      <hr color="green">
      <li><p style="font-size:50px;letter-spacing:50px;color: black;">hello 2023!</p></li>
      <hr color="blue">
      <h4 style="font-size:50px;letter-spacing:50px;color::#680000;">good bye 2022</h4>
      <hr color="indigo">
      
      <a href="https://xqimg.imedao.com/1766a082f0f40973fc577bf4.gif%21raw.gif"><p style="font-size: 70px;color: :#680000;">点击直接燃起来</p></a> 
      <hr color="purple">
      <a href="https://www.bilibili.com/bangumi/play/ep312861?theme=movie&spm_id_from=333.337.0.0"target="_blank"><img src="https://cdn.bapiw.com/wp-content/uploads/jp/2013-01-01/8864.jpg"style="border:10px double gold"/></a>
      <br>
      </br>
      <!--超链接-->
      <a href="https://www.bilibili.com/video/BV1j4411W7F7/?spm_id_from=333.337.search-card.all.click&vd_source=0c9d6153d2eeb450e6736bdb5971d896"target="_blank">点击收看猛男</a>
      </br>
      </center>
  </body>
</html>
