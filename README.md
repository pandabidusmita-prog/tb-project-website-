![logo](https://github.com/user-attachments/assets/ff02913c-ad5b-45e1-8865-4cf1b2d39a25)<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>TB & Anaerobic Culture Method</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

body{
margin:0;
font-family:Segoe UI, sans-serif;
height:100vh;
overflow:hidden;
background:radial-gradient(circle,#dff9fb,#7ed6df,#130f40);![QR](https://github.com/user-attachments/assets/b9eb1bd2-65fc-4401-84eb-467ba6215b9a)

color:#022;
display:flex;
flex-direction:column;
justify-content:space-between;
}

/* floating particles */
body::before{
content:"";
position:fixed;
width:200%;
height:200%;
background-image:
radial-gradient(#ffffff66 2px,transparent 2px),
radial-gradient(#7efff544 2px,transparent 2px);
background-size:70px 70px,140px 140px;
animation:move 70s linear infinite;
z-index:-1;
}

@keyframes move{
from{transform:translateY(0);}
to{transform:translateY(-700px);}
}

/* header */
header{
text-align:center;
padding:15px;
}

.logo{
width:110px;
margin-bottom:5px;
}

.title{
font-size:36px;
font-weight:900;
color:#0abde3;
}

.subtitle{
font-size:18px;
font-weight:700;
}

/* cards */
.container{
display:flex;
justify-content:center;
align-items:center;
gap:40px;
flex:1;
}

.card{
background:white;
border-radius:25px;
padding:30px;
width:260px;
text-align:center;
box-shadow:0 20px 50px rgba(0,0,0,.3);
cursor:pointer;
transition:.4s;
}

.card:hover{
transform:scale(1.08);
}

.card h2{
font-size:26px;
margin:0;
color:#0984e3;
font-weight:900;
}

/* QR + team row */
.bottom{
display:flex;
justify-content:space-around;
align-items:center;
padding:15px 20px;
}

/* QR */
.qr img{
width:140px;
border-radius:20px;
cursor:pointer;
transition:.3s;
}

.qr img:hover{
transform:scale(1.15);
}

/* team */
.team{
background:white;
padding:15px 25px;
border-radius:20px;
box-shadow:0 15px 40px rgba(0,0,0,.25);
font-size:15px;
text-align:center;
max-width:600px;
}

.team b{
font-size:18px;
color:#0984e3;
}

/* modal */
.modal{
display:none;
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,.9);
justify-content:center;
align-items:center;
z-index:1000;
}

.modal-content{
width:90%;
height:90%;
background:white;
border-radius:20px;
overflow:hidden;
position:relative;
}

iframe{
width:100%;
height:100%;
border:none;
}

.close{
position:absolute;
top:10px;
right:20px;
font-size:35px;
cursor:pointer;
}

</style>
</head>
<body>

<header>
<img src="logo.jpeg" class="logo">
<div class="title">Tuberculosis & Anaerobic Culture Method</div>
<div class="subtitle">
College of Dental Science and Research Centre — Department Of Microbiology
</div>
</header>

<div class="container">

<div class="card" onclick="openPDF('tb')">
<h2>🫁 Tuberculosis</h2>
<p>Click to open project</p>
</div>

<div class="card" onclick="openPDF('anaerobic')">
<h2>🧫 Anaerobic Culture</h2>
<p>Click to open project</p>
</div>

</div>

<div class="bottom">

<div class="qr">
<img src="QR.png" onclick="openQR()">
</div>

<div class="team">
<b>Project Team</b><br>
Bidusmita Panda • Dhwani Rana • Vedanshi Parekh • Jiya Salvi • Chirag Jotva •
Kayan Lakhva • Ahad Kazi • Darshil Nath • Mahi Patel • Sneha Agarwal •
Manal Gadhvi • Dhruv Makwana • Krisha Acharya
</div>

</div>

<!-- PDF viewer -->
<div id="pdfModal" class="modal">
<div class="modal-content">
<span class="close" onclick="closePDF()">✖</span>
<iframe id="viewer"></iframe>
</div>
</div>

<!-- QR viewer -->
<div id="qrModal" class="modal" onclick="closeQR()">
<img src="QR.png" style="width:400px;border-radius:20px;">
</div>

<script>
function openPDF(type){
let file="";
if(type==="tb")
file="Tuberculosis booklet _20260215_170334_0000.pdf";
else
file="Anaerobic Booklet_20260216_141313_0000.pdf";

document.getElementById("viewer").src=file;
document.getElementById("pdfModal").style.display="flex";
}

function closePDF(){
document.getElementById("pdfModal").style.display="none";
document.getElementById("viewer").src="";
}

function openQR(){
document.getElementById("qrModal").style.display="flex";
}

function closeQR(){
document.getElementById("qrModal").style.display="none";
}
</script>

</body>
</html>
[index.html](https://github.com/user-attachments/files/25522977/index.html)
![[Uploading Tuberculosis booklet _20260215_170334_0000.pdf…]()
QR](https://github.com/user-attachments/assets/[Uploading Anaerobic Booklet_20260216_141313_0000.pdf…]()
163362c7-0d8a-45fa-943d-a61b99a9c28a)
![Upl[Uploading Tuberculosis booklet _20260215_170334_0000.pdf…]()oading logo.jpeg…]()




