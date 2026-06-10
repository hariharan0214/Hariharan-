<!DOCTYPE html>
<html lang="ta">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Find the best lawyers in Tirunelveli. Experienced civil and criminal lawyers near you. Book a free consultation today." />
  <meta name="keywords" content="best lawyers in Tirunelveli, civil lawyer Tirunelveli, criminal lawyer Tirunelveli, advocate Tirunelveli" />
  <meta name="author" content="TN Legal Directory" />
  <title>Best Lawyers in Tirunelveli | Civil &amp; Criminal Advocates</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet" />

  <style>
    /* ============================================================
       RESET & VARIABLES
    ============================================================ */
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --navy:     #0A1F44;
      --navy2:    #122958;
      --gold:     #C9A13B;
      --gold2:    #E8C46A;
      --white:    #FFFFFF;
      --offwhite: #F7F8FC;
      --text:     #1A1A2E;
      --muted:    #6B7280;
      --border:   #E5E7EB;
      --card-shadow: 0 4px 24px rgba(10,31,68,.10);
      --radius:   14px;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'Inter', sans-serif;
      color: var(--text);
      background: var(--white);
      line-height: 1.6;
      overflow-x: hidden;
    }

    .container { max-width: 1100px; margin: 0 auto; padding: 0 20px; }
    .hidden { display: none !important; }
    .section { padding: 72px 0; }

    /* ============================================================
       HEADER
    ============================================================ */
    .site-header {
      position: sticky; top: 0; z-index: 100;
      background: var(--navy);
      box-shadow: 0 2px 12px rgba(0,0,0,.25);
    }
    .header-inner {
      display: flex; align-items: center; justify-content: space-between;
      padding: 14px 20px;
    }
    .logo { display: flex; align-items: center; gap: 10px; text-decoration: none; }
    .logo-icon { font-size: 26px; }
    .logo-main { display: block; font-family: 'Playfair Display', serif; font-size: 20px; color: var(--gold); font-weight: 800; line-height: 1.1; }
    .logo-sub  { display: block; font-size: 10px; color: rgba(255,255,255,.5); letter-spacing: .5px; text-transform: uppercase; }
    .nav-links { display: flex; gap: 28px; }
    .nav-links a { color: rgba(255,255,255,.8); text-decoration: none; font-size: 14px; font-weight: 500; transition: color .2s; }
    .nav-links a:hover { color: var(--gold); }

    /* ============================================================
       HERO
    ============================================================ */
    .hero {
      position: relative;
      background: var(--navy);
      color: var(--white);
      padding: 80px 0 72px;
      overflow: hidden;
    }
    .hero-bg {
      position: absolute; inset: 0; pointer-events: none;
      background-image:
        radial-gradient(circle at 80% 20%, rgba(201,161,59,.13) 0%, transparent 55%),
        radial-gradient(circle at 10% 80%, rgba(201,161,59,.08) 0%, transparent 45%);
    }
    .hero-content { position: relative; z-index: 1; text-align: center; }
    .hero-badge {
      display: inline-block; margin-bottom: 20px;
      background: rgba(201,161,59,.15); border: 1px solid rgba(201,161,59,.35);
      color: var(--gold2); font-size: 12px; font-weight: 600; letter-spacing: .8px;
      padding: 6px 16px; border-radius: 20px; text-transform: uppercase;
    }
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2.4rem, 6vw, 4rem);
      font-weight: 800; line-height: 1.1; margin-bottom: 18px;
    }
    .hero h1 .gold { color: var(--gold); }
    .hero-sub { font-size: 17px; color: rgba(255,255,255,.72); margin-bottom: 36px; }

    /* Search Bar */
    .search-bar {
      display: flex; gap: 10px; max-width: 640px; margin: 0 auto 40px;
      background: rgba(255,255,255,.08); border: 1px solid rgba(255,255,255,.15);
      border-radius: 50px; padding: 6px 6px 6px 14px;
      backdrop-filter: blur(6px);
    }
    .search-bar select, .search-bar input {
      background: transparent; border: none; outline: none;
      color: var(--white); font-size: 14px; font-family: 'Inter', sans-serif;
    }
    .search-bar select { color: rgba(255,255,255,.75); cursor: pointer; padding: 0 8px; }
    .search-bar select option { background: var(--navy2); color: var(--white); }
    .search-bar input { flex: 1; padding: 6px 0; }
    .search-bar input::placeholder { color: rgba(255,255,255,.45); }
    .search-bar button {
      background: var(--gold); color: var(--navy); font-weight: 700;
      border: none; padding: 10px 24px; border-radius: 40px; cursor: pointer;
      font-size: 14px; transition: background .2s, transform .15s; white-space: nowrap;
    }
    .search-bar button:hover { background: var(--gold2); transform: scale(1.04); }

    /* Hero Stats */
    .hero-stats { display: flex; justify-content: center; align-items: center; gap: 28px; flex-wrap: wrap; }
    .stat { display: flex; flex-direction: column; align-items: center; }
    .stat-num { font-family: 'Playfair Display', serif; font-size: 26px; color: var(--gold); font-weight: 800; line-height: 1; }
    .stat-label { font-size: 12px; color: rgba(255,255,255,.6); margin-top: 2px; }
    .stat-div { width: 1px; height: 36px; background: rgba(255,255,255,.2); }

    /* ============================================================
       FILTER CHIPS
    ============================================================ */
    .filter-section {
      display: flex; align-items: center; gap: 10px; flex-wrap: wrap;
      padding: 18px 20px; border-bottom: 1px solid var(--border);
      max-width: 1100px; margin: 0 auto;
    }
    .filter-label { font-size: 13px; color: var(--muted); font-weight: 600; margin-right: 4px; }
    .chip {
      background: var(--offwhite); border: 1px solid var(--border);
      color: var(--text); padding: 7px 16px; border-radius: 24px;
      font-size: 13px; font-weight: 500; cursor: pointer; transition: all .2s;
    }
    .chip:hover, .chip.active { background: var(--navy); color: var(--white); border-color: var(--navy); }

    /* ============================================================
       SECTION TITLES
    ============================================================ */
    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.6rem, 3.5vw, 2.1rem);
      font-weight: 800; color: var(--navy);
      margin-bottom: 8px; text-align: center;
    }
    .section-title.left { text-align: left; }
    .section-sub { text-align: center; color: var(--muted); font-size: 15px; margin-bottom: 44px; }

    /* ============================================================
       LAWYERS GRID
    ============================================================ */
    .lawyers-section { background: var(--offwhite); }
    .lawyers-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 24px;
    }
    .no-results { text-align: center; color: var(--muted); font-size: 16px; padding: 40px 0; }

    /* ============================================================
       LAWYER CARD
    ============================================================ */
    .lawyer-card {
      background: var(--white); border-radius: var(--radius);
      box-shadow: var(--card-shadow); border: 1px solid var(--border);
      overflow: hidden; transition: transform .25s, box-shadow .25s;
      display: flex; flex-direction: column;
    }
    .lawyer-card:hover { transform: translateY(-6px); box-shadow: 0 12px 36px rgba(10,31,68,.15); }

    .card-header {
      background: linear-gradient(135deg, var(--navy) 0%, var(--navy2) 100%);
      padding: 22px 20px 18px; display: flex; align-items: center; gap: 14px;
      position: relative;
    }
    .card-header::after {
      content: ''; position: absolute; bottom: 0; left: 0; right: 0; height: 2px;
      background: linear-gradient(90deg, var(--gold), var(--gold2));
    }
    .avatar {
      width: 56px; height: 56px; border-radius: 50%;
      background: rgba(201,161,59,.2); border: 2px solid var(--gold);
      display: flex; align-items: center; justify-content: center;
      font-size: 24px; flex-shrink: 0;
    }
    .card-name { font-family: 'Playfair Display', serif; font-size: 17px; font-weight: 700; color: var(--white); line-height: 1.2; }
    .card-location { font-size: 12px; color: rgba(255,255,255,.6); margin-top: 3px; }
    .badge-spec {
      position: absolute; top: 14px; right: 14px;
      font-size: 10px; font-weight: 700; letter-spacing: .6px; text-transform: uppercase;
      padding: 4px 10px; border-radius: 20px;
    }
    .badge-civil     { background: rgba(22,163,74,.2);   color: #4ADE80; border: 1px solid rgba(74,222,128,.3); }
    .badge-criminal  { background: rgba(239,68,68,.15);  color: #FCA5A5; border: 1px solid rgba(252,165,165,.3); }
    .badge-both      { background: rgba(201,161,59,.2);  color: var(--gold2); border: 1px solid rgba(201,161,59,.3); }

    .card-body { padding: 18px 20px 10px; flex: 1; }
    .card-meta { display: flex; gap: 20px; flex-wrap: wrap; margin-bottom: 14px; }
    .meta-item { display: flex; flex-direction: column; }
    .meta-label { font-size: 10px; color: var(--muted); text-transform: uppercase; letter-spacing: .5px; font-weight: 600; }
    .meta-value { font-size: 15px; font-weight: 600; color: var(--navy); }

    .success-bar-wrap { margin-bottom: 14px; }
    .success-bar-label { display: flex; justify-content: space-between; font-size: 12px; margin-bottom: 5px; }
    .success-bar-label span:first-child { color: var(--muted); }
    .success-bar-label span:last-child  { font-weight: 700; color: var(--navy); }
    .success-bar { height: 6px; background: var(--border); border-radius: 4px; overflow: hidden; }
    .success-bar-fill { height: 100%; background: linear-gradient(90deg, var(--gold), var(--gold2)); border-radius: 4px; width: 0%; transition: width 1.2s ease; }

    .stars { color: var(--gold); font-size: 14px; margin-bottom: 8px; }
    .card-tags { display: flex; gap: 6px; flex-wrap: wrap; margin-bottom: 16px; }
    .tag { background: var(--offwhite); border: 1px solid var(--border); color: var(--muted); font-size: 11px; padding: 3px 10px; border-radius: 12px; }

    .card-footer { padding: 0 20px 20px; display: flex; gap: 10px; }
    .btn-call {
      flex: 1; background: var(--navy); color: var(--white);
      border: none; padding: 13px 10px; border-radius: 10px;
      font-size: 14px; font-weight: 700; cursor: pointer;
      display: flex; align-items: center; justify-content: center; gap: 8px;
      transition: background .2s, transform .15s;
    }
    .btn-call:hover { background: var(--navy2); transform: scale(1.03); }
    .btn-wa {
      background: #25D366; color: var(--white);
      border: none; padding: 13px 14px; border-radius: 10px;
      font-size: 18px; cursor: pointer; transition: background .2s;
    }
    .btn-wa:hover { background: #1EA952; }

    /* ============================================================
       HOW IT WORKS
    ============================================================ */
    .how-section { background: var(--white); }
    .steps-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 24px; margin-top: 16px; }
    .step-card {
      background: var(--offwhite); border: 1px solid var(--border);
      border-radius: var(--radius); padding: 32px 24px; text-align: center;
      position: relative; transition: box-shadow .2s;
    }
    .step-card:hover { box-shadow: var(--card-shadow); }
    .step-num {
      position: absolute; top: 14px; left: 18px;
      font-family: 'Playfair Display', serif; font-size: 36px; font-weight: 800;
      color: rgba(10,31,68,.06); line-height: 1;
    }
    .step-icon { font-size: 36px; margin-bottom: 14px; }
    .step-card h3 { font-size: 17px; font-weight: 700; color: var(--navy); margin-bottom: 8px; }
    .step-card p  { font-size: 14px; color: var(--muted); }

    /* ============================================================
       CONTACT
    ============================================================ */
    .contact-section { background: var(--navy); color: var(--white); }
    .contact-section .section-title { color: var(--white); }
    .contact-section p { color: rgba(255,255,255,.72); margin-bottom: 18px; }
    .contact-inner { display: grid; grid-template-columns: 1fr 1fr; gap: 60px; align-items: center; }
    .contact-list { list-style: none; display: flex; flex-direction: column; gap: 10px; }
    .contact-list li { font-size: 15px; color: rgba(255,255,255,.8); }
    .contact-form-box {
      background: rgba(255,255,255,.07); border: 1px solid rgba(255,255,255,.12);
      border-radius: var(--radius); padding: 30px 24px;
    }
    .contact-form-box h3 { font-family: 'Playfair Display', serif; font-size: 20px; color: var(--gold); margin-bottom: 18px; }

    /* ============================================================
       FORM INPUTS & BUTTONS
    ============================================================ */
    .form-input {
      width: 100%; padding: 11px 14px; border-radius: 9px;
      border: 1px solid var(--border); background: var(--white);
      font-family: 'Inter', sans-serif; font-size: 14px; color: var(--text);
      margin-bottom: 12px; outline: none; transition: border-color .2s;
      resize: vertical; display: block;
    }
    .form-input:focus { border-color: var(--gold); box-shadow: 0 0 0 3px rgba(201,161,59,.15); }
    .form-input.error { border-color: #EF4444; }

    .btn-primary {
      background: linear-gradient(135deg, var(--gold), var(--gold2));
      color: var(--navy); font-weight: 700; border: none;
      padding: 13px 24px; border-radius: 10px; cursor: pointer;
      font-size: 15px; transition: opacity .2s, transform .15s;
      font-family: 'Inter', sans-serif; width: 100%; text-align: center;
      display: block; text-decoration: none;
    }
    .btn-primary:hover { opacity: .9; transform: scale(1.02); }

    /* ============================================================
       WHATSAPP STICKY
    ============================================================ */
    .wa-sticky {
      position: fixed; bottom: 28px; right: 28px; z-index: 99;
      width: 54px; height: 54px; background: #25D366; color: var(--white);
      border-radius: 50%; display: flex; align-items: center; justify-content: center;
      box-shadow: 0 4px 20px rgba(37,211,102,.5); text-decoration: none;
      transition: transform .2s; font-size: 26px;
    }
    .wa-sticky:hover { transform: scale(1.12); }

    /* ============================================================
       MODAL
    ============================================================ */
    .modal-overlay {
      position: fixed; inset: 0; z-index: 200;
      background: rgba(5,15,35,.75); backdrop-filter: blur(6px);
      display: flex; align-items: center; justify-content: center; padding: 20px;
    }
    .modal-box {
      background: var(--white); border-radius: 18px;
      box-shadow: 0 24px 60px rgba(0,0,0,.35);
      width: 100%; max-width: 440px;
      padding: 32px 28px; position: relative;
      animation: slideUp .3s ease;
    }
    @keyframes slideUp {
      from { transform: translateY(30px); opacity: 0; }
      to   { transform: translateY(0);    opacity: 1; }
    }
    .modal-close {
      position: absolute; top: 16px; right: 18px;
      background: var(--offwhite); border: none; color: var(--muted);
      width: 32px; height: 32px; border-radius: 50%; font-size: 14px;
      cursor: pointer; display: flex; align-items: center; justify-content: center;
      transition: background .2s;
    }
    .modal-close:hover { background: var(--border); }
    .modal-header {
      display: flex; align-items: center; gap: 14px;
      margin-bottom: 14px; padding-bottom: 14px;
      border-bottom: 1px solid var(--border);
    }
    .modal-icon { font-size: 32px; }
    .modal-header h3 { font-family: 'Playfair Display', serif; font-size: 18px; color: var(--navy); }
    .modal-spec { font-size: 13px; color: var(--muted); }
    .modal-desc { font-size: 14px; color: var(--muted); margin-bottom: 18px; }
    .modal-note { font-size: 11px; color: var(--muted); text-align: center; margin-top: 10px; }

    .success-box { text-align: center; padding: 12px 0; }
    .success-icon { font-size: 52px; margin-bottom: 12px; }
    .success-box h3 { font-family: 'Playfair Display', serif; font-size: 20px; color: var(--navy); margin-bottom: 6px; }
    .success-box p { color: var(--muted); font-size: 14px; margin-bottom: 18px; }

    /* ============================================================
       FOOTER
    ============================================================ */
    .site-footer { background: #060F22; padding: 22px 0; }
    .footer-inner {
      max-width: 1100px; margin: 0 auto; padding: 0 20px;
      display: flex; justify-content: space-between; align-items: center;
      flex-wrap: wrap; gap: 10px;
    }
    .footer-inner span { font-size: 13px; color: rgba(255,255,255,.4); }

    /* ============================================================
       RESPONSIVE
    ============================================================ */
    @media (max-width: 768px) {
      .nav-links { display: none; }
      .hero { padding: 56px 0 48px; }
      .search-bar { flex-direction: column; border-radius: 14px; padding: 12px; gap: 8px; }
      .search-bar button { width: 100%; border-radius: 9px; padding: 12px; }
      .hero-stats { gap: 16px; }
      .stat-div { display: none; }
      .contact-inner { grid-template-columns: 1fr; gap: 32px; }
      .section { padding: 48px 0; }
      .footer-inner { flex-direction: column; text-align: center; }
    }
    @media (max-width: 480px) {
      .lawyers-grid { grid-template-columns: 1fr; }
      .steps-grid   { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

  <!-- ===== HEADER ===== -->
  <header class="site-header">
    <div class="header-inner container">
      <div class="logo">
        <span class="logo-icon">⚖️</span>
        <div>
          <span class="logo-main">TN Legal</span>
          <span class="logo-sub">Tirunelveli Advocates Directory</span>
        </div>
      </div>
      <nav class="nav-links">
        <a href="#lawyers">Lawyers</a>
        <a href="#how-it-works">How it Works</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <!-- ===== HERO ===== -->
  <section class="hero">
    <div class="hero-bg"></div>
    <div class="container hero-content">
      <span class="hero-badge">✦ Trusted Legal Directory – Tirunelveli</span>
      <h1>Best Lawyers in<br /><span class="gold">Tirunelveli</span></h1>
      <p class="hero-sub">Find experienced civil &amp; criminal lawyers near you.<br />Free first consultation. Verified profiles.</p>

      <div class="search-bar">
        <select id="filterType" onchange="filterLawyers()">
          <option value="all">All Specializations</option>
          <option value="civil">Civil</option>
          <option value="criminal">Criminal</option>
          <option value="both">Civil &amp; Criminal</option>
        </select>
        <input type="text" id="searchInput" placeholder="Search by name or specialization…" oninput="filterLawyers()" />
        <button onclick="filterLawyers()">Search</button>
      </div>

      <div class="hero-stats">
        <div class="stat"><span class="stat-num">50+</span><span class="stat-label">Verified Lawyers</span></div>
        <div class="stat-div"></div>
        <div class="stat"><span class="stat-num">2,000+</span><span class="stat-label">Cases Handled</span></div>
        <div class="stat-div"></div>
        <div class="stat"><span class="stat-num">Free</span><span class="stat-label">First Consultation</span></div>
      </div>
    </div>
  </section>

  <!-- ===== FILTER CHIPS ===== -->
  <div class="filter-section">
    <span class="filter-label">Quick Filter:</span>
    <button class="chip active" onclick="quickFilter('all',this)">All</button>
    <button class="chip" onclick="quickFilter('civil',this)">⚖️ Civil</button>
    <button class="chip" onclick="quickFilter('criminal',this)">🔒 Criminal</button>
    <button class="chip" onclick="quickFilter('both',this)">🏛️ Civil &amp; Criminal</button>
  </div>

  <!-- ===== LAWYERS LISTING ===== -->
  <section class="section lawyers-section" id="lawyers">
    <div class="container">
      <h2 class="section-title">Top Advocates in Tirunelveli</h2>
      <p class="section-sub">All lawyers are verified by Tirunelveli Bar Association</p>
      <div class="lawyers-grid" id="lawyersGrid"></div>
      <p class="no-results hidden" id="noResults">No lawyers found. Try a different search.</p>
    </div>
  </section>

  <!-- ===== HOW IT WORKS ===== -->
  <section class="section how-section" id="how-it-works">
    <div class="container">
      <h2 class="section-title">How It Works</h2>
      <div class="steps-grid">
        <div class="step-card">
          <div class="step-num">01</div>
          <div class="step-icon">🔍</div>
          <h3>Browse Lawyers</h3>
          <p>Filter by Civil, Criminal, experience, or location in Tirunelveli.</p>
        </div>
        <div class="step-card">
          <div class="step-num">02</div>
          <div class="step-icon">📋</div>
          <h3>Share Your Details</h3>
          <p>Fill in your name and number so the lawyer is ready to help you.</p>
        </div>
        <div class="step-card">
          <div class="step-num">03</div>
          <div class="step-icon">📞</div>
          <h3>Get Connected</h3>
          <p>Your call is initiated instantly. Free first consultation.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== CONTACT ===== -->
  <section class="section contact-section" id="contact">
    <div class="container contact-inner">
      <div>
        <h2 class="section-title left">List Your Practice Here</h2>
        <p>Are you a lawyer in Tirunelveli? Get listed and receive direct client enquiries.</p>
        <ul class="contact-list">
          <li>📧 list@tnlegal.in</li>
          <li>📞 +91 98765 43210</li>
          <li>📍 Tirunelveli, Tamil Nadu</li>
        </ul>
      </div>
      <div class="contact-form-box">
        <h3>Send an Enquiry</h3>
        <input type="text"  class="form-input" placeholder="Your Name" />
        <input type="tel"   class="form-input" placeholder="Mobile Number" />
        <textarea           class="form-input" rows="3" placeholder="Your message…"></textarea>
        <button class="btn-primary">Send Message</button>
      </div>
    </div>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer class="site-footer">
    <div class="footer-inner">
      <span>© 2025 TN Legal Directory – Tirunelveli</span>
      <span>Made for the Tirunelveli legal community</span>
    </div>
  </footer>

  <!-- ===== WHATSAPP STICKY ===== -->
  <a class="wa-sticky"
     href="https://wa.me/919999999999?text=Hello%2C%20I%20need%20a%20lawyer%20in%20Tirunelveli"
     target="_blank" title="Chat on WhatsApp">💬</a>

  <!-- ===== CALL MODAL ===== -->
  <div class="modal-overlay hidden" id="callModal">
    <div class="modal-box">
      <button class="modal-close" onclick="closeModal()">✕</button>
      <div class="modal-header">
        <span class="modal-icon">📞</span>
        <div>
          <h3 id="modalName">Advocate Name</h3>
          <p class="modal-spec" id="modalSpec">Specialization</p>
        </div>
      </div>
      <p class="modal-desc">Share your details to connect instantly. Free first consultation.</p>

      <!-- Form Step -->
      <div id="formStep">
        <input  type="text" id="leadName"     class="form-input" placeholder="Your Full Name *" />
        <input  type="tel"  id="leadMobile"   class="form-input" placeholder="Mobile Number (10 digits) *" />
        <input  type="text" id="leadLocation" class="form-input" placeholder="Your Location (e.g. Palayamkottai) *" />
        <textarea           id="leadMessage"  class="form-input" rows="2" placeholder="Brief about your case (optional)"></textarea>
        <button class="btn-primary" onclick="submitLead()">📞 Connect &amp; Call Now</button>
        <p class="modal-note">Your details are private and shared only with the advocate.</p>
      </div>

      <!-- Success Step -->
      <div id="successStep" class="hidden success-box">
        <div class="success-icon">✅</div>
        <h3>Connecting You Now!</h3>
        <p id="successMsg">Calling advocate…</p>
        <p class="modal-note">If call doesn't start, tap below.</p>
        <a id="directCallBtn" href="#" class="btn-primary">📞 Tap to Call Directly</a>
      </div>
    </div>
  </div>

  <!-- ===== JAVASCRIPT ===== -->
  <script>
    /* ----------------------------------------------------------------
       LAWYER DATA
       To add more lawyers: copy one object, change the values, add comma.
       phone: Indian mobile with country code, e.g. "+919876543210"
    ---------------------------------------------------------------- */
    const lawyers = [
      {
        id: 1,
        name: "Advocate Rajesh Kumar",
        avatar: "👨‍⚖️",
        location: "Palayamkottai, Tirunelveli",
        experience: 12,
        specialization: "criminal",
        specLabel: "Criminal",
        successRate: 88,
        stars: 4.8,
        phone: "+919876543210",
        tags: ["Bail Cases", "Murder Defence", "Cyber Crime"],
        verified: true,
      },
      {
        id: 2,
        name: "Advocate Priya Sharma",
        avatar: "👩‍⚖️",
        location: "Tirunelveli Junction",
        experience: 8,
        specialization: "civil",
        specLabel: "Civil",
        successRate: 82,
        stars: 4.6,
        phone: "+919876543211",
        tags: ["Property Disputes", "Family Law", "Divorce"],
        verified: true,
      },
      {
        id: 3,
        name: "Advocate Arjun Ravi",
        avatar: "👨‍⚖️",
        location: "Tirunelveli Town",
        experience: 15,
        specialization: "both",
        specLabel: "Civil & Criminal",
        successRate: 91,
        stars: 5.0,
        phone: "+919876543212",
        tags: ["Land Cases", "Sessions Court", "High Court"],
        verified: true,
      },
      {
        id: 4,
        name: "Advocate Meena Devi",
        avatar: "👩‍⚖️",
        location: "Nanguneri, Tirunelveli",
        experience: 10,
        specialization: "civil",
        specLabel: "Civil",
        successRate: 79,
        stars: 4.4,
        phone: "+919876543213",
        tags: ["Consumer Cases", "Labour Law", "Rent Disputes"],
        verified: true,
      },
      {
        id: 5,
        name: "Advocate Suresh Pandian",
        avatar: "👨‍⚖️",
        location: "Tenkasi, Tirunelveli Dist.",
        experience: 20,
        specialization: "criminal",
        specLabel: "Criminal",
        successRate: 93,
        stars: 5.0,
        phone: "+919876543214",
        tags: ["POCSO Cases", "Drug Offences", "Appeals"],
        verified: true,
      },
      {
        id: 6,
        name: "Advocate Lakshmi Narayanan",
        avatar: "👩‍⚖️",
        location: "Cheranmahadevi, Tirunelveli",
        experience: 6,
        specialization: "both",
        specLabel: "Civil & Criminal",
        successRate: 76,
        stars: 4.2,
        phone: "+919876543215",
        tags: ["Women Rights", "Domestic Violence", "Property"],
        verified: false,
      },
    ];

    /* ---- STATE ---- */
    let currentLawyer = null;

    /* ---- RENDER ---- */
    function renderCards(list) {
      const grid = document.getElementById("lawyersGrid");
      const noResults = document.getElementById("noResults");
      grid.innerHTML = "";

      if (list.length === 0) {
        noResults.classList.remove("hidden");
        return;
      }
      noResults.classList.add("hidden");

      list.forEach(l => {
        const badgeClass = l.specialization === "civil"     ? "badge-civil"
                         : l.specialization === "criminal"  ? "badge-criminal"
                         : "badge-both";

        const fullStars  = Math.floor(l.stars);
        const halfStar   = l.stars % 1 >= 0.5 ? "½" : "";
        const emptyStars = 5 - fullStars - (halfStar ? 1 : 0);
        const starsHtml  = "★".repeat(fullStars) + halfStar + "☆".repeat(emptyStars);

        const tagsHtml = l.tags.map(t => `<span class="tag">${t}</span>`).join("");

        const card = document.createElement("div");
        card.className = "lawyer-card";
        card.innerHTML = `
          <div class="card-header">
            <div class="avatar">${l.avatar}</div>
            <div>
              <div class="card-name">${l.name} ${l.verified ? '<span style="font-size:11px;color:#4ADE80;">✓</span>' : ""}</div>
              <div class="card-location">📍 ${l.location}</div>
            </div>
            <span class="badge-spec ${badgeClass}">${l.specLabel}</span>
          </div>
          <div class="card-body">
            <div class="card-meta">
              <div class="meta-item">
                <span class="meta-label">Experience</span>
                <span class="meta-value">${l.experience}+ yrs</span>
              </div>
              <div class="meta-item">
                <span class="meta-label">Specialization</span>
                <span class="meta-value">${l.specLabel}</span>
              </div>
            </div>
            <div class="success-bar-wrap">
              <div class="success-bar-label">
                <span>Case Success Rate</span>
                <span>${l.successRate}%</span>
              </div>
              <div class="success-bar">
                <div class="success-bar-fill" data-width="${l.successRate}%"></div>
              </div>
            </div>
            <div class="stars">${starsHtml} <span style="font-size:12px;color:var(--muted);font-weight:600;">${l.stars.toFixed(1)}/5.0</span></div>
            <div class="card-tags">${tagsHtml}</div>
          </div>
          <div class="card-footer">
            <button class="btn-call" onclick="openModal(${l.id})">📞 Call Now</button>
            <button class="btn-wa" onclick="whatsappLawyer('${l.phone}','${l.name}')" title="WhatsApp">💬</button>
          </div>
        `;
        grid.appendChild(card);
      });

      // Animate bars
      setTimeout(() => {
        document.querySelectorAll(".success-bar-fill").forEach(b => {
          b.style.width = b.dataset.width;
        });
      }, 120);
    }

    /* ---- FILTER ---- */
    function filterLawyers() {
      const search = document.getElementById("searchInput").value.toLowerCase().trim();
      const type   = document.getElementById("filterType").value;

      const filtered = lawyers.filter(l => {
        const matchType   = type === "all" || l.specialization === type
                          || (type !== "both" && l.specialization === "both");
        const matchSearch = !search
                          || l.name.toLowerCase().includes(search)
                          || l.specLabel.toLowerCase().includes(search)
                          || l.tags.some(t => t.toLowerCase().includes(search));
        return matchType && matchSearch;
      });
      renderCards(filtered);
    }

    function quickFilter(type, btn) {
      document.querySelectorAll(".chip").forEach(c => c.classList.remove("active"));
      btn.classList.add("active");
      document.getElementById("filterType").value = type;
      filterLawyers();
    }

    /* ---- MODAL ---- */
    function openModal(id) {
      currentLawyer = lawyers.find(l => l.id === id);
      if (!currentLawyer) return;

      document.getElementById("modalName").textContent = currentLawyer.name;
      document.getElementById("modalSpec").textContent =
        currentLawyer.specLabel + " Lawyer | " + currentLawyer.experience + "+ yrs";

      // Reset
      ["leadName","leadMobile","leadLocation","leadMessage"].forEach(f => {
        document.getElementById(f).value = "";
        document.getElementById(f).classList.remove("error");
      });
      document.getElementById("formStep").classList.remove("hidden");
      document.getElementById("successStep").classList.add("hidden");

      document.getElementById("callModal").classList.remove("hidden");
      document.body.style.overflow = "hidden";
    }

    function closeModal() {
      document.getElementById("callModal").classList.add("hidden");
      document.body.style.overflow = "";
      currentLawyer = null;
    }

    // Close on overlay click
    document.getElementById("callModal").addEventListener("click", function(e) {
      if (e.target === this) closeModal();
    });

    /* ---- LEAD SUBMIT ---- */
    function submitLead() {
      const name     = document.getElementById("leadName").value.trim();
      const mobile   = document.getElementById("leadMobile").value.trim();
      const location = document.getElementById("leadLocation").value.trim();

      // Clear old errors
      ["leadName","leadMobile","leadLocation"].forEach(f =>
        document.getElementById(f).classList.remove("error"));

      let valid = true;
      if (!name)                            { document.getElementById("leadName").classList.add("error");     valid = false; }
      if (!mobile || !/^[6-9]\d{9}$/.test(mobile)) { document.getElementById("leadMobile").classList.add("error");   valid = false; }
      if (!location)                        { document.getElementById("leadLocation").classList.add("error"); valid = false; }
      if (!valid) return;

      // Save lead to localStorage
      try {
        const leads = JSON.parse(localStorage.getItem("tnlegal_leads") || "[]");
        leads.push({
          name, mobile, location,
          message:      document.getElementById("leadMessage").value.trim(),
          lawyer:       currentLawyer.name,
          lawyerPhone:  currentLawyer.phone,
          timestamp:    new Date().toISOString(),
        });
        localStorage.setItem("tnlegal_leads", JSON.stringify(leads));
      } catch(e) { /* silent */ }

      // Show success
      document.getElementById("formStep").classList.add("hidden");
      document.getElementById("successStep").classList.remove("hidden");
      document.getElementById("successMsg").textContent = "Calling " + currentLawyer.name + "…";
      document.getElementById("directCallBtn").href = "tel:" + currentLawyer.phone;

      // Trigger call
      setTimeout(() => { window.location.href = "tel:" + currentLawyer.phone; }, 1200);
    }

    /* ---- WHATSAPP ---- */
    function whatsappLawyer(phone, name) {
      const msg = encodeURIComponent(
        "Hello " + name + ", I found you on TN Legal Directory. I need legal assistance. Please let me know your availability."
      );
      window.open("https://wa.me/" + phone.replace(/\D/g,"") + "?text=" + msg, "_blank");
    }

    /* ---- ESC to close ---- */
    document.addEventListener("keydown", e => { if (e.key === "Escape") closeModal(); });

    /* ---- INIT ---- */
    renderCards(lawyers);
  </script>
</body>
</html>
