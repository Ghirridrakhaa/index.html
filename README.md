<!DOCTYPE html>
  <html>
  <head>
    <title>DARI AYANG RAKHA</title>

     <!-- Required meta tags -->
     <meta charset="utf-8">
     <meta name="viewport" content="width=device-width, initial-scale=1">
     <!-- Bootstrap CSS -->
     <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  </head>

<body>
  <center>
    <audio src="gombal/Troye Sivan - Angel Baby.mp3" hidden autoplay loop></audio>
    <font size="6" face="Poppins medium">HAI AYANG SHINTYA </font><br>
    <img src ="https://c.tenor.com/Z8ezUHZzcLoAAAAC/love.gif"/>
    </br>
    </br>
    <font size="5" face="Poppins medium">shinty sayang ga sama aku?</font>
    </br>
    </br>

    <button class="btn btn-success btn-md" id="btn_mau" onclick="alert('I LOVE YOU SAYANG,SABAR YAA AKAN ADA WAKTUNYA AKU MELAMAR MU ')">SAYANG DONG</button>
    
    <button class="btn btn-danger btn-md" id="btn_gamau" onclick="gamau(this)" style="position: absolute;">GAKK</button>
</center>
</body>


<script>
    function gamau(id){
        var mau = document.getElementById("btn_mau");
        var i = Math.floor(Math.random() * 300) + 1;
        var j = Math.floor(Math.random() * 100) + mau.offsetTop;

        id.style.left = i + "px";
        id.style.top  = j + "px";
    }
</script>
</html>
