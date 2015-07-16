# PR1_Moskalchuk_lab6
<head>
<script src="http://code.jquery.com/jquery-latest.js">
</script>
<script>
$(document).ready(function () 
{
$("#but1").click(function () 
{
$("#div1").fadeIn("slow");
$("#div1").fadeIn(2000);
$("#div2").fadeOut("hide");
$("#div2").fadeOut(2000);
});
$("#but2").click(function () 
{
$("#div1").fadeIn("slow");
$("#div1").fadeIn(2000);
$("#div2").fadeIn("slow");
$("#div2").fadeIn(2000);+});
});
</script>
</head>
<body>
<button id="but1">Нажмите на 1 кнопку</button>
<button id="but2">Нажмите на 2 кнопку</button>
<br><br>
<div id="div1" style="width:80px;height:80px;display:none;background-color:orange;"></div>
<div id="div2" style="width:80px;height:80px;display:none;background-color:green;"></div>
</body>
</html>
