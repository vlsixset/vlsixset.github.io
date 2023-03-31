<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>My Website</title>
	<style>
		body {
			background: linear-gradient(to bottom, #5f9ea0, #4682b4);
			animation: gradient 20s ease infinite;
		}

		@keyframes gradient {
			0% {
				background-position: 0% 50%;
			}

			50% {
				background-position: 100% 50%;
			}

			100% {
				background-position: 0% 50%;
			}
		}

		.container {
			max-width: 1200px;
			margin: 0 auto;
			padding: 20px;
			text-align: center;
		}

		.button {
			display: inline-block;
			padding: 10px 20px;
			background-color: #4682b4;
			color: #fff;
			border: none;
			border-radius: 5px;
			font-size: 16px;
			font-weight: bold;
			text-decoration: none;
			margin: 10px;
			transition: all 0.3s ease;
		}

		.button:hover {
			background-color: #fff;
			color: #4682b4;
		}

		.blue-text {
			color: #4682b4;
			font-weight: bold;
			font-size: 24px;
			margin: 20px;
		}
	</style>
</head>
<body>
	<div class="container">
		<h1 class="blue-text">Welcome to My Website</h1>
		<a href="https://www.google.com" class="button">Button 1</a>
		<a href="https://www.yahoo.com" class="button">Button 2</a>
		<a href="https://www.bing.com" class="button">Button 3</a>
	</div>
</body>
</html>
