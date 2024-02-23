# Tictactoe
<!DOCTYPE html>
<html>

<head>
<style>
   #cont{
     width:455px;
     height:480px;
     display:flex;
     flex-wrap:wrap;
     border:2px solid black;
    padding-right:0px;
    background-color: indigo;
    font-color:white;
   }
   .one{
     height:150px;
     width:150px;
     border-radius:30%;
     border:1px solid white;
     background-color: deepskyblue;
     font-size:8em;
     padding-top:10px;
   }
   #reset{
     margin-top:20px;
     font-size:5em;
     border-radius:20%;
     background-color:pink;
   }
   #result{
     height:70px;
     width:200px;
     border:5px solid rosybrown;
     font-size:4em;
     color:black;
     background-color: lightgreen
   }
   body{
     background-color: rgba(0,0,0,0.9)
   }
</style>
</head>

<body>
  
<h1>tic tac toe</h1>
<br>
<center > <div id="result"><marquee behavior="sliding"></marquee></div></center>
<br>
<center><div id="cont">
  <div class="one"onclick="func(0)"></div>
 <div class="one"onclick="func(1)"></div>
 <div class="one"onclick="func(2)"></div>
  <div class="one"onclick="func(3)"></div>
  <div class="one"onclick="func(4)"></div>
  <div class="one"onclick="func(5)"></div>
  <div class="one"onclick="func(6)"></div>
  <div class="one"onclick="func(7)"></div>
  <div class="one"onclick="func(8)"></div>
 
  
</div></center>
<br>

<center><button id="reset"onclick="reset()">Reset</button></center>
<script src="tic.js"></script>
</body>

</html>
