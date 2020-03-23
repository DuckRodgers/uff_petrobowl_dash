<html>
	<head>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
	<style>
		.pp_logo{
			display: block;
			margin-left: auto;
			margin-right: auto;
			width: 35%;
		}
		
		.col1{
			background: #5C7080;
		}
		
		.col2{
			background: #6BC0FF;
		}
	</style>
	<script type="text/javascript" src="javascript_petrobowl.js"></script>
		
		<title> Petrobowl Quizzify </title>
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
		<body>
			<div class="container text-center">
				<div class="col-md-4 px-0">
					<img src="C:/Users/mcantuaria/Desktop/petrobowl_app/pp_logo.jpg" class="pp_logo">
				</div>
			</div>
			
			<div class="container-xl p-3 my-3 bg-dark text-white text-center">
				<p id="counter_8"><h1> UFF Team Quiziffy </h1></p>
				<h4> Game Management App </h4>
			</div>
			
			<pre>
			
			</pre>
			
			<div class="container text-center">
				<h1 id="timer_slot"> 08:00 </h1>
				<button type="button" class="btn btn-success" id="play_butt" onclick="time_trigger()"> Play </button>
				<button type="button" class="btn btn-danger" onclick="StopBox()"> Stop </button>
				<button type="button" class="btn btn-dark" onclick="ClearBox()"> Reset </button>
			</div>
			
			<pre>
			
			</pre>
			
			<div class="row text-center">
				<div class="col"><h3> Team 1 </h3></div>
				<div class="col"><h3> Team 2 </h3></div>
			</div>
			
			<div class="row text-center">
				<div class="col" id="t1_score"> 0 </div>
				<div class="col" id="t2_score"> 0 </div>
			</div>
			
			<div class="row text-center">
				<div class="col">
					<div class="btn-group">
						<button type="button" class="btn btn-primary" onclick="t1_score_add()"> +10 </button>
						<button type="button" class="btn btn-primary" onclick="t1_score_sub()"> -05 </button>
					</div>
				</div>
				<div class="col">
					<div class="btn-group">
						<button type="button" class="btn btn-primary" onclick="t2_score_add()"> +10 </button>
						<button type="button" class="btn btn-primary" onclick="t2_score_sub()"> -05 </button>
					</div>
				</div>
			</div>
			
			
			<pre>
			
			</pre>
			
			
			<pre>
			
			</pre>
			
			<div class="container-xl bg-dark text-white">
				<em> Developed Patiently by Busterlock </em><br>
				<u>Petrobowl UFF Team - 2020 </u><br>
				<i class="fa fa-google" style="font-size:24px"></i> petrobowluff@gmail.com <br>
				<i class="fa fa-facebook-official" style="font-size:24px;color:red"></i> facebook.com/petrobowluff
			</div>
			
		</body>
	</head>
</html>
