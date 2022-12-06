# repository-5-
jquery
<!DOCTYPE html>
<html>
<head>
<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script>
$(document).ready(function(){
$("button").click(function(){
$("#div1").fadeIn();
$("#div2").fadeIn("slow");
$("#div3").fadeIn("3000");
});
});
</script>
</head>
<body>
<p>demonstrate</p>
<button>click</button><br>
<div id="div1" style="width:80px;height:80px;display:none;background-color:rgb(247, 9, 84);"></div><br>
<div id="div2" style="width:80px;height:80px;display:none;background-color:rgb(10, 244, 30);"></div><br>
<div id="div3" style="width:80px;height:80px;display:none;background-color:rgb(0, 221, 255);"></div><br>
</body>
</html>
