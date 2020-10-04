<html>
    <head>
        <meta charset="utf-8">
    </head>
       
<body>
    <h1>TRIAL</h1>
    <p>This is a trial page</p>
    
    <div>
    <iframe src="https://www.pku.edu.cn//" name="iframe_a">oo</iframe>
    <iframe src="https://www.spitfireaudio.com/" name="iframe_a">oo</iframe>
    </div>
    
    <p>Student name</p>
    <p>BiYiLong</p>
    
    var x=document.getElementById("demo");function getLocation(){
    if (navigator.geolocation)
    {
        navigator.geolocation.getCurrentPosition(showPosition);
    }
    else
    {
        x.innerHTML="该浏览器不支持获取地理位置。";
    }}function showPosition(position){
    x.innerHTML="纬度: " + position.coords.latitude + 
    "<br>经度: " + position.coords.longitude;    }
    
   </body>
</html>
