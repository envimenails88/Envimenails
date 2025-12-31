<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Envi Me Nails | DFW & Shreveport Nail Tech</title>
  <meta name="description" content="Envi Me Nails — nail services in DFW, TX and Shreveport, LA. Book now for clean, luxe sets and flawless finishes." />
  <meta name="theme-color" content="#F3EEE8" />

  <style>
    :root{
      --cream:#F7F1EA;
      --nude:#E7D6C7;
      --nude2:#D9BFAE;
      --ink:#1F1A17;
      --muted:#6B5F58;
      --card:#FFFFFF;
      --border:rgba(31,26,23,.12);
      --shadow: 0 10px 30px rgba(31,26,23,.08);
      --radius:18px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Apple Color Emoji","Segoe UI Emoji";
      color:var(--ink);
      background:
        radial-gradient(1200px 600px at 10% 0%, var(--cream), transparent 55%),
        radial-gradient(900px 500px at 90% 10%, var(--nude), transparent 60%),
        linear-gradient(180deg, #fff, var(--cream));
    }
    a{color:inherit; text-decoration:none}
    .wrap{max-width:1120px; margin:0 auto; padding:24px}
    header{
      position:sticky; top:0; z-index:50;
      background:rgba(247,241,234,.75);
      backdrop-filter: blur(10px);
      border-bottom:1px solid var(--border);
    }
    .nav{
      display:flex; align-items:center; justify-content:space-between;
      gap:14px;
    }
    .brand{
      display:flex; align-items:center; gap:10px;
      font-weight:700; letter-spacing:.3px;
    }
    .logo{
      width:38px; height:38px; border-radius:14px;
      background: linear-gradient(145deg, var(--nude), var(--cream));
      border:1px solid var(--border);
      box-shadow: var(--shadow);
      display:grid; place-items:center;
      font-weight:800;
    }
    .links{display:flex; gap:16px; flex-wrap:wrap}
    .links a{font-size:14px; color:var(--muted)}
    .links a:hover{color:var(--ink)}
    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      gap:10px;
      padding:12px 16px;
      border-radius:999px;
      border:1px solid var(--border);
      background: rgba(255,255,255,.75);
      box-shadow: 0 8px 18px rgba(31,26,23,.08);
      font-weight:600;
      cursor:pointer;
    }
    .btn.primary{
      background: linear-gradient(145deg, var(--nude2), var(--nude));
      border:1px solid rgba(31,26,23,.14);
    }
    .btn:hover{transform: translateY(-1px)}
    .hero{
      padding:52px 0 26px;
      display:grid;
      grid-template-columns: 1.2fr .8fr;
      gap:22px;
      align-items:stretch;
    }
    .hero-card{
      background:rgba(255,255,255,.72);
      border:1px solid var(--border);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding:28px;
    }
    h1{margin:0 0 10px; font-size:44px; line-height:1.05}
    .sub{margin:0 0 18px; color:var(--muted); font-size:16px; line-height:1.6}
    .pill-row{display:flex; gap:10px; flex-wrap:wrap; margin:14px 0 20px}
    .pill{
      font-size:13px; color:var(--ink);
      padding:8px 12px;
      border-radius:999px;
      border:1px solid var(--border);
      background:rgba(247,241,234,.7);
    }
    .cta-row{display:flex; gap:12px; flex-wrap:wrap; align-items:center}
    .small{font-size:13px; color:var(--muted)}
    .aside{
      display:grid; gap:14px;
    }
    .mini{
      background:rgba(255,255,255,.72);
      border:1px solid var(--border);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding:18px;
    }
    .mini h3{margin:0 0 8px; font-size:16px}
    .mini p{margin:0; color:var(--muted); font-size:14px; line-height:1.6}
    .grid{
      display:grid;
      grid-template-columns: repeat(12, 1fr);
      gap:14px;
      margin:26px 0 40px;
    }
    .card{
      grid-column: span 6;
      background:rgba(255,255,255,.78);
      border:1px solid var(--border);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding:20px;
    }
    .card h2{margin:0 0 10px; font-size:20px}
    .list{margin:0; padding-left:18px; color:var(--muted); line-height:1.75}
    .gallery{
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap:12px;
      margin-top:10px;
    }
    .ph{
      border-radius:16px;
      border:1px dashed rgba(31,26,23,.20);
      background:
        linear-gradient(135deg, rgba(231,214,199,.55), rgba(247,241,234,.75));
      height:140px;
      display:grid; place-items:center;
      color:rgba(31,26,23,.55);
      font-weight:600;
      font-size:14px;
    }
    form{display:grid; gap:10px; margin-top:10px}
    input, textarea{
      width:100%;
      padding:12px 12px;
      border-radius:14px;
      border:1px solid var(--border);
      background:rgba(255,255,255,.85);
      font:inherit;
      outline:none;
    }
    textarea{min-height:110px; resize:vertical}
    footer{
      border-top:1px solid var(--border);
      padding:24px 0 40px;
      color:var(--muted);
      font-size:13px;
    }
    .<div class="card" id="gallery">
  <h2>Our Work</h2>
  <div class="small">Soft glam • Florals • Custom luxury sets</div>

  <div class="gallery">
    <img src="images/nails1.jpg" alt="Envi Me Nails pink floral set">
    <img src="images/nails2.jpg" alt="Envi Me Nails French tip floral nails">
    <img src="images/nails3.jpg" alt="Envi Me Nails pedicure floral design">
    <img src="images/nails4.jpg" alt="Envi Me Nails pink gold stiletto nails">
    <img src="images/nails5.jpg" alt="Envi Me Nails teal pink freestyle nails">
    <img src="images/nails6.jpg" alt="Envi Me Nails short pink floral nails">
    <img src="images/nails7.jpg" alt="Envi Me Nails long rhinestone pink nails">
    <img src="images/nails8.jpg" alt="Envi Me Nails luxury gold floral nails">
    <img src="images/nails9.jpg" alt="Envi Me Nails sculpted floral nails">
  </div>
</div>-row{display:flex; gap:10px; justify-content:space-between; flex-wrap:wrap}
    .kicker{font-size:12px; letter-spacing:.18em; text-transform:uppercase; color:rgba(31,26,23,.55)}
    @media (max-width: 900px){
      .hero{grid-template-columns:1fr; padding-top:30px}
      h1{font-size:38px}
      .card{grid-column: span 12}
      .gallery{grid-template-columns: repeat(2, 1fr)}
    }
    @media (max-width: 520px){
      h1{font-size:34px}
      .gallery{grid-template-columns:1fr}
      .links{display:none}
    }
  </style>
</head>

<body>
  <header>
    <div class="wrap nav">
      <div class="brand">
        <div class="logo">EM</div>
        <div>
          <div style="line-height:1.05">Envi Me Nails</div>
          <div class="small">DFW, TX • Shreveport, LA</div>
        </div>
      </div>

      <nav class="links" aria-label="Primary">
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#booking">Book</a>
        <a href="#contact">Contact</a>
      </nav>

      <a class="btn primary" href="#booking">Book Now</a>
    </div>
  </header>

  <main class="wrap">
    <section class="hero" id="top">
      <div class="hero-card">
        <div class="kicker">Clean • Luxe • Confident</div>
        <h1>Nails that match your energy.</h1>
        <p class="sub">
          Serving <strong>DFW</strong> and <strong>Shreveport</strong> with soft glam sets, detailed finishes, and a professional experience from start to shine.
        </p>

        <div class="pill-row">
          <div class="pill">DFW & Shreveport Service Area</div>
          <div class="pill">Appointments Only</div>
          <div class="pill">Text to Book: <strong>945-283-5471</strong></div>
        </div>

        <div class="cta-row">
          <a class="btn primary" href="#booking">Book Now</a>
          <a class="btn" href="tel:+19452835471">Call</a>
          <a class="btn" href="sms:+19452835471?&body=Hi%20Envi%20Me%20Nails!%20I%E2%80%99d%20like%20to%20book%20an%20appointment.%20My%20name%20is%20_____%20and%20I%E2%80%99m%20in%20(DFW%20or%20Shreveport).%20I%E2%80%99m%20looking%20for%20_____." aria-label="Text to book">Text</a>
        </div>

        <p class="small" style="margin-top:14px">
          Email: <a href="mailto:envimenails88@icloud.com"><strong>envimenails88@icloud.com</strong></a>
        </p>
      </div>

      <div class="aside">
        <div class="mini">
          <h3>What you’ll get</h3>
          <p>Sanitized tools, attention to detail, and a set that lasts — designed to fit your vibe and your schedule.</p>
        </div>
        <div class="mini">
          <h3>Best for</h3>
          <p>Birthdays, weddings, vacations, photo shoots, or just because you deserve it.</p>
        </div>
        <div class="mini">
          <h3>Booking fast</h3>
          <p>Tap <strong>Book Now</strong> and send your preferred date/time + service. You’ll get confirmation ASAP.</p>
        </div>
      </div>
    </section>

    <section class="grid" id="services">
      <div class="card">
        <h2>Services</h2>
        <ul class="list">
          <li>Full Sets (Short/Medium/Long)</li>
          <li>Fill-Ins</li>
          <li>Gel Manicures</li>
          <li>Freestyle / Nail Art</li>
          <li>Soak-Off / Repairs</li>
        </ul>
        <p class="small" style="margin-top:10px">
          *Add your exact pricing anytime — I can plug it in cleanly.
        </p>
      </div>

      <div class="card" id="gallery">
        <h2>Gallery</h2>
        <div class="small">Drop your photos in here later (I’ll show you how below).</div>
        <div class="gallery" aria-label="Gallery placeholders">
          <div class="ph">Photo 1</div>
          <div class="ph">Photo 2</div>
          <div class="ph">Photo 3</div>
          <div class="ph">Photo 4</div>
          <div class="ph">Photo 5</div>
          <div class="ph">Photo 6</div>
        </div>
      </div>

      <div class="card" id="booking">
        <h2>Book Now</h2>
        <p class="sub" style="margin:0 0 10px">
          Send your info and I’ll confirm your appointment.
        </p>

        <!-- This form opens an email draft (works great for free hosting) -->
        <form onsubmit="return openEmailDraft(event)">
          <input id="name" name="name" placeholder="Your name" required />
          <input id="city" name="city" placeholder="DFW or Shreveport?" required />
          <input id="service" name="service" placeholder="Service you want (e.g., Full Set + Design)" required />
          <input id="date" name="date" placeholder="Preferred date/time" required />
          <textarea id="notes" name="notes" placeholder="Any notes (shape, length, inspiration, etc.)"></textarea>
          <button class="btn primary" type="submit">Send Booking Request</button>
          <div class="small">Or text: <strong>945-283-5471</strong></div>
        </form>
      </div>
      <div>© <span id="year"></span> Envi Me Nails • Luxury Nail Art</div>
<div class="small">
  <a href="https://instagram.com/envy_me_nails" target="_blank">Instagram</a> • 
  <a href="https://square.site/book/0XTW7BTYJ84D9/envymenails-shreveport-no" target="_blank">Book Now</a>
</div>

      <div class="card" id="contact">
        <h2>Contact</h2>
        <ul class="list">
          <li><strong>Phone:</strong> <a href="tel:+19452835471">945-283-5471</a></li>
          <li><strong>Email:</strong> <a href="mailto:envimenails88@icloud.com">envimenails88@icloud.com</a></li>
          <li><strong>Service Area:</strong> DFW, Texas & Shreveport, Louisiana</li>
        </ul>
        <.gallery img{
  width:100%;
  height:100%;
  object-fit:cover;
  border-radius:16px;
  border:1px solid rgba(31,26,23,.12);
  box-shadow: 0 10px 20px rgba(31,26,23,.08);
}
         <a class="btn primary" href="https://square.site/book/0XTW7BTYJ84D9/envymenails-shreveport-no" target="_blank">Book Now</a>
