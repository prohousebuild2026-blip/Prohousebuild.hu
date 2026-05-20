
<!DOCTYPE html>
<html lang="hu">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Prohouse-& Build | Prémium Generálkivitelezés</title>
<meta name="description" content="Prohouse-& Build - generálkivitelezés, lakásfelújítás, konténerházak, faházak Magyarországon. Prémium kivitelezés, gyors ajánlatadás.">
<meta name="keywords" content="generálkivitelezés, lakásfelújítás, konténerház, faház, burkolás, építőipar">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif;scroll-behavior:smooth;}
body{background:#0b0b0b;color:#fff;line-height:1.6;}

/* NAV */
.nav{
position:fixed;top:0;left:0;width:100%;z-index:1000;
display:flex;justify-content:space-between;align-items:center;
padding:15px 25px;
background:rgba(0,0,0,0.75);
backdrop-filter:blur(10px);
}
.nav a{color:#fff;text-decoration:none;margin-left:15px;font-size:14px;transition:0.3s;}
.nav a:hover{color:#d4af37;}
.nav strong{color:#d4af37;}

/* HERO */
.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.85)),
url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1600&q=80');
background-size:cover;
background-position:center;
}
.hero h1{font-size:56px;animation:fadeIn 1.5s ease;}
.hero p{font-size:20px;margin-top:10px;color:#ddd;animation:fadeIn 2s ease;}

.btn{
margin-top:20px;
padding:14px 30px;
background:#d4af37;
color:#000;
border:none;
font-weight:bold;
border-radius:8px;
text-decoration:none;
transition:0.3s;
display:inline-block;
}
.btn:hover{transform:scale(1.05);}

section{padding:90px 20px;max-width:1100px;margin:auto;}
.section-title{font-size:36px;margin-bottom:25px;color:#d4af37;text-align:center;}

/* SERVICES */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:20px;
}
.card{
background:#151515;
padding:25px;
border-radius:12px;
transition:0.3s;
border:1px solid #222;
}
.card:hover{
transform:translateY(-8px);
border-color:#d4af37;
}

/* ABOUT */
.about{
text-align:center;
max-width:800px;
margin:auto;
color:#ccc;
}

/* TESTIMONIALS */
.testimonial{
background:#151515;
padding:20px;
border-radius:10px;
font-style:italic;
}

/* CONTACT */
.contact{
background:#111;
padding:40px;
border-radius:12px;
max-width:700px;
margin:auto;
}
input,textarea{
width:100%;
padding:12px;
margin-top:10px;
border:none;
border-radius:6px;
background:#222;
color:#fff;
}

footer{text-align:center;padding:25px;background:#000;color:#777;margin-top:50px;}

/* WHATSAPP */
.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:#fff;
padding:14px 18px;
border-radius:50px;
font-weight:bold;
text-decoration:none;
box-shadow:0 0 15px rgba(0,0,0,0.5);
}

/* ANIMATION */
@keyframes fadeIn{
from{opacity:0;transform:translateY(20px);}
to{opacity:1;transform:translateY(0);}
}
</style>
</head>
<body>

<div class="nav">
<div><strong>Prohouse-& Build</strong></div>
<div>
<a href="#services">Szolgáltatások</a>
<a href="#about">Rólunk</a>
<a href="#testimonials">Vélemények</a>
<a href="#contact">Kapcsolat</a>
</div>
</div>

<div class="hero">
<h1>Prémium Generálkivitelezés</h1>
<p>Otthonok, amiket megálmodsz – mi megépítjük</p>
<a class="btn" href="#contact">Ingyenes ajánlatkérés</a>
</div>

<section id="services">
<h2 class="section-title">Szolgáltatások</h2>
<div class="grid">
<div class="card"><h3>Generál kivitelezés</h3><p>Teljes építési projektek A-tól Z-ig.</p></div>
<div class="card"><h3>Lakásfelújítás</h3><p>Modern, prémium felújítások.</p></div>
<div class="card"><h3>Konténerházak</h3><p>Gyors, modern megoldások.</p></div>
<div class="card"><h3>Faházak</h3><p>Természetes, időtálló szerkezetek.</p></div>
</div>
</section>

<section id="about">
<h2 class="section-title">Rólunk</h2>
<div class="about">
<p>
A Prohouse-& Build egy prémium építőipari vállalkozás, amely teljes körű kivitelezést, felújítást és egyedi építési megoldásokat kínál Magyarországon.
Célunk: minőség, gyorsaság és megbízhatóság.
</p>
</div>
</section>

<section id="testimonials">
<h2 class="section-title">Ügyfélvélemények</h2>
<div class="grid">
<div class="testimonial">„Gyors, precíz munka, nagyon elégedettek vagyunk!”</div>
<div class="testimonial">„A ház felújítás tökéletes lett, ajánlom!”</div>
<div class="testimonial">„Profi csapat, korrekt árak.”</div>
</div>
</section>

<section id="contact">
<h2 class="section-title">Kapcsolat</h2>
<div class="contact">
<p>📞 +36 30 636 9083</p>
<p>📧 prohouse.build2026@gmail.com</p>

<form action="mailto:prohouse.build2026@gmail.com" method="post" enctype="text/plain">
<input type="text" name="name" placeholder="Név" required>
<input type="email" name="email" placeholder="Email" required>
<textarea name="message" rows="5" placeholder="Üzenet" required></textarea>
<button class="btn" type="submit">Küldés</button>
</form>
</div>
</section>

<a class="whatsapp" href="https://wa.me/36306369083" target="_blank">WhatsApp</a>

<footer>
© 2026 Prohouse-& Build | Minden jog fenntartva
</footer>

</body>
</html>
