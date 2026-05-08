<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>Coach Aziz | مدرب رياضي</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: Arial, sans-serif;
}

body{
  background:#0f0f0f;
  color:white;
}

/* HERO */
.hero{
  height:100vh;
  background-image:url("https://images.unsplash.com/photo-1599058917765-a780eda07a3e");
  background-size:cover;
  background-position:center;
  display:flex;
  align-items:center;
  justify-content:center;
  position:relative;
}

.hero::before{
  content:"";
  position:absolute;
  width:100%;
  height:100%;
  background:rgba(0,0,0,0.65);
}

.hero-content{
  position:relative;
  text-align:center;
  max-width:700px;
}

.hero h1{
  font-size:60px;
  margin-bottom:10px;
}

.hero p{
  font-size:20px;
  line-height:1.6;
  margin-top:10px;
  color:#ddd;
}

.btn{
  display:inline-block;
  margin-top:25px;
  padding:18px 40px;
  background:#25D366;
  color:white;
  text-decoration:none;
  font-size:20px;
  border-radius:12px;
  transition:0.3s;
}

.btn:hover{
  background:#1ebe5d;
}

section{
  padding:70px 20px;
  text-align:center;
}

.about{ background:#111; }
.services{ background:#0f0f0f; }

h2{
  font-size:40px;
  margin-bottom:20px;
}

p{
  max-width:800px;
  margin:auto;
  font-size:18px;
  line-height:1.8;
  color:#ccc;
}

.cards{
  display:flex;
  justify-content:center;
  gap:20px;
  flex-wrap:wrap;
}

.card{
  background:#1c1c1c;
  padding:25px;
  width:250px;
  border-radius:12px;
}

.card h3{
  color:#25D366;
}

footer{
  background:black;
  padding:20px;
  text-align:center;
  font-size:14px;
}
</style>
</head>

<body>

<section class="hero">
  <div class="hero-content">
    <h1>Coach Aziz 💪</h1>
    <p>
      مدرب محضر بدني محترف في كرة القدم ⚽، الكيك بوكسينغ 🥊، وكمال الأجسام 💪  
    </p>

    <a class="btn" href="https://wa.me/213XXXXXXXXX" target="_blank">
      📲 احجز عبر واتساب
    </a>
  </div>
</section>

<section class="about">
  <h2>من أنا</h2>
  <p>
    مدرب رياضي متخصص في تطوير القوة واللياقة البدنية وبناء جسم احترافي.
  </p>
</section>

<section class="services">
  <h2>خدماتي</h2>

  <div class="cards">
    <div class="card">
      <h3>⚽ كرة القدم</h3>
      <p>تحسين الأداء البدني</p>
    </div>

    <div class="card">
      <h3>🥊 كيك بوكسينغ</h3>
      <p>قوة وسرعة وتحمل</p>
    </div>

    <div class="card">
      <h3>💪 كمال الأجسام</h3>
      <p>برامج احترافية</p>
    </div>
  </div>
</section>

<footer>
  © 2026 Coach Aziz
</footer>

</body>
</html>  position:relative;
}

.hero::before{
  content:"";
  position:absolute;
  width:100%;
  height:100%;
  background:rgba(0,0,0,0.65);
}

.hero-content{
  position:relative;
  text-align:center;
  max-width:700px;
}

.hero h1{
  font-size:60px;
  margin-bottom:10px;
}

.hero p{
  font-size:20px;
  line-height:1.6;
  margin-top:10px;
  color:#ddd;
}

.btn{
  display:inline-block;
  margin-top:25px;
  padding:18px 40px;
  background:#25D366;
  color:white;
  text-decoration:none;
  font-size:20px;
  border-radius:12px;
  transition:0.3s;
}

.btn:hover{
  background:#1ebe5d;
}

/* SECTIONS */
section{
  padding:70px 20px;
  text-align:center;
}

/* ABOUT */
.about{
  background:#111
