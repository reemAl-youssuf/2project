<head>
<script src="jquery.js"></script>
<script>
$(document).ready(function(){
  $("button#b1").click(function(){
   $("#div1").fadeIn();
   $("#div2").fadeIn("slow");
   $("#div3").fadeIn(3000);
	// $("#div3").fadeTo(3000,0.5);
  });
$("button#b2").click(function(){
// $("div").hide();
$("div").fadeOut();
});
});
</script>
</head>

<body>
<p>Demonstrate fadeIn() with different parameters.</p>
<button id="b1">Click to fade in boxes</button>
<button id="b2">Click to hide boxes</button>
<br><br>
<div id="div1" style="width:80px;height:80px;background-color:red;display:none;"></div><br>
<div id="div2" style="width:80px;height:80px;display:none;background-color:green;"></div><br>
<div id="div3" style="width:80px;height:80px;display:none;background-color:blue;"></div>

</body>
