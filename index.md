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
    <p>This is a trial page2</p>
    
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
    
   <h2>Pictures</h2>
   
    <div class="ex"><img src="smc0406_portrait_productview.jpg"></div>
    <div class="ex"><img src="smc0202_portrait_productview.jpg"></div>
    <div class="ex"><img src="smc0200_portrait_productview.jpg"></div>
    
    <p>
    今朝好风日。
    园苑足芳菲。
    竹动蝉争散。
    莲摇鱼暂飞。
    面红新着酒。
    风晚细吹衣。
    跂石多时望。
    莲船始复归。</p>
  
  
  
      </body>
    </html>
