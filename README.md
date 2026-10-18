<!DOCTYPE html>
<html lang="en-GB">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Stanmore Barbers | Haircuts, Fades and Shaves in Stanmore</title>
<meta name="description" content="Stanmore Barbers, 87b Stanmore Hill, Stanmore HA7 3DZ. Classic cuts, skin fades, beard grooming and hot towel shaves. Open 10:00 - 17:00.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,800&family=Work+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --night:#0b1427; --navy:#12203d; --navy2:#1b2e55; --chalk:#eef0f3; --white:#fff;
  --red:#d02a33; --blue:#3a6bc4; --mute:#9aa6bd; --ink:#16213a; --line:rgba(255,255,255,.12);
  --head:'Fraunces',Georgia,serif; --body:'Work Sans',system-ui,sans-serif;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font:400 1.05rem/1.7 var(--body);color:var(--ink);background:var(--chalk)}
a{color:inherit}
:focus-visible{outline:3px solid var(--red);outline-offset:3px}
.wrap{max-width:1120px;margin:0 auto;padding:0 28px}
h1,h2,h3{font-family:var(--head);margin:0;line-height:1.05}
h2{font-size:clamp(2rem,4.6vw,3.2rem);font-weight:800;letter-spacing:-.015em;margin-bottom:20px}
section{padding:96px 0}

/* buttons */
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;padding:15px 30px;border-radius:999px;font:600 1rem var(--body);text-decoration:none;border:2px solid transparent;cursor:pointer;transition:transform .15s,background .15s,color .15s}
.btn:hover{transform:translateY(-2px)}
.btn.red{background:var(--red);color:#fff;box-shadow:0 10px 28px -8px rgba(208,42,51,.7)}
.btn.red:hover{background:#e0333c}
.btn.line{border-color:rgba(255,255,255,.4);color:#fff}
.btn.line:hover{background:#fff;color:var(--night)}
.btn.navy{background:var(--navy);color:#fff}

/* header */
header{position:sticky;top:0;z-index:20;background:rgba(11,20,39,.85);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);border-bottom:1px solid var(--line);color:#fff}
.bar{display:flex;align-items:center;justify-content:space-between;gap:20px;height:72px}
.logo{font:800 1.35rem var(--head);text-decoration:none;display:flex;align-items:center;gap:12px}
.logo i{width:12px;height:30px;border-radius:6px;background:repeating-linear-gradient(135deg,var(--red) 0 5px,#fff 5px 10px,var(--blue) 10px 15px,#fff 15px 20px)}
nav{display:flex;gap:30px;font-weight:500;font-size:.95rem}
nav a{text-decoration:none;color:var(--mute)}
nav a:hover{color:#fff}
.bar .btn{padding:10px 22px}

/* hero */
.hero{background:radial-gradient(900px 600px at 80% 20%,var(--navy2),transparent 70%),var(--night);color:#fff;padding:84px 0 96px;overflow:hidden}
.hero .wrap{display:grid;grid-template-columns:1.5fr 1fr;gap:48px;align-items:center}
.hero h1{font-size:clamp(3rem,8vw,6.2rem);font-weight:800;letter-spacing:-.025em}
.hero p{font-size:1.2rem;color:#c5cddd;max-width:46ch;margin:26px 0 34px}
.cta{display:flex;flex-wrap:wrap;gap:12px}
.chips{display:flex;flex-wrap:wrap;gap:10px 28px;margin-top:42px;padding-top:26px;border-top:1px solid var(--line);color:var(--mute);font-size:.95rem}
.chips b{color:#fff;font-weight:600}

/* barber pole */
.polewrap{display:flex;justify-content:center}
.pole{width:150px;display:flex;flex-direction:column;align-items:center;filter:drop-shadow(0 30px 40px rgba(0,0,0,.5))}
.cap{width:170px;height:34px;border-radius:12px;background:linear-gradient(#f1f4f9,#aab4c6 60%,#7f8ba2)}
.cap.top{border-radius:60px 60px 10px 10px;height:44px}
.tube{position:relative;width:132px;height:380px;border-radius:14px;overflow:hidden;
  background:repeating-linear-gradient(145deg,var(--red) 0 34px,#fff 34px 68px,var(--blue) 68px 102px,#fff 102px 136px);
  background-size:190px 190px;animation:spin 7s linear infinite}
.tube::after{content:"";position:absolute;inset:0;
  background:linear-gradient(90deg,rgba(0,0,0,.35),rgba(255,255,255,.28) 22%,rgba(255,255,255,0) 40%,rgba(0,0,0,.05) 70%,rgba(0,0,0,.4))}
@keyframes spin{to{background-position:0 190px}}

/* services */
.sv-head{display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:end;margin-bottom:44px}
.sv-head p{margin:0 0 20px;color:#4a5670;max-width:46ch}
.rows{border-top:2px solid var(--ink)}
.row{display:grid;grid-template-columns:1fr 1.1fr;gap:32px;padding:30px 4px;border-bottom:1px solid #c9ced8;transition:background .2s,padding .2s}
.row:hover{background:var(--white);padding-left:20px}
.row h3{font-size:1.6rem;font-weight:800}
.row p{margin:0;color:#4a5670;align-self:center}

/* why */
.why{background:var(--night);color:#fff}
.why h2{max-width:18ch}
.why .lead{color:#c5cddd;max-width:56ch}
.pts{display:grid;grid-template-columns:repeat(3,1fr);gap:0;margin-top:52px;border-top:1px solid var(--line)}
.pts div{padding:32px 32px 0 0}
.pts div+div{padding-left:32px;border-left:1px solid var(--line)}
.pts h3{font-size:1.35rem;margin-bottom:10px}
.pts p{margin:0;color:var(--mute);font-size:.98rem}

/* booking */
.book{background:var(--chalk)}
.bk{display:grid;grid-template-columns:1fr 1.1fr;gap:56px;align-items:center}
.bk .lead{color:#4a5670;max-width:38ch}
.phone{display:inline-block;margin-top:14px;font:800 1.6rem var(--head);text-decoration:none;border-bottom:3px solid var(--red)}
.bcard{background:var(--navy);color:#fff;border-radius:24px;padding:40px;box-shadow:0 40px 80px -30px rgba(11,20,39,.55)}
.bcard h3{font-size:1.8rem;font-weight:800;margin-bottom:18px}
.bcard ol{margin:0 0 28px;padding-left:22px;color:#c5cddd}
.bcard li{padding:5px 0}

/* review prompt */
.ov{position:fixed;inset:0;z-index:50;display:none;align-items:center;justify-content:center;padding:20px;background:rgba(7,12,24,.78);backdrop-filter:blur(6px);-webkit-backdrop-filter:blur(6px)}
.ov.open{display:flex}
.modal{position:relative;width:100%;max-width:460px;background:var(--navy);color:#fff;border-radius:24px;padding:40px 34px 32px;text-align:center;box-shadow:0 40px 80px -20px rgba(0,0,0,.6)}
.modal .tick{width:60px;height:60px;margin:0 auto 18px;border-radius:50%;background:var(--red);display:grid;place-items:center;font-size:1.9rem;line-height:1}
.modal h2{font-size:1.9rem;margin-bottom:10px}
.modal p{margin:0 0 22px;color:#c5cddd}
.stars{display:flex;justify-content:center;gap:6px;margin-bottom:8px}
.stars button{background:none;border:0;padding:2px;font-size:2.6rem;line-height:1;cursor:pointer;color:rgba(255,255,255,.28);transition:transform .12s,color .12s}
.stars button.on{color:#f6b82e}
.stars button:hover{transform:scale(1.12)}
.rt{min-height:1.5em;margin:0 0 20px!important;font-weight:500;color:#fff!important}
.modal .btn[disabled]{opacity:.45;cursor:not-allowed;transform:none;box-shadow:none}
.later{display:block;margin:16px auto 0;background:none;border:0;color:var(--mute);font:500 .95rem var(--body);cursor:pointer;text-decoration:underline}

/* visit */
.visit{background:var(--white)}
.vs{display:grid;grid-template-columns:1fr 1.3fr;gap:56px;align-items:center}
address{font-style:normal;font:500 1.25rem/1.6 var(--head);margin:0 0 10px}
.hrs{color:#4a5670;margin:0 0 28px}
iframe{width:100%;height:400px;border:0;border-radius:24px;background:#d9dde6}

footer{background:var(--night);color:var(--mute);padding:34px 0 40px;font-size:.92rem}
footer .wrap{display:flex;flex-wrap:wrap;justify-content:space-between;gap:12px}
footer b{color:#fff;font-family:var(--head);font-size:1.1rem}

@media(max-width:860px){
  section{padding:68px 0}
  nav{display:none}
  .hero{padding:52px 0 64px}
  .hero .wrap,.sv-head,.bk,.vs{grid-template-columns:1fr;gap:36px}
  .polewrap{order:-1}
  .pole{transform:scale(.62);transform-origin:top center;height:300px}
  .row{grid-template-columns:1fr;gap:8px}
  .pts{grid-template-columns:1fr}
  .pts div,.pts div+div{padding:26px 0;border-left:0;border-bottom:1px solid var(--line)}
  .bcard{padding:28px}
  iframe{height:300px}
  .bar .btn{display:none}
}
@media(prefers-reduced-motion:reduce){.tube{animation:none}html{scroll-behavior:auto}.btn,.row{transition:none}}
</style>
</head>
<body>

<header>
  <div class="wrap bar">
    <a class="logo" href="#top"><i aria-hidden="true"></i>Stanmore Barbers</a>
    <nav aria-label="Main">
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#book">Book</a>
      <a href="#visit">Find us</a>
    </nav>
    <a class="btn red" href="https://cal.com/manav-pancholi-tgr8qa/haircut">Book now</a>
  </div>
</header>

<main id="top">
<div class="hero">
  <div class="wrap">
    <div>
      <h1>Sharp cuts in the heart of Stanmore.</h1>
      <p>Classic haircuts, skin fades, beard shaping and hot towel shaves, done with care on Stanmore Hill.</p>
      <div class="cta">
        <a class="btn red" href="https://cal.com/manav-pancholi-tgr8qa/haircut">Book now</a>
        <a class="btn line" href="tel:+447777936575">Call</a>
        <a class="btn line" href="https://www.google.com/maps/dir/?api=1&destination=87b+Stanmore+Hill+Stanmore+HA7+3DZ" target="_blank" rel="noopener">Directions</a>
      </div>
      <div class="chips">
        <span><b>10:00 - 17:00</b> opening hours</span>
        <span><b>87b Stanmore Hill</b> HA7 3DZ</span>
      </div>
    </div>
    <div class="polewrap" aria-hidden="true">
      <div class="pole"><div class="cap top"></div><div class="tube"></div><div class="cap"></div></div>
    </div>
  </div>
</div>

<section id="services">
  <div class="wrap">
    <div class="sv-head">
      <h2>Everything from a quick tidy to a full grooming</h2>
      <div>
        <p>A comprehensive grooming experience for men of all ages, from classic cuts to modern fades.</p>
        <a class="btn navy" href="https://cal.com/manav-pancholi-tgr8qa/haircut">Book your cut</a>
      </div>
    </div>
    <div class="rows">
      <div class="row"><h3>Classic men's haircuts</h3><p>Scissor and clipper cuts in traditional techniques, neat and well finished.</p></div>
      <div class="row"><h3>Skin fades and modern styles</h3><p>Clean, smooth blends from skin fades to longer tapers.</p></div>
      <div class="row"><h3>Beard grooming and shaping</h3><p>Trims, edges and shape that suit your face.</p></div>
      <div class="row"><h3>Hot towel shaves</h3><p>A traditional close shave with a hot towel finish.</p></div>
      <div class="row"><h3>Styling and consultation</h3><p>Tell us what you want and we will advise on the best cut for you.</p></div>
    </div>
  </div>
</section>

<section id="about" class="why">
  <div class="wrap">
    <h2>A local barber you can count on</h2>
    <p class="lead">Stanmore Barbers is a local grooming destination in the heart of Stanmore. Expect a professional atmosphere focused on quality craftsmanship and customer satisfaction.</p>
    <div class="pts">
      <div><h3>Skilled craft</h3><p>Traditional technique combined with modern styles, from classic cuts to sharp fades.</p></div>
      <div><h3>Friendly service</h3><p>A welcoming shop where you can talk through exactly the look you want.</p></div>
      <div><h3>Easy to reach</h3><p>On Stanmore Hill, with Stanmore Station nearby on the Jubilee line for direct links to London.</p></div>
    </div>
  </div>
</section>

<section id="book" class="book">
  <div class="wrap bk">
    <div>
      <h2>Book your appointment</h2>
      <p class="lead">Choose a time that suits you on our booking page. It takes less than a minute.</p>
      <a class="phone" href="tel:+447777936575">+44 7777 936575</a>
    </div>
    <div class="bcard">
      <h3>Book a haircut</h3>
      <ol>
        <li>Press Book now</li>
        <li>Pick a day and time between 10:00 and 17:00</li>
        <li>Confirm your details and you are booked</li>
      </ol>
      <a class="btn red" href="https://cal.com/manav-pancholi-tgr8qa/haircut" style="width:100%">Book now</a>
    </div>
  </div>
</section>

<section id="visit" class="visit">
  <div class="wrap vs">
    <div>
      <h2>Find us</h2>
      <address>Stanmore Barbers<br>87b Stanmore Hill<br>Stanmore HA7 3DZ</address>
      <p class="hrs">Open 10:00 - 17:00</p>
      <div class="cta">
        <a class="btn navy" href="tel:+447777936575">Call</a>
        <a class="btn navy" href="https://www.google.com/maps/dir/?api=1&destination=87b+Stanmore+Hill+Stanmore+HA7+3DZ" target="_blank" rel="noopener">Directions</a>
      </div>
    </div>
    <iframe title="Map of Stanmore Barbers" loading="lazy" referrerpolicy="no-referrer-when-downgrade"
      src="https://www.google.com/maps?q=87b+Stanmore+Hill+Stanmore+HA7+3DZ&output=embed"></iframe>
  </div>
</section>
</main>

<footer>
  <div class="wrap">
    <span><b>Stanmore Barbers</b><br>87b Stanmore Hill, Stanmore HA7 3DZ</span>
    <span>+44 7777 936575<br>Open 10:00 - 17:00</span>
  </div>
</footer>

<div class="ov" id="reviewOv" role="dialog" aria-modal="true" aria-labelledby="rvTitle">
  <div class="modal">
    <div class="tick" aria-hidden="true">&#10003;</div>
    <h2 id="rvTitle">You are booked in</h2>
    <p>Thank you for booking with Stanmore Barbers. How was your booking experience? Rate us, then leave a Google review.</p>
    <div class="stars" id="stars" role="radiogroup" aria-label="Star rating"></div>
    <p class="rt" id="rt" aria-live="polite"></p>
    <button class="btn red" id="rvBtn" type="button" style="width:100%" disabled>Select a rating</button>
    <button class="later" id="rvLater" type="button">Maybe later</button>
  </div>
</div>

<script>
// Replace with your direct Google review link (Google Business Profile > "Get more reviews").
// It looks like: https://search.google.com/local/writereview?placeid=YOUR_PLACE_ID
var GOOGLE_REVIEW_URL = "https://www.google.com/maps/search/?api=1&query=Stanmore+Barbers+87b+Stanmore+Hill+Stanmore+HA7+3DZ";

(function(){
  // The review prompt only appears when Cal.com sends the customer back
  // after a completed booking (to this page with ?booked=true).
  var params = new URLSearchParams(window.location.search);
  if (params.get('booked') !== 'true') return;
  history.replaceState(null, '', window.location.pathname + window.location.hash);

  var ov = document.getElementById('reviewOv'),
      starsEl = document.getElementById('stars'),
      rt = document.getElementById('rt'),
      btn = document.getElementById('rvBtn'),
      labels = ['Poor','Fair','Good','Very good','Excellent'],
      rating = 0, i, b;

  for (i = 1; i <= 5; i++) {
    b = document.createElement('button');
    b.type = 'button';
    b.innerHTML = '&#9733;';
    b.setAttribute('role','radio');
    b.setAttribute('aria-checked','false');
    b.setAttribute('aria-label', i + (i === 1 ? ' star' : ' stars'));
    b.dataset.v = i;
    starsEl.appendChild(b);
  }
  var stars = starsEl.querySelectorAll('button');

  function paint(n){
    stars.forEach(function(s){ s.classList.toggle('on', +s.dataset.v <= n); });
  }
  stars.forEach(function(s){
    s.addEventListener('mouseenter', function(){ paint(+s.dataset.v); });
    s.addEventListener('focus', function(){ paint(+s.dataset.v); });
    s.addEventListener('click', function(){
      rating = +s.dataset.v;
      stars.forEach(function(x){ x.setAttribute('aria-checked', String(+x.dataset.v === rating)); });
      rt.textContent = labels[rating - 1];
      btn.disabled = false;
      btn.textContent = 'Leave a Google review';
      paint(rating);
    });
  });
  starsEl.addEventListener('mouseleave', function(){ paint(rating); });
  starsEl.addEventListener('focusout', function(){ paint(rating); });

  btn.addEventListener('click', function(){
    if (rating) window.location.href = GOOGLE_REVIEW_URL;
  });
  function close(){ ov.classList.remove('open'); }
  document.getElementById('rvLater').addEventListener('click', close);
  document.addEventListener('keydown', function(e){ if (e.key === 'Escape') close(); });

  ov.classList.add('open');
  stars[0].focus();
})();
</script>
</body>
</html>
