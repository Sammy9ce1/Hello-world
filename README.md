# Hello-world
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>

	<style>
		#header {
			background-color: lightgrey;
		}

		.dot1, .dot2, .dot3, {
		float: left ;
		}
		.search {
			float: right;
			width: 400px;
			text-align: right;
		}

		}

		.search {
			background-color: lightgrey;
			position: fixed;
			top: 0;
			padding: 0px;
			}


		.dot1 {
			height: 10px;
			width: 10px;
			background-color: orangered;
			display: inline-block;
			border-radius: 50%;
		}
		.dot2 {
			height: 10px;
			width: 10px;
			background-color: yellow;
			display: inline-block;
			border-radius: 50%;
		}
		.dot3 {
			height: 10px;
			width: 10px;
			background-color: lightgreen;
			display: inline-block;
			border-radius: 50%;
		}
ul {
	list-style-type: none;
	 background-color:ghostwhite ;
	 float: left;
}
li {
	float: right;
	padding: 8px;
	text-align: right;
	color: black;
}
li a:hover {
  background-color: grey;
}
#joinus {
	background-color: red;
	color: white;
	padding: 10px;
	text-align: center;
	float: right;
}
#startup {
	margin-left: 10px;
}
.splitleft {
	text-align: center;
	font: ariel;
	font-size: 2;
	background-color:lightgoldenrodyellow ;
	float: left;
	width: 50%;
	height: 50%;
	position: relative;

}

#explore {
	color: white;
	background-color:sandybrown ;
	padding: 5px;

}
	</style>

	<title>Webpage</title>
</head>
<body>
	<div id="header">
		<span class="dot1"></span>
		<span class="dot2"></span>
		<span class="dot3"></span>
	</div>
	
	<div class="search">
		<form action="/action_page.php">
			<input type="text" name="search" placeholder="search...">
			<button 
			type="submit">Search</button>
		</form>
	</div>


<ul>
	<li id="joinus"><a href="#join">Join Us</a></<li>
	<li><a class="active" href="#home"> Home </li>
	<li><a href="#about">About</a></li>
	<li><a href="#source">Source</a></li>
	<li><a href="#store">Store</a></li>
	<li><a href="questions">Questions</a></li>
	<li id="startup"><button type="button" class="btn btn-default btn-sm">
		<span class="glyphicon glyphicon-star-empty">Startup</span>
	</button>
</li>
</ul>

<div class="splitleft">
	<p><span style="color: gold;"> we are open for the market</span></p>
	<h2><strong>We give the power back to user</strong></h2>
	<p>Content marketing is nothing but offering users value.<br> It is not just about traffic million customers.
	</p>
	<p id="explore"><a href="#explore">Explore Us</a></p>
</div>


</body>
</html>
