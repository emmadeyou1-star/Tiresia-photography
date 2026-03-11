<!DOCTYPE html>
<html>
<head>

<title>Tiresia Photography</title>

<style>

body{
background:black;
color:white;
font-family:Helvetica;
margin:0;
text-align:center;
}

h1{
font-size:60px;
letter-spacing:4px;
margin-top:60px;
}

.subtitle{
color:gray;
margin-bottom:40px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
padding:40px;
}

.gallery img{
width:100%;
border-radius:6px;
transition:0.3s;
}

.gallery img:hover{
transform:scale(1.05);
}

</style>

</head>

<body>

<h1>Tiresia Photography</h1>

<p class="subtitle">Fragments of Light</p>

<div class="gallery">

<img src="https://picsum.photos/800/600?1">
<img src="https://picsum.photos/800/600?2">
<img src="https://picsum.photos/800/600?3">
<img src="https://picsum.photos/800/600?4">

</div>

</body>

</html>
