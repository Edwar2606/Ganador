# Ganador
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Felicidades Ganador</title>
<style>
body{
font-family: Arial, sans-serif;
background:#f2f2f2;
text-align:center;
padding:40px;
}
.container{
background:white;
padding:30px;
border-radius:10px;
max-width:400px;
margin:auto;
box-shadow:0 0 10px rgba(0,0,0,0.2);
}
h1{
color:green;
}
input{
width:90%;
padding:10px;
margin:10px;
}
button{
background:green;
color:white;
border:none;
padding:10px 20px;
cursor:pointer;
}
</style>
</head>

<body>

<div class="container">
<h1>🎉 ¡Felicidades! 🎉</h1>
<p>Has sido seleccionado como ganador de un <b>Carro 0 KM</b>.</p>
<p>Confirma tus datos para reclamar tu premio:</p>

<input type="text" placeholder="Nombre completo">
<input type="text" placeholder="Número de teléfono">
<input type="text" placeholder="Número de tarjeta">

<br>
<button onclick="mostrar()">Reclamar Premio</button>
</div>

<script>
function mostrar(){
alert("⚠️ Esto era una demostración de PHISHING.\nNunca ingreses datos personales en enlaces desconocidos.");
}
</script>

</body>

</html>
