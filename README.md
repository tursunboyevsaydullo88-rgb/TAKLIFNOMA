<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Malika & Murod — To‘y taklifnomasi</title>
<meta name="theme-color" content="#fdf0f2">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400;1,600&family=Manrope:wght@300;400;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">
</head>
<body>
<div id="loader"><div class="ring">❤</div><p class="names">M & M</p></div>
<div id="progress"></div>
<canvas id="fx"></canvas>

<header class="hero" id="top">
  <div class="hero-bg photo" data-photo="hero"></div>
  <div class="glass hero-card">
    <p class="sub e1">Bizning to‘yimiz</p>
    <h1 class="e2"><span data-c="brideName">Malika</span> <i>&</i> <span data-c="groomName">Murod</span></h1>
    <p class="e3">Sizni hayotimizdagi eng baxtli kunimizga taklif qilamiz.</p>
    <p class="date e4" data-c="dateLong"></p>
    <button class="btn e5" id="openBtn">💌 Taklifnomani ochish</button>
  </div>
</header>

<section id="couple" class="sec">
  <h2 class="rv">Malika ❤️ Murod</h2>
  <p class="lead rv">Ikki qalb, bir sevgi va yangi bir hikoya...</p>
  <div class="pair">
    <figure class="rv left"><div class="frame photo" data-photo="malika"></div><figcaption data-c="brideName">Malika</figcaption><small>Kelin</small></figure>
    <figure class="rv right"><div class="frame photo" data-photo="murod"></div><figcaption data-c="groomName">Murod</figcaption><small>Kuyov</small></figure>
  </div>
</section>

<section class="sec alt">
  <h2 class="rv">Bizning lahzalarimiz</h2>
  <div class="slider rv" id="slider">
    <div class="slide photo on" data-photo="1"><span>Biz ikkimiz</span></div>
    <div class="slide photo" data-photo="2"><span>Unashtiruv</span></div>
    <div class="slide photo" data-photo="3"><span>Romantik lahza</span></div>
    <div class="slide photo" data-photo="4"><span>To‘y kuni</span></div>
    <button class="nav prev" aria-label="Oldingi">‹</button><button class="nav next" aria-label="Keyingi">›</button>
    <div class="dots"></div>
  </div>
</section>

<section class="sec">
  <h2 class="rv">To‘yimizgacha</h2>
  <div class="count rv" id="count">
    <div class="glass"><b id="d">0</b><small>Kun</small></div><div class="glass"><b id="h">0</b><small>Soat</small></div>
    <div class="glass"><b id="m">0</b><small>Daqiqa</small></div><div class="glass"><b id="s">0</b><small>Soniya</small></div>
  </div>
  <div class="info rv">
    <div class="glass"><span>📅</span><small>Sana</small><p data-c="dateLong"></p></div>
    <div class="glass"><span>⏰</span><small>Vaqt</small><p data-c="weddingTime"></p></div>
    <div class="glass"><span>📍</span><small>Manzil</small><p data-c="weddingAddress"></p></div>
  </div>
</section>

<section class="sec alt">
  <div class="glass loc rv">
    <h2>To‘y manzili</h2>
    <p>📍 <span data-c="weddingAddress"></span></p>
    <p>📅 <span data-c="dateLong"></span></p>
    <p>⏰ <span data-c="weddingTime"></span></p>
    <a class="btn" id="mapBtn" target="_blank" rel="noopener">📍 Manzilni ko‘rish</a>
  </div>
</section>

<section class="sec">
  <h2 class="rv">To‘y dasturi</h2>
  <ol class="tl">
    <li class="rv"><span>💍</span><p>Nikoh marosimi</p></li>
    <li class="rv"><span>🥂</span><p>Mehmonlarni kutib olish</p></li>
    <li class="rv"><span>🍽</span><p>To‘y dasturxoni</p></li>
    <li class="rv"><span>🎶</span><p>Musiqa va raqs</p></li>
    <li class="rv"><span>❤️</span><p>Baxtli yakun</p></li>
  </ol>
</section>

<section class="quote">
  <blockquote class="rv">Baxt — birga hayot qurish,<br>har bir lahzani birga qadrlashdir.</blockquote>
</section>

<section class="sec" id="rsvp">
  <div class="glass rsvp rv">
    <h2>To‘yimizda sizni kutamiz ❤️</h2>
    <input id="guest" type="text" placeholder="Ismingiz" autocomplete="name" maxlength="60">
    <button class="btn" data-a="yes">❤️ Men albatta kelaman</button>
    <button class="btn ghost" data-a="no">Afsuski, kela olmayman</button>
    <p id="rsvpMsg" role="status"></p>
  </div>
</section>

<footer>
  <p class="names"><span data-c="brideName">Malika</span> & <span data-c="groomName">Murod</span></p>
  <p>Sevgi bilan, sizni kutib qolamiz ❤️</p>
</footer>

<button id="music" aria-label="Musiqa">♪</button>
<button id="toTop" aria-label="Yuqoriga">↑</button>
<script src="script.js"></script>
</body>
</html>
