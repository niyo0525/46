body {color: silver; background-color: #282828; margin: 0%; overflow-y: hidden; overflow-x: hidden;}
a {color: #79bbff; margin-left: 0px; margin-right: 0px; }

div#livechat {color: white; background-color: #ffffff; ;margin: 0%;}
div#container {width: 78%;}
div#sub {padding-top:0px;}
<style>
div#player {display: block; width: 100%; height:  11%; color: black; }
p#bottom {width: 100%;}
p#playlist {font-size: 2.2rem; text-shadow: 1px 0 1px black;}

input {
	-moz-box-shadow:inset 0px 1px 0px 0px #7a8eb9;
	-webkit-box-shadow:inset 0px 1px 0px 0px #7a8eb9;
	box-shadow:inset 0px 1px 0px 0px #7a8eb9;
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #ff0000), color-stop(1, #000000));
	background:-moz-linear-gradient(top, #ff0000 5%, #000000 100%);
	background:-webkit-linear-gradient(top, #ff0000 5%, #000000 100%);
	background:-o-linear-gradient(top, #ff0000 5%, #000000 100%);
	background:-ms-linear-gradient(top, #ff0000 5%, #000000 100%);
	background:linear-gradient(to bottom, #ff0000 5%, #000000 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff0000', endColorstr='#000000',GradientType=0);
	background-color:#ff0000;
	border:0px solid #ffffff;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Arial;
	font-size:12px;
	font-weight:bold;
	padding:3px 10px 3px 10px;
	margin:0px 0px 0px 1px;
	text-decoration:none;
	vertical-align:top;
	height: 22px
}
input:hover {
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #000000), color-stop(1, #ff0000));
	background:-moz-linear-gradient(top, #000000 5%, #ff0000 100%);
	background:-webkit-linear-gradient(top, #000000 5%, #ff0000 100%);
	background:-o-linear-gradient(top, #000000 5%, #ff0000 100%);
	background:-ms-linear-gradient(top, #000000 5%, #ff0000 100%);
	background:linear-gradient(to bottom, #000000 5%, #ff0000 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#000000', endColorstr='#ff0000',GradientType=0);
	background-color:#000000;
}
input:active {
	position:relative;
	top:1px;
}

.btnnew {
	-moz-box-shadow:inset 0px 1px 0px 0px #7a8eb9;
	-webkit-box-shadow:inset 0px 1px 0px 0px #7a8eb9;
	box-shadow:inset 0px 1px 0px 0px #7a8eb9;
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #ff0000), color-stop(1, #000000));
	background:-moz-linear-gradient(top, #ff0000 5%, #000000 100%);
	background:-webkit-linear-gradient(top, #ff0000 5%, #000000 100%);
	background:-o-linear-gradient(top, #ff0000 5%, #000000 100%);
	background:-ms-linear-gradient(top, #ff0000 5%, #000000 100%);
	background:linear-gradient(to bottom, #ff0000 5%, #000000 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ff0000', endColorstr='#000000',GradientType=0);
	background-color:#ff0000;
	border:0px solid #ffffff;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Arial;
	font-size:12px;
	font-weight:bold;
	padding:3px 5px 3px 5px;
	margin:0px 0px 0px -10px;
	text-decoration:none;
	vertical-align:top;
}
.btnnew input:hover {
	background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #000000), color-stop(1, #ff0000));
	background:-moz-linear-gradient(top, #000000 5%, #ff0000 100%);
	background:-webkit-linear-gradient(top, #000000 5%, #ff0000 100%);
	background:-o-linear-gradient(top, #000000 5%, #ff0000 100%);
	background:-ms-linear-gradient(top, #000000 5%, #ff0000 100%);
	background:linear-gradient(to bottom, #000000 5%, #ff0000 100%);
	filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#000000', endColorstr='#ff0000',GradientType=0);
	background-color:#000000;
}
.btnnew input:active {
	position:relative;
	top:1px;
}

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



.flowplayer { width: 100%; background-color: #222; background-size: cover; }
.flowplayer .fp-controls { background-color: rgba(0, 0, 0, 0.4)}
.flowplayer .fp-timeline { background-color: rgba(0, 0, 0, 0.5)}
.flowplayer .fp-progress { background-color: rgba(219, 0, 0, 1)}
.flowplayer .fp-buffer { background-color: rgba(249, 249, 249, 1)}
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
