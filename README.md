<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <link rel="stylesheet"href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome.min.css">
  <script src="https://code.iconify.design/2/2.1.0/iconify.min.js"></script>
  <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
  <style>
    *{
    box-sizing: border-box;
    }
    
    body{
    font-family:Arial;
    padding:30px;
    font_size:40px;
    text-align:center;
    background:white;
    }
    
    .leftcolumn {
    float:left;
    width:75%;
    padding-left:5px;
    }
    
    .rightcolumn {
    float:left;
    width: 75%;
    padding-left:-15px;
    }
    
    input[type=text]{
    width: 130px;
    box-sizing: border-box;
    border:2px solid #0036b9;
    border-radius:4px;
    font-size: 16px;
    color:red;
    background-color:#0036b9;
    background-repeat:no-repeat;
    padding:12px 20px 12px 40px;
    -webkit-transition:width 0.4s ease-in-out;
    transition: width 0.4s ease-in-out;
    }
    
    input[type=text]:focus {
    width: 100%;
    }
    
    .card1 {
    padding:20px;
    margin-top: -693px;
    border-radius:10px;
    height:710px;
    margin-left:30px;
    background-color:#0036b9;
    }
    
    .card {
    background-color:white;
    padding: 30px;
    margin-top: -20px;
    border-radius:10px;
    width:1425px;
    height:738px;
    margin-left:-20px;
    }
    
    .row:after {
    content:"";
    display: table;
    clear:both;
    }
    
    @media screen and (max-width: 800px
    } {
    .leftcolumn,.rightcolumn {
    width:100%;
    padding: 0;
    }
    }
    
    .fa-naviicon{
    margin-left:-16px;
    border: 1px solid grey;
    border-radius:10px;
    width:35px;
    padding: 5px;
    background-color:WhiteSmoke;
    }
    
    .fa-folder-open{
    marigin-left:-16px;
    border: 1px solid grey;
    border-radius:10px;
    padding: 4px;
    background-color:WhiteSmoke;
    }
    
    .fa-cloud{
    marigin-left:-16px;
    border: 1px solid grey;
    border-radius:10px;
    padding:4px;
    background-color:Lightgrey;
    }
    
    .fa-archive{
    margin-left:-16px;
    border: 1px solid grey;
    border-radium:10px;
    padding: 5px;
    background-color:Lightgrey;
    }
    
    .fa-bell{
    margin-left:-16px;
    border: 1px solid grey;
    border-radium:10px;
    width:35px;
    line-height:30px;
    background-color:WhiteSmoke;
    }
    
    .fa-search{
    margin-left:20px;
    }
    
    .fa-gear{
    margin-left:680px;
    }
    
    .material-icons{border: 1px solid grey;
    border-radius:10px;
    background-color:AliceBlue;
    }
    .iconify{border: 1px solid grey;
    border-radius:10px;
    padding: 5px;
    background-color:AliceBlue;
    }
    img{
    margin-left:20px;
    border-radius:20px;
    }
  </style>
  </head>
  <body>
    <div class="card">
      <i class="fa fa-navicon" style="font-size:24px"></i><br><br>
      <i class="fa fa-folder-open" style="font-size:24px"></i><br><br>
      <i class="fa fa-cloud" style="font-size:24px"></i><br><br>
      <i class="fa fa-archive" style="font-size:24px"></i><br><br>
      <i class="fa fa-bell" style="font-size:24px"></i><br><br>
      <i class="fa fa-user" style="font-size:24px"></i><br><br>
      <div class="row">
        <div class="left column">
          <div class="card1">
            <form>
              <i class="fa fa-search" style="font-size:24px"></i>
              <input type="text"name="search" placeholder="search">
            </form>
            <h2 style="margin-left:20px"> WeatherForecast <i class="fa fa-gear" style="font-size:24px" " margin-right:60px"></i></h2>
            <img src="We1.PNG" alt="Aleq" width="420" height="250"/>
            <img src="We3.PNG" alt="Aleq" width="220" height="150" style="top:50px"/>
            <img src="We4.PNG" alt="Aleq" width="220" height="150" style="top:50px"/><br><br><br>
            <img src="We2.PNG" alt="Aleq" width="420" height="250"/>
            <img src="We5.PNG" alt="Aleq" width="220" height="150" style="top:50px"/>
            <img src="We6.PNG" alt="Aleq" width="220" height="150" style="top:50px"/>
          </div>
        </div>
        <div class="rightcolumn">
          <div class="card2">
            <i class="material-icons" style="font-size:32px" "border:1px solid grey" "border-radius:10px">brightness_7
            </i>
            <h2>It's hot today!</h2>
            <p>Be sure to grab a bottle</p>
            <p>of cold water</p><br>
            <h3>INFO</h3>
            <i class="material-icons"style="font-size:32px">air</i>
            <i class="material-icons"style="font-size:32px">water_drop</i>
            <i class="material-icons"style="font-size:32px">thermostat</i>
            <br><br>
            <i class="material-icons"style="font-size:32px">add</i>
             <br><br>
             <h3>CITY</h3>
            <span class="iconify"data-icon="fa-solid:cloud-rain"style="font-size:32px"></span>
            <p>Paris<br>:</b> 17 degree C</p><br>
          <span class="iconify"data-icon="fa-solid:umbrella"style="font-size:32px"></span>
        <p>London<br>:</b> 13 degree C</p><br>
    <i class="material-icons" style="font-size:32px">add</i>
    </div>
  </div>
  </div>
  </div>
  </body>
  </html>
