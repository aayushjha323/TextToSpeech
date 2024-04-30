<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport"
		content="width=device-width, initial-scale=1.0">
	<title>Text to Speech Converter</title>
	<link rel="stylesheet" href="style.css">
</head>

<body>
	<div class="container">
		<div class="app-container">
			<div class="headings-container">
				<h1>
					Text to Speech Converter Using 
					HTML, CSS, and JavaScript.
				</h1>
				<h3>
					Enter any text of your choice
					and change it into speech just by
					a click to the button.
				</h3>
			</div>

			<div class="interaction-container">
				<textarea id="textToConvert"
						placeholder="Enter text to convert into speech..."
						id="" cols="35"
						rows="10" class="text-control">
				</textarea>
				<p class="error-para"></p>
				<button class="btn" id="convertBtn">
				Play Converted Sound</button>
			</div>
		</div>
	</div>

	<script src="script.js"></script>
</body>

</html>
