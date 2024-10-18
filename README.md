
<!DOCTYPE html>
<html>
<head>
	<title>Treasure or Danger</title>
	<style>
		/* CSS styles */
		body {
			font-family: Arial, sans-serif;
			text-align: center;
		}
		.treasure {
			color: green;
			font-size: 36px;
		}
		.danger {
			color: red;
			font-size: 36px;
		}
	</style>
</head>
<body>
	<!-- HTML structure -->
	<h1 id="result"></h1>
	<script>
    
  let value = 4;
		let reason = 4;
		
// Check the value and reason
		if (value === 4) {
			document.getElementById("result").innerHTML = "<span class='treasure'>TREASURE</span>";
		}
		if (reason === 4) {
			document.getElementById("result").innerHTML = "<span class='danger'>DANGER</span>";
		}
			// Combine both conditions
		if (value === 4 && reason === 4) {
			document.getElementById("result").innerHTML = "<span class='treasure'>TREASURE</span> <span class='danger'>DANGER</span>";
		}
	</script>
</body>
</html>
