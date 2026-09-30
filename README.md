<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Kamola & Kamoldin — To‘y taklifnomasi</title>
<meta name="theme-color" content="#fdf0f2">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400;1,600&family=Manrope:wght@300;400;600&display=swap" rel="stylesheet">
<style>
:root{--blush:#fdf0f2;--pink:#f8d7de;--rose:#e8a0b0;--gold:#b76e79;--ink:#4a2c34;--w:#fffafa;
--serif:'Cormorant Garamond',Georgia,serif;--sans:'Manrope',system-ui,sans-serif}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:var(--sans);color:var(--ink);background:var(--blush);overflow-x:hidden;line-height:1.6;font-weight:300}
h1,h2,.names,blockquote,figcaption{font-family:var(--serif);font-weight:600}
#fx{position:fixed;inset:0;width:100%;height:100%;pointer-events:none;z-index:5}
#progress{position:fixed;top:0;left:0;height:3px;width:0;background:linear-gradient(90deg,var(--rose),var(--gold));z-index:50}
#loader{position:fixed;inset:0;z-index:100;background:var(--blush);display:grid;place-content:center;text-align:center;transition:opacity .8s,visibility .8s}
#loader.off{opacity:0;visibility:hidden}
.ring{font-size:3rem;color:var(--rose);animation:beat 1.2s infinite}
#loader .names{font-size:2rem;color:var(--gold)}
@keyframes beat{50%{transform:scale(1.2)}}
.photo{background:linear-gradient(135deg,var(--pink),#f3c1cc 55%,#e9b3a8) center/cover no-repeat}
.glass{background:rgba(255,255,255,.55);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);border:1px solid rgba(255,255,255,.8);border-radius:28px;box-shadow:0 12px 40px rgba(183,110,121,.18)}
.hero{position:relative;min-height:100svh;display:grid;place-items:center;padding:24px;overflow:hidden}
.hero-bg{position:absolute;inset:-10% 0;z-index:0}
.hero-bg::after{content:"";position:absolute;inset:0;background:linear-gradient(180deg,rgba(253,240,242,.2),rgba(253,240,242,.85))}
.hero-card{position:relative;z-index:6;text-align:center;padding:40px 24px;width:min(560px,100%)}
.sub{letter-spacing:.2em;color:var(--gold);font-size:.85rem}
h1{font-size:clamp(2.6rem,12vw,4.8rem);line-height:1.05;margin:12px 0 16px;background:linear-gradient(120deg,var(--gold),#d99aa5,var(--gold));-webkit-background-clip:text;background-clip:text;color:transparent}
h1 i{font-weight:400}
.date{margin:14px 0 24px;color:var(--gold);font-weight:600}
.btn{display:inline-block;border:0;cursor:pointer;font:600 1rem var(--sans);color:#fff;text-decoration:none;padding:16px 30px;min-height:52px;border-radius:99px;background:linear-gradient(135deg,#e8a0b0,#b76e79);box-shadow:0 8px 24px rgba(183,110,121,.4);transition:transform .25s}
.btn:active{transform:scale(.96)}
.btn.ghost{background:transparent;color:var(--gold);box-shadow:inset 0 0 0 1.5px var(--rose)}
.e1,.e2,.e3,.e4,.e5{opacity:0;transform:translateY(24px);animation:in 1s forwards}
.e1{animation-delay:1.2s}.e2{animation-delay:1.5s}.e3{animation-delay:1.9s}.e4{animation-delay:2.2s}.e5{animation-delay:2.5s}
@keyframes in{to{opacity:1;transform:none}}
.sec{padding:80px 20px;text-align:center;position:relative;z-index:1}
.alt{background:linear-gradient(180deg,var(--blush),var(--w),var(--blush))}
h2{font-size:clamp(2rem,8vw,3rem);color:var(--gold);margin-bottom:16px}
.lead{font-family:var(--serif);font-style:italic;font-size:1.4rem;margin-bottom:36px}
.pair{display:flex;gap:20px;justify-content:center;flex-wrap:wrap}
figure{width:min(240px,42%);min-width:150px}
.frame{aspect-ratio:3/4;border-radius:120px 120px 24px 24px;border:5px solid #fff;box-shadow:0 0 0 2px var(--rose),0 14px 36px rgba(183,110,121,.3);animation:float 6s ease-in-out infinite}
figure+figure .frame{animation-delay:-3s}
@keyframes float{50%{transform:translateY(-8px)}}
figcaption{font-size:1.8rem;margin-top:14px;color:var(--gold)}
small{color:var(--rose);letter-spacing:.08em}
.slider{position:relative;width:min(560px,100%);aspect-ratio:4/5;max-height:70svh;margin:24px auto 0;border-radius:28px;overflow:hidden;box-shadow:0 16px 44px rgba(183,110,121,.3);touch-action:pan-y}
.slide{position:absolute;inset:0;opacity:0;transform:scale(1.08);transition:opacity 1.2s,transform 5s}
.slide.on{opacity:1;transform:scale(1)}
.slide span{position:absolute;bottom:52px;left:0;right:0;color:#fff;font:italic 1.6rem var(--serif);text-shadow:0 2px 12px rgba(0,0,0,.35)}
.nav{position:absolute;top:50%;transform:translateY(-50%);width:44px;height:44px;border-radius:50%;border:0;background:rgba(255,255,255,.6);color:var(--gold);font-size:1.6rem;cursor:pointer;z-index:2}
.prev{left:10px}.next{right:10px}
.dots{position:absolute;bottom:16px;left:0;right:0;display:flex;justify-content:center;gap:8px;z-index:2}
.dots i{width:8px;height:8px;border-radius:9px;background:rgba(255,255,255,.6);transition:.3s}
.dots i.on{width:24px;background:#fff}
.count{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;max-width:520px;margin:24px auto 32px}
.count .glass{padding:18px 4px;border-radius:20px}
.count b{display:block;font:600 clamp(1.7rem,8vw,2.6rem) var(--serif);color:var(--gold)}
.info{display:grid;gap:14px;max-width:520px;margin:auto}
.info .glass{padding:20px}
.info span{font-size:1.5rem}.info small{display:block}
.loc{max-width:520px;margin:auto;padding:36px 22px}
.loc p{margin-bottom:10px;overflow-wrap:anywhere}
.loc .btn{margin-top:14px}
.tl{list-style:none;max-width:420px;margin:32px auto 0;position:relative;text-align:left;padding-left:8px}
.tl::before{content:"";position:absolute;left:31px;top:8px;bottom:8px;width:2px;background:linear-gradient(var(--rose),var(--gold))}
.tl li{display:flex;align-items:center;gap:18px;margin-bottom:26px}
.tl span{flex:none;width:48px;height:48px;border-radius:50%;background:#fff;display:grid;place-items:center;font-size:1.3rem;box-shadow:0 0 0 2px var(--rose),0 6px 16px rgba(183,110,121,.3);z-index:1}
.tl p{font:600 1.5rem var(--serif)}
.quote{padding:110px 24px;text-align:center;background:linear-gradient(135deg,#f8d7de,#f3c1cc,#f8d7de);position:relative;z-index:1}
blockquote{font-size:clamp(1.7rem,7vw,2.8rem);font-style:italic;font-weight:400;color:var(--ink);max-width:700px;margin:auto}
.rsvp{max-width:480px;margin:auto;padding:36px 22px;display:grid;gap:14px}
.rsvp h2{font-size:2rem}
input{font:400 1rem var(--sans);padding:16px 20px;border-radius:99px;border:1.5px solid var(--pink);background:rgba(255,255,255,.8);text-align:center;color:var(--ink);outline:0;width:100%}
input:focus{border-color:var(--rose);box-shadow:0 0 0 4px rgba(232,160,176,.25)}
#rsvpMsg{min-height:1.6em;color:var(--gold);font-weight:600}
footer{text-align:center;padding:56px 20px calc(56px + env(safe-area-inset-bottom));background:linear-gradient(180deg,var(--blush),var(--pink));position:relative;z-index:1}
footer .names{font-size:2.4rem;color:var(--gold)}
#music,#toTop{position:fixed;right:16px;width:48px;height:48px;border-radius:50%;border:0;z-index:40;background:rgba(255,255,255,.75);backdrop-filter:blur(8px);color:var(--gold);font-size:1.3rem;cursor:pointer;box-shadow:0 6px 20px rgba(183,110,121,.3)}
#music{bottom:16px;display:none}#music.show{display:block}
#music.play{animation:beat 1.6s infinite}
#toTop{bottom:76px;opacity:0;visibility:hidden;transition:.3s}
#toTop.show{opacity:1;visibility:visible}
.rv{opacity:0;transform:translateY(34px) scale(.97);transition:opacity 1s,transform 1s}
.rv.left{transform:translateX(-40px)}.rv.right{transform:translateX(40px)}
.rv.in{opacity:1;transform:none}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition-duration:.01s!important}.e1,.e2,.e3,.e4,.e5,.rv{opacity:1;transform:none}}
</style>
</head>
<body>
<div id="loader"><div class="ring">❤</div><p class="names">K & K</p></div>
<div id="progress"></div>
<canvas id="fx"></canvas>

<header class="hero" id="top">
  <div class="hero-bg photo" data-photo="hero"></div>
  <div class="glass hero-card">
    <p class="sub e1">Bizning to‘yimiz</p>
    <h1 class="e2"><span data-c="brideName">Kamola</span> <i>&</i> <span data-c="groomName">Kamoldin</span></h1>
    <p class="e3">Sizni hayotimizdagi eng baxtli kunimizga taklif qilamiz.</p>
    <p class="date e4" data-c="dateLong"></p>
    <button class="btn e5" id="openBtn">💌 Taklifnomani ochish</button>
  </div>
</header>

<section id="couple" class="sec">
  <h2 class="rv">Kamola ❤️ Kamoldin</h2>
  <p class="lead rv">Ikki qalb, bir sevgi va yangi bir hikoya...</p>
  <div class="pair">
    <figure class="rv left"><div class="frame photo" data-photo="malika"></div><figcaption data-c="brideName">Kamola</figcaption><small>Kelin</small></figure>
    <figure class="rv right"><div class="frame photo" data-photo="murod"></div><figcaption data-c="groomName">Kamoldin</figcaption><small>Kuyov</small></figure>
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
  <p class="names"><span data-c="brideName">Kamola</span> & <span data-c="groomName">Kamoldin</span></p>
  <p>Sevgi bilan, sizni kutib qolamiz ❤️</p>
</footer>

<button id="music" aria-label="Musiqa">♪</button>
<button id="toTop" aria-label="Yuqoriga">↑</button>
<script>
/* ===== SOZLAMALAR — faqat shu yerni o'zgartiring ===== */
const CONFIG = {
  brideName: "Kamola",
  groomName: "Kamoldin",
  weddingDate: "2026-10-10",          // YYYY-MM-DD
  weddingTime: "11-Oktabr",               // HH:MM
  weddingAddress: "To'raqo'rg'on yumani Toshkent MFY kosonsoy ko'chasi Mo'jjal Odil ahmedov yonidan kirganda 175 uy ",
  googleMapsLink: "https://maps.google.com/?q=Tashkent",   // CHANGE_GOOGLE_MAPS_LINK
  weddingMusicUrl: "CHANGE_MUSIC_URL", // masalan: assets/music.mp3
  photos: { hero:"", malika:"", murod:"", 1:"", 2:"", 3:"", 4:"" } // masalan: "assets/hero.jpg"
};
const GOOGLE_MAPS_LINK = CONFIG.googleMapsLink;
const WEDDING_MUSIC_URL = CONFIG.weddingMusicUrl;
/* ====================================================== */

const $ = (s, r = document) => r.querySelector(s), $$ = (s, r = document) => [...r.querySelectorAll(s)];
const months = ["yanvar","fevral","mart","aprel","may","iyun","iyul","avgust","sentabr","oktabr","noyabr","dekabr"];
const target = new Date(`${CONFIG.weddingDate}T${CONFIG.weddingTime}:00`);
const valid = !isNaN(target);
CONFIG.dateLong = valid ? `${target.getDate()} ${months[target.getMonth()]} ${target.getFullYear()}` : "Sana tez orada";

$$("[data-c]").forEach(e => e.textContent = CONFIG[e.dataset.c]);
$$("[data-photo]").forEach(e => { const p = CONFIG.photos[e.dataset.photo]; if (p) e.style.backgroundImage = `url(${p})`; });
$("#mapBtn").href = GOOGLE_MAPS_LINK;

addEventListener("load", () => setTimeout(() => $("#loader").classList.add("off"), 900));

/* Countdown */
function tick() {
  let t = valid ? Math.max(0, target - Date.now()) : 0;
  const v = { d: Math.floor(t / 864e5), h: Math.floor(t / 36e5) % 24, m: Math.floor(t / 6e4) % 60, s: Math.floor(t / 1e3) % 60 };
  for (const k in v) $("#" + k).textContent = String(v[k]).padStart(k === "d" ? 1 : 2, "0");
}
tick(); setInterval(tick, 1000);

/* Music */
const music = $("#music"); let audio;
if (!WEDDING_MUSIC_URL.startsWith("CHANGE")) { audio = new Audio([WEDDING_MUSIC_URL](https://www.youtube.com/watch?v=9Z_9VUrLUE4&list=RD9Z_9VUrLUE4&start_radio=1)); audio.loop = true; audio.volume = .6; music.classList.add("show"); }
const setPlay = on => { music.classList.toggle("play", on); music.textContent = on ? "♪" : "🔇"; };
music.onclick = () => { if (!audio) return; audio.paused ? audio.play().then(() => setPlay(true)) : (audio.pause(), setPlay(false)); };
$("#openBtn").onclick = () => {
  $("#couple").scrollIntoView({ behavior: "smooth" });
  if (audio) audio.play().then(() => setPlay(true)).catch(() => {});
};

/* Reveal on scroll */
const io = new IntersectionObserver(es => es.forEach(e => { if (e.isIntersecting) { e.target.classList.add("in"); io.unobserve(e.target); } }), { threshold: .15 });
$$(".rv").forEach((e, i) => { e.style.transitionDelay = (i % 3) * .12 + "s"; io.observe(e); });

/* Progress, back-to-top, parallax */
const bg = $(".hero-bg");
addEventListener("scroll", () => {
  const y = scrollY, max = document.documentElement.scrollHeight - innerHeight;
  $("#progress").style.width = (y / max * 100) + "%";
  $("#toTop").classList.toggle("show", y > 600);
  if (y < innerHeight) bg.style.transform = `translateY(${y * .25}px)`;
}, { passive: true });
$("#toTop").onclick = () => scrollTo({ top: 0, behavior: "smooth" });

/* Slider */
const slides = $$(".slide"), dots = $(".dots"); let cur = 0, timer;
slides.forEach((_, i) => { const d = document.createElement("i"); d.onclick = () => go(i, true); dots.append(d); });
function go(n, manual) {
  cur = (n + slides.length) % slides.length;
  slides.forEach((s, i) => s.classList.toggle("on", i === cur));
  $$("i", dots).forEach((d, i) => d.classList.toggle("on", i === cur));
  clearInterval(timer); timer = setInterval(() => go(cur + 1), 4500);
}
$(".prev").onclick = () => go(cur - 1); $(".next").onclick = () => go(cur + 1);
let sx = 0; const sl = $("#slider");
sl.addEventListener("touchstart", e => sx = e.touches[0].clientX, { passive: true });
sl.addEventListener("touchend", e => { const dx = e.changedTouches[0].clientX - sx; if (Math.abs(dx) > 40) go(cur + (dx < 0 ? 1 : -1)); });
go(0);

/* RSVP (brauzerda saqlanadi; server kerak emas) */
$$("#rsvp [data-a]").forEach(b => b.onclick = () => {
  const name = $("#guest").value.trim(), msg = $("#rsvpMsg");
  if (!name) { msg.textContent = "Iltimos, ismingizni yozing."; $("#guest").focus(); return; }
  const yes = b.dataset.a === "yes";
  try { localStorage.setItem("rsvp", JSON.stringify({ name, yes })); } catch (e) {}
  msg.textContent = yes ? `Rahmat, ${name}! Sizni kutamiz ❤️` : `Rahmat, ${name}. Xabaringiz uchun minnatdormiz.`;
  if (yes) burst();
});

/* Hearts, petals, sparkles */
const cv = $("#fx"), cx = cv.getContext("2d"); let W, H, ps = [];
const resize = () => { W = cv.width = innerWidth; H = cv.height = innerHeight; };
addEventListener("resize", resize); resize();
const kinds = ["❤", "❀", "✦", "🌸"], cols = ["#e8a0b0", "#f3c1cc", "#d99aa5", "#e6b8a2"];
const mk = (y) => ({ x: Math.random() * W, y: y ?? H + 20, k: kinds[Math.random() * 4 | 0], s: 8 + Math.random() * 14, v: .3 + Math.random() * .7, w: Math.random() * 6, c: cols[Math.random() * 4 | 0], a: .25 + Math.random() * .45 });
const N = innerWidth < 600 ? 16 : 30;
for (let i = 0; i < N; i++) ps.push(mk(Math.random() * H));
function burst() { for (let i = 0; i < 20; i++) { const p = mk(H * .6); p.s += 8; p.v += 1; ps.push(p); } }
const still = matchMedia("(prefers-reduced-motion:reduce)").matches;
(function draw() {
  cx.clearRect(0, 0, W, H);
  ps.forEach((p, i) => {
    p.y -= p.v; p.w += .02; p.x += Math.sin(p.w) * .6;
    cx.globalAlpha = p.a; cx.fillStyle = p.c; cx.font = p.s + "px serif"; cx.fillText(p.k, p.x, p.y);
    if (p.y < -30) i < N ? Object.assign(p, mk()) : (p.dead = 1);
  });
  ps = ps.filter(p => !p.dead);
  if (!still) requestAnimationFrame(draw);
})();
</script>
</body>
</html>
