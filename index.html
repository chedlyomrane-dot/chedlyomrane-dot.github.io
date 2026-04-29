<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Le Cercle — Growth Proposal</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Jost:wght@200;300;400;500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --gold: #c9a84c;
    --gold-light: #e8d08a;
    --gold-dim: rgba(201,168,76,0.18);
    --bg: #0a0905;
    --bg2: #100f0a;
    --surface: #141208;
    --text: #f0ead8;
    --text-dim: rgba(240,234,216,0.5);
    --text-muted: rgba(240,234,216,0.28);
    --line: rgba(201,168,76,0.2);
  }

  html, body {
    width: 100%; height: 100%;
    background: var(--bg);
    color: var(--text);
    font-family: 'Jost', sans-serif;
    font-weight: 300;
    overflow: hidden;
  }

  /* ── SLIDE CONTAINER ── */
  #deck {
    width: 100vw; height: 100vh;
    position: relative;
    overflow: hidden;
  }

  .slide {
    position: absolute;
    inset: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 6vh 8vw;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.7s ease, transform 0.7s ease;
    transform: translateY(24px);
  }
  .slide.active {
    opacity: 1;
    pointer-events: all;
    transform: translateY(0);
  }
  .slide.exit {
    opacity: 0;
    transform: translateY(-24px);
    transition: opacity 0.45s ease, transform 0.45s ease;
  }

  /* ── GOLD LINE DECORATION ── */
  .slide::before {
    content: '';
    position: absolute;
    top: 0; left: 8vw; right: 8vw;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
    opacity: 0.4;
  }
  .slide::after {
    content: '';
    position: absolute;
    bottom: 0; left: 8vw; right: 8vw;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
    opacity: 0.4;
  }

  /* ── AMBIENT BG ── */
  .bg-glow {
    position: fixed;
    border-radius: 50%;
    filter: blur(120px);
    pointer-events: none;
    z-index: 0;
  }
  .glow-1 {
    width: 600px; height: 600px;
    background: radial-gradient(circle, rgba(201,168,76,0.06) 0%, transparent 70%);
    top: -200px; right: -100px;
  }
  .glow-2 {
    width: 500px; height: 500px;
    background: radial-gradient(circle, rgba(201,168,76,0.04) 0%, transparent 70%);
    bottom: -200px; left: -100px;
  }

  /* ── NAVIGATION ── */
  #nav {
    position: fixed;
    bottom: 40px; left: 50%;
    transform: translateX(-50%);
    display: flex;
    align-items: center;
    gap: 16px;
    z-index: 100;
  }
  .nav-btn {
    background: none;
    border: 1px solid var(--line);
    color: var(--gold);
    font-family: 'Jost', sans-serif;
    font-size: 11px;
    font-weight: 400;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    padding: 10px 28px;
    cursor: pointer;
    transition: all 0.3s ease;
  }
  .nav-btn:hover {
    background: var(--gold-dim);
    border-color: var(--gold);
  }
  .nav-dots {
    display: flex;
    gap: 8px;
    align-items: center;
  }
  .dot {
    width: 4px; height: 4px;
    border-radius: 50%;
    background: var(--text-muted);
    transition: all 0.3s;
    cursor: pointer;
  }
  .dot.active {
    background: var(--gold);
    width: 20px;
    border-radius: 2px;
  }

  /* ── SLIDE NUMBER ── */
  #slide-num {
    position: fixed;
    top: 40px; right: 6vw;
    font-size: 11px;
    letter-spacing: 0.3em;
    color: var(--text-muted);
    font-weight: 300;
    z-index: 100;
  }

  /* ── LOGO / BRAND MARK ── */
  #brand {
    position: fixed;
    top: 36px; left: 6vw;
    font-family: 'Cormorant Garamond', serif;
    font-size: 13px;
    font-weight: 400;
    letter-spacing: 0.4em;
    color: var(--gold);
    text-transform: uppercase;
    z-index: 100;
  }

  /* ── TYPOGRAPHY ── */
  .eyebrow {
    font-size: 10px;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--gold);
    font-weight: 400;
    margin-bottom: 28px;
  }

  .display {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(3rem, 6vw, 5.5rem);
    font-weight: 300;
    line-height: 1.05;
    color: var(--text);
    text-align: center;
  }
  .display em {
    font-style: italic;
    color: var(--gold-light);
  }

  .h2 {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(2rem, 4vw, 3.6rem);
    font-weight: 300;
    line-height: 1.1;
    margin-bottom: 40px;
    text-align: center;
  }
  .h2 em { font-style: italic; color: var(--gold-light); }

  .subtitle {
    font-size: 14px;
    font-weight: 300;
    color: var(--text-dim);
    letter-spacing: 0.06em;
    text-align: center;
    line-height: 1.7;
    max-width: 560px;
    margin-top: 20px;
  }

  /* ── DIVIDER ── */
  .divider {
    width: 60px;
    height: 1px;
    background: var(--gold);
    margin: 32px auto;
    opacity: 0.6;
  }

  /* ── CONTENT LAYOUTS ── */
  .content-wrap {
    width: 100%;
    max-width: 860px;
    position: relative;
    z-index: 1;
  }

  /* ── PROBLEM LIST ── */
  .problem-list {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-top: 8px;
  }
  .problem-item {
    display: flex;
    align-items: flex-start;
    gap: 20px;
    padding: 22px 28px;
    border: 1px solid var(--line);
    background: rgba(201,168,76,0.03);
    transition: border-color 0.3s;
  }
  .problem-item:hover { border-color: rgba(201,168,76,0.4); }
  .problem-num {
    font-family: 'Cormorant Garamond', serif;
    font-size: 32px;
    font-weight: 300;
    color: var(--gold);
    opacity: 0.4;
    line-height: 1;
    flex-shrink: 0;
    min-width: 36px;
  }
  .problem-text strong {
    display: block;
    font-size: 14px;
    font-weight: 500;
    letter-spacing: 0.08em;
    color: var(--text);
    margin-bottom: 4px;
  }
  .problem-text span {
    font-size: 13px;
    color: var(--text-dim);
    line-height: 1.6;
  }

  /* ── TWO COL ── */
  .two-col {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 24px;
    margin-top: 8px;
  }
  .col-card {
    border: 1px solid var(--line);
    padding: 28px;
    background: rgba(255,255,255,0.01);
    position: relative;
    overflow: hidden;
  }
  .col-card.highlight {
    border-color: rgba(201,168,76,0.45);
    background: rgba(201,168,76,0.04);
  }
  .col-card::after {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
    opacity: 0;
    transition: opacity 0.3s;
  }
  .col-card.highlight::after { opacity: 1; }
  .col-label {
    font-size: 10px;
    letter-spacing: 0.35em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 16px;
    font-weight: 400;
  }
  .col-card ul {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
  .col-card ul li {
    font-size: 13px;
    color: var(--text-dim);
    padding-left: 16px;
    position: relative;
    line-height: 1.5;
  }
  .col-card ul li::before {
    content: '—';
    position: absolute;
    left: 0;
    color: var(--gold);
    opacity: 0.5;
  }
  .col-card.highlight ul li { color: var(--text); }

  /* ── SYSTEM FLOW ── */
  .system-flow {
    display: flex;
    align-items: stretch;
    gap: 0;
    margin-top: 8px;
  }
  .flow-step {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 28px 16px;
    border: 1px solid var(--line);
    position: relative;
    background: rgba(201,168,76,0.02);
    transition: background 0.3s;
  }
  .flow-step:not(:last-child) { border-right: none; }
  .flow-step:hover { background: rgba(201,168,76,0.06); }
  .flow-icon {
    font-size: 22px;
    margin-bottom: 14px;
    display: block;
  }
  .flow-title {
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--gold);
    font-weight: 500;
    margin-bottom: 10px;
  }
  .flow-desc {
    font-size: 12px;
    color: var(--text-dim);
    line-height: 1.6;
  }
  .flow-arrow {
    position: absolute;
    right: -12px;
    top: 50%;
    transform: translateY(-50%);
    color: var(--gold);
    font-size: 14px;
    z-index: 2;
    opacity: 0.5;
  }

  /* ── OFFER CARDS ── */
  .offer-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 24px;
    margin-top: 8px;
  }
  .offer-card {
    border: 1px solid var(--line);
    padding: 32px 28px;
    position: relative;
  }
  .offer-tag {
    font-size: 10px;
    letter-spacing: 0.35em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 12px;
    font-weight: 400;
  }
  .offer-price {
    font-family: 'Cormorant Garamond', serif;
    font-size: 2.4rem;
    font-weight: 300;
    color: var(--text);
    margin-bottom: 4px;
  }
  .offer-price span {
    font-size: 1rem;
    color: var(--text-dim);
    font-family: 'Jost', sans-serif;
  }
  .offer-note {
    font-size: 11px;
    color: var(--text-muted);
    margin-bottom: 20px;
    letter-spacing: 0.05em;
  }
  .offer-items {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 8px;
  }
  .offer-items li {
    font-size: 12px;
    color: var(--text-dim);
    display: flex;
    align-items: flex-start;
    gap: 10px;
    line-height: 1.5;
  }
  .offer-items li::before {
    content: '✦';
    color: var(--gold);
    font-size: 8px;
    margin-top: 3px;
    flex-shrink: 0;
    opacity: 0.7;
  }

  /* ── ROI STATEMENT ── */
  .roi-wrap {
    text-align: center;
    margin-top: 32px;
    padding: 24px;
    border: 1px solid rgba(201,168,76,0.3);
    background: rgba(201,168,76,0.05);
  }
  .roi-stat {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(2rem, 4vw, 3.2rem);
    font-weight: 300;
    color: var(--gold-light);
    margin-bottom: 8px;
  }
  .roi-sub {
    font-size: 12px;
    color: var(--text-dim);
    letter-spacing: 0.1em;
  }

  /* ── OBJECTION GRID ── */
  .obj-grid {
    display: flex;
    flex-direction: column;
    gap: 16px;
    margin-top: 8px;
  }
  .obj-row {
    display: grid;
    grid-template-columns: 1fr 40px 1fr;
    gap: 12px;
    align-items: center;
  }
  .obj-doubt {
    border: 1px solid var(--line);
    padding: 18px 20px;
    font-size: 13px;
    color: var(--text-muted);
    font-style: italic;
    line-height: 1.5;
  }
  .obj-arrow {
    text-align: center;
    color: var(--gold);
    font-size: 16px;
  }
  .obj-answer {
    border: 1px solid rgba(201,168,76,0.35);
    background: rgba(201,168,76,0.04);
    padding: 18px 20px;
    font-size: 13px;
    color: var(--text);
    line-height: 1.5;
  }

  /* ── CTA SLIDE ── */
  .cta-wrap {
    text-align: center;
    max-width: 640px;
  }
  .cta-steps {
    display: flex;
    justify-content: center;
    gap: 48px;
    margin: 40px 0;
  }
  .cta-step {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
  }
  .cta-step-num {
    width: 36px; height: 36px;
    border: 1px solid var(--gold);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 12px;
    color: var(--gold);
    letter-spacing: 0.05em;
  }
  .cta-step-label {
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--text-dim);
    text-align: center;
    line-height: 1.5;
    max-width: 90px;
  }
  .cta-connector {
    width: 48px; height: 1px;
    background: var(--line);
    margin-top: 18px;
  }
  .cta-quote {
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(1.1rem, 2vw, 1.5rem);
    font-style: italic;
    font-weight: 300;
    color: var(--text-dim);
    line-height: 1.6;
    margin-top: 32px;
  }

  /* ── SLIDE 1 SPECIFIC ── */
  .cover-ornament {
    width: 1px;
    height: 80px;
    background: linear-gradient(180deg, transparent, var(--gold), transparent);
    margin: 28px auto;
    opacity: 0.5;
  }

  /* ── KEYBOARD HINT ── */
  #hint {
    position: fixed;
    bottom: 100px;
    right: 6vw;
    font-size: 10px;
    color: var(--text-muted);
    letter-spacing: 0.2em;
    text-transform: uppercase;
    z-index: 100;
  }

  /* ── PROGRESS BAR ── */
  #progress {
    position: fixed;
    top: 0; left: 0;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--gold));
    transition: width 0.6s ease;
    z-index: 200;
  }

  /* staggered animation for children */
  .slide.active .anim-child {
    animation: fadeUp 0.6s ease forwards;
  }
  .slide.active .anim-child:nth-child(1) { animation-delay: 0.1s; opacity: 0; }
  .slide.active .anim-child:nth-child(2) { animation-delay: 0.2s; opacity: 0; }
  .slide.active .anim-child:nth-child(3) { animation-delay: 0.3s; opacity: 0; }
  .slide.active .anim-child:nth-child(4) { animation-delay: 0.4s; opacity: 0; }
  .slide.active .anim-child:nth-child(5) { animation-delay: 0.5s; opacity: 0; }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(16px); }
    to   { opacity: 1; transform: translateY(0); }
  }
</style>
</head>
<body>

<div class="bg-glow glow-1"></div>
<div class="bg-glow glow-2"></div>

<div id="progress"></div>
<div id="brand">Confidentiel</div>
<div id="slide-num">01 / 07</div>

<!-- ═══════════════════════════════════════════ -->
<!-- SLIDE 1 — COVER -->
<!-- ═══════════════════════════════════════════ -->
<div id="deck">
<div class="slide active" id="s1">
  <div class="content-wrap" style="text-align:center;">
    <div class="eyebrow anim-child">Proposition stratégique — 2026</div>
    <div class="display anim-child">
      De la visibilité<br>à la <em>clientèle</em>
    </div>
    <div class="cover-ornament anim-child"></div>
    <div class="subtitle anim-child">
      Comment transformer votre présence en ligne<br>en un système d'acquisition de clients 10k€ – 50k€
    </div>
    <div style="margin-top:40px;font-size:11px;letter-spacing:0.3em;color:var(--text-muted);" class="anim-child">
      Le Cercle — Growth Proposal
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════ -->
<!-- SLIDE 2 — THE REAL PROBLEM -->
<!-- ═══════════════════════════════════════════ -->
<div class="slide" id="s2">
  <div class="content-wrap">
    <div class="eyebrow anim-child" style="text-align:center;">La réalité du marché</div>
    <div class="h2 anim-child">Votre service est <em>exceptionnel.</em><br>Mais personne ne le sait.</div>
    <div class="problem-list anim-child">
      <div class="problem-item">
        <div class="problem-num">01</div>
        <div class="problem-text">
          <strong>Visibilité sans stratégie</strong>
          <span>Poster du contenu ne suffit pas. Sans système, vous attirez les mauvaises personnes — ou personne.</span>
        </div>
      </div>
      <div class="problem-item">
        <div class="problem-num">02</div>
        <div class="problem-text">
          <strong>Le client haute gamme ne cherche pas — il est convaincu</strong>
          <span>Votre cible ne scroll pas Instagram en mode "achat". Elle doit être attirée, rassurée, et guidée.</span>
        </div>
      </div>
      <div class="problem-item">
        <div class="problem-num">03</div>
        <div class="problem-text">
          <strong>Un écart entre votre offre et votre présence</strong>
          <span>Votre service vaut 50 000€. Est-ce que votre image en ligne le reflète aujourd'hui ?</span>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════ -->
<!-- SLIDE 3 — REFRAME -->
<!-- ═══════════════════════════════════════════ -->
<div class="slide" id="s3">
  <div class="content-wrap">
    <div class="eyebrow anim-child" style="text-align:center;">La distinction essentielle</div>
    <div class="h2 anim-child">Ce n'est pas un problème<br>de <em>contenu.</em> C'est un problème de <em>système.</em></div>
    <div class="two-col anim-child">
      <div class="col-card">
        <div class="col-label">❌ L'approche ordinaire</div>
        <ul>
          <li>Poster régulièrement</li>
          <li>Faire de beaux reels</li>
          <li>Gagner des abonnés</li>
          <li>Espérer que ça convertit</li>
          <li>Recommencer chaque mois</li>
        </ul>
      </div>
      <div class="col-card highlight">
        <div class="col-label">✦ L'approche système</div>
        <ul>
          <li>Contenu pensé pour attirer votre client idéal</li>
          <li>Parcours clair du Reel à la réservation</li>
          <li>Site optimisé pour convertir</li>
          <li>Stratégie qui s'améliore chaque mois</li>
          <li>Un actif qui travaille pour vous</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════ -->
<!-- SLIDE 4 — THE SYSTEM -->
<!-- ═══════════════════════════════════════════ -->
<div class="slide" id="s4">
  <div class="content-wrap">
    <div class="eyebrow anim-child" style="text-align:center;">La méthode</div>
    <div class="h2 anim-child">Un système d'acquisition<br><em>complet</em> et <em>cohérent</em></div>
    <div class="system-flow anim-child">
      <div class="flow-step">
        <span class="flow-icon">✦</span>
        <div class="flow-title">Positionnement</div>
        <div class="flow-desc">Clarifier votre client idéal & repositionner l'offre en expérience luxe</div>
        <span class="flow-arrow">›</span>
      </div>
      <div class="flow-step">
        <span class="flow-icon">◈</span>
        <div class="flow-title">Contenu</div>
        <div class="flow-desc">Reels stratégiques : POV luxe, autorité, exclusivité, transformation</div>
        <span class="flow-arrow">›</span>
      </div>
      <div class="flow-step">
        <span class="flow-icon">⬡</span>
        <div class="flow-title">Funnel</div>
        <div class="flow-desc">Instagram → Site → Capture → WhatsApp → Conversion</div>
        <span class="flow-arrow">›</span>
      </div>
      <div class="flow-step">
        <span class="flow-icon">◎</span>
        <div class="flow-title">Optimisation</div>
        <div class="flow-desc">Site revu pour convertir. Tracking. Analyse mensuelle. Amélioration continue.</div>
      </div>
    </div>
    <div style="text-align:center;margin-top:24px;font-size:12px;color:var(--text-muted);letter-spacing:0.1em;" class="anim-child">
      Chaque élément alimente le suivant. Rien n'est isolé.
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════ -->
<!-- SLIDE 5 — CONTENT DETAIL -->
<!-- ═══════════════════════════════════════════ -->
<div class="slide" id="s5">
  <div class="content-wrap">
    <div class="eyebrow anim-child" style="text-align:center;">Le contenu qui convertit</div>
    <div class="h2 anim-child">Chaque Reel a un <em>rôle précis</em><br>dans le parcours client</div>
    <div class="two-col anim-child">
      <div class="col-card" style="border-color:rgba(201,168,76,0.25)">
        <div class="col-label">Les 4 types de contenu</div>
        <ul>
          <li><strong style="color:var(--text)">POV Luxe</strong> — Faire vivre l'expérience avant l'achat</li>
          <li><strong style="color:var(--text)">Transformation</strong> — Avant / après le séjour en Ibiza</li>
          <li><strong style="color:var(--text)">Autorité</strong> — Expertise, coulisses, storytelling</li>
          <li><strong style="color:var(--text)">Exclusivité</strong> — Rareté, urgence, accès limité</li>
        </ul>
      </div>
      <div class="col-card" style="border-color:rgba(201,168,76,0.25)">
        <div class="col-label">Ce que je crée pour vous</div>
        <ul>
          <li>Stratégie de contenu mensuelle</li>
          <li>Scripts Reels prêts à filmer</li>
          <li>Calendrier éditorial</li>
          <li>Montage (optionnel)</li>
          <li>Analyse des performances</li>
        </ul>
      </div>
    </div>
    <div class="roi-wrap anim-child" style="margin-top:20px;padding:16px 24px;">
      <p style="font-size:12px;color:var(--text-dim);letter-spacing:0.08em;">
        Vous filmez ce qui se passe déjà. <strong style="color:var(--text)">Je transforme ça en outil d'acquisition.</strong>
      </p>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════ -->
<!-- SLIDE 6 — OFFER & PRICING -->
<!-- ═══════════════════════════════════════════ -->
<div class="slide" id="s6">
  <div class="content-wrap">
    <div class="eyebrow anim-child" style="text-align:center;">La proposition</div>
    <div class="h2 anim-child">Un investissement <em>calculé,</em><br>pas une dépense</div>
    <div class="offer-grid anim-child">
      <div class="offer-card">
        <div class="offer-tag">Phase 01 — Fondation</div>
        <div class="offer-price">1500 <span>DT</span></div>
        <div class="offer-note">Paiement unique · 2–3 semaines</div>
        <ul class="offer-items">
          <li>Audit complet de votre présence</li>
          <li>Définition du client idéal & positionnement</li>
          <li>Stratégie de marketing globale</li>
          <li>Optimisation site & parcours client</li>
          <li>Mise en place du système de capture</li>
        </ul>
      </div>
      <div class="offer-card" style="border-color:rgba(201,168,76,0.45);background:rgba(201,168,76,0.04);">
        <div class="offer-tag">Phase 02 — Croissance mensuelle</div>
        <div class="offer-price">1 200 – 2 200 <span>DT/mois</span></div>
        <div class="offer-note">Contrat mensuel · Sans engagement long</div>
        <ul class="offer-items">
          <li>Stratégie de contenu mensuelle</li>
          <li>Scripts & Posts (2–16/mois)</li>
          <li>Analyse des performances</li>
          <li>Optimisation continue du funnel</li>
          <li>Support stratégique illimité</li>
        </ul>
      </div>
    </div>
    <div class="roi-wrap anim-child">
      <div class="roi-stat">1 client = 1 à 2% d'une seule réservation</div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════ -->
<!-- SLIDE 8 — CTA / NEXT STEP -->
<!-- ═══════════════════════════════════════════ -->
<div class="slide" id="s8">
  <div class="cta-wrap">
    <div class="eyebrow anim-child">La prochaine étape</div>
    <div class="display anim-child" style="font-size:clamp(2.2rem,4.5vw,4rem);margin-bottom:0;">
      Construisons votre<br><em>système ensemble</em>
    </div>
    <div class="divider anim-child"></div>
    <div class="cta-steps anim-child">
      <div class="cta-step">
        <div class="cta-step-num">01</div>
        <div class="cta-step-label">Audit stratégique gratuit</div>
      </div>
      <div class="cta-connector" style="margin-top:18px;"></div>
      <div class="cta-step">
        <div class="cta-step-num">02</div>
        <div class="cta-step-label">Proposition personnalisée</div>
      </div>
      <div class="cta-connector" style="margin-top:18px;"></div>
      <div class="cta-step">
        <div class="cta-step-num">03</div>
        <div class="cta-step-label">Lancement de la Phase 01</div>
      </div>
    </div>
    <div class="cta-quote anim-child">
      "Ce n'est pas une dépense marketing.<br>C'est votre prochain client qui attend d'être convaincu."
    </div>
    <div style="margin-top:36px;font-size:11px;letter-spacing:0.3em;color:var(--text-muted);" class="anim-child">
      CONFIDENTIEL · PROPOSÉ PAR Chedly Omrane & Hamza Ben Chaaben
    </div>
  </div>
</div>

</div><!-- #deck -->

<!-- Navigation -->
<div id="nav">
  <button class="nav-btn" id="prevBtn" onclick="navigate(-1)">← Précédent</button>
  <div class="nav-dots" id="dots"></div>
  <button class="nav-btn" id="nextBtn" onclick="navigate(1)">Suivant →</button>
</div>

<div id="hint">← → pour naviguer</div>

<script>
  let current = 0;
  let animating = false;

  const slides = Array.from(document.querySelectorAll('.slide'));
  const totalSlides = slides.length;
  const dotsContainer = document.getElementById('dots');
  const slideNum = document.getElementById('slide-num');
  const progress = document.getElementById('progress');

  // Create dots
  slides.forEach((_, i) => {
    const d = document.createElement('div');
    d.className = 'dot' + (i === 0 ? ' active' : '');
    d.onclick = () => goTo(i);
    dotsContainer.appendChild(d);
  });

  function updateUI() {
    const pct = ((current + 1) / totalSlides) * 100;
    progress.style.width = pct + '%';
    slideNum.textContent = String(current + 1).padStart(2,'0') + ' / ' + String(totalSlides).padStart(2,'0');
    document.querySelectorAll('.dot').forEach((d,i) => d.classList.toggle('active', i === current));
  }

  function goTo(idx) {
    if (animating || idx === current) return;
    animating = true;
    const old = slides[current];
    old.classList.add('exit');
    old.classList.remove('active');
    setTimeout(() => { old.classList.remove('exit'); }, 450);

    current = idx;
    const next = slides[current];
    next.classList.add('active');
    updateUI();
    setTimeout(() => { animating = false; }, 700);
  }

  function navigate(dir) {
    const idx = current + dir;
    if (idx < 0 || idx >= totalSlides) return;
    goTo(idx);
  }

  document.addEventListener('keydown', e => {
    if (e.key === 'ArrowRight' || e.key === 'ArrowDown') navigate(1);
    if (e.key === 'ArrowLeft' || e.key === 'ArrowUp') navigate(-1);
  });

  // Touch/swipe
  let startX = 0;
  document.addEventListener('touchstart', e => { startX = e.touches[0].clientX; });
  document.addEventListener('touchend', e => {
    const dx = e.changedTouches[0].clientX - startX;
    if (Math.abs(dx) > 50) navigate(dx < 0 ? 1 : -1);
  });

  updateUI();
</script>
</body>
</html>
