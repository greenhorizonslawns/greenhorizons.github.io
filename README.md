# greenhorizons.github.io
Lawn Care and Landscaping in Bowling Green, Ohio and Surrounding Areas
<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Green Horizons Land Care & Landscaping | Bowling Green, OH</title>
  <meta name="description" content="Budget-friendly lawn care in Bowling Green and surrounding areas. Mowing, trimming, edging, cleanups, mulch, and landscaping. Call/Text 419-601-1918 for a free quote." />
  <style>
    :root{
      --bg:#0b1220;
      --card:#111a2e;
      --text:#eaf0ff;
      --muted:#b8c2e0;
      --accent:#48d17a;
      --accent2:#31b76c;
      --border:rgba(255,255,255,.10);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      background: radial-gradient(1000px 600px at 20% 0%, rgba(72,209,122,.15), transparent 55%),
                  radial-gradient(900px 500px at 80% 10%, rgba(49,183,108,.12), transparent 60%),
                  var(--bg);
      color:var(--text);
      line-height:1.45;
    }
    a{color:inherit}
    .wrap{max-width:1100px;margin:0 auto;padding:24px}
    header{
      position:sticky; top:0; backdrop-filter: blur(10px);
      background: rgba(11,18,32,.6);
      border-bottom:1px solid var(--border);
      z-index:10;
    }
    .nav{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:10px;font-weight:800;letter-spacing:.3px}
    .logo{
      width:36px;height:36px;border-radius:12px;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      box-shadow: 0 10px 30px rgba(72,209,122,.25);
    }
    .navlinks{display:flex;gap:14px;flex-wrap:wrap}
    .navlinks a{opacity:.9;text-decoration:none;font-weight:600}
    .navlinks a:hover{opacity:1;text-decoration:underline}
    .btn{
      display:inline-flex;align-items:center;justify-content:center;
      padding:12px 16px;border-radius:14px;
      border:1px solid var(--border);
      background: rgba(255,255,255,.06);
      text-decoration:none;font-weight:700;
      cursor:pointer;
    }
    .btn.primary{
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      color:#06120b; border:0;
    }
    .btnrow{display:flex;gap:12px;flex-wrap:wrap;margin-top:18px}
    .hero{
      padding:56px 0 26px 0;
      display:grid;grid-template-columns: 1.15fr .85fr;gap:22px;align-items:center;
    }
    .kicker{color:var(--accent);font-weight:800;letter-spacing:.22em;text-transform:uppercase;font-size:12px}
    h1{margin:10px 0 10px 0;font-size:42px;line-height:1.1}
    .lead{color:var(--muted);font-size:18px;max-width:60ch}
    .card{
      background: rgba(17,26,46,.78);
      border:1px solid var(--border);
      border-radius:18px;
      padding:18px;
      box-shadow: 0 16px 50px rgba(0,0,0,.25);
    }
    .grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
    section{padding:24px 0}
    h2{margin:0 0 12px 0;font-size:26px}
    .muted{color:var(--muted)}
    .pill{
      display:inline-block;padding:8px 12px;border-radius:999px;
      border:1px solid var(--border);background: rgba(255,255,255,.05);
      margin:6px 6px 0 0;font-weight:700;font-size:13px;color:var(--muted)
    }
    .service h3{margin:0 0 6px 0}
    .service p{margin:0;color:var(--muted)}
    .checklist{margin:10px 0 0 0;padding-left:18px;color:var(--muted)}
    .checklist li{margin:6px 0}
    .gallery{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}
    .ph{
      border-radius:16px;border:1px solid var(--border);
      background: linear-gradient(135deg, rgba(255,255,255,.06), rgba(255,255,255,.02));
      aspect-ratio: 4 / 3;
      display:flex;align-items:center;justify-content:center;
      color:rgba(234,240,255,.55);font-weight:800;
    }
    form{display:grid;gap:10px}
    input, textarea{
      width:100%;
      padding:12px 14px;
      border-radius:14px;
      border:1px solid var(--border);
      background: rgba(255,255,255,.04);
      color:var(--text);
      font-size:15px;
      outline:none;
    }
    textarea{min-height:110px;resize:vertical}
    footer{padding:30px 0;color:var(--muted);border-top:1px solid var(--border);margin-top:28px}
    .split{display:grid;grid-template-columns:1fr 1fr;gap:14px}
    .small{font-size:13px}
    @media (max-width: 900px){
      .hero{grid-template-columns:1fr}
      .grid3{grid-template-columns:1fr}
      .split{grid-template-columns:1fr}
      .gallery{grid-template-columns:repeat(2,1fr)}
      h1{font-size:36px}
    }
  </style>
</head>
<body>
  <header>
    <div class="wrap nav">
      <div class="brand">
        <div class="logo" aria-hidden="true"></div>
        <div>
          Green Horizons<br><span class="small muted">Land Care & Landscaping</span>
        </div>
      </div>
      <nav class="navlinks" aria-label="Primary">
        <a href="#services">Services</a>
        <a href="#area">Service Area</a>
        <a href="#gallery">Gallery</a>
        <a href="#quote">Free Quote</a>
      </nav>
      <a class="btn primary" href="tel:+14196011918">Call / Text</a>
    </div>
  </header>

  <main class="wrap">
    <section class="hero">
      <div>
        <div class="kicker">BUDGET-FRIENDLY • FAST • RELIABLE</div>
        <h1>Affordable lawn care<br>that still looks sharp.</h1>
        <p class="lead">
          Green Horizons provides budget-friendly mowing and landscaping in Bowling Green and surrounding areas.
          Simple scheduling, quick communication, and a clean finish — without overpaying.
        </p>
        <div class="btnrow">
          <a class="btn primary" href="#quote">Get a Free Quote</a>
          <a class="btn" href="sms:+14196011918">Text Us</a>
          <a class="btn" href="#services">View Services</a>
        </div>
        <ul class="checklist">
          <li>Fair prices + dependable service</li>
          <li>Trimming & edging every visit</li>
          <li>Easy quote: call/text or email</li>
        </ul>
      </div>

      <div class="card">
        <h2 style="margin-top:0">Quick Info</h2>
        <p><strong>Phone/Text:</strong> <a href="tel:+14196011918">419-601-1918</a></p>
        <p><strong>Email:</strong> <a href="mailto:Greenhorizonslawns@gmail.com">Greenhorizonslawns@gmail.com</a></p>
        <p><strong>Service Area:</strong> Bowling Green + surrounding areas</p>
        <p><strong>Hours:</strong> Mon–Sat • 8am–6pm</p>
        <div>
          <span class="pill">Free estimates</span>
          <span class="pill">Budget-friendly</span>
          <span class="pill">Quick scheduling</span>
        </div>
      </div>
    </section>

    <section id="services">
      <h2>Services</h2>
      <p class="muted">Most requested services — easy, affordable, and done right.</p>
      <div class="grid3">
        <div class="card service">
          <h3>Mowing</h3>
          <p>Weekly or biweekly mowing with a clean, consistent cut.</p>
        </div>
        <div class="card service">
          <h3>Trimming & Edging</h3>
          <p>Crisp edges + trimming around fences, beds, and obstacles.</p>
        </div>
        <div class="card service">
          <h3>Cleanups</h3>
          <p>Spring/fall cleanups, leaf removal, and debris hauling.</p>
        </div>
        <div class="card service">
          <h3>Mulch & Beds</h3>
          <p>Mulch installs, bed weeding, and bed edge touchups.</p>
        </div>
        <div class="card service">
          <h3>Shrub Trimming</h3>
          <p>Seasonal trimming to keep things tidy and healthy.</p>
        </div>
        <div class="card service">
          <h3>Small Landscaping</h3>
          <p>Simple upgrades that boost curb appeal on a budget.</p>
        </div>
      </div>
    </section>

    <section id="area">
      <div class="card">
        <h2 style="margin-top:0">Service Area</h2>
        <p class="muted" style="margin:0">
          Serving Bowling Green and surrounding areas. If you’re nearby, reach out — we’ll let you know if we can fit you in.
        </p>
        <div style="margin-top:10px">
          <span class="pill">Bowling Green</span>
          <span class="pill">Surrounding Areas</span>
        </div>
      </div>
    </section>

    <section id="gallery">
      <h2>Recent Work</h2>
      <p class="muted">Add your photos here (before/after shots work best).</p>
      <div class="gallery">
        <div class="ph">Before/After</div>
        <div class="ph">Mowing</div>
        <div class="ph">Cleanup</div>
        <div class="ph">Mulch</div>
      </div>
    </section>

    <section id="quote">
      <div class="split">
        <div class="card">
          <h2 style="margin-top:0">Get a Free Quote</h2>
          <p class="muted" style="margin-top:0">
            Fastest way: call/text <strong>419-601-1918</strong>.  
            Or email us at <strong>Greenhorizonslawns@gmail.com</strong>.
          </p>

          <form action="mailto:Greenhorizonslawns@gmail.com" method="post" enctype="text/plain">
            <input name="Name" placeholder="Your name" required />
            <input name="Phone" placeholder="Phone number" required />
            <input name="Address" placeholder="Service address" />
            <textarea name="Details" placeholder="What do you need? (mowing, cleanup, mulch, etc.)"></textarea>
            <button class="btn primary" type="submit">Request Quote</button>
          </form>

          <p class="muted small" style="margin:10px 0 0 0">
            Want a form that works everywhere (no email app needed)? I can swap this to a hosted form in 2 minutes.
          </p>
        </div>

        <div class="card">
          <h2 style="margin-top:0">What “Budget-Friendly” Means</h2>
          <ul class="checklist">
            <li>No upsell pressure — you choose what you want done</li>
            <li>Fair pricing with consistent quality</li>
            <li>Simple scheduling and fast responses</li>
            <li>We show up and finish the job</li>
          </ul>
          <div style="margin-top:16px">
            <a class="btn primary" href="tel:+14196011918">Call Now</a>
            <a class="btn" href="sms:+14196011918" style="margin-left:10px">Text Now</a>
          </div>
        </div>
      </div>
    </section>

    <footer>
      <div class="split">
        <div>
          <strong style="color:var(--text)">Green Horizons Land Care & Landscaping</strong><br>
          <span class="small">© <span id="year"></span> • Bowling Green, OH</span>
        </div>
        <div class="small">
          <div><strong>Phone/Text:</strong> <a href="tel:+14196011918">419-601-1918</a></div>
          <div><strong>Email:</strong> <a href="mailto:Greenhorizonslawns@gmail.com">Greenhorizonslawns@gmail.com</a></div>
          <div><strong>Service Area:</strong> Bowling Green + surrounding areas</div>
        </div>
      </div>
    </footer>
  </main>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
