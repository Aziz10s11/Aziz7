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

/* ABOUT */
section{
  padding:70px 20px;
  text-align:center;
}

.about{
  background:#111;
}

.about h2{
  font-size:40px;
  margin-bottom:20px;
}

.about p{
  max-width:800px;
  margin:auto;
  font-size:18px;
  line-height:1.8;
  color:#ccc;
}

/* SERVICES */
.services{
  background:#0f0f0f;
}

.services h2{
  font-size:40px;
  margin-bottom:40px;
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
  margin-bottom:10px;
}

/* RESULTS */
.results{
  background:#111;
}

.boxes{
  display:flex;
  justify-content:center;
  gap:20px;
  flex-wrap:wrap;
}

.box{
  background:#1c1c1c;
  padding:30px;
  width:200px;
  border-radius:10px;
}

.box h3{
  font-size:30px;
  color:#25D366;
}

/* CONTACT */
.contact{
  background:#0f0f0f;
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

<!-- HERO -->
<section class="hero">
  <div class="hero-content">
    <h1>Hello 🤗
