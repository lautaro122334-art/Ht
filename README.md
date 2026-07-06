<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Colecta Solidaria</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}

body{
font-family:'Poppins',sans-serif;
background:linear-gradient(135deg,#0f172a,#1e3a8a);
display:flex;
justify-content:center;
align-items:center;
min-height:100vh;
padding:20px;
color:white;
}

.card{
width:100%;
max-width:600px;
background:rgba(255,255,255,.08);
backdrop-filter:blur(18px);
border:1px solid rgba(255,255,255,.2);
border-radius:25px;
padding:35px;
box-shadow:0 20px 50px rgba(0,0,0,.4);
}

.logo{
font-size:55px;
text-align:center;
margin-bottom:10px;
}

h1{
text-align:center;
font-size:32px;
margin-bottom:10px;
}

p{
text-align:center;
opacity:.9;
line-height:1.6;
margin-bottom:20px;
}

.objetivo{
margin:25px 0;
}

.progress{
background:#ffffff33;
height:16px;
border-radius:20px;
overflow:hidden;
}

.progress div{
height:100%;
width:58%;
background:linear-gradient(90deg,#22c55e,#4ade80);
}

.alias-box{
margin:25px 0;
padding:18px;
background:white;
color:#111827;
border-radius:15px;
text-align:center;
font-size:22px;
font-weight:bold;
letter-spacing:1px;
}

button{
width:100%;
padding:16px;
font-size:18px;
border:none;
border-radius:15px;
background:#22c55e;
color:white;
cursor:pointer;
font-weight:bold;
transition:.3s;
}

button:hover{
background:#16a34a;
}

.info{
margin-top:25px;
display:flex;
justify-content:space-between;
font-size:14px;
opacity:.9;
}

footer{
margin-top:25px;
text-align:center;
font-size:13px;
opacity:.7;
}
</style>
</head>

<body>

<div class="card">

<div class="logo">❤️</div>

<h1>Colecta Solidaria</h1>

<p>
Cada aporte, sin importar el monto, ayuda a alcanzar el objetivo de esta campaña.
Gracias por colaborar.
</p>

<div class="objetivo">
<p><b>Meta:</b> $500.000</p>

<div class="progress">
<div></div>
</div>

<div class="info">
<span>Recaudado: $290.000</span>
<span>58%</span>
</div>
</div>

<div class="alias-box" id="alias">
TU.ALIAS.AQUI
</div>

<button onclick="copiarAlias()">
Copiar alias para transferir
</button>

<footer>
Las contribuciones son voluntarias. Gracias por tu apoyo.
</footer>

</div>

<script>
function copiarAlias(){
const alias=document.getElementById("alias").innerText;
navigator.clipboard.writeText(alias);
alert("Alias copiado correctamente.");
}
</script>

</body>
</html># Ht
Pag web
