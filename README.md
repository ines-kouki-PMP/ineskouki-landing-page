<!DOCTYPE html>
<html lang="fr" style="color-scheme: dark;">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#2E1F47">
<title>Inès Kouki</title>
<meta name="description" content="Consultante senior en transformation. 17 ans chez BNP Paribas, Société Générale, IDEMIA, Philip Morris. Réservez un appel de clarté de 30 minutes gratuit pour clarifier votre rôle, votre posture et votre trajectoire.">

<!-- Open Graph (LinkedIn, WhatsApp, Facebook, Slack) -->
<meta property="og:type" content="website">
<meta property="og:site_name" content="Inès Kouki">
<meta property="og:title" content="Clarify Your Positioning — Inès Kouki">
<meta property="og:description" content="Consultante senior en transformation. Clarifiez votre rôle, renforcez votre posture, accélérez votre trajectoire. Book a discovery call.">
<meta property="og:url" content="https://ines-kouki-pmp.github.io/ineskouki/">
<meta property="og:image" content="https://ines-kouki-pmp.github.io/ineskouki/og-preview.jpg">
<meta property="og:image:secure_url" content="https://ines-kouki-pmp.github.io/ineskouki/og-preview.jpg">
<meta property="og:image:type" content="image/jpeg">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
<meta property="og:image:alt" content="Clarify Your Positioning — Book a discovery call with Inès Kouki">
<meta property="og:locale" content="fr_FR">

<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Clarify Your Positioning — Inès Kouki">
<meta name="twitter:description" content="Consultante senior en transformation. Clarifiez votre rôle, renforcez votre posture, accélérez votre trajectoire.">
<meta name="twitter:image" content="https://ines-kouki-pmp.github.io/ineskouki/og-preview.jpg">
<meta name="twitter:image:alt" content="Clarify Your Positioning — Book a discovery call with Inès Kouki">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,400;1,500&family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">

<style>
:root {
  /* Palette V2 — Violet Nuit / Rose Poudré / Blanc Nacré */
  --midnight: #2E1F47;          /* Violet Nuit — fond principal, autorité */
  --deep-navy: #3A2856;         /* variation un cran plus claire */
  --slate: #5A4878;             /* texte mid-tone */
  --cream: #FAF7F2;             /* Blanc Nacré — texte/respiration */
  --ivory: #F5F0E8;             /* fond cartes clairs */
  --pearl: #E8DFD2;             /* séparateurs */
  --warm-gray: #A99CB8;         /* texte secondaire (warm violet-gray) */
  --terracotta: #C4789A;        /* Rose Poudré — accent principal, CTA */
  --terracotta-deep: #A55F7E;   /* hover du CTA */
  --teal: #4B7F8C;              /* Pilier P — Posture */
  --sage: #6B8068;              /* Pilier T — Trajectoire */

  --display: "Cormorant Garamond", Georgia, serif;
  --body: "DM Sans", -apple-system, BlinkMacSystemFont, "Helvetica Neue", sans-serif;
  --mono: "JetBrains Mono", "Courier New", monospace;
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; }

body {
  background: var(--midnight);
  color: var(--cream);
  font-family: var(--body);
  font-size: 16px;
  line-height: 1.6;
  font-weight: 400;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  overflow-x: hidden;
}

/* Skip link for keyboard users */
.skip-link {
  position: absolute;
  left: -9999px;
  top: 8px;
  background: var(--terracotta);
  color: var(--cream);
  padding: 12px 20px;
  font-family: var(--mono);
  font-size: 12px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  z-index: 100;
}
.skip-link:focus-visible {
  left: 8px;
}

/* Focus styles — visible rings for all interactive elements */
a:focus-visible,
button:focus-visible,
input:focus-visible {
  outline: 2px solid var(--terracotta);
  outline-offset: 3px;
}

/* Touch targets */
button, a, input, label {
  touch-action: manipulation;
  -webkit-tap-highlight-color: transparent;
}

/* Grain overlay — adds editorial texture */
body::before {
  content: "";
  position: fixed; inset: 0;
  pointer-events: none;
  z-index: 1;
  opacity: 0.035;
  background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='200' height='200'><filter id='n'><feTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2'/></filter><rect width='200' height='200' filter='url(%23n)'/></svg>");
}

.container { width: 100%; max-width: 1280px; margin: 0 auto; padding: 0 40px; }

a { color: inherit; text-decoration: none; }

/* ——— NAV ——— */
.nav {
  position: relative;
  z-index: 10;
  padding: 28px 0;
  border-bottom: 1px solid rgba(250, 247, 242, 0.08);
}
.nav-inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 24px;
}
.nav-brand {
  font-family: var(--display);
  font-size: 22px;
  font-weight: 500;
  letter-spacing: 0.01em;
  color: var(--cream);
}
.nav-brand-sub {
  display: block;
  font-family: var(--mono);
  font-size: 10px;
  font-weight: 400;
  letter-spacing: 0.18em;
  color: var(--warm-gray);
  text-transform: uppercase;
  margin-top: 2px;
}
.nav-cta {
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--cream);
  padding: 12px 20px;
  border: 1px solid rgba(250, 247, 242, 0.2);
  transition: background-color 0.3s ease, border-color 0.3s ease, color 0.3s ease;
}
.nav-cta:hover {
  background: var(--terracotta);
  border-color: var(--terracotta);
}

/* ——— HERO ——— */
.hero {
  position: relative;
  padding: 100px 0 120px;
  overflow: hidden;
}
.hero::before {
  content: "";
  position: absolute;
  top: 10%; right: -10%;
  width: 500px; height: 500px;
  background: radial-gradient(circle, rgba(196, 120, 154, 0.12) 0%, transparent 70%);
  pointer-events: none;
}
.hero-grid {
  display: grid;
  grid-template-columns: 1.4fr 1fr;
  gap: 80px;
  align-items: center;
  position: relative;
  z-index: 2;
}
.hero-single {
  position: relative;
  z-index: 2;
  max-width: 820px;
}
.kicker {
  display: inline-block;
  font-family: var(--mono);
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 40px;
  padding-left: 48px;
  position: relative;
}
.kicker::before {
  content: "";
  position: absolute;
  left: 0; top: 50%;
  width: 36px; height: 1px;
  background: var(--terracotta);
}
.hero h1 {
  font-family: var(--display);
  font-weight: 400;
  font-size: clamp(46px, 6.2vw, 84px);
  line-height: 1.04;
  letter-spacing: -0.015em;
  color: var(--cream);
  margin-bottom: 36px;
  text-wrap: balance;
}
.hero h1 .underline-accent {
  position: relative;
  white-space: nowrap;
}
.hero h1 .underline-accent::after {
  content: "";
  position: absolute;
  left: 0; right: 0;
  bottom: -0.04em;
  height: 0.11em;
  background: var(--terracotta);
  transform: skew(-6deg);
}
.hero h1 em {
  font-style: italic;
  color: var(--cream);
}
.hero-lede {
  font-size: 19px;
  line-height: 1.55;
  color: var(--pearl);
  max-width: 540px;
  margin-bottom: 44px;
  font-weight: 300;
}
.hero-meta {
  display: flex;
  gap: 40px;
  padding-top: 28px;
  border-top: 1px solid rgba(250, 247, 242, 0.1);
  max-width: 540px;
}
.hero-meta-item {
  flex: 1;
}
.hero-meta-label {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
  margin-bottom: 6px;
}
.hero-meta-value {
  font-family: var(--display);
  font-size: 22px;
  color: var(--cream);
  font-weight: 500;
}

/* Hero secondary CTA — discreet direct-booking link */
.hero-secondary-cta {
  display: inline-flex;
  align-items: center;
  gap: 12px;
  margin-top: 28px;
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
  padding-bottom: 4px;
  border-bottom: 1px solid rgba(169, 156, 184, 0.3);
  transition: color 0.3s ease, border-color 0.3s ease, gap 0.3s ease;
}
.hero-secondary-cta:hover,
.hero-secondary-cta:focus-visible {
  color: var(--terracotta);
  border-bottom-color: var(--terracotta);
  gap: 18px;
}
.hero-secondary-cta .dot {
  width: 5px; height: 5px;
  border-radius: 50%;
  background: var(--terracotta);
  flex-shrink: 0;
}

/* ——— INTERSTITIAL CTA ——— */
.interstitial {
  background: var(--midnight);
  padding: 100px 0;
  border-top: 1px solid rgba(250, 247, 242, 0.06);
  border-bottom: 1px solid rgba(250, 247, 242, 0.06);
  position: relative;
  overflow: hidden;
}
.interstitial::before {
  content: "";
  position: absolute;
  top: -20%; left: -10%;
  width: 60%; height: 140%;
  background: radial-gradient(ellipse at left, rgba(196, 120, 154, 0.12) 0%, transparent 55%);
  pointer-events: none;
}
.interstitial-inner {
  position: relative;
  z-index: 2;
  display: grid;
  grid-template-columns: 1.3fr 1fr;
  gap: 80px;
  align-items: center;
}
.interstitial-label {
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 20px;
  display: flex;
  align-items: center;
  gap: 14px;
}
.interstitial-label::before {
  content: "";
  width: 24px; height: 1px;
  background: var(--terracotta);
}
.interstitial-title {
  font-family: var(--display);
  font-size: clamp(34px, 3.8vw, 52px);
  font-weight: 400;
  line-height: 1.12;
  letter-spacing: -0.01em;
  color: var(--cream);
  margin-bottom: 18px;
  text-wrap: balance;
}
.interstitial-title em {
  font-style: italic;
  color: var(--terracotta);
}
.interstitial-sub {
  font-family: var(--display);
  font-style: italic;
  font-size: 19px;
  line-height: 1.5;
  color: var(--pearl);
  font-weight: 400;
  max-width: 520px;
}
.interstitial-action {
  display: flex;
  justify-content: flex-end;
}
.interstitial-cta {
  display: inline-flex;
  align-items: center;
  gap: 16px;
  background: var(--terracotta);
  color: var(--cream);
  padding: 24px 38px;
  font-family: var(--mono);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  transition: background-color 0.3s ease, gap 0.3s ease;
  position: relative;
  border: 1px solid var(--terracotta);
}
.interstitial-cta::before {
  content: "";
  position: absolute;
  inset: 4px;
  border: 1px solid rgba(250, 247, 242, 0.15);
  pointer-events: none;
}
.interstitial-cta:hover,
.interstitial-cta:focus-visible {
  background: var(--terracotta-deep);
  gap: 22px;
}
.interstitial-cta .arrow {
  font-size: 14px;
  position: relative;
}
.interstitial-micro {
  margin-top: 16px;
  text-align: right;
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--warm-gray);
}

/* ——— INÈS PHOTO (with original background) ——— */
.ines-photo {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}
.ines-photo-frame {
  position: relative;
  width: 100%;
  max-width: 480px;
  aspect-ratio: 1 / 1;
  overflow: hidden;
  box-shadow:
    -16px 22px 40px rgba(0, 0, 0, 0.35),
    0 0 0 1px rgba(196, 120, 154, 0.25);
}
.ines-photo-frame img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
.ines-photo-frame::before {
  /* Subtle inner border for editorial polish */
  content: "";
  position: absolute;
  inset: 14px;
  border: 1px solid rgba(250, 247, 242, 0.18);
  pointer-events: none;
  z-index: 2;
}
.ines-photo-sigil {
  position: absolute;
  left: -8px;
  top: 50%;
  transform: translateY(-50%) rotate(180deg);
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.32em;
  text-transform: uppercase;
  color: var(--terracotta);
  z-index: 3;
  writing-mode: vertical-rl;
  white-space: nowrap;
  background: var(--midnight);
  padding: 8px 4px;
}

/* Hero primary CTA — the main button in the hero */
.hero-primary-cta {
  display: inline-flex;
  align-items: center;
  gap: 14px;
  background: var(--terracotta);
  color: var(--cream);
  padding: 20px 34px;
  margin-top: 36px;
  font-family: var(--mono);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  transition: background-color 0.3s ease, gap 0.3s ease;
  position: relative;
  border: 1px solid var(--terracotta);
}
.hero-primary-cta::before {
  content: "";
  position: absolute;
  inset: 4px;
  border: 1px solid rgba(250, 247, 242, 0.15);
  pointer-events: none;
}
.hero-primary-cta:hover,
.hero-primary-cta:focus-visible {
  background: var(--terracotta-deep);
  gap: 20px;
}

/* ——— SECTION SHARED ——— */
section { position: relative; z-index: 2; }
.section-label {
  font-family: var(--mono);
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 32px;
  display: flex;
  align-items: center;
  gap: 14px;
}
.section-label::before {
  content: "";
  width: 24px; height: 1px;
  background: var(--terracotta);
}

/* ——— MANIFESTO ——— */
.manifesto {
  background: var(--cream);
  color: var(--midnight);
  padding: 120px 0;
  position: relative;
}
.manifesto::before,
.manifesto::after {
  content: "";
  position: absolute;
  left: 0; right: 0;
  height: 80px;
  pointer-events: none;
}
.manifesto-inner {
  max-width: 860px;
  margin: 0 auto;
  text-align: left;
}
.manifesto-quote {
  font-family: var(--display);
  font-size: clamp(32px, 4vw, 52px);
  line-height: 1.22;
  font-weight: 400;
  color: var(--midnight);
  letter-spacing: -0.01em;
  margin-bottom: 40px;
  text-wrap: balance;
}
.manifesto-quote em {
  font-style: italic;
  color: var(--terracotta);
}
.manifesto-sig {
  display: flex;
  align-items: center;
  gap: 20px;
  padding-top: 24px;
  border-top: 1px solid var(--pearl);
  max-width: 380px;
}
.manifesto-sig-name {
  font-family: var(--display);
  font-size: 20px;
  font-weight: 500;
  color: var(--midnight);
}
.manifesto-sig-role {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--slate);
  margin-top: 4px;
}

/* ——— R.P.T. SECTION ——— */
.rpt {
  padding: 140px 0;
  background: var(--midnight);
}
.rpt-intro {
  max-width: 720px;
  margin-bottom: 80px;
}
.rpt-title {
  font-family: var(--display);
  font-size: clamp(38px, 4.5vw, 60px);
  font-weight: 400;
  line-height: 1.1;
  letter-spacing: -0.01em;
  margin-bottom: 24px;
  color: var(--cream);
}
.rpt-lede {
  font-size: 17px;
  line-height: 1.65;
  color: var(--pearl);
  font-weight: 300;
  max-width: 620px;
}
.rpt-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2px;
  background: rgba(250, 247, 242, 0.08);
  border: 1px solid rgba(250, 247, 242, 0.08);
}
.pillar {
  background: var(--deep-navy);
  padding: 56px 44px 52px;
  position: relative;
  transition: background 0.4s ease;
  cursor: default;
  min-height: 380px;
  display: flex;
  flex-direction: column;
}
.pillar:hover { background: #4A3568; }
.pillar-letter {
  font-family: var(--display);
  font-size: 120px;
  line-height: 1;
  font-weight: 300;
  letter-spacing: -0.02em;
  margin-bottom: 8px;
  transition: color 0.4s ease;
}
.pillar--r .pillar-letter { color: var(--terracotta); }
.pillar--p .pillar-letter { color: var(--teal); }
.pillar--t .pillar-letter { color: var(--sage); }
.pillar-tag {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--warm-gray);
  margin-bottom: 20px;
}
.pillar-name {
  font-family: var(--display);
  font-size: 30px;
  font-weight: 500;
  color: var(--cream);
  margin-bottom: 18px;
  letter-spacing: -0.005em;
}
.pillar-desc {
  font-size: 15px;
  line-height: 1.6;
  color: var(--pearl);
  font-weight: 300;
  flex: 1;
}
.pillar-result {
  margin-top: 28px;
  padding-top: 20px;
  border-top: 1px solid rgba(250, 247, 242, 0.1);
  font-family: var(--display);
  font-style: italic;
  font-size: 17px;
  line-height: 1.4;
}
.pillar--r .pillar-result { color: var(--terracotta); }
.pillar--p .pillar-result { color: var(--teal); }
.pillar--t .pillar-result { color: var(--sage); }

/* ——— POUR QUI ——— */
.pour-qui {
  background: var(--ivory);
  color: var(--midnight);
  padding: 140px 0;
}
.pour-qui-grid {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  gap: 100px;
  align-items: start;
}
.pour-qui-title {
  font-family: var(--display);
  font-size: clamp(38px, 4.5vw, 56px);
  font-weight: 400;
  line-height: 1.1;
  letter-spacing: -0.01em;
  color: var(--midnight);
}
.pour-qui-title em {
  font-style: italic;
  color: var(--terracotta);
}
.pour-qui-list {
  list-style: none;
}
.pour-qui-item {
  display: flex;
  gap: 24px;
  padding: 26px 0;
  border-bottom: 1px solid var(--pearl);
}
.pour-qui-item:last-child { border-bottom: none; }
.pour-qui-num {
  font-family: var(--mono);
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.15em;
  color: var(--terracotta);
  flex-shrink: 0;
  padding-top: 4px;
}
.pour-qui-text {
  font-family: var(--display);
  font-size: 20px;
  line-height: 1.4;
  color: var(--slate);
  font-weight: 400;
}
.pour-qui-text strong {
  color: var(--midnight);
  font-weight: 500;
}

/* ——— INÈS ——— */
.ines {
  padding: 140px 0;
  background: var(--midnight);
  border-top: 1px solid rgba(250, 247, 242, 0.06);
}
.ines-grid {
  display: grid;
  grid-template-columns: 1.2fr 1fr;
  gap: 80px;
  align-items: center;
}
.ines-name {
  font-family: var(--display);
  font-size: clamp(40px, 4.5vw, 56px);
  font-weight: 400;
  line-height: 1.05;
  letter-spacing: -0.01em;
  margin-bottom: 14px;
  color: var(--cream);
}
.ines-role {
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 36px;
}
.ines-bio {
  font-size: 17px;
  line-height: 1.7;
  color: var(--pearl);
  font-weight: 300;
  margin-bottom: 24px;
}
.ines-bio em {
  font-family: var(--display);
  font-style: italic;
  color: var(--cream);
  font-size: 19px;
}
.ines-stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 32px;
  margin-top: 40px;
  padding-top: 40px;
  border-top: 1px solid rgba(250, 247, 242, 0.1);
}
.stat-num {
  font-family: var(--display);
  font-size: 42px;
  font-weight: 400;
  line-height: 1;
  color: var(--terracotta);
  margin-bottom: 8px;
}
.stat-label {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
}

/* ——— CAPTURE ——— */
.capture {
  position: relative;
  padding: 140px 0;
  background: var(--midnight);
  overflow: hidden;
}
.capture::before {
  content: "";
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at 75% 40%, rgba(196, 120, 154, 0.14) 0%, transparent 55%);
  pointer-events: none;
}
.capture-inner {
  position: relative;
  max-width: 980px;
  margin: 0 auto;
  background: var(--deep-navy);
  border: 1px solid rgba(196, 120, 154, 0.25);
  padding: 80px;
  z-index: 2;
}
.capture-inner::before {
  content: "";
  position: absolute;
  top: 18px; left: 18px; right: 18px; bottom: 18px;
  border: 1px solid rgba(250, 247, 242, 0.05);
  pointer-events: none;
}
.capture-title {
  font-family: var(--display);
  font-size: clamp(34px, 4vw, 52px);
  font-weight: 400;
  line-height: 1.1;
  letter-spacing: -0.01em;
  color: var(--cream);
  margin-bottom: 20px;
  max-width: 720px;
}
.capture-title em {
  font-style: italic;
  color: var(--terracotta);
}
.capture-sub {
  font-size: 17px;
  line-height: 1.55;
  color: var(--pearl);
  margin-bottom: 44px;
  max-width: 640px;
  font-weight: 300;
}
.form {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 18px;
  max-width: 700px;
}
.form-row {
  grid-column: span 2;
}
.field {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.field label {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
}
.field input {
  background: transparent;
  border: none;
  border-bottom: 1px solid rgba(250, 247, 242, 0.2);
  padding: 12px 2px;
  color: var(--cream);
  font-family: var(--body);
  font-size: 16px;
  outline: none;
  transition: border-color 0.3s ease;
}
.field input:focus {
  border-bottom-color: var(--terracotta);
}
.field input::placeholder {
  color: rgba(250, 247, 242, 0.3);
}
.submit {
  margin-top: 18px;
  grid-column: span 2;
  display: flex;
  align-items: center;
  gap: 20px;
  flex-wrap: wrap;
}
.btn-primary {
  display: inline-flex;
  align-items: center;
  gap: 14px;
  background: var(--terracotta);
  color: var(--cream);
  border: none;
  padding: 20px 36px;
  font-family: var(--mono);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.3s ease;
  position: relative;
  overflow: hidden;
}
.btn-primary::before {
  content: "";
  position: absolute;
  inset: 0;
  background: var(--terracotta-deep);
  transform: translateX(-100%);
  transition: transform 0.4s ease;
}
.btn-primary span { position: relative; }
.btn-primary:hover::before { transform: translateX(0); }
.btn-primary .arrow {
  transition: transform 0.3s ease;
  position: relative;
}
.btn-primary:hover .arrow { transform: translateX(6px); }
.submit-note {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--warm-gray);
  line-height: 1.6;
  flex: 1;
  min-width: 200px;
}
.submit-note strong { color: var(--terracotta); font-weight: 500; }

.form-status {
  margin-top: 24px;
  font-family: var(--mono);
  font-size: 11px;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: var(--sage);
  min-height: 1.4em;
}
.form-status.is-error { color: var(--terracotta); }

/* ——— DIRECT CALENDLY CTA (no form) ——— */
.capture-cta {
  display: inline-flex;
  align-items: center;
  gap: 16px;
  background: var(--terracotta);
  color: var(--cream);
  padding: 24px 40px;
  margin: 8px 0 20px;
  font-family: var(--mono);
  font-size: 12px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  transition: background-color 0.3s ease, gap 0.3s ease;
  position: relative;
  border: 1px solid var(--terracotta);
}
.capture-cta::before {
  content: "";
  position: absolute;
  inset: 4px;
  border: 1px solid rgba(250, 247, 242, 0.15);
  pointer-events: none;
}
.capture-cta:hover,
.capture-cta:focus-visible {
  background: var(--terracotta-deep);
  gap: 22px;
}
.capture-note {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--warm-gray);
  line-height: 1.8;
  max-width: 520px;
}
.capture-note strong { color: var(--terracotta); font-weight: 500; }

/* ——— WHAT YOU GET ——— */
.perks {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0;
  margin-top: 56px;
  padding-top: 40px;
  border-top: 1px solid rgba(250, 247, 242, 0.08);
}
.perk {
  display: flex;
  gap: 18px;
  padding: 20px 0;
}
.perk-num {
  font-family: var(--display);
  font-style: italic;
  font-size: 28px;
  color: var(--terracotta);
  font-weight: 400;
  line-height: 1;
  flex-shrink: 0;
}
.perk-text {
  font-size: 14px;
  line-height: 1.55;
  color: var(--pearl);
}
.perk-text strong {
  color: var(--cream);
  font-weight: 500;
  display: block;
  margin-bottom: 4px;
  font-size: 15px;
}

/* ——— FOOTER ——— */
.footer {
  background: var(--midnight);
  padding: 80px 0 40px;
  border-top: 1px solid rgba(250, 247, 242, 0.08);
  position: relative;
}
.footer::before {
  /* subtle decorative glow */
  content: "";
  position: absolute;
  top: 0; left: 50%;
  width: 60%; height: 200px;
  transform: translateX(-50%);
  background: radial-gradient(ellipse at center, rgba(196, 120, 154, 0.08) 0%, transparent 70%);
  pointer-events: none;
}
.footer-grid {
  position: relative;
  display: grid;
  grid-template-columns: 1.2fr 1.4fr 1fr;
  gap: 60px;
  align-items: start;
  padding-bottom: 56px;
  border-bottom: 1px solid rgba(250, 247, 242, 0.08);
}
.footer-col-label {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--terracotta);
  margin-bottom: 18px;
  display: flex;
  align-items: center;
  gap: 12px;
}
.footer-col-label::before {
  content: "";
  width: 18px; height: 1px;
  background: var(--terracotta);
}
.footer-brand-block .footer-name {
  font-family: var(--display);
  font-size: 30px;
  font-weight: 500;
  color: var(--cream);
  line-height: 1.1;
  margin-bottom: 8px;
  letter-spacing: -0.005em;
}
.footer-tagline {
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: var(--warm-gray);
  margin-bottom: 20px;
}
.footer-tagline span { color: var(--terracotta); }
.footer-pitch {
  font-family: var(--display);
  font-style: italic;
  font-size: 16px;
  line-height: 1.5;
  color: var(--pearl);
  max-width: 280px;
}

/* Contacts */
.footer-contacts {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: column;
  gap: 16px;
}
.footer-contact-item {
  display: flex;
  align-items: center;
  gap: 14px;
  color: var(--cream);
  font-family: var(--body);
  font-size: 15px;
  transition: color 0.3s ease, gap 0.3s ease;
  line-height: 1.4;
}
.footer-contact-item:hover,
.footer-contact-item:focus-visible {
  color: var(--terracotta);
  gap: 18px;
}
.contact-icon {
  flex-shrink: 0;
  width: 36px; height: 36px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  border: 1px solid rgba(196, 120, 154, 0.3);
  color: var(--terracotta);
  transition: background-color 0.3s ease, border-color 0.3s ease;
}
.footer-contact-item:hover .contact-icon,
.footer-contact-item:focus-visible .contact-icon {
  background: var(--terracotta);
  border-color: var(--terracotta);
  color: var(--cream);
}
.contact-icon svg {
  width: 16px; height: 16px;
  display: block;
}
.contact-label {
  font-family: var(--mono);
  font-size: 9px;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--warm-gray);
  display: block;
  margin-bottom: 2px;
}
.contact-value {
  font-size: 15px;
  color: inherit;
}

/* Footer CTA mini */
.footer-cta-block {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.footer-cta {
  display: inline-flex;
  align-items: center;
  gap: 12px;
  background: transparent;
  color: var(--cream);
  padding: 14px 22px;
  font-family: var(--mono);
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  border: 1px solid var(--terracotta);
  transition: background-color 0.3s ease, gap 0.3s ease;
}
.footer-cta:hover,
.footer-cta:focus-visible {
  background: var(--terracotta);
  gap: 16px;
}

/* Footer bottom bar */
.footer-bottom {
  position: relative;
  margin-top: 32px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 16px;
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: var(--warm-gray);
}
.footer-credit { color: var(--warm-gray); }
.footer-credit em {
  font-family: var(--display);
  font-style: italic;
  font-size: 13px;
  letter-spacing: 0.02em;
  text-transform: none;
  color: var(--pearl);
}

/* ——— WHATSAPP FLOATING BUTTON ——— */
.whatsapp-fab {
  position: fixed;
  bottom: 24px;
  right: 24px;
  z-index: 50;
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: #25D366; /* WhatsApp brand green */
  color: #fff;
  padding: 14px 18px 14px 14px;
  font-family: var(--body);
  font-size: 14px;
  font-weight: 500;
  letter-spacing: 0.01em;
  border-radius: 999px;
  box-shadow:
    0 12px 28px rgba(37, 211, 102, 0.35),
    0 4px 8px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
  text-decoration: none;
}
.whatsapp-fab:hover,
.whatsapp-fab:focus-visible {
  background: #20BA5A;
  transform: translateY(-2px);
  box-shadow:
    0 16px 32px rgba(37, 211, 102, 0.45),
    0 6px 12px rgba(0, 0, 0, 0.25);
}
.whatsapp-fab svg {
  width: 24px; height: 24px;
  display: block;
}
.whatsapp-fab .wa-label {
  display: inline-block;
}

@media (max-width: 520px) {
  .whatsapp-fab {
    padding: 14px;
    bottom: 18px;
    right: auto;
    left: 50%;
    transform: translateX(-50%);
  }
  .whatsapp-fab:hover,
  .whatsapp-fab:focus-visible {
    transform: translateX(-50%) translateY(-2px);
  }
  .whatsapp-fab .wa-label {
    display: none;
  }
}

/* ——— REVEAL ——— */
.reveal {
  opacity: 0;
  transform: translateY(24px);
  transition: opacity 0.8s ease, transform 0.8s ease;
}
.reveal.is-visible {
  opacity: 1;
  transform: translateY(0);
}

/* ——— PREFERS REDUCED MOTION ——— */
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }
  .reveal { opacity: 1; transform: none; transition: none; }
}

/* ——— RESPONSIVE ——— */
@media (max-width: 960px) {
  .container { padding: 0 24px; }
  .hero { padding: 60px 0 80px; }
  .hero-grid { grid-template-columns: 1fr; gap: 60px; }
  .hero-photo { order: -1; }
  .ines-grid { grid-template-columns: 1fr; gap: 56px; }
  .ines-photo { order: -1; }
  .ines-photo-frame { max-width: 360px; }
  .ines-photo-sigil { display: none; }
  .hero-meta { gap: 24px; }
  .rpt-grid { grid-template-columns: 1fr; }
  .pour-qui-grid { grid-template-columns: 1fr; gap: 48px; }
  .interstitial { padding: 72px 0; }
  .interstitial-inner { grid-template-columns: 1fr; gap: 40px; }
  .interstitial-action { justify-content: flex-start; }
  .interstitial-micro { text-align: left; }
  .interstitial-cta { padding: 20px 28px; width: 100%; justify-content: center; }
  .capture-inner { padding: 48px 28px; }
  .perks { grid-template-columns: 1fr; }
  .manifesto, .rpt, .pour-qui, .ines, .capture { padding: 80px 0; }
  .footer-grid { grid-template-columns: 1fr; gap: 48px; padding-bottom: 40px; }
  .footer { padding: 60px 0 32px; }
}

@media (max-width: 520px) {
  .nav-cta { display: none; }
  .hero h1 { font-size: 44px; }
  .hero-meta { flex-direction: column; gap: 16px; }
  .ines-stats { gap: 20px; }
  .stat-num { font-size: 32px; }
}
</style>
</head>

<body>

<a href="#main" class="skip-link">Aller au contenu</a>

<!-- NAV -->
<nav class="nav">
  <div class="container nav-inner">
    <div>
      <div class="nav-brand">Inès Kouki</div>
      <div class="nav-brand-sub">Rôle · Posture · Trajectoire</div>
    </div>
    <a href="#capture" class="nav-cta">Réserver un appel</a>
  </div>
</nav>

<!-- HERO -->
<main id="main">
<section class="hero">
  <div class="container">
    <div class="hero-single">
      <h1 class="reveal">La transformation échoue quand les <span class="underline-accent">rôles sont flous</span>.</h1>
      <p class="hero-lede reveal">
        17&nbsp;ans à piloter des programmes de transformation dans la banque, le retail et la tech. Aujourd'hui, j'accompagne les femmes en transformation Agile à clarifier leur rôle, renforcer leur posture et piloter leur trajectoire.
      </p>
      <div class="hero-meta reveal">
        <div class="hero-meta-item">
          <div class="hero-meta-label">Terrain</div>
          <div class="hero-meta-value">17&nbsp;ans</div>
        </div>
        <div class="hero-meta-item">
          <div class="hero-meta-label">Pays</div>
          <div class="hero-meta-value">4</div>
        </div>
        <div class="hero-meta-item">
          <div class="hero-meta-label">Secteurs</div>
          <div class="hero-meta-value">3</div>
        </div>
      </div>

      <a href="https://calendly.com/ines-kouki-yb9r/30min" class="hero-primary-cta reveal">
        <span>Réserver mon appel gratuit</span>
        <span aria-hidden="true">→</span>
      </a>
    </div>
  </div>
</section>

<!-- MANIFESTO -->
<section class="manifesto">
  <div class="container">
    <div class="manifesto-inner reveal">
      <div class="section-label" style="color: var(--terracotta);">Manifeste</div>
      <p class="manifesto-quote">
        La transformation n'échoue pas par manque de méthode. <em>Elle échoue quand les rôles sont flous, les postures fragiles et les trajectoires subies.</em>
      </p>
      <div class="manifesto-sig">
        <div>
          <div class="manifesto-sig-name">Inès Kouki</div>
          <div class="manifesto-sig-role">Consultante en transformation · 17&nbsp;ans · 4&nbsp;pays</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- R.P.T. -->
<section class="rpt">
  <div class="container">
    <div class="rpt-intro reveal">
      <div class="section-label">Ce que vous allez comprendre</div>
      <h2 class="rpt-title">Trois piliers. <em style="font-style: italic;">Une lecture claire de votre situation.</em></h2>
      <p class="rpt-lede">
        La méthode R.P.T. ne remplace ni SAFe, ni ICP-ACC, ni votre expérience. Elle vous donne un cadre pour y voir clair sur votre place dans le système &mdash; avant que le système ne décide à votre place.
      </p>
    </div>

    <div class="rpt-grid">
      <div class="pillar pillar--r reveal">
        <div class="pillar-letter">R</div>
        <div class="pillar-tag">Pilier 01 · Rôle</div>
        <h3 class="pillar-name">Rôle</h3>
        <p class="pillar-desc">
          Scrum Master, PMO, Product Owner, Transformation Lead : les titres sont trompeurs. Vous apprenez à définir la valeur réelle que vous apportez, votre périmètre d'influence, et les attentes implicites que personne n'énonce.
        </p>
        <div class="pillar-result">Fin du flou professionnel.</div>
      </div>

      <div class="pillar pillar--p reveal">
        <div class="pillar-letter">P</div>
        <div class="pillar-tag">Pilier 02 · Posture</div>
        <h3 class="pillar-name">Posture</h3>
        <p class="pillar-desc">
          Deux personnes avec le même rôle peuvent avoir des impacts opposés. La différence tient à la posture : présence en réunion, niveau d'affirmation, gestion des jeux politiques, crédibilité perçue.
        </p>
        <div class="pillar-result">Influence sans surjouer.</div>
      </div>

      <div class="pillar pillar--t reveal">
        <div class="pillar-letter">T</div>
        <div class="pillar-tag">Pilier 03 · Trajectoire</div>
        <h3 class="pillar-name">Trajectoire</h3>
        <p class="pillar-desc">
          Vous enchaînez les missions sans direction claire. Vous apprenez à lire les signaux de carrière, choisir la prochaine étape intentionnellement, et construire une cohérence de long terme.
        </p>
        <div class="pillar-result">Carrière pilotée, non subie.</div>
      </div>
    </div>
  </div>
</section>

<!-- POUR QUI -->
<section class="pour-qui">
  <div class="container">
    <div class="pour-qui-grid">
      <div class="reveal">
        <div class="section-label">Pour qui</div>
        <h2 class="pour-qui-title">Si vous vous reconnaissez dans <em>ne serait-ce qu'une seule</em> de ces situations, 30&nbsp;minutes avec moi peuvent tout changer.</h2>
      </div>

      <ul class="pour-qui-list">
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">01</span>
          <span class="pour-qui-text">Votre mission vient de changer et vous ne savez <strong>plus comment présenter ce que vous valez vraiment.</strong></span>
        </li>
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">02</span>
          <span class="pour-qui-text">Une réorganisation a flouté votre périmètre et <strong>vous ne savez plus où vous situer.</strong></span>
        </li>
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">03</span>
          <span class="pour-qui-text">Un collègue moins expérimenté a été promu à votre place &mdash; <strong>et ce n'est pas une question de compétence.</strong></span>
        </li>
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">04</span>
          <span class="pour-qui-text">Vous cumulez les missions sans jamais <strong>construire de trajectoire lisible.</strong></span>
        </li>
        <li class="pour-qui-item reveal">
          <span class="pour-qui-num">05</span>
          <span class="pour-qui-text">Vous travaillez bien, vous êtes fiable, mais <strong>on vous voit peu là où ça compte.</strong></span>
        </li>
      </ul>
    </div>
  </div>
</section>

<!-- INTERSTITIAL CTA — pic émotionnel, après reconnaissance des pain points -->
<section class="interstitial">
  <div class="container">
    <div class="interstitial-inner">
      <div class="reveal">
        <div class="interstitial-label">L'étape suivante</div>
        <h2 class="interstitial-title">Vous vous êtes reconnue dans l'une de ces situations<em>&nbsp;?</em></h2>
        <p class="interstitial-sub">
          30&nbsp;minutes avec Inès suffisent pour poser une première lecture claire de votre rôle, de votre posture et de votre trajectoire.
        </p>
      </div>
      <div class="reveal">
        <div class="interstitial-action">
          <a href="https://calendly.com/ines-kouki-yb9r/30min" class="interstitial-cta">
            <span>Réserver mon appel</span>
            <span class="arrow" aria-hidden="true">→</span>
          </a>
        </div>
        <div class="interstitial-micro">
          Gratuit · 30&nbsp;minutes · Sans engagement
        </div>
      </div>
    </div>
  </div>
</section>

<!-- INÈS -->
<section class="ines">
  <div class="container">
    <div class="ines-grid">
      <div class="reveal">
        <div class="section-label">Qui est Inès</div>
        <h2 class="ines-name">Inès Kouki</h2>
        <div class="ines-role">Consultante senior · Transformation · Méthode R.P.T.</div>
        <p class="ines-bio">
          <em>Vous pouvez être hautement compétente… et vous sentir invisible. Ce n'est pas un problème de compétence. C'est un problème de positionnement.</em>
        </p>
        <p class="ines-bio">
          17&nbsp;ans à piloter des programmes de transformation à travers l'Afrique, l'Europe et le Moyen-Orient. Banque, retail, tech. J'ai vu des profils remarquables stagner non par manque de capacité, mais par manque de clarté sur leur rôle réel.
        </p>
        <p class="ines-bio">
          Ma conviction&nbsp;: la certification valide vos connaissances, pas votre positionnement. Ce qui change vraiment tout, c'est la clarté sur le rôle que vous occupez, la posture que vous tenez, et la trajectoire que vous pilotez — plutôt que de la subir.
        </p>

        <div class="ines-stats">
          <div>
            <div class="stat-num">17</div>
            <div class="stat-label">Années de terrain</div>
          </div>
          <div>
            <div class="stat-num">4</div>
            <div class="stat-label">Pays</div>
          </div>
          <div>
            <div class="stat-num">3</div>
            <div class="stat-label">Secteurs</div>
          </div>
        </div>
      </div>

      <div class="ines-photo reveal">
        <div class="ines-photo-sigil" aria-hidden="true">Rôle · Posture · Trajectoire</div>
        <div class="ines-photo-frame">
          <img src="data:image/webp;base64,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" alt="Portrait d'Inès Kouki, consultante senior en transformation" width="750" height="750">
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CAPTURE (direct Calendly CTA) -->
<section class="capture" id="capture">
  <div class="container">
    <div class="capture-inner reveal">
      <div class="section-label">Réserver votre appel</div>
      <h2 class="capture-title">30&nbsp;minutes pour poser les premières pierres de votre <em>clarté professionnelle.</em></h2>
      <p class="capture-sub">
        Un échange privé avec Inès. Votre situation, vos blocages réels, votre prochaine étape. Gratuit, sans engagement, sans relance commerciale.
      </p>

      <a href="https://calendly.com/ines-kouki-yb9r/30min" class="capture-cta">
        <span>Choisir mon créneau</span>
        <span aria-hidden="true">→</span>
      </a>
      <div class="capture-note">
        Vous serez redirigée vers le calendrier de réservation. <strong>Confidentialité absolue.</strong>
      </div>

      <div class="perks">
        <div class="perk">
          <div class="perk-num">i.</div>
          <div class="perk-text">
            <strong>Une lecture claire de votre situation</strong>
            On regarde ensemble votre rôle réel, votre posture actuelle, votre trajectoire — sans jargon ni généralités.
          </div>
        </div>
        <div class="perk">
          <div class="perk-num">ii.</div>
          <div class="perk-text">
            <strong>L'angle R.P.T. appliqué à vous</strong>
            Rôle · Posture · Trajectoire&nbsp;: où c'est aligné, où ça bloque, et pourquoi.
          </div>
        </div>
        <div class="perk">
          <div class="perk-num">iii.</div>
          <div class="perk-text">
            <strong>Des prochaines étapes concrètes</strong>
            Vous repartez avec 2 ou 3&nbsp;leviers immédiatement actionnables dans votre contexte.
          </div>
        </div>
        <div class="perk">
          <div class="perk-num">iv.</div>
          <div class="perk-text">
            <strong>Aucun engagement</strong>
            Pas de relance commerciale. Vous repartez avec une lecture, c'est tout.
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
</main>
<footer class="footer">
  <div class="container">
    <div class="footer-grid">
      <div class="footer-brand-block">
        <div class="footer-col-label">Marque</div>
        <div class="footer-name">Inès Kouki</div>
        <div class="footer-tagline">Rôle <span>·</span> Posture <span>·</span> Trajectoire</div>
        <p class="footer-pitch">Je transforme la confusion professionnelle en clarté stratégique.</p>
      </div>

      <div>
        <div class="footer-col-label">Me contacter</div>
        <ul class="footer-contacts">
          <li>
            <a class="footer-contact-item" href="mailto:ines.kouki@outlook.com">
              <span class="contact-icon" aria-hidden="true">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round">
                  <rect x="3" y="5" width="18" height="14" rx="1"></rect>
                  <path d="M3 7l9 6 9-6"></path>
                </svg>
              </span>
              <span>
                <span class="contact-label">Email</span>
                <span class="contact-value">ines.kouki@outlook.com</span>
              </span>
            </a>
          </li>
          <li>
            <a class="footer-contact-item" href="https://wa.me/33631805966" target="_blank" rel="noopener">
              <span class="contact-icon" aria-hidden="true">
                <svg viewBox="0 0 24 24" fill="currentColor">
                  <path d="M17.5 14.4c-.3-.1-1.7-.8-2-.9-.3-.1-.5-.1-.7.1-.2.3-.8.9-.9 1.1-.2.2-.3.2-.6.1-.3-.1-1.2-.5-2.3-1.5-.9-.8-1.5-1.7-1.6-2-.2-.3 0-.4.1-.6.1-.1.3-.3.4-.5.1-.1.2-.3.3-.4.1-.2 0-.3 0-.5-.1-.1-.7-1.6-.9-2.2-.2-.6-.5-.5-.7-.5h-.6c-.2 0-.5.1-.8.4-.3.3-1 1-1 2.4 0 1.4 1 2.8 1.2 3 .1.2 2 3 4.8 4.2.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.5-.1 1.7-.7 1.9-1.4.2-.7.2-1.2.2-1.4-.1-.1-.3-.2-.5-.3z"></path>
                  <path d="M20.5 3.5C18.3 1.2 15.3 0 12.1 0 5.5 0 .2 5.3.2 11.9c0 2.1.6 4.2 1.6 6L0 24l6.3-1.7c1.8 1 3.7 1.5 5.7 1.5h.1c6.5 0 11.9-5.3 11.9-11.9 0-3.2-1.2-6.2-3.5-8.4zM12.1 21.7c-1.8 0-3.6-.5-5.1-1.4l-.4-.2-3.7 1 1-3.6-.2-.4c-1-1.6-1.5-3.5-1.5-5.4 0-5.5 4.5-10 10-10 2.7 0 5.2 1 7.1 2.9 1.9 1.9 2.9 4.4 2.9 7.1-.1 5.5-4.5 10-10.1 10z"></path>
                </svg>
              </span>
              <span>
                <span class="contact-label">WhatsApp</span>
                <span class="contact-value">+33&nbsp;6&nbsp;31&nbsp;80&nbsp;59&nbsp;66</span>
              </span>
            </a>
          </li>
          <li>
            <a class="footer-contact-item" href="https://www.linkedin.com/in/ines-kouki-ik/" target="_blank" rel="noopener" aria-label="Profil LinkedIn d'Inès Kouki">
              <span class="contact-icon" aria-hidden="true">
                <svg viewBox="0 0 24 24" fill="currentColor">
                  <path d="M20.45 20.45h-3.55v-5.57c0-1.33-.02-3.04-1.85-3.04-1.85 0-2.14 1.45-2.14 2.94v5.67H9.36V9h3.41v1.56h.05c.47-.9 1.64-1.85 3.37-1.85 3.6 0 4.27 2.37 4.27 5.46v6.28zM5.34 7.43a2.06 2.06 0 1 1 0-4.12 2.06 2.06 0 0 1 0 4.12zM7.12 20.45H3.56V9h3.56v11.45zM22.22 0H1.77C.79 0 0 .77 0 1.72v20.56C0 23.23.79 24 1.77 24h20.45C23.2 24 24 23.23 24 22.28V1.72C24 .77 23.2 0 22.22 0z"></path>
                </svg>
              </span>
              <span>
                <span class="contact-value">LinkedIn</span>
              </span>
            </a>
          </li>
        </ul>
      </div>

      <div class="footer-cta-block">
        <div class="footer-col-label">Prochaine étape</div>
        <p class="footer-pitch" style="margin-bottom: 22px;">Un appel de clarté, 30&nbsp;minutes, gratuit.</p>
        <a href="https://calendly.com/ines-kouki-yb9r/30min" class="footer-cta">
          <span>Réserver</span>
          <span aria-hidden="true">→</span>
        </a>
      </div>
    </div>

    <div class="footer-bottom">
      <div class="footer-credit">© 2026 Inès Kouki · Tous droits réservés</div>
    </div>
  </div>
</footer>

<!-- WhatsApp floating CTA -->
<a class="whatsapp-fab" href="https://wa.me/33631805966?text=Bonjour%20In%C3%A8s%2C%20j%27aimerais%20%C3%A9changer%20avec%20vous." target="_blank" rel="noopener" aria-label="Discuter avec Inès sur WhatsApp">
  <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
    <path d="M17.5 14.4c-.3-.1-1.7-.8-2-.9-.3-.1-.5-.1-.7.1-.2.3-.8.9-.9 1.1-.2.2-.3.2-.6.1-.3-.1-1.2-.5-2.3-1.5-.9-.8-1.5-1.7-1.6-2-.2-.3 0-.4.1-.6.1-.1.3-.3.4-.5.1-.1.2-.3.3-.4.1-.2 0-.3 0-.5-.1-.1-.7-1.6-.9-2.2-.2-.6-.5-.5-.7-.5h-.6c-.2 0-.5.1-.8.4-.3.3-1 1-1 2.4 0 1.4 1 2.8 1.2 3 .1.2 2 3 4.8 4.2.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.5-.1 1.7-.7 1.9-1.4.2-.7.2-1.2.2-1.4-.1-.1-.3-.2-.5-.3z"></path>
    <path d="M20.5 3.5C18.3 1.2 15.3 0 12.1 0 5.5 0 .2 5.3.2 11.9c0 2.1.6 4.2 1.6 6L0 24l6.3-1.7c1.8 1 3.7 1.5 5.7 1.5h.1c6.5 0 11.9-5.3 11.9-11.9 0-3.2-1.2-6.2-3.5-8.4zM12.1 21.7c-1.8 0-3.6-.5-5.1-1.4l-.4-.2-3.7 1 1-3.6-.2-.4c-1-1.6-1.5-3.5-1.5-5.4 0-5.5 4.5-10 10-10 2.7 0 5.2 1 7.1 2.9 1.9 1.9 2.9 4.4 2.9 7.1-.1 5.5-4.5 10-10.1 10z"></path>
  </svg>
  <span class="wa-label">Discutons sur WhatsApp</span>
</a>

<script>
// Intersection Observer for reveal animations
const observer = new IntersectionObserver((entries) => {
  entries.forEach((entry, i) => {
    if (entry.isIntersecting) {
      setTimeout(() => entry.target.classList.add('is-visible'), i * 80);
      observer.unobserve(entry.target);
    }
  });
}, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });

document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

// Hero reveals immediately with stagger
document.addEventListener('DOMContentLoaded', () => {
  const heroReveals = document.querySelectorAll('.hero .reveal');
  heroReveals.forEach((el, i) => {
    setTimeout(() => el.classList.add('is-visible'), 120 + i * 140);
  });
});
</script>

</body>
</html>
