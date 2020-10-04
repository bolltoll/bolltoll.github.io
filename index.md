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
	     </style>
	
    <!--引入百度 API，"ak=" app-->
    <script type="text/javascript" src="https://api.map.baidu.com/api?v=2.0&ak=7a6QKaIilZftIMmKGAFLG7QT1GLfIncg"></script>
    </head>
       
<body>
    <h1>TRIAL</h1>
    <p>This is a trial page</p>
    
    <div>
    <iframe src="https://www.pku.edu.cn//" name="iframe_a">oo</iframe>
    </div>
    
    <p>Student name</p>
    <p>BiYiLong</p>
    
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
  
  
      </body>
    </html>
