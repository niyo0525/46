<style>
#layerPopup{
  width:  77%; 
  height: 15%;
  padding:0px; 
  border:0px solid #fff; 
  position:absolute; 
  left:0.5%; 
  bottom:3%; 
  background:#fff;
  filter:alpha(opacity=50); opacity:0.5; -moz-opacity:0.5;
  text-align:right;
}

#layerPopup input{
  cursor:pointer;
}
</style>

<html>
<head>
<title>니요방송</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<link rel="stylesheet" href="default.css" type="text/css">
</head>

<body oncontextmenu='return false' ondragstart='return false' onselectstart='return false' >
	<div id="container" style="float: left; width:78%; ">
	  <iframe width="100%" height="100%" src="https://player.twitch.tv/?channel=940046&parent=niyo0525.github.io/46/" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen=""></iframe>
	</div>
	<div id="livechat" style=" float: left; width:22%; height:100%;">
		<script async src="//client.uchat.io/uchat.js"></script>
		<u-chat room='940046' style="display:inline-block; width:100%; height:100%;"></u-chat>		
	</div>
</body>
</html>
