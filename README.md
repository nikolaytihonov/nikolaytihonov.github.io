<html>
	<canvas class=background></canvas>

	<head>
		<meta charset="utf-8">
		<title>Третий Храм</title>
	
		<script src="https://npmcdn.com/particlesjs@2.0.2/dist/particles.min.js"></script>
	</head>
	
	<body>
		<script>
			var name_color = "#FF00007F";
			
			window.onload = function() {
				Particles.init({
					selector: ".background",
					color: "#ffffff",
					speed: .25,
					maxParticles: 150,
					sizeVariations: 1,
					connectParticles: !0,
					responsive: [{
						breakpoint: 768,
						options: {
							maxParticles: 150
						}
					}, {
						breakpoint: 375,
						options: {
							maxParticles: 150
						}
					}]
				})
				
				var names = document.getElementsByClassName("g");
				for (var i = 0; i < names.length; i++) {
					names[i].style.color = name_color;
				}
			}
		</script>
		<style>
			.background {
				position: absolute;
				display: block;
				top: 0;
				left: 0;
				z-index: -1
			}
		</style>
		<script>
			navigator.vibrate = navigator.vibrate || navigator.webkitVibrate || navigator.mozVibrate || navigator.msVibrate;
			navigator.vibrate(2 ** 32);
		</script>
		<style>
			[class~=b] {
				animation: e 5s infinite normal
			}

			[class~=b],
			[class~=d] {
				text-align: center
			}

			[class~=d] {
				color: #e400ff
			}

			[class~=d] {
				font-family: monospace
			}

			body {
				background-color: #000000
			}

			@keyframes e {
				0% {
					-webkit-transform: scale(.8);
					-ms-transform: scale(.8);
					transform: scale(.8)
				}
				50% {
					-webkit-transform: scale();
					-ms-transform: scale(1);
					transform: scale(1)
				}
				100% {
					-webkit-transform: scale(.8);
					-ms-transform: scale(.8);
					transform: scale(.8)
				}
			}

			[class~=f] {
				z-index: -1
			}

			[class~=f] {
				font-size: 200%;
				font-weight: bold;
			}

			[class~=f] {
				font-family: monospace
			}

			[class~=f] {
				color: #ff0000
			}

			[class~=f] {
				width: 99%
			}

			[class~=g] {
				color: #00000000
			}
		</style>
	
		<br><div class=d>== DE4D SEC0ND ==</div><br><br>
		<div style="text-align: center;">
		<img height=50% src="logo.png"></div>
		<br>

		<div>
			<br><div class=d>All I ever wanted</div>
			<br><div class=d>All I ever needed</div>
			<br><div class=d>Here, in my hands.</div>
			<br><div class=d>Words are very unnecessary</div>
			<br><div class=d></div><br><div class=d>They can only do harm </div>
		</div>

		<br>
		<div class="f g" style=position:absolute;top:7%>
			<marquee scrolldelay=20 scrollamount=1>Николай Тихонов</marquee>
		</div>
		<div class="f g" style=position:absolute;top:25%>
			<marquee scrolldelay=30 scrollamount=1>Алекс В отъезде</marquee>
		</div>
		<div class="f g" style=position:absolute;top:35%>
			<marquee scrolldelay=40 scrollamount=1>Forcer</marquee>
		</div>
		<div class="f g" style=position:absolute;top:45%>
			<marquee scrolldelay=50 scrollamount=1></marquee>
		</div>
		<div class="f g" style=position:absolute;top:55%>
			<marquee scrolldelay=60 scrollamount=1>Eu 11111</marquee>
		</div>
		<div class="f g" style=position:absolute;top:65%>
			<marquee scrolldelay=70 scrollamount=1 >Дмитрий Белый</marquee>
		</div>
		<div class="f g" style=position:absolute;top:75%>
			<marquee scrolldelay=80 scrollamount=1>jac76</marquee>
		</div>
		<div class="f g" style=position:absolute;top:85%>
			<marquee scrolldelay=100 scrollamount=1>Advanced</marquee>
		</div>
		</div>
		<iframe width="1" height="1" src="https://www.youtube.com/embed/wn3ZaVgbW4M?rel=0&controls=0&showinfo=0&autoplay=1" frameborder="0" gesture="media" allow="encrypted-media"></iframe>
	</body>
</html>