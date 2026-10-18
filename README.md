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
.bk{display:grid;grid-template-columns:1fr 1.35fr;gap:56px;align-items:start}
.bk .lead{color:#4a5670;max-width:38ch}
.phone{display:inline-block;margin-top:14px;font:800 1.6rem var(--head);text-decoration:none;border-bottom:3px solid var(--red)}
form{background:var(--navy);color:#fff;border-radius:24px;padding:36px;display:grid;grid-template-columns:1fr 1fr;gap:20px;box-shadow:0 40px 80px -30px rgba(11,20,39,.55)}
.full{grid-column:1/-1}
label,.lbl{display:block;font-weight:600;font-size:.9rem;margin-bottom:8px;color:#d6dcea}
input,select,textarea{width:100%;padding:14px 16px;font:inherit;color:#fff;background:rgba(255,255,255,.07);border:1.5px solid rgba(255,255,255,.2);border-radius:12px}
select option{color:#16213a}
input::placeholder,textarea::placeholder{color:#7f8ba2}
input:focus,select:focus,textarea:focus{outline:none;border-color:#fff;background:rgba(255,255,255,.12)}
input[type=date]{color-scheme:dark}
textarea{resize:vertical;min-height:88px}
.slots{display:grid;grid-template-columns:repeat(auto-fill,minmax(76px,1fr));gap:8px}
.slots label{margin:0}
.slots input{position:absolute;opacity:0;width:1px;height:1px}
.slots span{display:block;text-align:center;padding:10px 0;border-radius:10px;border:1.5px solid rgba(255,255,255,.2);font-weight:500;font-size:.92rem;cursor:pointer;color:#fff;transition:background .15s}
.slots span:hover{background:rgba(255,255,255,.12)}
.slots input:checked+span{background:var(--red);border-color:var(--red)}
.slots input:focus-visible+span{outline:3px solid #fff;outline-offset:2px}
.note{font-size:.86rem;color:var(--mute);margin:12px 0 0;text-align:center}

/* visit */
.visit{background:var(--white)}
.vs{display:grid;grid-template-columns:1fr 1.3fr;gap:56px;align-items:center}
address{font-style:normal;font:500 1.25rem/1.6 var(--head);margin:0 0 10px}
.hrs{color:#4a5670;margin:0 0 28px}
iframe{width:100%;height:400px;border:0;border-radius:24px;background:#d9dde6}

footer{background:var(--night);color:var(--mute);padding:34px 0 40px;font-size:.92rem}
footer .wrap{display:flex;flex-wrap:wrap;justify-content:space-between;gap:12px}
footer b{color:#fff;font-family:var(--head);font-size:1.1rem}

/* mobile action bar */
.mbar{display:none}
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
  form{grid-template-columns:1fr;padding:26px}
  iframe{height:300px}
  .bar .btn{display:none}
  body{padding-bottom:76px}
  .mbar{display:grid;grid-template-columns:1fr 1fr;gap:10px;position:fixed;left:0;right:0;bottom:0;z-index:30;padding:12px 16px calc(12px + env(safe-area-inset-bottom,0px));background:rgba(11,20,39,.95);border-top:1px solid var(--line)}
  .mbar .btn{padding:13px 10px}
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
    <a class="btn red" href="#book">Book now</a>
  </div>
</header>

<main id="top">
<div class="hero">
  <div class="wrap">
    <div>
      <h1>Sharp cuts in the heart of Stanmore.</h1>
      <p>Classic haircuts, skin fades, beard shaping and hot towel shaves, done with care on Stanmore Hill.</p>
      <div class="cta">
        <a class="btn red" href="#book">Book now</a>
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
        <a class="btn navy" href="#book">Book your cut</a>
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
      <p class="lead">Pick a service, a day and a time between 10:00 and 17:00. Your booking opens in Gmail ready to send, and we will confirm with you.</p>
      <a class="phone" href="tel:+447777936575">+44 7777 936575</a>
    </div>
    <form id="bookingForm">
      <div>
        <label for="name">Your name</label>
        <input id="name" name="name" required autocomplete="name" placeholder="Full name">
      </div>
      <div>
        <label for="phone">Phone number</label>
        <input id="phone" name="phone" type="tel" required autocomplete="tel" placeholder="07...">
      </div>
      <div>
        <label for="service">Service</label>
        <select id="service" name="service" required>
          <option value="">Choose a service</option>
          <option>Classic men's haircut</option>
          <option>Skin fade</option>
          <option>Beard grooming and shaping</option>
          <option>Hot towel shave</option>
          <option>Haircut and beard</option>
          <option>Styling and consultation</option>
        </select>
      </div>
      <div>
        <label for="date">Date</label>
        <input id="date" name="date" type="date" required>
      </div>
      <div class="full">
        <span class="lbl" id="tl">Time</span>
        <div class="slots" id="slots" role="radiogroup" aria-labelledby="tl"></div>
      </div>
      <div class="full">
        <label for="notes">Notes (optional)</label>
        <textarea id="notes" name="notes" placeholder="Anything we should know?"></textarea>
      </div>
      <div class="full">
        <button class="btn red" type="submit" style="width:100%">Book now</button>
        <p class="note">Opens Gmail with your booking. Press Send there to finish.</p>
      </div>
    </form>
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

<div class="mbar">
  <a class="btn line" href="tel:+447777936575">Call</a>
  <a class="btn red" href="#book">Book now</a>
</div>

<script>
// Bookings are sent to this Gmail address.
var BOOKING_EMAIL = "ukmanavpancholi@gmail.com";

(function(){
  var slots = document.getElementById('slots'), html = '', first = true;
  for (var h = 10; h < 17; h++) {
    ['00','30'].forEach(function(m){
      var t = (h < 10 ? '0' : '') + h + ':' + m;
      html += '<label><input type="radio" name="time" value="' + t + '"' + (first ? ' required' : '') + '><span>' + t + '</span></label>';
      first = false;
    });
  }
  slots.innerHTML = html;
  document.getElementById('date').min = new Date().toISOString().split('T')[0];

  document.getElementById('bookingForm').addEventListener('submit', function(e){
    e.preventDefault();
    var f = e.target;
    var time = f.querySelector('input[name=time]:checked').value;
    var d = new Date(f.date.value + 'T00:00:00');
    var pretty = d.toLocaleDateString('en-GB', {weekday:'long', day:'numeric', month:'long', year:'numeric'});
    var subject = 'Booking request: ' + f.service.value + ' on ' + pretty + ' at ' + time;
    var body = 'Hello Stanmore Barbers,\n\nI would like to book an appointment.\n\n' +
      'Name: ' + f.name.value + '\n' +
      'Phone: ' + f.phone.value + '\n' +
      'Service: ' + f.service.value + '\n' +
      'Date: ' + pretty + '\n' +
      'Time: ' + time + '\n' +
      (f.notes.value ? 'Notes: ' + f.notes.value + '\n' : '') +
      '\nThank you.';
    var url = 'https://mail.google.com/mail/?view=cm&fs=1&to=' + encodeURIComponent(BOOKING_EMAIL) +
      '&su=' + encodeURIComponent(subject) + '&body=' + encodeURIComponent(body);
    window.open(url, '_blank', 'noopener');
  });
})();
</script>
</body>
</html>
