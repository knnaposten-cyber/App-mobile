
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My First App</title>
<style>
body {
font-family: system-ui, -apple-system, sans-serif;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
min-height: 100vh;
margin: 0;
background-color: #f4f4f9;
color: #333;
text-align: center;
}
.card {
background: white;
padding: 2rem;
border-radius: 12px;
box-shadow: 0 4px 12px rgba(0,0,0,0.1);
max-width: 300px;
}
button {
background-color: #0969da;
color: white;
border: none;
padding: 10px 20px;
font-size: 1rem;
border-radius: 6px;
cursor: pointer;
margin-top: 1rem;
}
button:active {
transform: scale(0.98);
}
</style>
</head>
<body>
<div class="card">
<h1>My Mobile Web App</h1>
<p>Tap the button below to test interactivity!</p>
<button onclick="showMessage()">Tap Me</button>
<p id="output"></p>
</div>
<script>
function showMessage() {
document.getElementById("output").innerText = "🎉 It works! Your GitHub app is live.";
}
</script>
</body>
</html>
