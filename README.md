# Aziz7
My personal website1
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
  background-image:url("https://images.unsplash.com/photo-1571019614242-c5c5dee9f50b");
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

/* SECTIONS */
section{
  padding:70px 20px;
  text-align:center;
}

/* ABOUT */
.about{
  background:#111
