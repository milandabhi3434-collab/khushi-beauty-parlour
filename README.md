# khushi-beauty-parlourecho "# khushi-beauty-parlour" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/milandabhi3434-collab/khushi-beauty-parlour.git
git push -u origin main
<!DOCTYPE html>
<html lang="gu">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Khushi Beauty Parlour | Beauty & Makeup</title>
<meta name="description" content="Khushi Beauty Parlour - Bridal Makeup, Facial, Hair Styling, Mehndi, Waxing and Beauty Services. Book on WhatsApp.">

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
 font-family:Arial,sans-serif;
 background:#fff9fc;
 color:#39232f;
 line-height:1.6;
}
:root{--pink:#d94d86;--dark:#702b4c;--gold:#c49a50}
header{
 background:#fff;
 padding:16px 7%;
 display:flex;
 justify-content:space-between;
 align-items:center;
 position:sticky;top:0;z-index:10;
 box-shadow:0 2px 12px #00000012;
}
.logo{font-size:21px;font-weight:bold;color:var(--dark)}
.logo span{color:var(--pink)}
nav a{
 text-decoration:none;color:#60364b;
 margin-left:18px;font-size:14px;
}
.hero{
 min-height:520px;
 display:flex;align-items:center;
 padding:60px 8%;
 background:linear-gradient(90deg,#fff0f6ed,#fff0f600),
 url('https://images.unsplash.com/photo-1560066984-138dadb4c035?w=1400') center/cover;
}
.hero-content{max-width:540px}
.tag{color:var(--pink);font-weight:bold;letter-spacing:2px}
h1{font-size:48px;line-height:1.15;color:var(--dark);margin:15px 0}
.hero p{font-size:17px;color:#67485a;margin-bottom:25px}
.btn{
 display:inline-block;padding:13px 23px;
 border-radius:30px;text-decoration:none;
 font-weight:bold;margin:5px 5px 5px 0;
}
.primary{background:var(--pink);color:white}
.secondary{border:1px solid var(--pink);color:var(--pink)}
section{padding:65px 7%}
.heading{text-align:center;margin-bottom:35px}
.heading small{color:var(--pink);font-weight:bold}
.heading h2{font-size:32px;color:var(--dark);margin-top:5px}
.heading p{color:#806779}
.about{
 display:grid;grid-template-columns:1fr 1fr;
 gap:35px;align-items:center;
}
.about img{
 width:100%;height:340px;object-fit:cover;
 border-radius:22px;
}
.about h2{color:var(--dark);font-size:30px;margin-bottom:15px}
.services{
 display:grid;
 grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
 gap:20px;
}
.card{
 background:white;padding:24px;
 border-radius:18px;
 border:1px solid #f5dce8;
 box-shadow:0 5px 22px #8d426010;
 transition:.25s;
}
.card:hover{transform:translateY(-5px)}
.card img{
 width:100%;height:155px;object-fit:cover;
 border-radius:12px;margin-bottom:14px;
}
.card h3{color:var(--dark);margin-bottom:8px}
.card p{font-size:14px;color:#765b6b}
.price{color:var(--pink)!important;font-weight:bold;margin:12px 0}
.book{
 display:inline-block;color:var(--pink);
 font-weight:bold;text-decoration:none;
}
.gallery{
 display:grid;grid-template-columns:repeat(3,1fr);
 gap:15px;
}
.gallery img{
 width:100%;height:220px;object-fit:cover;
 border-radius:16px;
}
.banner{
 text-align:center;
 background:linear-gradient(120deg,#8d345d,#d94d86);
 color:white;border-radius:25px;
 padding:50px 20px;
}
.banner h2{font-size:30px;margin-bottom:10px}
.banner p{margin-bottom:15px}
.banner .btn{background:white;color:#a52e64}
footer{
 background:#402333;color:white;
 text-align:center;padding:35px 15px;
}
footer p{margin:7px}
footer a{color:#ffd3e5}
@media(max-width:650px){
 nav{display:none}
 .hero{min-height:450px;padding:45px 6%}
 h1{font-size:36px}
 section{padding:48px 6%}
 .about{grid-template-columns:1fr}
 .gallery{grid-template-columns:1fr 1fr}
 .gallery img{height:160px}
}
</style>
</head>

<body>

<header>
 <div class="logo">Khushi <span>Beauty Parlour</span></div>
 <nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#gallery">Gallery</a>
  <a href="#contact">Contact</a>
 </nav>
</header>

<section class="hero" id="home">
 <div class="hero-content">
  <div class="tag">BEAUTY • CARE • CONFIDENCE</div>
  <h1>તમારી સુંદરતા, અમારી ઓળખ!</h1>
  <p>તમારા દરેક ખાસ પ્રસંગ માટે સુંદર મેકઅપ, સ્કિન કેર અને હેર સ્ટાઇલિંગની ખાસ સેવાઓ.</p>
  <a class="btn primary" href="https://wa.me/919265384827?text=Hello%20Khushi%20Beauty%20Parlour%2C%20I%20want%20to%20book%20an%20appointment.">Book Appointment</a>
  <a class="btn secondary" href="#services">Our Services</a>
 </div>
</section>

<section id="about">
 <div class="about">
  <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?w=900" alt="Beauty makeup">
  <div>
   <small style="color:#d94d86;font-weight:bold">WELCOME TO KHUSHI</small>
   <h2>તમારી સુંદરતા માટે ખાસ કાળજી</h2>
   <p>Khushi Beauty Parlour માં મેકઅપ, ફેશિયલ, હેર સ્ટાઇલિંગ, મહેંદી અને બ્યુટી કેરની સેવાઓ ઉપલબ્ધ છે.</p>
   <p>તમારા ખાસ દિવસને વધુ સુંદર બનાવવા માટે આજે જ બુકિંગ કરો.</p>
   <a class="btn primary" href="https://wa.me/919265384827">Contact Us</a>
  </div>
 </div>
</section>

<section id="services">
 <div class="heading">
  <small>OUR SERVICES</small>
  <h2>અમારી બ્યુટી સેવાઓ</h2>
  <p>તમારી પસંદગીની સર્વિસ પસંદ કરો અને બુકિંગ કરો.</p>
 </div>

 <div class="services">

  <article class="card">
   <img src="https://images.unsplash.com/photo-1487412947147-5cebf100ffc2?w=600" alt="Bridal makeup">
   <h3>Bridal Makeup</h3>
   <p>લગ્ન, સગાઈ અને રિસેપ્શન માટે ખાસ બ્રાઇડલ મેકઅપ.</p>
   <p class="price">ભાવ જાણવા માટે સંપર્ક કરો</p>
   <a class="book" href="https://wa.me/919265384827?text=I%20want%20Bridal%20Makeup">Book Bridal →</a>
  </article>

  <article class="card">
   <img src="https://images.unsplash.com/photo-1616394584738-fc6e612e71b9?w=600" alt="Facial skincare">
   <h3>Facial</h3>
   <p>ફ્રૂટ, ગોલ્ડ અને ડી-ટેન ફેશિયલની સુવિધા.</p>
   <p class="price">₹400 થી શરૂ</p>
   <a class="book" href="https://wa.me/919265384827?text=I%20want%20Facial">Book Facial →</a>
  </article>

  <article class="card">
   <img src="https://images.unsplash.com/photo-1600334129128-685c5582fd35?w=600" alt="Skin care">
   <h3>Cleanup & Skin Care</h3>
   <p>ક્લીનઅપ અને સરળ સ્કિન કેર સેવાઓ.</p>
   <p class="price">₹250 થી શરૂ</p>
   <a class="book" href="https://wa.me/919265384827?text=I%20want%20Cleanup">Book Cleanup →</a>
  </article>

  <article class="card">
   <img src="https://images.unsplash.com/photo-1600948836101-f9ffda59d250?w=600" alt="Hair styling">
   <h3>Hair Cut & Style</h3>
   <p>ટ્રિમ, લેયર, સ્ટેપ કટ અને પાર્ટી હેર સ્ટાઇલ.</p>
   <p class="price">Haircut ₹100 થી શરૂ</p>
   <a class="book" href="https://wa.me/919265384827?text=I%20want%20Haircut">Book Haircut →</a>
  </article>

  <article class="card">
   <img src="https://images.unsplash.com/photo-1512496015851-a90fb38ba796?w=600" alt="Beauty products">
   <h3>Hair Colour & Spa</h3>
   <p>હેર કલર, હાઇલાઇટ્સ અને હેર સ્પા.</p>
   <p class="price">Spa ₹500, Colour ₹400 થી શરૂ</p>
   <a class="book" href="https://wa.me/919265384827?text=I%20want%20Hair%20Spa">Book Now →</a>
  </article>

  <article class="card">
   <img src="https://images.unsplash.com/photo-1516975080664-ed2fc6a32937?w=600" alt="Manicure">
   <h3>Manicure & Pedicure</h3>
   <p>હાથ અને પગની સુંદરતા માટે ખાસ કેર.</p>
   <p class="price">Manicure ₹300, Pedicure ₹400 થી શરૂ</p>
   <a class="book" href="https://wa.me/919265384827?text=I%20want%20Manicure%20or%20Pedicure">Book Now →</a>
  </article>

  <article class="card">
   <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?w=600" alt="Party makeup">
   <h3>Party Makeup</h3>
   <p>ફંક્શન અને તહેવારો માટે સુંદર પાર્ટી મેકઅપ.</p>
   <p class="price">₹800 થી શરૂ</p>
   <a class="book" href="https://wa.me/919265384827?text=I%20want%20Party%20Makeup">Book Makeup →</a>
  </article>

  <article class="card">
   <img src="https://images.unsplash.com/photo-1604848698030-c434ba08ece1?w=600" alt="Mehndi">
   <h3>Mehndi & Threading</h3>
   <p>મહેંદી, આઇબ્રો, થ્રેડિંગ અને વેક્સિંગ.</p>
   <p class="price">Mehndi ₹100, Threading ₹20 થી શરૂ</p>
   <a class="book" href="https://wa.me/919265384827?text=I%20want%20Mehndi%20or%20Threading">Book Now →</a>
  </article>

 </div>
</section>

<section id="gallery">
 <div class="heading">
  <small>OUR GALLERY</small>
  <h2>Beauty Inspiration</h2>
  <p>અમારી બ્યુટી અને મેકઅપ ગેલેરી</p>
 </div>
 <div class="gallery">
  <img src="https://images.unsplash.com/photo-1487412947147-5cebf100ffc2?w=600" alt="Makeup">
  <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?w=600" alt="Beauty">
  <img src="https://images.unsplash.com/photo-1512496015851-a90fb38ba796?w=600" alt="Cosmetics">
  <img src="https://images.unsplash.com/photo-1600334129128-685c5582fd35?w=600" alt="Skincare">
  <img src="https://images.unsplash.com/photo-1600948836101-f9ffda59d250?w=600" alt="Hair">
  <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?w=600" alt="Beauty style">
 </div>
</section>

<section id="contact">
 <div class="banner">
  <h2>તમારી Appointment આજે જ બુક કરો!</h2>
  <p>તમારી પસંદગીની બ્યુટી સર્વિસ માટે WhatsApp કરો.</p>
  <a class="btn" href="https://wa.me/919265384827?text=Hello%20Khushi%20Beauty%20Parlour%2C%20I%20want%20to%20book%20an%20appointment.">WhatsApp Booking</a>
 </div>
</section>

<footer>
 <h2>Khushi Beauty Parlour</h2>
 <p>તમારી સુંદરતા, અમારી ઓળખ!</p>
 <p>WhatsApp: +91 92653 84827</p>
 <p>© 2026 Khushi Beauty Parlour. All Rights Reserved.</p>
</footer>

</body>
</html>
