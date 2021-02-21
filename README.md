# code
Recharge pins generators

<!DOCTYPE html>
<html lang="en">
<head>
<title> Recharge pins </title>
<script>
function GenPin(){
Var hd = [ "0","1","2","3","4","5","6","7","8","9","0","1"]
Var hn1 = math.floor[math.random()*12]
Var hn2 = math.floor[math.random()*12]
var hn3 = math.floor[math.random()*12]
var hn4 = math.floor[math.random()*12]
var hn5 = math.floor[math.random()*12]
var hn6 = math.floor[math.random()*12]
var hn7 = math.floor[math.random()*12]
var hn8 = math.floor[math.random()*12]
var hn9 = math.floor[math.random()*12]
var hn10 = math.floor[math.random()*12]
var hn11 = math.floor[math.random()*12]
var hn12 = math.floor[math.random()*12]
document.getElemntById(GenPin").innerHtml= hd[hn1] + hd[hn2] + hd[hn3] + hd[hn4] + hd[hn5] + hd[hn6] + hd[hn7] + hd[hn8] + hd[hn9] + hd[hn9] + hd[hn10] + hd[hn11] + hd[hn12];
}
</script>
<style>
body{font-size: 300%;}
button{font-size: 100%; Background-color; #00FF00; color: #FF0000; border: 3px solid red;}
</style>
</head>
<body onload="GenPin()">
Recharge pin code:
<p id="GenPin"></p>
<button onclick="GenPin()">Generate Code!</button>
</body>
</html>
