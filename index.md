<html>
    <head>
        <meta charset="utf-8">
        <title></title>
	   
	     <style>
	     div.ex
	     {
	     width:220px;
	     padding:10px;
	     border:5px solid gray;
	     margin:0px;
	     }
	     
	      div.rx
	     {
	     width:328px;
	     padding:10px;
	     border:5px solid gray;
	     margin:0px;
	     }
	     
	     body
	     {
	background-image: url(back.jpg);
	}
	h1
	{
	color:#363636;
	text-align:center;
	}
	p
	{
	font-family:"Times New Roman";
	font-size:20px;
	}

	     </style>
	
    <!--引入百度 API，"ak=" app-->
    <script type="text/javascript" src="https://api.map.baidu.com/api?v=2.0&ak=7a6QKaIilZftIMmKGAFLG7QT1GLfIncg"></script>
    </head>
       
<body>
    <h1>TRIAL</h1>
    <center>This is a trial page</center>
	
     <marquee>ヘ(￣ω￣ヘ）ヘ(￣ω￣ヘ)ヘ(￣ω￣ヘ)ヘ(￣ω￣ヘ）</marquee>
     <marquee>                                     </marquee>
     <marquee>弘扬      富强    民主     文明     和谐    </marquee>
      <marquee><marquee><marquee>哇，光头</marquee></marquee></marquee>
     
     <marquee>社会主义    自由    平等     公正     法治   </marquee>
      <marquee>w(ﾟДﾟ)w<marquee>社会主义核心价值观</marquee>啊啊啊吖</marquee>
     
     <marquee>核心价值观    爱国    敬业     诚信     友善 </marquee>
     <marquee>                                    </marquee>
     <marquee>ヘ(￣ω￣ヘ）ヘ(￣ω￣ヘ)ヘ(￣ω￣ヘ)ヘ(￣ω￣ヘ）</marquee>
     <marquee>啊啊<marquee>啊啊啊</marquee>啊啊</marquee>
     
     <kbd>  </Kbd>
     
    
    <div class="rx">
    <iframe src="https://www.pku.edu.cn//" name="iframe_a">oo</iframe>
    </div>
    
   
    <p>Student name
    BiYiLong</p>
    
  <h2>Current Location</h2>
    
    
    <input type="button" onclick="getLocation()" value="确认" />
    <div id="position"></div>
    <script type="text/javascript">
    var x = document.getElementById('position');
    function getLocation() {
        var geolocation = new BMap.Geolocation();
        geolocation.getCurrentPosition(function(e) {
            if(this.getStatus() == BMAP_STATUS_SUCCESS){
                x.innerHTML = 'Lati：' + e.point.lat + '<br/>Grati：' + e.point.lng;
            } else {
                x.innerHTML = 'failed' + this.getStatus();
            }
        });
    }
    </script>
    
    <font color="#4E2F2F">LOCATIONAL SCALES</font>
    
   <h2>Pictures</h2>
   
     <span>
    <img src="smc0406_portrait_productview.jpg">
    <img src="smc0200_portrait_productview.jpg">
    <img src="smc0201_portrait_productview.jpg">
     </span>
    
    <marquee>
    今朝好风日。
    园苑足芳菲。
    竹动蝉争散。
    莲摇鱼暂飞。
    面红新着酒。
    风晚细吹衣。
    跂石多时望。
    莲船始复归。</marquee>
  
    <b>啊啊啊啊啊啊啊啊啊啊啊</b>
    
  
  
  </body>
  </html>
