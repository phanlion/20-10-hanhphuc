<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
  <meta name="theme-color" content="#21030c">
  <meta name="description" content="Một món quà nhỏ với lời chúc 20/10 được cá nhân hóa, tấm thiệp phong ấn và những lời yêu thương dành cho phụ nữ Việt Nam.">
  <meta property="og:title" content="Chúc Mừng 20/10 – Tôn Vinh Phụ Nữ Việt Nam">
  <meta property="og:description" content="Tạo lời chúc 20/10 thật riêng và mở bức thư yêu thương.">
  <title>Chúc Mừng 20/10 – Tôn Vinh Phụ Nữ Việt Nam</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;600;700&family=Dancing+Script:wght@600;700&family=Playfair+Display:wght@500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      color-scheme: dark;
      --bg: #170208;
      --bg-2: #26040e;
      --wine: #4a0718;
      --gold: #d4af37;
      --gold-light: #fff2c6;
      --rose: #e8b4b8;
      --text: #fff8ef;
      --muted: #d9c6c9;
      --line: rgba(212,175,55,.27);
      --card: rgba(48,5,17,.76);
      --serif: "Playfair Display", Georgia, serif;
      --sans: "Be Vietnam Pro", system-ui, sans-serif;
      --script: "Dancing Script", cursive;
      --safe-bottom: env(safe-area-inset-bottom, 0px);
      --safe-top: env(safe-area-inset-top, 0px);
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; scroll-padding-top: 88px; }
    body {
      margin: 0; min-width: 320px; overflow-x: hidden; background:
        radial-gradient(ellipse at 50% -15%, rgba(133,20,48,.48), transparent 48%),
        radial-gradient(ellipse at 5% 38%, rgba(107,17,35,.18), transparent 34%),
        linear-gradient(180deg, #1a0208, #24030d 54%, #170208);
      color: var(--text); font-family: var(--sans); line-height: 1.65;
      -webkit-font-smoothing: antialiased; text-rendering: optimizeLegibility;
    }
    body.modal-open { overflow: hidden; }
    a { color: inherit; text-decoration: none; }
    button, input, select { font: inherit; }
    button, a, select { -webkit-tap-highlight-color: transparent; }
    button { cursor: pointer; }
    button:focus-visible, a:focus-visible, input:focus-visible, select:focus-visible { outline: 3px solid #fff0ad; outline-offset: 3px; }
    .container { width: min(100% - 36px, 1080px); margin-inline: auto; }
    .serif { font-family: var(--serif); }
    .gold-text { color: var(--gold-light); background: linear-gradient(120deg, #fff6d3, #d4af37 58%, #a7791c); -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; }
    .rose-text { color: var(--rose); }
    .eyebrow { display: inline-flex; align-items: center; justify-content: center; gap: 8px; padding: 7px 13px; border: 1px solid var(--line); border-radius: 999px; color: #f1d778; background: rgba(212,175,55,.075); font-size: .72rem; letter-spacing: .09em; text-transform: uppercase; }
    .section { padding: 72px 0; position: relative; }
    .section-heading { text-align: center; max-width: 720px; margin: 0 auto 28px; }
    .section-heading h2 { margin: 14px 0 12px; font: 700 clamp(1.7rem, 6vw, 2.7rem)/1.2 var(--serif); }
    .section-heading p { color: var(--muted); margin: 0 auto; max-width: 620px; font-size: .95rem; }
    .glass { background: var(--card); border: 1px solid var(--line); border-radius: 22px; box-shadow: 0 18px 45px rgba(0,0,0,.2), inset 0 1px rgba(255,255,255,.025); backdrop-filter: blur(12px); -webkit-backdrop-filter: blur(12px); }
    .btn { min-height: 48px; display: inline-flex; justify-content: center; align-items: center; gap: 9px; border: 1px solid transparent; border-radius: 999px; padding: 12px 19px; font-size: .88rem; font-weight: 700; line-height: 1.35; transition: transform .2s ease, filter .2s ease, background .2s ease; text-align: center; }
    .btn:active { transform: scale(.98); }
    .btn-gold { color: #26040c; background: linear-gradient(130deg, #ffe7a0, #d4af37 57%, #ad7d1d); box-shadow: 0 8px 25px rgba(212,175,55,.17); }
    .btn-gold:hover { filter: brightness(1.07); }
    .btn-outline { color: #f3d97c; border-color: rgba(212,175,55,.48); background: rgba(212,175,55,.045); }
    .btn-outline:hover { background: rgba(212,175,55,.11); }
    .site-header { z-index: 30; position: sticky; top: 0; padding-top: var(--safe-top); background: rgba(24,2,8,.9); border-bottom: 1px solid rgba(212,175,55,.2); backdrop-filter: blur(15px); -webkit-backdrop-filter: blur(15px); }
    .header-inner { min-height: 68px; display: flex; align-items: center; justify-content: space-between; gap: 10px; }
    .brand { display: flex; gap: 10px; align-items: center; min-width: 0; }
    .brand-mark { flex: 0 0 42px; width: 42px; height: 42px; display: grid; place-items: center; border-radius: 50%; color: #2a040b; font: 800 1rem var(--serif); background: linear-gradient(145deg, #fff0b6, #bf9024); box-shadow: 0 3px 18px rgba(212,175,55,.15); }
    .brand-copy { min-width: 0; }
    .brand-title { display: block; font: 700 clamp(.69rem, 2.7vw, .92rem)/1.25 var(--serif); letter-spacing: .045em; white-space: normal; }
    .brand-sub { display: block; color: #ddb7bd; font-size: .62rem; line-height: 1.45; letter-spacing: .025em; margin-top: 3px; }
    .desktop-nav { display: none; }
    .header-actions { display: flex; align-items: center; gap: 7px; flex: 0 0 auto; }
    .fireworks-btn { min-height: 40px; padding: 9px 12px; font-size: .76rem; }
    .menu-toggle { width: 42px; height: 42px; display: grid; place-items: center; color: var(--gold-light); border: 1px solid var(--line); border-radius: 13px; background: transparent; font-size: 1.2rem; }
    .mobile-nav { display: none; padding: 2px 0 14px; }
    .mobile-nav.open { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; }
    .mobile-nav a { padding: 11px 12px; border-radius: 12px; color: #f7e9dd; font-size: .82rem; border: 1px solid rgba(212,175,55,.15); background: rgba(255,255,255,.025); }

    .hero { min-height: auto; padding: 54px 0 58px; text-align: center; position: relative; }
    .hero:before, .hero:after { content: "✦"; position: absolute; color: rgba(212,175,55,.42); font-size: 1.3rem; pointer-events: none; }
    .hero:before { top: 12%; left: 8%; }
    .hero:after { bottom: 14%; right: 7%; color: rgba(232,180,184,.55); }
    .hero-inner { max-width: 780px; position: relative; margin: auto; }
    .hero h1 { margin: 19px 0 18px; font: 800 clamp(2.15rem, 9.1vw, 4.7rem)/1.12 var(--serif); letter-spacing: -.035em; }
    .hero h1 .script-line { display: block; margin: 2px 0; font: 700 clamp(2.7rem, 10vw, 5.1rem)/1 var(--script); letter-spacing: 0; }
    .hero-copy { max-width: 640px; margin: 0 auto; color: #eadde0; font-size: .94rem; line-height: 1.9; }
    .hero-actions { display: grid; gap: 11px; margin: 25px auto 0; max-width: 380px; }
    .hero-quote { color: #e8b4b8; font: 600 1.22rem/1.6 var(--script); margin: 27px auto 0; max-width: 520px; }
    .hero-ornament { display: flex; align-items: center; justify-content: center; gap: 12px; margin: 20px auto 0; color: var(--gold); font-size: .7rem; }
    .hero-ornament:before, .hero-ornament:after { content: ""; width: 42px; height: 1px; background: linear-gradient(90deg, transparent, var(--gold)); }
    .hero-ornament:after { transform: rotate(180deg); }

    .wishes-section { background: linear-gradient(180deg, transparent, rgba(75,7,25,.25), transparent); }
    .wish-card { padding: 20px; max-width: 760px; margin: 0 auto; }
    .form-label { display: block; color: #f2d78c; font-size: .8rem; font-weight: 700; margin: 0 0 8px; }
    .field { width: 100%; min-height: 49px; border-radius: 13px; color: var(--text); padding: 13px 14px; background: rgba(17,2,7,.65); border: 1px solid rgba(212,175,55,.3); }
    .field::placeholder { color: #b9a3a8; }
    select.field { appearance: auto; }
    select.field option { color: #fff; background: #2a0610; }
    .form-grid { display: grid; gap: 17px; }
    .wish-output { margin: 21px 0 0; min-height: 150px; padding: 18px; border-radius: 16px; color: #f8edef; white-space: pre-line; line-height: 1.9; font-size: .93rem; background: linear-gradient(145deg, rgba(255,255,255,.035), rgba(212,175,55,.025)); border: 1px solid rgba(212,175,55,.16); }
    .wish-bottom { display: grid; gap: 14px; padding-top: 16px; }
    .helper { color: #d2abb3; font-size: .75rem; }
    .wish-buttons { display: grid; grid-template-columns: 1fr; gap: 9px; }

    .envelope-section { overflow: hidden; }
    .envelope-tip { font-size: .82rem !important; }
    .envelope-stage { min-height: 255px; padding: 34px 0 14px; display: flex; align-items: center; justify-content: center; }
    .envelope-wrap { width: min(100%, 370px); height: 230px; perspective: 900px; position: relative; cursor: pointer; outline: none; }
    .envelope-wrap:focus-visible { border-radius: 14px; outline: 3px solid #fff0ad; outline-offset: 5px; }
    .envelope { position: absolute; inset: 13px 0 13px; border: 1.5px solid var(--gold); border-radius: 8px; background: linear-gradient(145deg,#4c071a,#21030c); box-shadow: 0 22px 43px rgba(0,0,0,.38), 0 0 24px rgba(212,175,55,.1); }
    .envelope-pocket { position: absolute; inset: 0; z-index: 3; border-radius: 7px; background: linear-gradient(145deg,#5b0a20,#2a030d); clip-path: polygon(0 0,50% 58%,100% 0,100% 100%,0 100%); }
    .envelope-flap { position: absolute; left: 0; right: 0; top: 0; height: 0; z-index: 5; border-left: calc(min(42vw, 155px)) solid transparent; border-right: calc(min(42vw, 155px)) solid transparent; border-top: 105px solid #710e2b; transform-origin: top; transition: transform .6s ease, z-index .1s .25s; filter: drop-shadow(0 3px 5px rgba(0,0,0,.3)); }
    .letter-peek { position: absolute; z-index: 2; left: 5%; bottom: 6px; width: 90%; height: 84%; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; padding: 14px; border-radius: 6px; color: #4b1020; background: linear-gradient(145deg,#fffdf8,#f6e8cc); border: 1px solid #d4af37; transition: transform .7s .25s cubic-bezier(.2,.8,.2,1); }
    .letter-peek strong { font: 700 1.1rem var(--serif); }
    .letter-peek span { margin-top: 9px; font: 600 1.1rem var(--script); }
    .wax-seal { position: absolute; z-index: 6; width: 61px; height: 61px; top: 58%; left: 50%; transform: translate(-50%,-50%); display: grid; place-items: center; border-radius: 50%; color: #2a030b; font: 800 .76rem var(--serif); border: 2px solid #fff1bf; background: radial-gradient(circle at 35% 25%, #fff1a6, #d4af37 48%, #8a6412); box-shadow: 0 5px 12px rgba(0,0,0,.35), inset 0 1px 5px rgba(255,255,255,.5); transition: opacity .35s ease, transform .35s ease; }
    .envelope-wrap.open .envelope-flap { transform: rotateX(180deg); z-index: 1; }
    .envelope-wrap.open .letter-peek { transform: translateY(-42px) scale(1.015); }
    .envelope-wrap.open .wax-seal { opacity: 0; transform: translate(-50%,-50%) scale(1.4); pointer-events: none; }
    .envelope-caption { text-align: center; color: #d9bbc0; font-size: .8rem; margin: 0 0 15px; }
    .envelope-actions { display: grid; gap: 10px; max-width: 330px; margin: 0 auto; }

    .qualities { display: grid; gap: 13px; }
    .quality-card { padding: 22px 19px; text-align: center; }
    .quality-icon { width: 53px; height: 53px; border-radius: 50%; margin: 0 auto 14px; display: grid; place-items: center; font-size: 1.35rem; color: #f3d578; background: rgba(212,175,55,.09); border: 1px solid rgba(212,175,55,.35); }
    .quality-card h3 { margin: 0 0 8px; color: #fff0bc; font: 700 1.16rem var(--serif); }
    .quality-card p { margin: 0; color: #d8c4c8; font-size: .86rem; line-height: 1.8; }
    .hug-card { padding: 27px 20px; margin-top: 26px; text-align: center; background: linear-gradient(125deg, rgba(73,7,25,.94), rgba(33,3,12,.96)); }
    .hug-card .big-heart { font-size: 2rem; }
    .hug-card h3 { font: 700 1.55rem/1.3 var(--serif); margin: 10px 0; }
    .hug-card p { color: var(--muted); font-size: .88rem; margin: 0 auto 18px; max-width: 520px; }
    .site-footer { padding: 32px 0 calc(28px + var(--safe-bottom)); text-align: center; border-top: 1px solid rgba(212,175,55,.18); background: rgba(17,1,6,.3); }
    .footer-title { font: 700 1.1rem var(--serif); color: var(--gold-light); }
    .site-footer p { margin: 8px auto; color: #bca8ad; font-size: .78rem; max-width: 600px; }

    .music-widget { position: fixed; z-index: 25; left: 13px; bottom: calc(13px + var(--safe-bottom)); display: flex; align-items: center; gap: 9px; max-width: calc(100vw - 26px); padding: 7px 13px 7px 7px; border-radius: 999px; background: rgba(32,3,12,.92); border: 1px solid rgba(212,175,55,.38); box-shadow: 0 6px 24px rgba(0,0,0,.3); backdrop-filter: blur(10px); }
    .music-toggle { width: 41px; height: 41px; flex: 0 0 41px; display: grid; place-items: center; color: #2a040b; background: linear-gradient(145deg,#ffedb0,#c39a2c); border: 0; border-radius: 50%; font-size: 1.05rem; }
    .music-copy { display: flex; flex-direction: column; font-size: .69rem; line-height: 1.35; }
    .music-copy strong { color: #f1d87e; font-size: .7rem; }
    .music-copy span { color: #c9b3b9; }
    .toast { position: fixed; z-index: 80; left: 50%; bottom: calc(82px + var(--safe-bottom)); width: max-content; max-width: calc(100vw - 32px); transform: translate(-50%, 12px); opacity: 0; pointer-events: none; transition: opacity .25s, transform .25s; color: #27050d; background: #f4d782; padding: 11px 16px; font-size: .82rem; font-weight: 700; text-align: center; border-radius: 14px; box-shadow: 0 8px 25px rgba(0,0,0,.35); }
    .toast.show { opacity: 1; transform: translate(-50%,0); }
    .spark-layer { z-index: 75; pointer-events: none; position: fixed; inset: 0; overflow: hidden; }
    .spark { position: absolute; bottom: -40px; animation: floatUp 2.8s ease-out forwards; filter: drop-shadow(0 0 7px rgba(255,201,77,.35)); }
    @keyframes floatUp { 0% { transform: translateY(0) rotate(0) scale(.6); opacity: 0; } 12% { opacity: 1; } 80% { opacity: .95; } 100% { transform: translateY(-105vh) rotate(50deg) scale(1.25); opacity: 0; } }
    .modal { position: fixed; z-index: 60; inset: 0; display: flex; align-items: center; justify-content: center; padding: 16px; padding-bottom: calc(16px + var(--safe-bottom)); background: rgba(14,1,5,.88); backdrop-filter: blur(12px); opacity: 0; visibility: hidden; transition: opacity .25s, visibility .25s; }
    .modal.open { opacity: 1; visibility: visible; }
    .modal-panel { width: min(100%, 560px); max-height: calc(100dvh - 32px - var(--safe-bottom)); overflow-y: auto; position: relative; padding: 25px 21px 22px; border-radius: 20px; background: linear-gradient(150deg,#fffdf7,#f7ead6); color: #461020; border: 2px solid #d4af37; box-shadow: 0 22px 80px rgba(0,0,0,.5); transform: translateY(12px) scale(.99); transition: transform .25s; }
    .modal.open .modal-panel { transform: translateY(0) scale(1); }
    .modal-close { position: absolute; top: 10px; right: 10px; width: 38px; height: 38px; border: 1px solid rgba(74,16,32,.2); border-radius: 50%; background: rgba(74,16,32,.07); color: #461020; font-size: 1.3rem; }
    .modal-kicker { display: inline-block; padding: 5px 10px; color: #78501a; border: 1px solid rgba(143,100,24,.25); border-radius: 999px; font-size: .68rem; letter-spacing: .12em; text-transform: uppercase; }
    .modal-panel h2 { font: 700 clamp(1.55rem, 6vw, 2.2rem)/1.2 var(--serif); margin: 15px 35px 18px 0; }
    .modal-letter { white-space: pre-line; font: 500 .92rem/1.95 var(--sans); }
    .modal-sign { margin-top: 21px; font: 700 1.5rem var(--script); color: #8d243e; text-align: right; }
    .modal-actions { margin-top: 20px; display: grid; gap: 9px; }
    .sr-only { position: absolute; width: 1px; height: 1px; padding: 0; margin: -1px; overflow: hidden; clip: rect(0,0,0,0); white-space: nowrap; border: 0; }

    @media (min-width: 620px) {
      .container { width: min(100% - 56px, 1080px); }
      .section { padding: 88px 0; }
      .header-inner { min-height: 76px; }
      .brand-mark { width: 46px; height: 46px; flex-basis: 46px; }
      .brand-title { font-size: .98rem; }
      .brand-sub { font-size: .68rem; }
      .desktop-nav { display: flex; align-items: center; gap: 20px; margin-left: auto; margin-right: 12px; }
      .desktop-nav a { color: #e6d5d9; font-size: .78rem; white-space: nowrap; }
      .desktop-nav a:hover { color: var(--gold-light); }
      .menu-toggle, .mobile-nav { display: none !important; }
      .hero { padding: 78px 0 82px; }
      .hero-actions { display: flex; max-width: none; justify-content: center; }
      .hero-actions .btn { min-width: 220px; }
      .wish-card { padding: 28px; }
      .form-grid { grid-template-columns: .85fr 1.15fr; }
      .wish-bottom { grid-template-columns: 1fr auto; align-items: center; }
      .wish-buttons { grid-template-columns: auto auto; }
      .qualities { grid-template-columns: repeat(3, 1fr); gap: 16px; }
      .quality-card { padding: 25px 19px; }
      .hug-card { padding: 38px 28px; }
      .envelope-wrap { width: 440px; height: 275px; }
      .envelope { inset: 15px 0 15px; }
      .envelope-flap { border-left-width: 220px; border-right-width: 220px; border-top-width: 130px; }
      .wax-seal { width: 69px; height: 69px; }
      .envelope-stage { min-height: 315px; }
      .envelope-wrap.open .letter-peek { transform: translateY(-55px) scale(1.02); }
      .envelope-actions { grid-template-columns: 1fr 1fr; max-width: 430px; }
      .music-widget { left: 22px; bottom: 22px; }
      .toast { bottom: 92px; }
      .modal-panel { padding: 34px 35px 28px; }
      .modal-actions { grid-template-columns: 1fr 1fr; }
    }
    @media (min-width: 900px) {
      .desktop-nav { gap: 25px; }
      .desktop-nav a { font-size: .83rem; }
      .hero { min-height: 75vh; display: flex; align-items: center; }
      .hero-inner { padding: 22px 0; }
      .hero-copy { font-size: 1.02rem; }
    }
    @media (max-width: 370px) {
      .container { width: calc(100% - 26px); }
      .brand-mark { width: 37px; height: 37px; flex-basis: 37px; font-size: .9rem; }
      .brand-title { font-size: .64rem; letter-spacing: .015em; }
      .brand-sub { font-size: .56rem; }
      .fireworks-btn { min-height: 37px; padding: 8px 9px; font-size: .69rem; }
      .menu-toggle { width: 37px; height: 37px; }
      .wish-card { padding: 15px; }
      .hero { padding-top: 43px; }
      .hero h1 { font-size: 2rem; }
      .hero h1 .script-line { font-size: 2.45rem; }
      .section { padding: 58px 0; }
      .music-copy { max-width: 132px; }
    }
    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after { scroll-behavior: auto !important; animation-duration: .01ms !important; animation-iteration-count: 1 !important; transition-duration: .01ms !important; }
    }
  </style>
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="brand" href="#home" aria-label="Về đầu trang">
        <span class="brand-mark">20</span>
        <span class="brand-copy">
          <span class="brand-title gold-text">TÔN VINH PHỤ NỮ VIỆT NAM</span>
          <span class="brand-sub">20 Tháng 10 · Dành cho tất cả phái đẹp</span>
        </span>
      </a>
      <nav class="desktop-nav" aria-label="Điều hướng chính">
        <a href="#home">Trang chủ</a><a href="#wishes">Lời chúc</a><a href="#envelope">Bức thư</a><a href="#all-women">Tôn vinh phái đẹp</a>
      </nav>
      <div class="header-actions">
        <button class="btn btn-outline fireworks-btn" type="button" id="fireworksBtn" aria-label="Bắn pháo hoa">✧ <span>Pháo hoa</span></button>
        <button class="menu-toggle" type="button" id="menuToggle" aria-expanded="false" aria-controls="mobileNav" aria-label="Mở menu">☰</button>
      </div>
    </div>
    <nav class="container mobile-nav" id="mobileNav" aria-label="Điều hướng điện thoại">
      <a href="#home">⌂ Trang chủ</a><a href="#wishes">♡ Tạo lời chúc</a><a href="#envelope">✉ Bức thư</a><a href="#all-women">✿ Tôn vinh phái đẹp</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container hero-inner">
        <span class="eyebrow">♛ &nbsp; Ngày Phụ nữ Việt Nam 20/10</span>
        <h1 class="gold-text">Tôn Vinh Vẻ Đẹp <span class="script-line rose-text">&amp; Bản Lĩnh</span> Phụ Nữ Việt</h1>
        <p class="hero-copy">Dành tặng Mẹ kính yêu, người thương, cô giáo, chị em gái, đồng nghiệp và <strong style="color:#f2d67d">tất cả</strong> những người phụ nữ tuyệt vời – nguồn cảm hứng dịu dàng nuôi dưỡng cuộc đời.</p>
        <div class="hero-actions">
          <a class="btn btn-gold" href="#wishes">Khám phá món quà yêu thương <span aria-hidden="true">↓</span></a>
          <a class="btn btn-outline" href="#envelope">✉ Mở thiệp phong ấn</a>
        </div>
        <p class="hero-quote">“Mỗi người phụ nữ là một bông hoa độc bản, khoe sắc rực rỡ và tỏa ngát hương thơm.”</p>
        <div class="hero-ornament" aria-hidden="true">✦ ✧ ✦</div>
      </div>
    </section>

    <section class="section wishes-section" id="wishes">
      <div class="container">
        <div class="section-heading">
          <span class="eyebrow">♡ Gửi lời yêu thương</span>
          <h2 class="gold-text">Lời Chúc Chân Thành Dành Cho Phái Đẹp</h2>
          <p>Chọn người nhận, nhập tên riêng và tạo một lời chúc 20/10 thật ý nghĩa để gửi đi.</p>
        </div>
        <div class="glass wish-card">
          <div class="form-grid">
            <div>
              <label class="form-label" for="recipientType">Bạn muốn gửi lời chúc đến</label>
              <select class="field" id="recipientType">
                <option value="all">Tất cả phái đẹp</option>
                <option value="mom">Mẹ kính yêu</option>
                <option value="lover">Người thương / Vợ</option>
                <option value="colleague">Đồng nghiệp &amp; bạn bè</option>
                <option value="teacher">Cô giáo kính yêu</option>
                <option value="sister">Chị em gái</option>
              </select>
            </div>
            <div>
              <label class="form-label" for="recipientName">Tên người nhận</label>
              <input class="field" id="recipientName" maxlength="60" autocomplete="name" placeholder="Ví dụ: Mẹ yêu, chị Ngọc, cô Lan…">
            </div>
          </div>
          <div class="wish-output" id="wishOutput" aria-live="polite">Gửi bạn – bông hoa xinh đẹp giữa cuộc đời!

Nhân ngày Phụ nữ Việt Nam 20/10, chúc bạn luôn tự tin, rạng rỡ và bản lĩnh. Mong mỗi ngày đều ngập tràn niềm vui, nụ cười và hạnh phúc bên những người thân yêu!</div>
          <div class="wish-bottom">
            <div class="helper">✧ Tên người nhận sẽ tự động xuất hiện trong lời chúc.</div>
            <div class="wish-buttons">
              <button class="btn btn-outline" id="refreshWish" type="button">↻ Tạo lời chúc khác</button>
              <button class="btn btn-gold" id="copyWish" type="button">▢ Sao chép lời chúc</button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="section envelope-section" id="envelope">
      <div class="container">
        <div class="section-heading">
          <span class="eyebrow">✉ Món quà bí mật</span>
          <h2 class="gold-text">Bức Thư Phong Ấn Mạ Vàng</h2>
          <p class="envelope-tip">Chạm vào con dấu để mở phong thư, rồi đọc thông điệp yêu thương dành riêng cho người nhận.</p>
        </div>
        <div class="envelope-stage">
          <div class="envelope-wrap" id="envelopeWrap" role="button" tabindex="0" aria-label="Chạm để mở phong thư" aria-expanded="false">
            <div class="envelope">
              <div class="letter-peek"><strong>Gửi <span id="letterNamePreview">Chị Em Phụ Nữ</span></strong><span>Chúc bạn luôn bình an &amp; hạnh phúc ✨</span></div>
              <div class="envelope-pocket"></div>
              <div class="envelope-flap"></div>
              <div class="wax-seal">20/10</div>
            </div>
          </div>
        </div>
        <p class="envelope-caption" id="envelopeCaption">Chạm nhẹ vào con dấu vàng để mở thư ✨</p>
        <div class="envelope-actions">
          <button class="btn btn-gold" type="button" id="openLetterBtn">Đọc toàn thư yêu thương</button>
          <button class="btn btn-outline" type="button" id="envelopeFireworks">Thắp sáng bầu trời ✦</button>
        </div>
      </div>
    </section>

    <section class="section" id="all-women">
      <div class="container">
        <div class="section-heading">
          <span class="eyebrow">✿ Gửi đến mọi đóa hoa</span>
          <h2 class="gold-text">Tất Cả Phụ Nữ Là Những Bông Hoa Tỏa Sáng</h2>
          <p>Dù ở bất kỳ vị trí nào, phái đẹp luôn cống hiến, lan tỏa yêu thương và làm thế giới trở nên tốt đẹp hơn.</p>
        </div>
        <div class="qualities">
          <article class="glass quality-card"><div class="quality-icon" aria-hidden="true">✧</div><h3>Sang Trọng &amp; Tự Tin</h3><p>Luôn vững tin vào giá trị bản thân, làm chủ cuộc sống và gặt hái những thành công rực rỡ.</p></article>
          <article class="glass quality-card"><div class="quality-icon" aria-hidden="true">♡</div><h3>Ấm Áp &amp; Bao Dung</h3><p>Trái tim dịu dàng sưởi ấm mái ấm gia đình và tiếp thêm sức mạnh cho những người xung quanh.</p></article>
          <article class="glass quality-card"><div class="quality-icon" aria-hidden="true">☼</div><h3>Cảm Hứng Rạng Rỡ</h3><p>Sự cống hiến và tri thức thắp sáng tương lai, lan tỏa niềm vui và hy vọng mỗi ngày.</p></article>
        </div>
        <div class="glass hug-card">
          <div class="big-heart" aria-hidden="true">💗</div>
          <h3 class="gold-text">Gửi Một Vòng Tay Ôm Ngọt Ngào</h3>
          <p>Trao gửi năng lượng tích cực, những trái tim ấm áp và lời chúc bình an đến tất cả phụ nữ.</p>
          <button class="btn btn-gold" type="button" id="hugBtn">Gửi yêu thương ngay ❤️</button>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <div class="footer-title">Tôn Vinh Phụ Nữ Việt Nam 20/10</div>
      <p>Trân trọng gửi tặng tất cả phái đẹp – những đóa hoa rạng rỡ của cuộc đời.</p>
      <p>© 2026 · Special Edition for All Vietnamese Women.</p>
    </div>
  </footer>

  <aside class="music-widget" aria-label="Nhạc nền">
    <button class="music-toggle" type="button" id="musicToggle" aria-label="Bật nhạc nền" aria-pressed="false">♫</button>
    <div class="music-copy"><strong>Nhạc nền thư giãn</strong><span id="musicStatus">Chạm để bật piano du dương</span></div>
  </aside>
  <div class="toast" id="toast" role="status" aria-live="polite"></div>
  <div class="spark-layer" id="sparkLayer" aria-hidden="true"></div>

  <div class="modal" id="letterModal" role="dialog" aria-modal="true" aria-labelledby="modalTitle" aria-hidden="true">
    <div class="modal-panel">
      <button class="modal-close" type="button" id="closeModal" aria-label="Đóng thư">×</button>
      <span class="modal-kicker">Thư chúc mừng 20/10 hoàng gia</span>
      <h2 id="modalTitle">Gửi Chị Em Phụ Nữ,</h2>
      <div class="modal-letter" id="modalLetter">Nhân ngày Phụ nữ Việt Nam 20/10, xin gửi tới bạn – người phụ nữ tuyệt vời – những lời chúc trân trọng và dịu dàng nhất.

Cảm ơn bạn vì đã luôn cống hiến, mang đến cho thế giới những nụ cười ấm áp, sự bao dung dịu dàng và bản lĩnh kiên cường. Dù ở vai trò là người mẹ, người vợ, cô giáo, chị em hay đồng nghiệp, bạn luôn tỏa sáng theo một cách rất riêng.

Nguyện chúc chặng đường phía trước của bạn luôn ngập tràn ánh nắng ấm áp, hoa nở rực rỡ và đong đầy hạnh phúc bên những người thân yêu!</div>
      <div class="modal-sign">Trân trọng &amp; yêu thương! ♡</div>
      <div class="modal-actions">
        <button class="btn btn-gold" type="button" id="copyLetter">Sao chép bức thư</button>
        <button class="btn btn-outline" type="button" id="modalCelebrate">Bắn pháo hoa ✦</button>
      </div>
    </div>
  </div>

  <script>
    (() => {
      const $ = (id) => document.getElementById(id);
      const recipientName = $('recipientName');
      const recipientType = $('recipientType');
      const wishOutput = $('wishOutput');
      let wishVariant = 0;
      let toastTimer;
      let audioContext = null;
      let audioTimer = null;
      let audioPlaying = false;
      let lastFocus = null;

      const wishes = {
        all: [
          'Gửi {NAME} – bông hoa xinh đẹp giữa cuộc đời!\n\nNhân ngày Phụ nữ Việt Nam 20/10, chúc {NAME} luôn giữ vững sự tự tin, rạng rỡ và bản lĩnh. Mong mỗi ngày đều ngập tràn niềm vui, nụ cười và hạnh phúc bên những người thân yêu!',
          'Thân gửi {NAME}!\n\nChúc {NAME} một ngày 20/10 thật dịu dàng, nhận thật nhiều yêu thương và luôn được trân trọng. Mong những điều tốt đẹp nhất sẽ nở hoa trên hành trình của {NAME} hôm nay và cả những ngày sau.'
        ],
        mom: [
          'Gửi {NAME} kính yêu!\n\nNhân ngày 20/10, con xin gửi tới {NAME} lời tri ân sâu sắc từ đáy lòng. Cảm ơn {NAME} đã luôn là vầng thái dương ấm áp, nuôi dưỡng con bằng tình yêu thương vô bờ bến. Chúc {NAME} thật nhiều sức khỏe, bình an và mãi nở nụ cười hạnh phúc!',
          'Gửi {NAME} yêu quý!\n\nMong mẹ luôn khỏe mạnh, an yên và vui vẻ mỗi ngày. Cảm ơn mẹ vì những điều giản dị mà lớn lao mẹ đã dành cho gia đình. Chúc mẹ luôn được yêu thương như cách mẹ vẫn yêu thương mọi người.'
        ],
        lover: [
          'Gửi {NAME} – người thương yêu quý!\n\nNgày 20/10 này, cảm ơn {NAME} vì đã đến và làm thế giới trở nên ngập tràn màu sắc, niềm vui. Chúc {NAME} luôn rạng rỡ, tự tin, thành công và nhận được thật nhiều điều ngọt ngào!',
          'Gửi {NAME} thân thương!\n\nChúc người mình quý luôn vui vẻ, bình an và tỏa sáng theo cách riêng. Mong mọi ước mơ của {NAME} đều có cơ hội thành hình, và mỗi ngày đều mang đến một lý do để mỉm cười.'
        ],
        colleague: [
          'Thân gửi {NAME}!\n\nChúc {NAME} ngày 20/10 thật nhiều niềm vui, nhận được thật nhiều hoa và lời chúc tốt đẹp. Cảm ơn {NAME} vì sự nhiệt huyết và năng lượng tích cực. Chúc {NAME} ngày càng thành công, hạnh phúc và luôn tự tin!',
          'Chúc mừng 20/10, {NAME}!\n\nChúc bạn luôn giữ được tinh thần lạc quan, gặp nhiều thuận lợi trong công việc và có thật nhiều khoảnh khắc đáng nhớ bên những người thân yêu.'
        ],
        teacher: [
          'Kính gửi {NAME}!\n\nNhân ngày 20/10, em xin gửi tới {NAME} lời chúc sức khỏe, hạnh phúc và lòng biết ơn chân thành. Cảm ơn {NAME} đã tận tụy truyền dạy tri thức và thắp sáng tương lai. Chúc cô luôn vui vẻ, bình an và giữ mãi ngọn lửa nhiệt huyết!',
          'Kính chúc {NAME} một ngày 20/10 thật ấm áp!\n\nEm xin cảm ơn cô vì sự tận tâm, bao dung và những bài học quý giá. Chúc cô luôn mạnh khỏe, hạnh phúc, gặp nhiều niềm vui và luôn được học trò yêu quý.'
        ],
        sister: [
          'Gửi {NAME} thân mến!\n\nChúc {NAME} luôn vui tươi, tự tin, gặp nhiều may mắn và đạt được những điều mình mong ước. Mong cuộc sống sẽ dành tặng {NAME} thật nhiều cơ hội, tiếng cười và những người chân thành bên cạnh!',
          'Chúc {NAME} một ngày 20/10 ngập tràn niềm vui!\n\nMong bạn luôn mạnh mẽ theo cách của riêng mình, dịu dàng với bản thân và không quên rằng bạn xứng đáng với những điều tốt đẹp.'
        ]
      };
      const categoryLabels = { all: 'Chị Em Phụ Nữ', mom: 'Mẹ Kính Yêu', lover: 'Người Thương', colleague: 'Bạn Thân Mến', teacher: 'Cô Giáo Kính Yêu', sister: 'Chị Em Gái' };

      function getName() {
        const name = recipientName.value.trim();
        return name || (recipientType.value === 'mom' ? 'Mẹ' : recipientType.value === 'teacher' ? 'Cô' : recipientType.value === 'all' ? 'bạn' : 'bạn');
      }
      function renderWish() {
        const type = recipientType.value;
        const variants = wishes[type] || wishes.all;
        const name = getName();
        wishOutput.textContent = variants[wishVariant % variants.length].replaceAll('{NAME}', name);
        const displayName = recipientName.value.trim() || categoryLabels[type] || 'Chị Em Phụ Nữ';
        $('letterNamePreview').textContent = displayName;
        $('envelopeRecipientLabel')?.replaceChildren(document.createTextNode(displayName));
        $('modalTitle').textContent = `Gửi ${displayName},`;
        $('modalLetter').textContent = `Nhân ngày Phụ nữ Việt Nam 20/10, xin gửi tới ${displayName} – người phụ nữ tuyệt vời – những lời chúc trân trọng và dịu dàng nhất.\n\nCảm ơn ${displayName} vì đã luôn cống hiến, mang đến cho thế giới những nụ cười ấm áp, sự bao dung và bản lĩnh kiên cường. ${displayName} luôn tỏa sáng theo một cách rất riêng.\n\nNguyện chúc chặng đường phía trước của ${displayName} luôn ngập tràn ánh nắng ấm áp, hoa nở rực rỡ và đong đầy hạnh phúc bên những người thân yêu!`;
      }
      function showToast(message) {
        const toast = $('toast');
        toast.textContent = message;
        toast.classList.add('show');
        clearTimeout(toastTimer);
        toastTimer = setTimeout(() => toast.classList.remove('show'), 2300);
      }
      async function copyText(value, successMessage) {
        try {
          if (navigator.clipboard && window.isSecureContext) {
            await navigator.clipboard.writeText(value);
          } else {
            const area = document.createElement('textarea');
            area.value = value; area.style.position = 'fixed'; area.style.opacity = '0';
            document.body.appendChild(area); area.select();
            const ok = document.execCommand('copy'); area.remove();
            if (!ok) throw new Error('Copy command failed');
          }
          showToast(successMessage);
        } catch (_) { showToast('Không sao chép được tự động. Bạn hãy nhấn giữ để sao chép nhé.'); }
      }
      $('copyWish').addEventListener('click', () => copyText(wishOutput.textContent, 'Đã sao chép lời chúc! ♡'));
      $('copyLetter').addEventListener('click', () => copyText(`${$('modalTitle').textContent}\n\n${$('modalLetter').textContent}\n\n${document.querySelector('.modal-sign').textContent}`, 'Đã sao chép bức thư! ♡'));
      $('refreshWish').addEventListener('click', () => { wishVariant++; renderWish(); showToast('Đã tạo một lời chúc mới ✨'); });
      recipientType.addEventListener('change', () => { wishVariant = 0; renderWish(); });
      recipientName.addEventListener('input', renderWish);

      const mobileNav = $('mobileNav');
      $('menuToggle').addEventListener('click', () => {
        const open = mobileNav.classList.toggle('open');
        $('menuToggle').setAttribute('aria-expanded', String(open));
        $('menuToggle').setAttribute('aria-label', open ? 'Đóng menu' : 'Mở menu');
        $('menuToggle').textContent = open ? '×' : '☰';
      });
      mobileNav.querySelectorAll('a').forEach(link => link.addEventListener('click', () => {
        mobileNav.classList.remove('open'); $('menuToggle').setAttribute('aria-expanded', 'false'); $('menuToggle').setAttribute('aria-label', 'Mở menu'); $('menuToggle').textContent = '☰';
      }));

      function sparkle(count = 34) {
        const layer = $('sparkLayer');
        const symbols = ['✦','✧','♡','♥','✨','🌸'];
        for (let i = 0; i < count; i++) {
          const node = document.createElement('span');
          node.className = 'spark'; node.textContent = symbols[Math.floor(Math.random() * symbols.length)];
          node.style.left = `${Math.random() * 100}%`;
          node.style.fontSize = `${12 + Math.random() * 18}px`;
          node.style.animationDelay = `${Math.random() * .8}s`;
          node.style.animationDuration = `${2 + Math.random() * 1.7}s`;
          layer.appendChild(node); setTimeout(() => node.remove(), 4800);
        }
      }
      $('fireworksBtn').addEventListener('click', () => { sparkle(40); showToast('Pháo hoa yêu thương dành tặng phái đẹp! ✨'); });
      $('envelopeFireworks').addEventListener('click', () => { sparkle(50); showToast('Gửi ngàn tia sáng và lời chúc tốt đẹp! ✨'); });
      $('hugBtn').addEventListener('click', () => { sparkle(55); showToast('Đã gửi một vòng tay yêu thương đến tất cả phái đẹp! 💗'); });

      const envelopeWrap = $('envelopeWrap');
      function toggleEnvelope() {
        const open = envelopeWrap.classList.toggle('open');
        envelopeWrap.setAttribute('aria-expanded', String(open));
        $('envelopeCaption').textContent = open ? 'Phong thư đã mở – hãy đọc lời nhắn bên trong 💌' : 'Chạm nhẹ vào con dấu vàng để mở thư ✨';
        if (open) sparkle(16);
      }
      envelopeWrap.addEventListener('click', toggleEnvelope);
      envelopeWrap.addEventListener('keydown', (event) => { if (event.key === 'Enter' || event.key === ' ') { event.preventDefault(); toggleEnvelope(); } });

      const modal = $('letterModal');
      function openModal() {
        lastFocus = document.activeElement; modal.classList.add('open'); modal.setAttribute('aria-hidden', 'false'); document.body.classList.add('modal-open'); $('closeModal').focus();
      }
      function closeModal() {
        modal.classList.remove('open'); modal.setAttribute('aria-hidden', 'true'); document.body.classList.remove('modal-open'); if (lastFocus && typeof lastFocus.focus === 'function') lastFocus.focus();
      }
      $('openLetterBtn').addEventListener('click', openModal);
      $('closeModal').addEventListener('click', closeModal);
      modal.addEventListener('click', event => { if (event.target === modal) closeModal(); });
      document.addEventListener('keydown', event => { if (event.key === 'Escape' && modal.classList.contains('open')) closeModal(); });
      $('modalCelebrate').addEventListener('click', () => sparkle(45));

      // Âm piano tổng hợp nhẹ; âm thanh chỉ phát sau khi người dùng chạm nút.
      const chords = [[261.63,329.63,392.00,493.88],[220,261.63,329.63,392],[174.61,220,261.63,349.23],[196,246.94,293.66,392]];
      function playNote(freq, when, duration = 2.5) {
        if (!audioContext) return;
        const osc = audioContext.createOscillator(); const gain = audioContext.createGain();
        osc.type = 'sine'; osc.frequency.setValueAtTime(freq, when);
        gain.gain.setValueAtTime(.0001, when); gain.gain.exponentialRampToValueAtTime(.045, when + .06); gain.gain.exponentialRampToValueAtTime(.0001, when + duration);
        osc.connect(gain); gain.connect(audioContext.destination); osc.start(when); osc.stop(when + duration + .05);
      }
      function scheduleMusic() {
        if (!audioPlaying || !audioContext) return;
        const chord = chords[Math.floor(Math.random() * chords.length)]; const start = audioContext.currentTime + .05;
        chord.forEach((note, i) => playNote(note, start + i * .28, 2.4));
        audioTimer = setTimeout(scheduleMusic, 2700);
      }
      $('musicToggle').addEventListener('click', async () => {
        const button = $('musicToggle');
        const status = $('musicStatus');
        try {
          if (audioPlaying) {
            audioPlaying = false;
            clearTimeout(audioTimer);
            if (audioContext && audioContext.state === 'running') await audioContext.suspend();
            button.setAttribute('aria-label', 'Bật nhạc nền');
            button.setAttribute('aria-pressed', 'false');
            status.textContent = 'Đã tạm dừng · Chạm để phát lại';
            showToast('Đã tạm dừng nhạc');
            return;
          }
          if (!audioContext) {
            const AudioCtx = window.AudioContext || window.webkitAudioContext;
            if (!AudioCtx) throw new Error('Audio not available');
            audioContext = new AudioCtx();
          }
          if (audioContext.state !== 'running') await audioContext.resume();
          audioPlaying = true;
          scheduleMusic();
          button.setAttribute('aria-label', 'Tắt nhạc nền');
          button.setAttribute('aria-pressed', 'true');
          status.textContent = 'Đang phát piano du dương…';
          showToast('Đã bật nhạc nền thư giãn');
        } catch (_) {
          audioPlaying = false;
          clearTimeout(audioTimer);
          button.setAttribute('aria-label', 'Bật nhạc nền');
          button.setAttribute('aria-pressed', 'false');
          status.textContent = 'Không thể phát nhạc trên trình duyệt này';
          showToast('Trình duyệt chưa hỗ trợ phát nhạc. Bạn hãy thử trình duyệt khác nhé.');
        }
      });

      renderWish();
    })();
  </script>
</body>
</html>
