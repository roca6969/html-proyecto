<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Aprende inteligencia artificial desde cero. Guías prácticas, prompts listos y comparativas de herramientas IA para trabajar mejor. En español, sin tecnicismos.">
<title>AprendeIA — Guías de inteligencia artificial en español para el trabajo</title>

<!-- ═══ SEO CANÓNICO ═══ -->
<link rel="canonical" href="https://aprendeia.github.io/aprendeia/">

<!-- ═══ OPEN GRAPH (WhatsApp, LinkedIn, Facebook) ═══ -->
<meta property="og:type" content="website">
<meta property="og:title" content="AprendeIA — Inteligencia artificial en español para el trabajo">
<meta property="og:description" content="Guías prácticas, prompts listos y comparativas de herramientas IA. Todo en español, sin tecnicismos.">
<meta property="og:url" content="https://aprendeia.github.io/aprendeia/">
<meta property="og:image" content="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?w=1200&q=80">
<meta property="og:locale" content="es_ES">
<meta property="og:site_name" content="AprendeIA">

<!-- ═══ TWITTER CARD ═══ -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="AprendeIA — Inteligencia artificial en español">
<meta name="twitter:description" content="Guías prácticas de IA para el trabajo. Prompts listos, comparativas y tutoriales en español.">
<meta name="twitter:image" content="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?w=1200&q=80">

<!-- ═══ SCHEMA.ORG WebSite (Google Rich Results) ═══ -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "AprendeIA",
  "url": "https://aprendeia.github.io/aprendeia/",
  "description": "Guías prácticas de inteligencia artificial para el trabajo en español",
  "inLanguage": "es",
  "publisher": {
    "@type": "Organization",
    "name": "AprendeIA"
  },
  "potentialAction": {
    "@type": "SearchAction",
    "target": "https://aprendeia.github.io/aprendeia/?q={search_term_string}",
    "query-input": "required name=search_term_string"
  }
}
</script>

<!-- ═══ SCHEMA Blog + artículos ═══ -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Blog",
  "name": "AprendeIA",
  "url": "https://aprendeia.github.io/aprendeia/",
  "inLanguage": "es",
  "blogPost": [
    {
      "@type": "BlogPosting",
      "headline": "Cómo usar ChatGPT en el trabajo: guía práctica para principiantes",
      "description": "Aprende a usar ChatGPT en el trabajo con ejemplos reales y prompts listos para usar.",
      "datePublished": "2025-05-13",
      "dateModified": "2025-05-13",
      "author": { "@type": "Organization", "name": "AprendeIA" },
      "image": "https://images.unsplash.com/photo-1677442135703-1787eea5ce01?w=1200&q=80"
    },
    {
      "@type": "BlogPosting",
      "headline": "Los 50 mejores prompts en español para ChatGPT",
      "description": "Colección completa de prompts en español listos para copiar y usar en ChatGPT.",
      "datePublished": "2025-05-13",
      "dateModified": "2025-05-13",
      "author": { "@type": "Organization", "name": "AprendeIA" },
      "image": "https://images.unsplash.com/photo-1655720031554-a929595ffad7?w=1200&q=80"
    }
  ]
}
</script>

<!-- ═══ FAVICON SVG inline (sin archivo externo) ═══ -->
<link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 32 32'><rect width='32' height='32' rx='8' fill='%232563eb'/><text y='22' x='4' font-size='17' font-family='Arial' font-weight='bold' fill='white'>IA</text></svg>">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@300;400;500;600&family=Lora:ital,wght@0,400;1,400&display=swap" rel="stylesheet">
<style>
:root {
  --ink: #111;
  --ink2: #555;
  --ink3: #999;
  --blue: #2563eb;
  --blue-h: #1d4ed8;
  --blue-l: #eff6ff;
  --blue-m: #bfdbfe;
  --purple-l: #f5f3ff;
  --purple: #7c3aed;
  --teal-l: #f0fdf4;
  --teal: #059669;
  --amber-l: #fffbeb;
  --amber: #d97706;
  --surface: #f8f8f6;
  --white: #fff;
  --border: #e5e5e3;
  --border2: #d1d0ce;
  --r: 12px;
  --r-sm: 8px;
}
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; font-size: 16px; }
body { font-family: 'Bricolage Grotesque', sans-serif; color: var(--ink); background: var(--white); -webkit-font-smoothing: antialiased; }
a { text-decoration: none; color: inherit; }
img { display: block; width: 100%; object-fit: cover; }
.serif { font-family: 'Lora', serif; }

/* ─── PAGES ─── */
.page { display: none; }
.page.active { display: block; }

/* ─── NAV ─── */
nav {
  position: sticky; top: 0; z-index: 200;
  background: rgba(255,255,255,0.96);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--border);
  padding: 0 48px; height: 58px;
  display: flex; align-items: center; justify-content: space-between;
}
.nav-brand { display: flex; align-items: center; gap: 9px; cursor: pointer; }
.nav-logo-box {
  width: 30px; height: 30px; background: var(--blue);
  border-radius: 7px; display: flex; align-items: center; justify-content: center;
}
.nav-logo-box svg { width: 17px; height: 17px; fill: white; }
.nav-brand-name { font-size: 15px; font-weight: 600; letter-spacing: -0.3px; }
.nav-brand-name span { color: var(--blue); }
.nav-menu { display: flex; align-items: center; gap: 6px; }
.nav-btn {
  background: none; border: none; padding: 7px 13px;
  font-size: 13px; font-weight: 400; color: var(--ink2);
  cursor: pointer; border-radius: 6px; font-family: inherit;
  transition: background .15s, color .15s;
}
.nav-btn:hover { background: var(--surface); color: var(--ink); }
.nav-btn.active { color: var(--blue); font-weight: 500; }
.nav-cta {
  background: var(--ink); color: white !important;
  padding: 7px 16px; border-radius: 6px;
  font-size: 13px; font-weight: 500;
  cursor: pointer; border: none; font-family: inherit;
  transition: background .15s;
}
.nav-cta:hover { background: #333; }

/* ─── HERO ─── */
.hero {
  max-width: 1140px; margin: 0 auto;
  padding: 72px 48px 64px;
  display: grid; grid-template-columns: 1fr 440px; gap: 64px; align-items: center;
  border-bottom: 1px solid var(--border);
}
.hero-eyebrow {
  display: inline-flex; align-items: center; gap: 7px;
  background: var(--blue-l); color: var(--blue);
  font-size: 12px; font-weight: 500; padding: 4px 12px;
  border-radius: 20px; margin-bottom: 22px;
}
.hero-eyebrow::before { content:''; width:6px; height:6px; background:var(--blue); border-radius:50%; }
.hero h1 {
  font-family: 'Lora', serif; font-size: 54px; line-height: 1.08;
  letter-spacing: -1.5px; margin-bottom: 22px; color: var(--ink);
}
.hero h1 em { font-style: italic; color: var(--blue); }
.hero-lead { font-size: 16px; color: var(--ink2); line-height: 1.75; margin-bottom: 34px; max-width: 460px; }
.hero-actions { display: flex; gap: 12px; flex-wrap: wrap; margin-bottom: 44px; }
.btn-primary {
  background: var(--blue); color: white; border: none;
  padding: 13px 26px; border-radius: var(--r-sm);
  font-size: 14px; font-weight: 500; cursor: pointer; font-family: inherit;
  transition: background .15s, transform .12s;
}
.btn-primary:hover { background: var(--blue-h); transform: translateY(-1px); }
.btn-ghost {
  background: none; color: var(--ink); font-family: inherit;
  border: 1px solid var(--border2); padding: 13px 26px; border-radius: var(--r-sm);
  font-size: 14px; cursor: pointer; transition: background .15s;
}
.btn-ghost:hover { background: var(--surface); }
.hero-trust { display: flex; gap: 28px; padding-top: 32px; border-top: 1px solid var(--border); }
.trust-n { font-family: 'Lora', serif; font-size: 26px; color: var(--blue); }
.trust-l { font-size: 12px; color: var(--ink3); margin-top: 2px; }

/* Hero image panel */
.hero-img-wrap { border-radius: 16px; overflow: hidden; border: 1px solid var(--border); position: relative; }
.hero-img-wrap img { height: 420px; }
.hero-img-badge {
  position: absolute; bottom: 14px; left: 14px; right: 14px;
  background: rgba(255,255,255,0.95); border-radius: 10px;
  padding: 12px 14px; display: flex; align-items: center; gap: 12px;
  border: 1px solid var(--border);
}
.badge-ava {
  width: 36px; height: 36px; border-radius: 50%; overflow: hidden; flex-shrink: 0;
}
.badge-ava img { height: 36px; }
.badge-text p:first-child { font-size: 13px; font-weight: 500; }
.badge-text p:last-child { font-size: 11px; color: var(--ink3); }
.badge-stars { margin-left: auto; color: var(--amber); font-size: 13px; }

/* ─── SECTION COMMONS ─── */
.section { padding: 64px 48px; }
.section.bg-surface { background: var(--surface); }
.container { max-width: 1140px; margin: 0 auto; }
.sec-eyebrow { font-size: 11px; font-weight: 500; letter-spacing: .08em; text-transform: uppercase; color: var(--ink3); margin-bottom: 6px; }
.sec-title { font-family: 'Lora', serif; font-size: 34px; letter-spacing: -.5px; line-height: 1.15; margin-bottom: 8px; }
.sec-sub { font-size: 15px; color: var(--ink2); margin-bottom: 40px; }
.sec-header { display: flex; justify-content: space-between; align-items: flex-end; margin-bottom: 36px; flex-wrap: wrap; gap: 12px; }
.sec-header > div { max-width: 520px; }
.link-more { font-size: 13px; color: var(--blue); font-weight: 500; cursor: pointer; white-space: nowrap; }
.link-more:hover { text-decoration: underline; }

/* ─── CARDS ─── */
.card {
  background: var(--white); border: 1px solid var(--border);
  border-radius: var(--r); overflow: hidden;
  transition: transform .2s, box-shadow .2s;
  cursor: pointer;
}
.card:hover { transform: translateY(-3px); box-shadow: 0 8px 28px rgba(0,0,0,.07); }

.card-img { position: relative; overflow: hidden; }
.card-img img { transition: transform .4s; }
.card:hover .card-img img { transform: scale(1.03); }
.card-img-overlay {
  position: absolute; inset: 0;
  background: linear-gradient(to top, rgba(0,0,0,.3) 0%, transparent 50%);
}
.card-tag {
  position: absolute; top: 12px; left: 12px;
  font-size: 11px; font-weight: 500; padding: 3px 10px;
  border-radius: 20px; backdrop-filter: blur(6px);
}
.card-tag.blue { background: rgba(37,99,235,.85); color: white; }
.card-tag.purple { background: rgba(124,58,237,.85); color: white; }
.card-tag.teal { background: rgba(5,150,105,.85); color: white; }
.card-tag.amber { background: rgba(217,119,6,.85); color: white; }
.card-body { padding: 18px; }
.card-title { font-size: 16px; font-weight: 500; line-height: 1.35; margin-bottom: 8px; }
.card-meta { font-size: 12px; color: var(--ink3); display: flex; gap: 12px; align-items: center; }
.card-meta-dot { width: 3px; height: 3px; border-radius: 50%; background: var(--border2); }

/* Featured big card */
.featured-grid { display: grid; grid-template-columns: 1.8fr 1fr; gap: 18px; }
.featured-grid .card-img img { height: 260px; }
.featured-grid .card:last-child .card-img img { height: 120px; }
.feat-side-col { display: flex; flex-direction: column; gap: 18px; }

/* Articles grid 3-col */
.arts-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 18px; }
.arts-grid .card-img img { height: 180px; }

/* ─── CATEGORIES ─── */
.cats-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 14px; }
.cat-card {
  background: var(--white); border: 1px solid var(--border);
  border-radius: var(--r); padding: 22px 18px; cursor: pointer;
  transition: border-color .2s, transform .2s;
}
.cat-card:hover { border-color: var(--blue-m); transform: translateY(-2px); }
.cat-icon {
  width: 46px; height: 46px; border-radius: 11px;
  display: flex; align-items: center; justify-content: center; margin-bottom: 14px;
}
.cat-icon svg { width: 22px; height: 22px; }
.cat-icon.blue { background: var(--blue-l); }
.cat-icon.blue svg { fill: var(--blue); }
.cat-icon.purple { background: var(--purple-l); }
.cat-icon.purple svg { fill: var(--purple); }
.cat-icon.teal { background: var(--teal-l); }
.cat-icon.teal svg { fill: var(--teal); }
.cat-icon.amber { background: var(--amber-l); }
.cat-icon.amber svg { fill: var(--amber); }
.cat-name { font-size: 14px; font-weight: 500; margin-bottom: 3px; }
.cat-count { font-size: 12px; color: var(--ink3); }

/* ─── LIST ROWS ─── */
.rows-wrap { border: 1px solid var(--border); border-radius: var(--r); overflow: hidden; background: var(--white); }
.row-item {
  display: flex; align-items: center; gap: 14px;
  padding: 14px 18px; border-bottom: 1px solid var(--border);
  cursor: pointer; transition: background .12s;
}
.row-item:last-child { border-bottom: none; }
.row-item:hover { background: var(--surface); }
.row-num { font-size: 12px; color: var(--ink3); min-width: 20px; font-variant-numeric: tabular-nums; }
.row-thumb { width: 52px; height: 42px; border-radius: 7px; overflow: hidden; flex-shrink: 0; }
.row-thumb img { height: 42px; width: 52px; }
.row-info { flex: 1; min-width: 0; }
.row-title { font-size: 14px; font-weight: 500; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
.row-sub { font-size: 12px; color: var(--ink3); margin-top: 2px; }
.pill {
  font-size: 11px; font-weight: 500; padding: 3px 10px;
  border-radius: 20px; flex-shrink: 0;
}
.pill.new { background: #dcfce7; color: #15803d; }
.pill.pop { background: var(--blue-l); color: var(--blue); }
.pill.guide { background: var(--purple-l); color: var(--purple); }
.pill.hot { background: #fef3c7; color: #b45309; }

/* ─── PROMPTS PAGE ─── */
.prompts-hero {
  background: var(--blue); padding: 60px 48px;
  color: white; text-align: center;
}
.prompts-hero h1 { font-family: 'Lora', serif; font-size: 42px; margin-bottom: 12px; color: white; }
.prompts-hero p { font-size: 16px; color: rgba(255,255,255,.7); max-width: 500px; margin: 0 auto; }
.prompts-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px; }
.prompt-card {
  background: var(--white); border: 1px solid var(--border);
  border-radius: var(--r); padding: 20px; cursor: pointer;
  transition: border-color .2s, transform .2s;
}
.prompt-card:hover { border-color: var(--blue-m); transform: translateY(-2px); }
.prompt-category {
  font-size: 11px; font-weight: 500; color: var(--blue);
  background: var(--blue-l); padding: 3px 9px; border-radius: 20px;
  display: inline-block; margin-bottom: 10px;
}
.prompt-title { font-size: 14px; font-weight: 500; margin-bottom: 8px; line-height: 1.35; }
.prompt-text {
  font-size: 12px; color: var(--ink2); line-height: 1.6;
  background: var(--surface); border-radius: 7px; padding: 10px 12px;
  border-left: 3px solid var(--blue-m); font-family: monospace;
}
.copy-btn {
  margin-top: 10px; background: none; border: 1px solid var(--border);
  border-radius: 6px; padding: 5px 12px; font-size: 12px; cursor: pointer;
  font-family: inherit; color: var(--ink2); transition: background .15s;
}
.copy-btn:hover { background: var(--surface); }
.copy-btn.copied { color: var(--teal); border-color: var(--teal); }

/* ─── TOOLS PAGE ─── */
.tools-hero { background: var(--surface); padding: 56px 48px; border-bottom: 1px solid var(--border); }
.tools-hero-inner { max-width: 1140px; margin: 0 auto; }
.tools-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 18px; }
.tool-card {
  background: var(--white); border: 1px solid var(--border);
  border-radius: var(--r); padding: 22px; cursor: pointer;
  transition: border-color .2s, transform .2s;
}
.tool-card:hover { border-color: var(--blue-m); transform: translateY(-2px); }
.tool-header { display: flex; align-items: center; gap: 12px; margin-bottom: 14px; }
.tool-logo {
  width: 44px; height: 44px; border-radius: 10px;
  overflow: hidden; flex-shrink: 0; border: 1px solid var(--border);
}
.tool-logo img { height: 44px; width: 44px; }
.tool-name { font-size: 15px; font-weight: 500; }
.tool-type { font-size: 11px; color: var(--ink3); }
.tool-desc { font-size: 13px; color: var(--ink2); line-height: 1.6; margin-bottom: 14px; }
.tool-tags { display: flex; gap: 6px; flex-wrap: wrap; }
.tool-tag { font-size: 11px; background: var(--surface); border: 1px solid var(--border); border-radius: 5px; padding: 2px 8px; color: var(--ink3); }
.tool-footer { display: flex; align-items: center; justify-content: space-between; margin-top: 14px; padding-top: 12px; border-top: 1px solid var(--border); }
.tool-price { font-size: 12px; font-weight: 500; color: var(--teal); }
.tool-price.paid { color: var(--amber); }
.tool-rating { font-size: 12px; color: var(--ink3); }

/* ─── NEWSLETTER ─── */
.nl-section { background: var(--ink); padding: 64px 48px; }
.nl-inner { max-width: 1140px; margin: 0 auto; display: flex; align-items: center; justify-content: space-between; gap: 48px; flex-wrap: wrap; }
.nl-left h2 { font-family: 'Lora', serif; font-size: 30px; color: white; margin-bottom: 8px; }
.nl-left p { font-size: 14px; color: rgba(255,255,255,.5); }
.nl-form { display: flex; gap: 8px; flex-shrink: 0; }
.nl-form input {
  background: rgba(255,255,255,.08); border: 1px solid rgba(255,255,255,.15);
  border-radius: var(--r-sm); padding: 12px 16px; font-size: 14px;
  color: white; width: 240px; font-family: inherit; outline: none;
}
.nl-form input::placeholder { color: rgba(255,255,255,.3); }
.nl-form button {
  background: var(--blue); color: white; border: none;
  padding: 12px 22px; border-radius: var(--r-sm);
  font-size: 14px; font-weight: 500; cursor: pointer; font-family: inherit;
  white-space: nowrap; transition: background .15s;
}
.nl-form button:hover { background: var(--blue-h); }

/* ─── FOOTER ─── */
footer {
  background: var(--white); border-top: 1px solid var(--border);
  padding: 36px 48px;
}
.footer-inner { max-width: 1140px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 16px; }
.footer-brand { font-size: 14px; font-weight: 500; }
.footer-brand span { color: var(--blue); }
.footer-links { display: flex; gap: 20px; list-style: none; flex-wrap: wrap; }
.footer-links a { font-size: 13px; color: var(--ink3); }
.footer-links a:hover { color: var(--ink); }
.footer-copy { font-size: 12px; color: var(--ink3); }

/* ─── ARTICLE PAGE ─── */
.article-hero { max-width: 740px; margin: 0 auto; padding: 56px 48px 40px; }
.article-hero-img { border-radius: var(--r); overflow: hidden; margin-bottom: 32px; }
.article-hero-img img { height: 380px; }
.article-tag-row { display: flex; gap: 8px; margin-bottom: 16px; flex-wrap: wrap; }
.article-tag-pill { font-size: 12px; font-weight: 500; background: var(--blue-l); color: var(--blue); padding: 4px 12px; border-radius: 20px; }
.article-hero h1 { font-family: 'Lora', serif; font-size: 38px; line-height: 1.15; margin-bottom: 16px; letter-spacing: -.5px; }
.article-hero .lead { font-size: 17px; color: var(--ink2); line-height: 1.7; margin-bottom: 24px; }
.article-meta-bar { display: flex; align-items: center; gap: 16px; padding: 16px 0; border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); margin-bottom: 40px; }
.article-author { display: flex; align-items: center; gap: 8px; }
.author-ava { width: 32px; height: 32px; border-radius: 50%; overflow: hidden; }
.author-ava img { height: 32px; }
.author-name { font-size: 13px; font-weight: 500; }
.article-date { font-size: 12px; color: var(--ink3); }
.article-read { font-size: 12px; color: var(--ink3); }
.article-body { max-width: 740px; margin: 0 auto; padding: 0 48px 64px; font-size: 16px; line-height: 1.8; color: var(--ink2); }
.article-body h2 { font-family: 'Lora', serif; font-size: 26px; color: var(--ink); margin: 40px 0 14px; font-weight: 400; }
.article-body p { margin-bottom: 20px; }
.article-body .callout { background: var(--blue-l); border-left: 3px solid var(--blue); border-radius: 0 var(--r-sm) var(--r-sm) 0; padding: 16px 20px; margin: 28px 0; font-size: 15px; color: var(--blue-h); }
.article-body .prompt-box { background: var(--surface); border: 1px solid var(--border); border-radius: var(--r-sm); padding: 16px 18px; font-family: monospace; font-size: 14px; color: var(--ink); margin: 20px 0; line-height: 1.6; }
.article-body-img { border-radius: var(--r); overflow: hidden; margin: 28px 0; }
.article-body-img img { height: 280px; }
.back-btn { background: none; border: none; font-family: inherit; font-size: 14px; color: var(--ink2); cursor: pointer; padding: 0; display: flex; align-items: center; gap: 6px; margin-bottom: 28px; }
.back-btn:hover { color: var(--ink); }

/* ─── RESPONSIVE ─── */
@media (max-width: 900px) {
  nav { padding: 0 20px; }
  .nav-menu { gap: 2px; }
  .nav-btn { padding: 6px 8px; font-size: 12px; }
  .hero { grid-template-columns: 1fr; padding: 40px 20px 36px; }
  .hero-img-wrap { display: none; }
  .hero h1 { font-size: 38px; }
  .section { padding: 48px 20px; }
  .featured-grid { grid-template-columns: 1fr; }
  .arts-grid { grid-template-columns: repeat(2, 1fr); }
  .cats-grid { grid-template-columns: repeat(2, 1fr); }
  .prompts-hero { padding: 48px 20px; }
  .prompts-grid { grid-template-columns: repeat(2, 1fr); }
  .tools-hero { padding: 40px 20px; }
  .tools-grid { grid-template-columns: repeat(2, 1fr); }
  .nl-section { padding: 48px 20px; }
  .nl-inner { flex-direction: column; }
  .nl-form { flex-direction: column; width: 100%; }
  .nl-form input { width: 100%; }
  footer { padding: 24px 20px; }
  .article-hero { padding: 36px 20px 24px; }
  .article-body { padding: 0 20px 48px; }
}
@media (max-width: 600px) {
  .arts-grid { grid-template-columns: 1fr; }
  .prompts-grid { grid-template-columns: 1fr; }
  .tools-grid { grid-template-columns: 1fr; }
  .nav-btn:not(.nav-cta) { display: none; }
}
</style>
</head>
<body>

<!-- ═══════════════════════════════ NAV ═══════════════════════════════ -->
<nav>
  <div class="nav-brand" onclick="showPage('home')">
    <div class="nav-logo-box">
      <svg viewBox="0 0 24 24"><path d="M21 10.12h-6.78l2.74-2.82c-2.73-2.7-7.15-2.8-9.88-.1-2.73 2.71-2.73 7.08 0 9.79 2.73 2.71 7.15 2.71 9.88 0C18.32 15.65 19 14.08 19 12.1h2c0 1.98-.88 4.55-2.64 6.29-3.51 3.48-9.21 3.48-12.72 0-3.5-3.47-3.53-9.11-.02-12.58 3.51-3.47 9.14-3.47 12.65 0L21 3v7.12z"/></svg>
    </div>
    <span class="nav-brand-name">Aprende<span>IA</span>.net</span>
  </div>
  <div class="nav-menu">
    <button class="nav-btn active" id="btn-home" onclick="showPage('home')">Inicio</button>
    <button class="nav-btn" id="btn-guias" onclick="showPage('guias')">Guías</button>
    <button class="nav-btn" id="btn-prompts" onclick="showPage('prompts')">Prompts</button>
    <button class="nav-btn" id="btn-herramientas" onclick="showPage('herramientas')">Herramientas</button>
    <button class="nav-btn" id="btn-sobre" onclick="showPage('sobre')">Sobre nosotros</button>
    <button class="nav-cta" onclick="showPage('newsletter')">Newsletter gratis</button>
  </div>
</nav>

<!-- ═══════════════════════════════ HOME ═══════════════════════════════ -->
<div class="page active" id="page-home">

  <!-- HERO -->
  <div style="border-bottom:1px solid var(--border)">
    <div class="hero">
      <div>
        <div class="hero-eyebrow">Actualizado mayo 2025</div>
        <h1>La IA es tu nuevo <em>superpoder</em> en el trabajo</h1>
        <p class="hero-lead">Guías en español para aprender inteligencia artificial desde cero. Prompts listos para copiar, comparativas de herramientas y tutoriales prácticos. Sin tecnicismos.</p>
        <div class="hero-actions">
          <button class="btn-primary" onclick="showPage('guias')">Empezar gratis →</button>
          <button class="btn-ghost" onclick="showPage('prompts')">Ver los 50 prompts</button>
        </div>
        <div class="hero-trust">
          <div><div class="trust-n">15+</div><div class="trust-l">Guías publicadas</div></div>
          <div><div class="trust-n">50+</div><div class="trust-l">Prompts listos</div></div>
          <div><div class="trust-n">100%</div><div class="trust-l">En español</div></div>
        </div>
      </div>
      <div class="hero-img-wrap">
        <img src="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?w=860&q=80" alt="Persona trabajando con inteligencia artificial en su ordenador">
        <div class="hero-img-badge">
          <div class="badge-ava"><img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=80&q=80" alt="Usuario"></div>
          <div class="badge-text">
            <p>"Me ahorré 2 horas diarias con estos prompts"</p>
            <p>María G. · Diseñadora freelance</p>
          </div>
          <div class="badge-stars">★★★★★</div>
        </div>
      </div>
    </div>
  </div>

  <!-- FEATURED -->
  <section class="section bg-surface">
    <div class="container">
      <div class="sec-header">
        <div>
          <p class="sec-eyebrow">Lo más leído</p>
          <h2 class="sec-title">Artículos destacados</h2>
        </div>
        <span class="link-more" onclick="showPage('guias')">Ver todos los artículos →</span>
      </div>
      <div class="featured-grid">
        <div class="card" onclick="showPage('article')">
          <div class="card-img">
            <img src="https://images.unsplash.com/photo-1677442135703-1787eea5ce01?w=900&q=80" alt="ChatGPT en el trabajo" style="height:260px">
            <div class="card-img-overlay"></div>
            <span class="card-tag blue">Principiantes</span>
          </div>
          <div class="card-body">
            <h3 class="card-title">Cómo usar ChatGPT en el trabajo: guía práctica para principiantes</h3>
            <div class="card-meta">
              <span>ChatGPT</span><span class="card-meta-dot"></span>
              <span>8 min lectura</span><span class="card-meta-dot"></span>
              <span>Mayo 2025</span>
            </div>
          </div>
        </div>
        <div class="feat-side-col">
          <div class="card" onclick="showPage('prompts')">
            <div class="card-img">
              <img src="https://images.unsplash.com/photo-1655720031554-a929595ffad7?w=600&q=80" alt="Prompts para ChatGPT" style="height:120px">
              <div class="card-img-overlay"></div>
              <span class="card-tag purple">Prompts</span>
            </div>
            <div class="card-body">
              <h3 class="card-title" style="font-size:14px">Los 50 mejores prompts en español para ChatGPT</h3>
              <div class="card-meta"><span>5 min</span><span class="card-meta-dot"></span><span>Lista práctica</span></div>
            </div>
          </div>
          <div class="card" onclick="showPage('herramientas')">
            <div class="card-img">
              <img src="https://images.unsplash.com/photo-1591453089816-0fbb971b454c?w=600&q=80" alt="Herramientas de IA" style="height:120px">
              <div class="card-img-overlay"></div>
              <span class="card-tag teal">Herramientas</span>
            </div>
            <div class="card-body">
              <h3 class="card-title" style="font-size:14px">Las 15 mejores herramientas de IA para trabajar en 2025</h3>
              <div class="card-meta"><span>10 min</span><span class="card-meta-dot"></span><span>Comparativa</span></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CATEGORIES -->
  <section class="section">
    <div class="container">
      <div class="sec-header"><div>
        <p class="sec-eyebrow">Explora por tema</p>
        <h2 class="sec-title">Categorías</h2>
      </div></div>
      <div class="cats-grid">
        <div class="cat-card" onclick="showPage('guias')">
          <div class="cat-icon blue"><svg viewBox="0 0 24 24"><path d="M20 2H4c-1.1 0-2 .9-2 2v18l4-4h14c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2z"/></svg></div>
          <div class="cat-name">ChatGPT</div><div class="cat-count">8 guías</div>
        </div>
        <div class="cat-card" onclick="showPage('prompts')">
          <div class="cat-icon purple"><svg viewBox="0 0 24 24"><path d="M3 13h2v-2H3v2zm0 4h2v-2H3v2zm0-8h2V7H3v2zm4 4h14v-2H7v2zm0 4h14v-2H7v2zM7 7v2h14V7H7z"/></svg></div>
          <div class="cat-name">Prompts</div><div class="cat-count">12 colecciones</div>
        </div>
        <div class="cat-card" onclick="showPage('herramientas')">
          <div class="cat-icon teal"><svg viewBox="0 0 24 24"><path d="M22.7 19l-9.1-9.1c.9-2.3.4-5-1.5-6.9-2-2-5-2.4-7.4-1.3L9 6 6 9 1.6 4.7C.4 7.1.9 10.1 2.9 12.1c1.9 1.9 4.6 2.4 6.9 1.5l9.1 9.1c.4.4 1 .4 1.4 0l2.3-2.3c.5-.4.5-1.1.1-1.4z"/></svg></div>
          <div class="cat-name">Herramientas IA</div><div class="cat-count">15 comparativas</div>
        </div>
        <div class="cat-card" onclick="showPage('guias')">
          <div class="cat-icon amber"><svg viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-7 3c1.93 0 3.5 1.57 3.5 3.5S13.93 13 12 13s-3.5-1.57-3.5-3.5S10.07 6 12 6zm7 13H5v-.23c0-.62.28-1.2.76-1.58C7.47 15.82 9.64 15 12 15s4.53.82 6.24 2.19c.48.38.76.97.76 1.58V19z"/></svg></div>
          <div class="cat-name">Para freelancers</div><div class="cat-count">6 guías</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ALL ARTICLES LIST -->
  <section class="section bg-surface">
    <div class="container">
      <div class="sec-header">
        <div><p class="sec-eyebrow">Todas las guías</p><h2 class="sec-title">Últimos artículos</h2></div>
        <span class="link-more" onclick="showPage('guias')">Ver archivo completo →</span>
      </div>
      <div class="rows-wrap">
        <div class="row-item" onclick="showPage('art1')">
          <span class="row-num">01</span>
          <div class="row-thumb"><img src="https://images.unsplash.com/photo-1677442135703-1787eea5ce01?w=120&q=70" alt="ChatGPT"></div>
          <div class="row-info"><div class="row-title">Cómo usar ChatGPT en el trabajo: guía práctica para principiantes</div><div class="row-sub">ChatGPT · 8 min</div></div>
          <span class="pill new">Nuevo</span>
        </div>
        <div class="row-item" onclick="showPage('art2')">
          <span class="row-num">02</span>
          <div class="row-thumb"><img src="https://images.unsplash.com/photo-1596526131083-e8c633c948d2?w=120&q=70" alt="ChatGPT"></div>
          <div class="row-info"><div class="row-title">Cómo usar ChatGPT para escribir emails profesionales (con plantillas)</div><div class="row-sub">ChatGPT · 6 min</div></div>
          <span class="pill pop">Popular</span>
        </div>
        <div class="row-item" onclick="showPage('art3')">
          <span class="row-num">03</span>
          <div class="row-thumb"><img src="https://images.unsplash.com/photo-1518186285589-2f7649de83e0?w=120&q=70" alt="Productividad"></div>
          <div class="row-info"><div class="row-title">Cómo automatizar tareas repetitivas con ChatGPT: 10 ejemplos reales</div><div class="row-sub">Productividad · 7 min</div></div>
          <span class="pill guide">Guía</span>
        </div>
        <div class="row-item" onclick="showPage('art4')">
          <span class="row-num">04</span>
          <div class="row-thumb"><img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=120&q=70" alt="Educación"></div>
          <div class="row-info"><div class="row-title">ChatGPT para estudiantes: cómo usarlo sin hacer trampa</div><div class="row-sub">Educación · 6 min</div></div>
          <span class="pill new">Nuevo</span>
        </div>
        <div class="row-item" onclick="showPage('art5')">
          <span class="row-num">05</span>
          <div class="row-thumb"><img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=120&q=70" alt="Conceptos"></div>
          <div class="row-info"><div class="row-title">Qué es la inteligencia artificial: explicación sencilla para no técnicos</div><div class="row-sub">Conceptos · 5 min</div></div>
          <span class="pill hot">Tendencia</span>
        </div>
        <div class="row-item" onclick="showPage('art6')">
          <span class="row-num">06</span>
          <div class="row-thumb"><img src="https://images.unsplash.com/photo-1611532736597-de2d4265fba3?w=120&q=70" alt="Productividad"></div>
          <div class="row-info"><div class="row-title">Cómo usar Notion AI para ser más productivo: guía completa</div><div class="row-sub">Productividad · 8 min</div></div>
          <span class="pill pop">Popular</span>
        </div>
        <div class="row-item" onclick="showPage('art7')">
          <span class="row-num">07</span>
          <div class="row-thumb"><img src="https://images.unsplash.com/photo-1655720031554-a929595ffad7?w=120&q=70" alt="Comparativa"></div>
          <div class="row-info"><div class="row-title">ChatGPT vs Gemini vs Claude: ¿cuál es el mejor en 2025?</div><div class="row-sub">Comparativa · 9 min</div></div>
          <span class="pill guide">Guía</span>
        </div>
      </div>
    </div>
  </section>

  <!-- NEWSLETTER -->
  <section class="nl-section">
    <div class="nl-inner">
      <div class="nl-left">
        <h2>Las mejores guías de IA,<br>cada semana en tu correo</h2>
        <p>Sin spam. Solo lo que necesitas para trabajar mejor con inteligencia artificial.</p>
      </div>
      <div class="nl-form">
        <input type="email" placeholder="tucorreo@ejemplo.com" id="nl-email-home">
        <button onclick="subscribeNL('nl-email-home')">Suscribirme gratis</button>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-inner">
      <span class="footer-brand">Aprende<span>IA</span>.net</span>
      <ul class="footer-links">
        <li><a href="#" onclick="showPage('guias')">Guías</a></li>
        <li><a href="#" onclick="showPage('prompts')">Prompts</a></li>
        <li><a href="#" onclick="showPage('herramientas')">Herramientas</a></li>
        <li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li>
        <li><a href="#" onclick="showPage('aviso')">Aviso legal</a></li>
        <li><a href="#" onclick="showPage('contacto')">Contacto</a></li>
      </ul>
      <span class="footer-copy">© 2025 AprendeIA.net</span>
    </div>
  </footer>
</div>

<!-- ═══════════════════════════════ GUÍAS ═══════════════════════════════ -->
<div class="page" id="page-guias">
  <section class="section bg-surface" style="padding-top:48px;padding-bottom:32px">
    <div class="container">
      <p class="sec-eyebrow">Todas las guías</p>
      <h1 class="sec-title">Aprende IA desde cero</h1>
      <p class="sec-sub">Artículos prácticos para usar la inteligencia artificial en tu trabajo diario.</p>
    </div>
  </section>
  <section class="section">
    <div class="container">
      <div class="arts-grid">
        <div class="card" onclick="showPage('art1')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1677442135703-1787eea5ce01?w=600&q=85" alt="Pantalla con ChatGPT abierto en el trabajo" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag blue">ChatGPT</span></div>
          <div class="card-body"><h3 class="card-title">Cómo usar ChatGPT en el trabajo: guía práctica para principiantes</h3><div class="card-meta"><span>ChatGPT</span><span class="card-meta-dot"></span><span>8 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art2')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1596526131083-e8c633c948d2?w=600&q=85" alt="Persona escribiendo un email profesional" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag blue">ChatGPT</span></div>
          <div class="card-body"><h3 class="card-title">Cómo usar ChatGPT para escribir emails profesionales (con plantillas)</h3><div class="card-meta"><span>ChatGPT</span><span class="card-meta-dot"></span><span>6 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art3')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1518186285589-2f7649de83e0?w=600&q=85" alt="Automatización de tareas con inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag teal">Productividad</span></div>
          <div class="card-body"><h3 class="card-title">Cómo automatizar tareas repetitivas con ChatGPT: 10 ejemplos reales</h3><div class="card-meta"><span>Productividad</span><span class="card-meta-dot"></span><span>7 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art4')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=600&q=85" alt="Estudiante usando inteligencia artificial para estudiar" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag purple">Educación</span></div>
          <div class="card-body"><h3 class="card-title">ChatGPT para estudiantes: cómo usarlo sin hacer trampa</h3><div class="card-meta"><span>Educación</span><span class="card-meta-dot"></span><span>6 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art5')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=600&q=85" alt="Representación visual de la inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag amber">Conceptos</span></div>
          <div class="card-body"><h3 class="card-title">Qué es la inteligencia artificial: explicación sencilla para no técnicos</h3><div class="card-meta"><span>Conceptos</span><span class="card-meta-dot"></span><span>5 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art6')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1611532736597-de2d4265fba3?w=600&q=85" alt="Notion AI en pantalla de ordenador" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag teal">Productividad</span></div>
          <div class="card-body"><h3 class="card-title">Cómo usar Notion AI para ser más productivo: guía completa</h3><div class="card-meta"><span>Productividad</span><span class="card-meta-dot"></span><span>8 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art7')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1655720031554-a929595ffad7?w=600&q=85" alt="Comparativa entre asistentes de inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag purple">Comparativa</span></div>
          <div class="card-body"><h3 class="card-title">ChatGPT vs Gemini vs Claude: ¿cuál es el mejor en 2025?</h3><div class="card-meta"><span>Comparativa</span><span class="card-meta-dot"></span><span>9 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art8')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1499750310107-5fef28a66643?w=600&q=85" alt="Persona creando su currículum con inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag blue">Trabajo</span></div>
          <div class="card-body"><h3 class="card-title">Cómo crear un currículum perfecto con ChatGPT: paso a paso</h3><div class="card-meta"><span>Trabajo</span><span class="card-meta-dot"></span><span>7 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art9')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1512941937669-90a1b58e7e9c?w=600&q=85" alt="Imágenes generadas con inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag purple">Imágenes IA</span></div>
          <div class="card-body"><h3 class="card-title">Cómo usar Midjourney en español: guía para principiantes</h3><div class="card-meta"><span>Imágenes IA</span><span class="card-meta-dot"></span><span>9 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art10')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf?w=600&q=85" alt="Freelancer trabajando con herramientas de inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag amber">Freelancers</span></div>
          <div class="card-body"><h3 class="card-title">Las mejores herramientas de IA para freelancers en 2025</h3><div class="card-meta"><span>Freelancers</span><span class="card-meta-dot"></span><span>8 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art11')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=600&q=85" alt="Creación de contenido para redes sociales con IA" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag amber">Marketing</span></div>
          <div class="card-body"><h3 class="card-title">Cómo crear contenido para redes sociales con inteligencia artificial</h3><div class="card-meta"><span>Marketing</span><span class="card-meta-dot"></span><span>7 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art12')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1553729459-efe14ef6055d?w=600&q=85" alt="Persona ganando dinero con inteligencia artificial online" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag teal">Ingresos</span></div>
          <div class="card-body"><h3 class="card-title">Cómo ganar dinero con inteligencia artificial en 2025: 10 formas reales</h3><div class="card-meta"><span>Ingresos</span><span class="card-meta-dot"></span><span>10 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art13')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1434030216411-0b793f4b4173?w=600&q=85" alt="Persona aprendiendo un idioma con inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag purple">Educación</span></div>
          <div class="card-body"><h3 class="card-title">Cómo usar ChatGPT para aprender un idioma más rápido</h3><div class="card-meta"><span>Educación</span><span class="card-meta-dot"></span><span>7 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art14')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?w=600&q=85" alt="Errores comunes al usar inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag blue">ChatGPT</span></div>
          <div class="card-body"><h3 class="card-title">10 errores comunes al usar ChatGPT (y cómo evitarlos)</h3><div class="card-meta"><span>ChatGPT</span><span class="card-meta-dot"></span><span>6 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('art15')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1515187029135-18ee286d815b?w=600&q=85" alt="Presentación creada con inteligencia artificial" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag teal">Productividad</span></div>
          <div class="card-body"><h3 class="card-title">Cómo hacer una presentación de PowerPoint con inteligencia artificial</h3><div class="card-meta"><span>Productividad</span><span class="card-meta-dot"></span><span>7 min</span></div></div>
        </div>
      </div><span class="card-tag blue">Principiantes</span></div>
          <div class="card-body"><h3 class="card-title">Cómo usar ChatGPT en el trabajo: guía práctica</h3><div class="card-meta"><span>ChatGPT</span><span class="card-meta-dot"></span><span>8 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('article')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1596526131083-e8c633c948d2?w=600&q=80" alt="Emails con IA" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag blue">Tutorial</span></div>
          <div class="card-body"><h3 class="card-title">Cómo escribir emails profesionales con ChatGPT</h3><div class="card-meta"><span>Emails</span><span class="card-meta-dot"></span><span>6 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('article')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1518186285589-2f7649de83e0?w=600&q=80" alt="Automatizar tareas" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag teal">Productividad</span></div>
          <div class="card-body"><h3 class="card-title">Cómo automatizar tareas repetitivas con ChatGPT</h3><div class="card-meta"><span>Automatización</span><span class="card-meta-dot"></span><span>7 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('article')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=600&q=80" alt="Estudiantes" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag purple">Educación</span></div>
          <div class="card-body"><h3 class="card-title">ChatGPT para estudiantes: cómo usarlo sin hacer trampa</h3><div class="card-meta"><span>Educación</span><span class="card-meta-dot"></span><span>5 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('article')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=600&q=80" alt="Freelancers" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag amber">Freelance</span></div>
          <div class="card-body"><h3 class="card-title">Herramientas de IA para freelancers en 2025</h3><div class="card-meta"><span>Freelancers</span><span class="card-meta-dot"></span><span>7 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('article')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1512941937669-90a1b58e7e9c?w=600&q=80" alt="Midjourney" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag purple">Imágenes</span></div>
          <div class="card-body"><h3 class="card-title">Cómo usar Midjourney en español: guía para principiantes</h3><div class="card-meta"><span>Midjourney</span><span class="card-meta-dot"></span><span>9 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('article')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1611532736597-de2d4265fba3?w=600&q=80" alt="Notion AI" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag teal">Productividad</span></div>
          <div class="card-body"><h3 class="card-title">Cómo usar Notion AI para ser más productivo</h3><div class="card-meta"><span>Notion</span><span class="card-meta-dot"></span><span>8 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('article')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1499750310107-5fef28a66643?w=600&q=80" alt="CV con IA" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag blue">Trabajo</span></div>
          <div class="card-body"><h3 class="card-title">Cómo crear un currículum perfecto con ChatGPT</h3><div class="card-meta"><span>Empleo</span><span class="card-meta-dot"></span><span>6 min</span></div></div>
        </div>
        <div class="card" onclick="showPage('article')">
          <div class="card-img"><img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=600&q=80" alt="Marketing IA" style="height:180px"><div class="card-img-overlay"></div><span class="card-tag amber">Marketing</span></div>
          <div class="card-body"><h3 class="card-title">IA para marketing digital: guía completa 2025</h3><div class="card-meta"><span>Marketing</span><span class="card-meta-dot"></span><span>11 min</span></div></div>
        </div>
      </div>
    </div>
  </section>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li><li><a href="#" onclick="showPage('contacto')">Contacto</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ PROMPTS ═══════════════════════════════ -->
<div class="page" id="page-prompts">
  <div class="prompts-hero">
    <h1>Los mejores prompts en español</h1>
    <p>Copia y pega estos prompts directamente en ChatGPT. Listos para usar en el trabajo.</p>
  </div>
  <section class="section">
    <div class="container">
      <div class="prompts-grid">
        <div class="prompt-card">
          <span class="prompt-category">Emails profesionales</span>
          <p class="prompt-title">Email para pedir reunión</p>
          <p class="prompt-text">Escribe un email profesional para solicitar una reunión de 30 minutos con [nombre]. El objetivo es presentarle [tema]. Tono amable y directo. Máximo 5 líneas.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Emails profesionales</span>
          <p class="prompt-title">Responder queja de cliente</p>
          <p class="prompt-text">Redacta una respuesta empática para un cliente insatisfecho con [motivo]. Reconoce el problema, discúlpate y ofrece [solución]. Tono cercano y profesional.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Resumir documentos</span>
          <p class="prompt-title">Resumen ejecutivo</p>
          <p class="prompt-text">Resume el siguiente texto en 5 puntos clave para presentarlo a directivos. Usa lenguaje claro, sin tecnicismos. Máximo 3 líneas por punto: [pega el texto]</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Presentaciones</span>
          <p class="prompt-title">Esquema de presentación</p>
          <p class="prompt-text">Crea un esquema para una presentación de 10 diapositivas sobre [tema]. Incluye: título, objetivo, 6 diapositivas de contenido, conclusiones y próximos pasos.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Lluvia de ideas</span>
          <p class="prompt-title">Generar ideas de negocio</p>
          <p class="prompt-text">Dame 10 ideas innovadoras para [sector/objetivo]. Para cada idea incluye: nombre, descripción en 1 línea, público objetivo y por qué funcionaría en 2025.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Redes sociales</span>
          <p class="prompt-title">Post para LinkedIn</p>
          <p class="prompt-text">Escribe un post de LinkedIn sobre [tema]. Que sea personal, con historia real, gancho en la primera línea y llamada a la acción al final. Máximo 150 palabras.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">SEO y contenido</span>
          <p class="prompt-title">Artículo SEO completo</p>
          <p class="prompt-text">Escribe un artículo SEO de 1200 palabras sobre [keyword]. Incluye: introducción, 5 secciones H2 con contenido práctico, ejemplos reales y conclusión con CTA.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Currículum</span>
          <p class="prompt-title">Adaptar CV a oferta</p>
          <p class="prompt-text">Adapta mi currículum para esta oferta de trabajo: [pega la oferta]. Resalta mis puntos fuertes relevantes y usa las palabras clave de la oferta: [pega tu CV]</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Análisis</span>
          <p class="prompt-title">Análisis DAFO</p>
          <p class="prompt-text">Realiza un análisis DAFO completo para [empresa/proyecto/idea]. Incluye 4 puntos por cada sección: Debilidades, Amenazas, Fortalezas y Oportunidades.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Aprendizaje</span>
          <p class="prompt-title">Aprender un concepto rápido</p>
          <p class="prompt-text">Explícame [concepto] como si tuviera 15 años. Usa una analogía del mundo real, da 3 ejemplos prácticos y dime los 3 errores más comunes al aprenderlo.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Negociación</span>
          <p class="prompt-title">Negociar subida de sueldo</p>
          <p class="prompt-text">Ayúdame a preparar argumentos para negociar un aumento salarial del [%]. Mi puesto es [puesto], llevo [tiempo] en la empresa y mis logros son: [logros].</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
        <div class="prompt-card">
          <span class="prompt-category">Productividad</span>
          <p class="prompt-title">Plan de proyecto</p>
          <p class="prompt-text">Crea un plan de proyecto para [objetivo] en [plazo]. Divide en fases semanales, indica responsables (yo solo o equipo) y señala los 3 riesgos principales con solución.</p>
          <button class="copy-btn" onclick="copyPrompt(this)">Copiar prompt</button>
        </div>
      </div>
    </div>
  </section>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li><li><a href="#" onclick="showPage('contacto')">Contacto</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ HERRAMIENTAS ═══════════════════════════════ -->
<div class="page" id="page-herramientas">
  <div class="tools-hero">
    <div class="tools-hero-inner">
      <p class="sec-eyebrow">Comparativa actualizada</p>
      <h1 class="sec-title">Las mejores herramientas de IA para trabajar</h1>
      <p class="sec-sub">Analizamos y comparamos las principales herramientas de inteligencia artificial para que elijas la que mejor se adapta a tu trabajo.</p>
    </div>
  </div>
  <section class="section">
    <div class="container">
      <div class="tools-grid">
        <div class="tool-card">
          <div class="tool-header">
            <div class="tool-logo"><img src="https://images.unsplash.com/photo-1677442135703-1787eea5ce01?w=100&q=80" alt="ChatGPT"></div>
            <div><div class="tool-name">ChatGPT</div><div class="tool-type">Asistente IA conversacional</div></div>
          </div>
          <p class="tool-desc">El asistente de IA más popular del mundo. Ideal para escribir, resumir, analizar y automatizar tareas de texto. GPT-4o disponible en la versión gratuita.</p>
          <div class="tool-tags"><span class="tool-tag">Texto</span><span class="tool-tag">Emails</span><span class="tool-tag">Código</span><span class="tool-tag">Análisis</span></div>
          <div class="tool-footer"><span class="tool-price">Gratis + desde 20$/mes</span><span class="tool-rating">★★★★★ 4.9</span></div>
        </div>
        <div class="tool-card">
          <div class="tool-header">
            <div class="tool-logo"><img src="https://images.unsplash.com/photo-1655720031554-a929595ffad7?w=100&q=80" alt="Claude"></div>
            <div><div class="tool-name">Claude</div><div class="tool-type">Asistente IA de Anthropic</div></div>
          </div>
          <p class="tool-desc">Excelente para textos largos, análisis de documentos y tareas que requieren razonamiento profundo. Destaca en escritura creativa y profesional.</p>
          <div class="tool-tags"><span class="tool-tag">Documentos</span><span class="tool-tag">Escritura</span><span class="tool-tag">Análisis</span></div>
          <div class="tool-footer"><span class="tool-price">Gratis + desde 20$/mes</span><span class="tool-rating">★★★★★ 4.8</span></div>
        </div>
        <div class="tool-card">
          <div class="tool-header">
            <div class="tool-logo"><img src="https://images.unsplash.com/photo-1611532736597-de2d4265fba3?w=100&q=80" alt="Notion AI"></div>
            <div><div class="tool-name">Notion AI</div><div class="tool-type">Productividad con IA</div></div>
          </div>
          <p class="tool-desc">Integra IA directamente en tu espacio de trabajo. Resume notas, genera contenido, organiza proyectos y extrae información de tus documentos.</p>
          <div class="tool-tags"><span class="tool-tag">Notas</span><span class="tool-tag">Proyectos</span><span class="tool-tag">Resúmenes</span></div>
          <div class="tool-footer"><span class="tool-price paid">Desde 10$/mes</span><span class="tool-rating">★★★★☆ 4.6</span></div>
        </div>
        <div class="tool-card">
          <div class="tool-header">
            <div class="tool-logo"><img src="https://images.unsplash.com/photo-1542744094-3a31f272c490?w=100&q=80" alt="Canva AI"></div>
            <div><div class="tool-name">Canva IA</div><div class="tool-type">Diseño con inteligencia artificial</div></div>
          </div>
          <p class="tool-desc">Genera imágenes, presenta contenido visualmente y crea diseños profesionales con ayuda de IA. Ideal para marketing y comunicación visual.</p>
          <div class="tool-tags"><span class="tool-tag">Diseño</span><span class="tool-tag">Imágenes</span><span class="tool-tag">Presentaciones</span></div>
          <div class="tool-footer"><span class="tool-price">Gratis + desde 13€/mes</span><span class="tool-rating">★★★★☆ 4.5</span></div>
        </div>
        <div class="tool-card">
          <div class="tool-header">
            <div class="tool-logo"><img src="https://images.unsplash.com/photo-1518186285589-2f7649de83e0?w=100&q=80" alt="Make"></div>
            <div><div class="tool-name">Make (ex-Integromat)</div><div class="tool-type">Automatización sin código</div></div>
          </div>
          <p class="tool-desc">Conecta aplicaciones y automatiza flujos de trabajo sin programar. Integra ChatGPT en tus procesos: emails, hojas de cálculo, CRM y más.</p>
          <div class="tool-tags"><span class="tool-tag">Automatización</span><span class="tool-tag">No-code</span><span class="tool-tag">Integraciones</span></div>
          <div class="tool-footer"><span class="tool-price">Gratis + desde 9$/mes</span><span class="tool-rating">★★★★☆ 4.7</span></div>
        </div>
        <div class="tool-card">
          <div class="tool-header">
            <div class="tool-logo"><img src="https://images.unsplash.com/photo-1512941937669-90a1b58e7e9c?w=100&q=80" alt="Midjourney"></div>
            <div><div class="tool-name">Midjourney</div><div class="tool-type">Generación de imágenes IA</div></div>
          </div>
          <p class="tool-desc">El estándar de oro para generar imágenes a partir de texto. Resultados fotorrealistas y artísticos de altísima calidad para proyectos creativos y marketing.</p>
          <div class="tool-tags"><span class="tool-tag">Imágenes</span><span class="tool-tag">Diseño</span><span class="tool-tag">Marketing</span></div>
          <div class="tool-footer"><span class="tool-price paid">Desde 10$/mes</span><span class="tool-rating">★★★★★ 4.8</span></div>
        </div>
      </div>
    </div>
  </section>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li><li><a href="#" onclick="showPage('contacto')">Contacto</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ ARTICLE ═══════════════════════════════ -->
<div class="page" id="page-article">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1677442135703-1787eea5ce01?w=1400&q=85" alt="Cómo usar ChatGPT en el trabajo"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill">ChatGPT</span>
      <span class="article-tag-pill">Principiantes</span>
      <span class="article-tag-pill">Productividad</span>
    </div>
    <h1>Cómo usar ChatGPT en el trabajo: guía práctica para principiantes (2025)</h1>
    <p class="lead">Aprende a usar ChatGPT en tu trabajo desde cero con esta guía completa. Ejemplos reales, prompts listos y consejos para ser más productivo desde el primer día.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">Mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">8 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    <p>Si alguna vez te preguntaste cómo usar ChatGPT en el trabajo sin perder horas aprendiendo, esta guía es para ti. En los próximos minutos vas a entender exactamente qué puede hacer esta herramienta por tu día a día laboral, con ejemplos reales que puedes aplicar hoy mismo.</p>
    <div class="callout">💡 No necesitas experiencia técnica. Solo necesitas saber qué pedirle y cómo hacerlo.</div>
    <h2>¿Qué es ChatGPT y por qué importa en el trabajo?</h2>
    <p>ChatGPT es una herramienta de inteligencia artificial desarrollada por OpenAI que puede leer texto, entender lo que necesitas y responderte de forma natural. En el contexto laboral, eso significa que puedes usarlo para redactar documentos, resumir información, responder correos, analizar datos y generar ideas, todo en segundos.</p>
    <div class="article-body-img"><img src="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?w=1200&q=80" alt="Persona usando inteligencia artificial en el trabajo"></div>
    <h2>Cómo escribir un buen prompt</h2>
    <p>El secreto para sacarle partido a ChatGPT en el trabajo está en cómo le haces las preguntas. A esas instrucciones se les llama <strong>prompts</strong>. La fórmula básica es:</p>
    <div class="prompt-box">Rol + Tarea + Contexto + Formato<br><br>Ejemplo: "Actúa como redactor profesional. Escribe un resumen ejecutivo del siguiente texto para presentarlo a directivos. Máximo 3 párrafos, lenguaje formal."</div>
    <h2>7 usos reales de ChatGPT en el trabajo</h2>
    <p>Estos son los casos de uso más habituales entre profesionales hispanohablantes que ya usan ChatGPT en su día a día:</p>
    <p><strong>1. Redactar y mejorar correos</strong> — El uso más popular. ChatGPT puede escribir, mejorar o traducir cualquier email en segundos.</p>
    <p><strong>2. Resumir documentos largos</strong> — Pega el texto y pídele que lo resuma en puntos clave.</p>
    <p><strong>3. Preparar presentaciones</strong> — Genera el esquema completo con los puntos de cada diapositiva.</p>
    <p><strong>4. Redactar informes</strong> — Le das los datos y lo convierte en un informe bien estructurado.</p>
    <p><strong>5. Generar ideas</strong> — Lluvia de ideas ilimitada sobre cualquier tema.</p>
    <p><strong>6. Gestionar situaciones difíciles</strong> — Te ayuda a encontrar las palabras correctas para comunicaciones delicadas.</p>
    <p><strong>7. Traducir y adaptar textos</strong> — Traducciones naturales sin los errores de los traductores automáticos.</p>
    <div class="article-body-img"><img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf?w=1200&q=80" alt="Equipo trabajando con herramientas de IA"></div>
    <h2>Errores que debes evitar</h2>
    <p>No compartas información confidencial de tu empresa. Siempre revisa lo que genera. No esperes perfección a la primera: ajusta el prompt si la respuesta no es lo que buscabas.</p>
    <h2>Conclusión</h2>
    <p>ChatGPT no es el futuro del trabajo. Es el presente. Empieza con algo simple hoy: pídele que te ayude a redactar el próximo correo que tengas que escribir. A partir de ahí, irás descubriendo todo lo que puede hacer por ti.</p>
  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ NEWSLETTER ═══════════════════════════════ -->
<div class="page" id="page-newsletter">
  <section style="max-width:560px;margin:0 auto;padding:80px 48px;text-align:center">
    <div style="width:56px;height:56px;background:var(--blue);border-radius:14px;display:flex;align-items:center;justify-content:center;margin:0 auto 24px">
      <svg width="28" height="28" viewBox="0 0 24 24" fill="white"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
    </div>
    <h1 style="font-family:'Lora',serif;font-size:36px;margin-bottom:14px;letter-spacing:-.5px">Las mejores guías de IA cada semana</h1>
    <p style="font-size:16px;color:var(--ink2);margin-bottom:32px;line-height:1.7">Únete a más de 2.000 profesionales hispanohablantes que ya reciben nuestras guías. Sin spam. Cancela cuando quieras.</p>
    <div style="display:flex;gap:8px;max-width:420px;margin:0 auto 20px">
      <input type="email" placeholder="tucorreo@ejemplo.com" id="nl-email-page" style="flex:1;border:1px solid var(--border2);border-radius:var(--r-sm);padding:12px 16px;font-size:14px;font-family:inherit;outline:none">
      <button onclick="subscribeNL('nl-email-page')" style="background:var(--blue);color:white;border:none;padding:12px 20px;border-radius:var(--r-sm);font-size:14px;font-weight:500;cursor:pointer;font-family:inherit;white-space:nowrap">Suscribirme</button>
    </div>
    <p style="font-size:12px;color:var(--ink3)">✓ Gratis para siempre &nbsp; ✓ Sin spam &nbsp; ✓ Cancela cuando quieras</p>
    <div style="margin-top:48px;padding-top:40px;border-top:1px solid var(--border)">
      <p style="font-size:13px;color:var(--ink3);margin-bottom:16px">Lo que recibirás cada semana</p>
      <div style="display:flex;flex-direction:column;gap:12px;text-align:left">
        <div style="display:flex;gap:12px;align-items:flex-start"><span style="color:var(--blue);font-size:18px">→</span><p style="font-size:14px;color:var(--ink2)">Una guía práctica de IA para aplicar en tu trabajo</p></div>
        <div style="display:flex;gap:12px;align-items:flex-start"><span style="color:var(--blue);font-size:18px">→</span><p style="font-size:14px;color:var(--ink2)">3 prompts de la semana listos para copiar</p></div>
        <div style="display:flex;gap:12px;align-items:flex-start"><span style="color:var(--blue);font-size:18px">→</span><p style="font-size:14px;color:var(--ink2)">Las herramientas de IA más relevantes del momento</p></div>
      </div>
    </div>
  </section>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li><li><a href="#" onclick="showPage('contacto')">Contacto</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ SOBRE NOSOTROS ═══════════════════════════════ -->
<div class="page" id="page-sobre">
  <div style="max-width:740px;margin:0 auto;padding:56px 48px 64px">
    <button class="back-btn" onclick="showPage('home')">← Volver al inicio</button>
    <div style="display:flex;align-items:center;gap:16px;margin-bottom:32px">
      <div style="width:64px;height:64px;background:var(--blue);border-radius:16px;display:flex;align-items:center;justify-content:center;flex-shrink:0">
        <svg width="32" height="32" viewBox="0 0 24 24" fill="white"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 14.5v-9l6 4.5-6 4.5z"/></svg>
      </div>
      <div>
        <h1 style="font-family:'Lora',serif;font-size:36px;letter-spacing:-.5px;margin-bottom:4px">Sobre AprendeIA</h1>
        <p style="font-size:14px;color:var(--ink2)">Quiénes somos y por qué creamos este blog</p>
      </div>
    </div>

    <div style="border-radius:var(--r);overflow:hidden;margin-bottom:36px">
      <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?w=1200&q=80" alt="Equipo trabajando con inteligencia artificial" style="height:280px;width:100%;object-fit:cover">
    </div>

    <div style="font-size:16px;color:var(--ink2);line-height:1.85">
      <p style="margin-bottom:20px"><strong style="color:var(--ink)">AprendeIA nació de una frustración real:</strong> la mayoría del contenido sobre inteligencia artificial está en inglés, es demasiado técnico o no explica cómo aplicarlo en el trabajo del día a día.</p>

      <p style="margin-bottom:20px">Somos un equipo de profesionales hispanohablantes — diseñadores, redactores, marketers y emprendedores — que empezamos a usar herramientas de IA en nuestro trabajo y no encontramos recursos en español que fueran prácticos, claros y actualizados.</p>

      <p style="margin-bottom:20px">Así que decidimos crearlo nosotros.</p>

      <h2 style="font-family:'Lora',serif;font-size:24px;color:var(--ink);margin:36px 0 14px;font-weight:400">Nuestra misión</h2>
      <p style="margin-bottom:20px">Hacer que cualquier profesional hispanohablante — sin importar su nivel técnico — pueda aprender a usar la inteligencia artificial para trabajar mejor, ahorrar tiempo y crecer profesionalmente.</p>

      <h2 style="font-family:'Lora',serif;font-size:24px;color:var(--ink);margin:36px 0 14px;font-weight:400">Cómo trabajamos</h2>
      <p style="margin-bottom:12px">Todo el contenido de AprendeIA sigue estos principios:</p>
      <div style="display:flex;flex-direction:column;gap:10px;margin-bottom:24px">
        <div style="display:flex;gap:12px;align-items:flex-start;background:var(--surface);border-radius:var(--r-sm);padding:12px 14px">
          <span style="color:var(--blue);font-size:18px;flex-shrink:0">✓</span>
          <div><strong style="color:var(--ink)">Probado en el mundo real</strong> — solo publicamos lo que hemos testado nosotros mismos.</div>
        </div>
        <div style="display:flex;gap:12px;align-items:flex-start;background:var(--surface);border-radius:var(--r-sm);padding:12px 14px">
          <span style="color:var(--blue);font-size:18px;flex-shrink:0">✓</span>
          <div><strong style="color:var(--ink)">Actualizado constantemente</strong> — la IA cambia rápido, nuestro contenido también.</div>
        </div>
        <div style="display:flex;gap:12px;align-items:flex-start;background:var(--surface);border-radius:var(--r-sm);padding:12px 14px">
          <span style="color:var(--blue);font-size:18px;flex-shrink:0">✓</span>
          <div><strong style="color:var(--ink)">Sin tecnicismos innecesarios</strong> — explicamos todo como si fuera la primera vez que lo escuchas.</div>
        </div>
        <div style="display:flex;gap:12px;align-items:flex-start;background:var(--surface);border-radius:var(--r-sm);padding:12px 14px">
          <span style="color:var(--blue);font-size:18px;flex-shrink:0">✓</span>
          <div><strong style="color:var(--ink)">100% en español</strong> — pensado para España y Latinoamérica.</div>
        </div>
      </div>

      <h2 style="font-family:'Lora',serif;font-size:24px;color:var(--ink);margin:36px 0 14px;font-weight:400">¿Tienes alguna pregunta?</h2>
      <p>Si quieres contactar con nosotros, sugerir un tema o colaborar, escríbenos a <a href="mailto:hola@aprendeia.net" style="color:var(--blue)">hola@aprendeia.net</a> o usa nuestra <span style="color:var(--blue);cursor:pointer" onclick="showPage('contacto')">página de contacto</span>.</p>
    </div>
  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li><li><a href="#" onclick="showPage('contacto')">Contacto</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ CONTACTO ═══════════════════════════════ -->
<div class="page" id="page-contacto">
  <div style="max-width:600px;margin:0 auto;padding:56px 48px 64px">
    <button class="back-btn" onclick="showPage('home')">← Volver al inicio</button>
    <h1 style="font-family:'Lora',serif;font-size:36px;letter-spacing:-.5px;margin-bottom:8px">Contacto</h1>
    <p style="font-size:15px;color:var(--ink2);margin-bottom:36px">¿Tienes alguna pregunta, sugerencia o quieres colaborar? Escríbenos.</p>

    <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:32px">
      <div style="background:var(--surface);border-radius:var(--r);padding:18px;text-align:center">
        <div style="font-size:24px;margin-bottom:8px">✉️</div>
        <div style="font-size:13px;font-weight:500;margin-bottom:4px">Email</div>
        <a href="mailto:hola@aprendeia.net" style="font-size:13px;color:var(--blue)">hola@aprendeia.net</a>
      </div>
      <div style="background:var(--surface);border-radius:var(--r);padding:18px;text-align:center">
        <div style="font-size:24px;margin-bottom:8px">⏱️</div>
        <div style="font-size:13px;font-weight:500;margin-bottom:4px">Tiempo de respuesta</div>
        <div style="font-size:13px;color:var(--ink2)">24–48 horas</div>
      </div>
    </div>

    <div style="background:var(--white);border:1px solid var(--border);border-radius:var(--r);padding:28px">
      <h2 style="font-size:18px;font-weight:500;margin-bottom:20px">Envíanos un mensaje</h2>
      <div style="display:flex;flex-direction:column;gap:14px">
        <div>
          <label style="font-size:13px;font-weight:500;display:block;margin-bottom:6px">Tu nombre</label>
          <input type="text" placeholder="María García" id="contact-name" style="width:100%;border:1px solid var(--border2);border-radius:var(--r-sm);padding:11px 14px;font-size:14px;font-family:inherit;outline:none;color:var(--ink)">
        </div>
        <div>
          <label style="font-size:13px;font-weight:500;display:block;margin-bottom:6px">Tu email</label>
          <input type="email" placeholder="maria@ejemplo.com" id="contact-email" style="width:100%;border:1px solid var(--border2);border-radius:var(--r-sm);padding:11px 14px;font-size:14px;font-family:inherit;outline:none;color:var(--ink)">
        </div>
        <div>
          <label style="font-size:13px;font-weight:500;display:block;margin-bottom:6px">Asunto</label>
          <select id="contact-subject" style="width:100%;border:1px solid var(--border2);border-radius:var(--r-sm);padding:11px 14px;font-size:14px;font-family:inherit;outline:none;color:var(--ink);background:white">
            <option>Sugerencia de artículo</option>
            <option>Colaboración</option>
            <option>Corrección de contenido</option>
            <option>Consulta general</option>
            <option>Otro</option>
          </select>
        </div>
        <div>
          <label style="font-size:13px;font-weight:500;display:block;margin-bottom:6px">Mensaje</label>
          <textarea id="contact-msg" placeholder="Escribe tu mensaje aquí..." rows="5" style="width:100%;border:1px solid var(--border2);border-radius:var(--r-sm);padding:11px 14px;font-size:14px;font-family:inherit;outline:none;resize:vertical;color:var(--ink)"></textarea>
        </div>
        <button onclick="sendContact()" style="background:var(--blue);color:white;border:none;padding:13px;border-radius:var(--r-sm);font-size:14px;font-weight:500;cursor:pointer;font-family:inherit;transition:background .15s" onmouseover="this.style.background='#1d4ed8'" onmouseout="this.style.background='#2563eb'">Enviar mensaje</button>
        <p id="contact-ok" style="font-size:13px;color:#059669;text-align:center;display:none">✓ Mensaje enviado. Te responderemos en 24–48h.</p>
      </div>
    </div>
  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li><li><a href="#" onclick="showPage('aviso')">Aviso legal</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ POLÍTICA DE PRIVACIDAD ═══════════════════════════════ -->
<div class="page" id="page-privacidad">
  <div style="max-width:740px;margin:0 auto;padding:56px 48px 64px;font-size:15px;color:var(--ink2);line-height:1.85">
    <button class="back-btn" onclick="showPage('home')">← Volver al inicio</button>
    <h1 style="font-family:'Lora',serif;font-size:36px;letter-spacing:-.5px;margin-bottom:6px;color:var(--ink)">Política de privacidad</h1>
    <p style="font-size:13px;color:var(--ink3);margin-bottom:36px">Última actualización: 13 de mayo de 2025</p>

    <p style="margin-bottom:20px">En <strong style="color:var(--ink)">AprendeIA</strong> (en adelante, "el sitio web") nos tomamos muy en serio la privacidad de nuestros usuarios. Esta política explica qué datos recogemos, cómo los usamos y qué derechos tienes.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">1. Responsable del tratamiento</h2>
    <p style="margin-bottom:20px">El responsable del tratamiento de los datos personales recogidos a través de este sitio web es el titular de <strong>AprendeIA</strong>, contactable a través de <a href="mailto:hola@aprendeia.net" style="color:var(--blue)">hola@aprendeia.net</a>.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">2. Datos que recogemos</h2>
    <p style="margin-bottom:12px">Este sitio web puede recoger los siguientes datos:</p>
    <ul style="padding-left:20px;margin-bottom:20px;display:flex;flex-direction:column;gap:8px">
      <li><strong style="color:var(--ink)">Datos de navegación:</strong> dirección IP, tipo de navegador, páginas visitadas y tiempo de permanencia, recogidos de forma anónima a través de Google Analytics.</li>
      <li><strong style="color:var(--ink)">Datos del formulario de contacto:</strong> nombre y email, únicamente cuando el usuario los facilita voluntariamente.</li>
      <li><strong style="color:var(--ink)">Datos de suscripción:</strong> email, cuando el usuario se suscribe voluntariamente a la newsletter.</li>
      <li><strong style="color:var(--ink)">Cookies:</strong> información técnica necesaria para el funcionamiento del sitio y cookies de análisis de Google Analytics.</li>
    </ul>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">3. Finalidad del tratamiento</h2>
    <p style="margin-bottom:12px">Los datos recogidos se utilizan para:</p>
    <ul style="padding-left:20px;margin-bottom:20px;display:flex;flex-direction:column;gap:8px">
      <li>Analizar el tráfico y comportamiento de los usuarios para mejorar el contenido del sitio.</li>
      <li>Responder a los mensajes recibidos a través del formulario de contacto.</li>
      <li>Enviar la newsletter a quienes se hayan suscrito voluntariamente.</li>
      <li>Mostrar publicidad relevante a través de Google AdSense.</li>
    </ul>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">4. Google AdSense y publicidad</h2>
    <p style="margin-bottom:20px">Este sitio utiliza <strong style="color:var(--ink)">Google AdSense</strong> para mostrar anuncios. Google puede usar cookies para mostrar anuncios basados en las visitas anteriores del usuario a este sitio u otros sitios web. Para más información sobre cómo Google usa los datos, visita <a href="https://policies.google.com/privacy" target="_blank" rel="noopener" style="color:var(--blue)">policies.google.com/privacy</a>. Puedes desactivar el uso de cookies de Google en <a href="https://adssettings.google.com" target="_blank" rel="noopener" style="color:var(--blue)">adssettings.google.com</a>.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">5. Google Analytics</h2>
    <p style="margin-bottom:20px">Utilizamos Google Analytics para analizar el uso del sitio web. Google Analytics recopila información de forma anónima. Puedes desactivar el seguimiento de Google Analytics instalando el <a href="https://tools.google.com/dlpage/gaoptout" target="_blank" rel="noopener" style="color:var(--blue)">complemento de inhabilitación del navegador</a>.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">6. Derechos del usuario</h2>
    <p style="margin-bottom:12px">De acuerdo con el Reglamento General de Protección de Datos (RGPD), tienes derecho a:</p>
    <ul style="padding-left:20px;margin-bottom:20px;display:flex;flex-direction:column;gap:6px">
      <li>Acceder a tus datos personales.</li>
      <li>Rectificar datos inexactos.</li>
      <li>Solicitar la supresión de tus datos.</li>
      <li>Oponerte al tratamiento de tus datos.</li>
      <li>Solicitar la portabilidad de tus datos.</li>
    </ul>
    <p style="margin-bottom:20px">Para ejercer estos derechos, escríbenos a <a href="mailto:hola@aprendeia.net" style="color:var(--blue)">hola@aprendeia.net</a>.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">7. Cookies</h2>
    <p style="margin-bottom:20px">Este sitio utiliza cookies propias y de terceros. Al continuar navegando, aceptas su uso conforme a esta política. Puedes gestionar o desactivar las cookies desde la configuración de tu navegador. Para más información, consulta nuestra <span style="color:var(--blue);cursor:pointer" onclick="showPage('aviso')">política de cookies</span>.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">8. Cambios en esta política</h2>
    <p>Nos reservamos el derecho de actualizar esta política de privacidad en cualquier momento. Los cambios serán publicados en esta página con la fecha de actualización.</p>
  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('aviso')">Aviso legal</a></li><li><a href="#" onclick="showPage('contacto')">Contacto</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ AVISO LEGAL ═══════════════════════════════ -->
<div class="page" id="page-aviso">
  <div style="max-width:740px;margin:0 auto;padding:56px 48px 64px;font-size:15px;color:var(--ink2);line-height:1.85">
    <button class="back-btn" onclick="showPage('home')">← Volver al inicio</button>
    <h1 style="font-family:'Lora',serif;font-size:36px;letter-spacing:-.5px;margin-bottom:6px;color:var(--ink)">Aviso legal y cookies</h1>
    <p style="font-size:13px;color:var(--ink3);margin-bottom:36px">Última actualización: 13 de mayo de 2025</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:0 0 12px;font-weight:400">1. Titularidad del sitio web</h2>
    <p style="margin-bottom:20px">El presente sitio web <strong style="color:var(--ink)">AprendeIA</strong>, accesible en aprendeia.github.io, es de carácter informativo y educativo. El contenido publicado tiene como único fin divulgar información sobre el uso de herramientas de inteligencia artificial.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">2. Propiedad intelectual</h2>
    <p style="margin-bottom:20px">Todos los contenidos de este sitio web, incluyendo textos, imágenes, diseño y código, son propiedad de AprendeIA o se utilizan bajo licencia. Queda prohibida su reproducción total o parcial sin autorización expresa.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">3. Exención de responsabilidad</h2>
    <p style="margin-bottom:20px">AprendeIA no se hace responsable de los posibles errores u omisiones en los contenidos publicados, ni de los daños que pudieran derivarse del uso de la información aquí recogida. Los artículos son de carácter orientativo y no constituyen asesoramiento profesional.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">4. Política de cookies</h2>
    <p style="margin-bottom:12px">Este sitio web utiliza cookies. A continuación detallamos las cookies utilizadas:</p>
    <div style="border:1px solid var(--border);border-radius:var(--r);overflow:hidden;margin-bottom:20px">
      <table style="width:100%;border-collapse:collapse;font-size:13px">
        <thead><tr style="background:var(--surface)">
          <th style="padding:10px 14px;text-align:left;font-weight:500;border-bottom:1px solid var(--border)">Cookie</th>
          <th style="padding:10px 14px;text-align:left;font-weight:500;border-bottom:1px solid var(--border)">Proveedor</th>
          <th style="padding:10px 14px;text-align:left;font-weight:500;border-bottom:1px solid var(--border)">Finalidad</th>
          <th style="padding:10px 14px;text-align:left;font-weight:500;border-bottom:1px solid var(--border)">Duración</th>
        </tr></thead>
        <tbody>
          <tr style="border-bottom:1px solid var(--border)"><td style="padding:9px 14px">_ga, _gid</td><td style="padding:9px 14px">Google Analytics</td><td style="padding:9px 14px">Análisis de tráfico</td><td style="padding:9px 14px">2 años / 24h</td></tr>
          <tr style="border-bottom:1px solid var(--border)"><td style="padding:9px 14px">_gads</td><td style="padding:9px 14px">Google AdSense</td><td style="padding:9px 14px">Publicidad personalizada</td><td style="padding:9px 14px">13 meses</td></tr>
          <tr><td style="padding:9px 14px">cookie_consent</td><td style="padding:9px 14px">AprendeIA</td><td style="padding:9px 14px">Preferencias de cookies</td><td style="padding:9px 14px">1 año</td></tr>
        </tbody>
      </table>
    </div>
    <p style="margin-bottom:20px">Puedes gestionar o desactivar las cookies desde la configuración de tu navegador. Ten en cuenta que desactivar algunas cookies puede afectar al funcionamiento del sitio.</p>

    <h2 style="font-family:'Lora',serif;font-size:22px;color:var(--ink);margin:36px 0 12px;font-weight:400">5. Legislación aplicable</h2>
    <p>Este aviso legal se rige por la legislación española y europea vigente, en particular por el RGPD (Reglamento UE 2016/679) y la LSSI-CE.</p>
  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li><li><a href="#" onclick="showPage('contacto')">Contacto</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>


<!-- ═══ ARTÍCULO: art1 ═══ -->
<div class="page" id="page-art1">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1677442135703-1787eea5ce01?w=1400&q=85" alt="Pantalla con ChatGPT abierto en el trabajo"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--blue-l);color:var(--blue)">ChatGPT</span>
    </div>
    <h1>Cómo usar ChatGPT en el trabajo: guía práctica para principiantes</h1>
    <p class="lead">Aprende a usar ChatGPT en tu trabajo desde cero. Ejemplos reales, prompts listos y consejos para ser más productivo desde el primer día. Sin tecnicismos.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">13 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">8 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Si alguna vez te preguntaste cómo usar ChatGPT en el trabajo sin perder horas aprendiendo, esta guía es para ti. En los próximos minutos vas a entender exactamente qué puede hacer esta herramienta por tu día a día laboral, con ejemplos reales que puedes aplicar hoy mismo.</p>
<div class="callout">💡 No necesitas experiencia técnica. Solo necesitas saber qué pedirle y cómo hacerlo.</div>
<h2>¿Qué es ChatGPT y por qué importa en el trabajo?</h2>
<p>ChatGPT es una herramienta de inteligencia artificial creada por OpenAI que entiende texto en lenguaje natural y te responde como si chatearas con una persona muy bien informada. En el trabajo, eso significa que puedes pedirle que redacte, resuma, analice, traduzca o genere ideas — todo en segundos.</p>
<p>Según datos de OpenAI, más de 100 millones de personas usan ChatGPT cada semana, la mayoría para ser más productivos en su trabajo. No es una moda: es una ventaja competitiva real que ya están usando tus competidores.</p>
<h2>Cómo crear tu cuenta gratis</h2>
<p>Entra en <strong>chat.openai.com</strong>, haz clic en "Registrarse" y accede con tu cuenta de Google. En menos de 2 minutos tendrás acceso a ChatGPT gratuito. La versión gratuita con GPT-4o es más que suficiente para empezar.</p>
<h2>La fórmula para escribir buenos prompts</h2>
<p>El secreto está en cómo le haces las preguntas. A esas instrucciones se les llama <strong>prompts</strong>. La fórmula básica es: <strong>Rol + Tarea + Contexto + Formato</strong>.</p>
<div class="prompt-box">Actúa como redactor profesional. Escribe un resumen ejecutivo del siguiente texto para presentarlo a directivos. Máximo 3 párrafos, lenguaje formal: [pega aquí el texto]</div>
<h2>7 usos reales en el trabajo</h2>
<p><strong>1. Redactar y mejorar correos</strong> — El uso más popular. Pídele que escriba, mejore o traduzca cualquier email en segundos.</p>
<p><strong>2. Resumir documentos largos</strong> — Pega el texto y pídele que lo resuma en 5 puntos clave.</p>
<p><strong>3. Preparar presentaciones</strong> — Genera el esquema completo con los puntos de cada diapositiva.</p>
<p><strong>4. Redactar informes</strong> — Le das los datos en bruto y lo convierte en un informe estructurado.</p>
<p><strong>5. Lluvia de ideas</strong> — Genera 10 ideas sobre cualquier tema en 10 segundos.</p>
<p><strong>6. Gestionar situaciones difíciles</strong> — Te ayuda a encontrar las palabras correctas para comunicaciones delicadas.</p>
<p><strong>7. Traducir y adaptar textos</strong> — Traducciones naturales sin los errores de los traductores automáticos.</p>
<h2>Errores que debes evitar</h2>
<p>No compartas información confidencial de tu empresa. Siempre revisa lo que genera. Y no te frustres si la primera respuesta no es perfecta: ajusta el prompt y vuelve a intentarlo.</p>
<h2>Conclusión</h2>
<p>ChatGPT no es el futuro del trabajo. Es el presente. Empieza hoy con algo simple: pídele que te ayude con el próximo correo que tengas que escribir. A partir de ahí, irás descubriendo todo lo que puede hacer por ti.</p>
<div class="callout">📌 Siguiente paso: lee nuestra guía sobre <strong>los 50 mejores prompts en español</strong> para sacarle el máximo partido desde el primer día.</div>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art2 ═══ -->
<div class="page" id="page-art2">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1596526131083-e8c633c948d2?w=1400&q=85" alt="Persona escribiendo un email profesional"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--blue-l);color:var(--blue)">ChatGPT</span>
    </div>
    <h1>Cómo usar ChatGPT para escribir emails profesionales (con plantillas)</h1>
    <p class="lead">Aprende a usar ChatGPT para redactar emails profesionales en segundos. Incluye prompts listos y plantillas para los tipos de emails más habituales en el trabajo.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">13 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">6 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Escribir emails profesionales ocupa una parte enorme de nuestra jornada laboral. Según estudios, los trabajadores de oficina dedican de media más de 2 horas diarias al correo electrónico. ChatGPT puede reducir ese tiempo drásticamente.</p>
<h2>Por qué usar IA para escribir emails</h2>
<p>No se trata de ser vago. Se trata de ser más eficiente. ChatGPT te ayuda a estructurar mejor las ideas, elegir el tono adecuado y evitar errores de redacción — especialmente útil cuando escribes bajo presión o en un idioma que no es el tuyo.</p>
<h2>El prompt base para cualquier email</h2>
<div class="prompt-box">Escribe un email profesional para [objetivo]. Destinatario: [nombre/cargo]. Tono: [formal/cercano/urgente]. Puntos clave a mencionar: [punto 1, punto 2]. Máximo [X] líneas.</div>
<h2>Plantillas para los emails más habituales</h2>
<p><strong>Email de seguimiento tras reunión:</strong></p>
<div class="prompt-box">Escribe un email de seguimiento tras una reunión con [nombre] sobre [tema]. Resume los acuerdos alcanzados, los próximos pasos y quién es responsable de cada uno. Tono profesional y directo.</div>
<p><strong>Email para pedir extensión de plazo:</strong></p>
<div class="prompt-box">Escribe un email para pedir a [nombre] una extensión de [X días] para entregar [proyecto]. Explica brevemente el motivo [razón] y ofrece una nueva fecha. Tono respetuoso.</div>
<p><strong>Respuesta a queja de cliente:</strong></p>
<div class="prompt-box">Redacta una respuesta empática a un cliente insatisfecho con [problema]. Reconoce el inconveniente, discúlpate y ofrece [solución]. Tono cercano y profesional. Máximo 5 líneas.</div>
<h2>Trucos para mejorar los resultados</h2>
<p>Si la primera versión no te convence, dile exactamente qué cambiar: "hazlo más corto", "usa un tono más cercano", "añade urgencia sin ser agresivo". ChatGPT entiende estas instrucciones de ajuste perfectamente.</p>
<h2>Lo que NO debes hacer</h2>
<p>No envíes el email sin leerlo primero. ChatGPT puede cometer errores de contexto o incluir información incorrecta. Siempre revisa antes de pulsar "Enviar".</p>
<h2>Conclusión</h2>
<p>Con los prompts correctos, puedes pasar de invertir 20 minutos en un email a menos de 5. Empieza con el tipo de email que más te cuesta escribir y verás la diferencia inmediatamente.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art3 ═══ -->
<div class="page" id="page-art3">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1518186285589-2f7649de83e0?w=1400&q=85" alt="Automatización de tareas con inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--teal-l);color:var(--teal)">Productividad</span>
    </div>
    <h1>Cómo automatizar tareas repetitivas con ChatGPT: 10 ejemplos reales</h1>
    <p class="lead">Descubre cómo automatizar las tareas más repetitivas de tu trabajo usando ChatGPT. 10 ejemplos reales con prompts listos para copiar.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">13 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">7 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Una de las formas más poderosas de usar ChatGPT no es para hacer cosas nuevas, sino para dejar de hacer cosas repetitivas. Si hay una tarea que haces cada semana de la misma manera, probablemente puedas delegársela a la IA.</p>
<h2>¿Qué tareas se pueden automatizar con ChatGPT?</h2>
<p>Cualquier tarea que implique: procesar texto de forma repetitiva, generar documentos con estructura fija, responder preguntas frecuentes o transformar datos de un formato a otro.</p>
<h2>10 ejemplos reales con sus prompts</h2>
<p><strong>1. Generar informes semanales</strong></p>
<div class="prompt-box">Genera un informe semanal ejecutivo basado en estos datos: [datos]. Estructura: resumen ejecutivo, métricas clave, logros, incidencias y próximos pasos. Tono profesional.</div>
<p><strong>2. Responder preguntas frecuentes</strong></p>
<div class="prompt-box">Actúa como agente de soporte. Responde esta pregunta de cliente de forma amable y clara: [pregunta]. Base de conocimiento: [información relevante].</div>
<p><strong>3. Crear descripciones de productos</strong></p>
<div class="prompt-box">Escribe una descripción de producto para [nombre del producto]. Características: [lista]. Público objetivo: [descripción]. Tono: [tono]. Máximo 100 palabras.</div>
<p><strong>4. Resumir reuniones</strong></p>
<div class="prompt-box">Resume esta transcripción de reunión en: asistentes, temas tratados, decisiones tomadas y próximos pasos con responsables: [transcripción].</div>
<p><strong>5. Convertir datos en tablas</strong></p>
<div class="prompt-box">Convierte estos datos en una tabla Markdown clara y ordenada: [datos]. Añade una fila de totales si aplica.</div>
<p><strong>6. Generar ideas de contenido para redes sociales</strong></p>
<div class="prompt-box">Genera 10 ideas de posts para LinkedIn sobre [tema]. Para cada idea incluye: gancho inicial, desarrollo en 2 líneas y hashtags relevantes.</div>
<p><strong>7. Redactar convocatorias de reunión</strong></p>
<div class="prompt-box">Redacta la convocatoria de una reunión sobre [tema] con [asistentes]. Fecha: [fecha]. Duración: [duración]. Incluye agenda detallada con tiempos.</div>
<p><strong>8. Analizar feedback de clientes</strong></p>
<div class="prompt-box">Analiza estas opiniones de clientes y extrae: temas principales, sentimiento general, problemas más mencionados y sugerencias de mejora: [opiniones].</div>
<p><strong>9. Crear plantillas de documentos</strong></p>
<div class="prompt-box">Crea una plantilla reutilizable para [tipo de documento] en mi empresa [sector]. Incluye todas las secciones estándar con instrucciones de qué escribir en cada una.</div>
<p><strong>10. Traducir y adaptar al mercado local</strong></p>
<div class="prompt-box">Traduce y adapta culturalmente este texto del inglés al español latinoamericano para el mercado de [país]: [texto]. Mantén el tono original.</div>
<h2>Conclusión</h2>
<p>La automatización con ChatGPT no requiere conocimientos técnicos. Solo necesitas identificar qué tareas haces repetidamente y construir el prompt adecuado. Empieza por la tarea que más tiempo te roba y verás un ahorro inmediato.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art4 ═══ -->
<div class="page" id="page-art4">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=1400&q=85" alt="Estudiante usando inteligencia artificial para estudiar"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--purple-l);color:var(--purple)">Educación</span>
    </div>
    <h1>ChatGPT para estudiantes: cómo usarlo sin hacer trampa</h1>
    <p class="lead">Guía honesta para estudiantes sobre cómo usar ChatGPT de forma ética y productiva: resumir apuntes, entender conceptos difíciles y preparar exámenes.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">14 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">6 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>ChatGPT puede ser el mejor compañero de estudio que hayas tenido — o una trampa que arruine tu aprendizaje. La diferencia está en cómo lo usas. Esta guía te explica cómo aprovecharlo sin cruzar la línea.</p>
<h2>Lo que SÍ está bien hacer</h2>
<p>Usar ChatGPT como herramienta de aprendizaje es completamente legítimo. Igual que usarías un libro, un tutor o YouTube para entender algo, ChatGPT puede explicarte conceptos difíciles de formas diferentes hasta que los entiendas.</p>
<h2>Resumir y estructurar apuntes</h2>
<div class="prompt-box">Resume estos apuntes en un esquema claro con los conceptos principales, definiciones clave y ejemplos para cada uno: [pega tus apuntes].</div>
<h2>Entender conceptos difíciles</h2>
<div class="prompt-box">Explícame [concepto] como si tuviera 15 años. Usa una analogía del mundo real y dame 2 ejemplos concretos. Luego hazme 3 preguntas para comprobar si lo entendí.</div>
<h2>Preparar exámenes</h2>
<div class="prompt-box">Basándote en este temario: [temario], crea un examen de práctica con 10 preguntas de tipo test y 3 preguntas de desarrollo. Al final, dame las respuestas correctas con explicación.</div>
<h2>Practicar idiomas</h2>
<div class="prompt-box">Quiero practicar inglés. Actúa como mi profesor de conversación. Empieza hablándome sobre [tema], corrígeme cuando cometa errores y explícame por qué son errores.</div>
<h2>Lo que NO debes hacer</h2>
<p>Pedirle que escriba tus trabajos o ensayos para entregarlos como propios es trampa académica, igual que copiar de un libro. Más allá de las consecuencias académicas, te priva de desarrollar habilidades que vas a necesitar en tu vida profesional.</p>
<p>Además, ChatGPT comete errores. Si copias sin entender lo que copias, no podrás defenderlo cuando te pregunten sobre ello.</p>
<h2>Conclusión</h2>
<p>Úsalo para aprender más rápido y mejor, no para evitar el aprendizaje. Los estudiantes que usan IA como herramienta de comprensión tienen ventaja sobre los que no la usan — y sobre los que la usan para hacer trampa.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art5 ═══ -->
<div class="page" id="page-art5">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=1400&q=85" alt="Representación visual de la inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--amber-l);color:var(--amber)">Conceptos</span>
    </div>
    <h1>Qué es la inteligencia artificial: explicación sencilla para no técnicos</h1>
    <p class="lead">¿Qué es realmente la inteligencia artificial? Explicación clara y sin tecnicismos para cualquier persona, con ejemplos del día a día que ya conoces.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">14 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">5 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>La inteligencia artificial lleva años en los titulares, pero muy poca gente entiende realmente qué es. Esta guía te lo explica de forma clara, sin jerga técnica y con ejemplos que ya forman parte de tu vida cotidiana.</p>
<h2>La definición simple</h2>
<p>La inteligencia artificial (IA) es la capacidad de los ordenadores para realizar tareas que normalmente requerirían inteligencia humana: entender lenguaje, reconocer imágenes, tomar decisiones o aprender de la experiencia.</p>
<p>Una analogía útil: imagina que entrenas a alguien mostrándole millones de ejemplos de algo hasta que aprende a reconocerlo o hacerlo solo. Eso es esencialmente lo que hace la IA, pero con datos en lugar de ejemplos físicos.</p>
<h2>La IA que ya usas sin saberlo</h2>
<p>No es ciencia ficción. Ya usas IA todos los días: cuando Netflix te recomienda series, cuando Gmail filtra el spam, cuando el GPS calcula la mejor ruta, cuando tu móvil desbloquea con tu cara o cuando le hablas a Siri o Google Asistente.</p>
<h2>Los tipos principales de IA</h2>
<p><strong>IA estrecha o débil:</strong> diseñada para una tarea específica. El reconocimiento de voz de tu móvil, los filtros de spam, los sistemas de recomendación de Spotify. Es la IA que existe hoy.</p>
<p><strong>IA general:</strong> capaz de hacer cualquier tarea intelectual que haría un humano. Todavía no existe, aunque herramientas como ChatGPT se acercan en algunas áreas.</p>
<p><strong>IA generativa:</strong> la que genera contenido nuevo — texto, imágenes, audio, vídeo. Es la revolución actual. ChatGPT, Midjourney, DALL-E, Stable Diffusion pertenecen a esta categoría.</p>
<h2>¿Debería preocuparme por la IA en mi trabajo?</h2>
<p>La pregunta correcta no es si la IA va a reemplazar tu trabajo, sino cómo puedes usarla para hacer tu trabajo mejor y más rápido. Las personas que aprenden a trabajar con IA tienen una ventaja enorme sobre las que la ignoran.</p>
<h2>Conclusión</h2>
<p>La IA no es magia ni ciencia ficción. Es una herramienta poderosísima que ya está transformando cómo trabajamos. Cuanto antes la entiendas y empieces a usarla, mejor posicionado estarás en los próximos años.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art6 ═══ -->
<div class="page" id="page-art6">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1611532736597-de2d4265fba3?w=1400&q=85" alt="Notion AI en pantalla de ordenador"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--teal-l);color:var(--teal)">Productividad</span>
    </div>
    <h1>Cómo usar Notion AI para ser más productivo: guía completa</h1>
    <p class="lead">Guía completa para sacar el máximo partido a Notion AI. Aprende a resumir notas, generar contenido y organizar proyectos con inteligencia artificial integrada.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">15 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">8 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Notion AI integra la inteligencia artificial directamente en tu espacio de trabajo. En lugar de cambiar entre aplicaciones, puedes pedirle ayuda sin salir de donde ya tienes toda tu información.</p>
<h2>Qué es Notion AI</h2>
<p>Notion AI es una capa de inteligencia artificial añadida a Notion que te permite generar texto, resumir contenido, mejorar redacciones y responder preguntas directamente dentro de tus páginas y bases de datos.</p>
<h2>Cómo activarlo</h2>
<p>En cualquier página de Notion, escribe <strong>/IA</strong> o pulsa la tecla <strong>Espacio</strong> en una línea vacía. Aparecerá el menú de Notion AI con todas las opciones disponibles. También puedes seleccionar texto y hacer clic en "Preguntar a la IA".</p>
<h2>Los 5 usos más útiles</h2>
<p><strong>1. Resumir reuniones y notas largas</strong> — Selecciona el texto y pídele "Resumir". Obtiene los puntos clave en segundos.</p>
<p><strong>2. Mejorar tus escritos</strong> — "Mejorar redacción", "Hacer más formal" o "Simplificar" son comandos que transforman cualquier texto con un clic.</p>
<p><strong>3. Generar plantillas</strong> — Pídele que cree una plantilla para cualquier tipo de documento: propuesta de proyecto, acta de reunión, plan de marketing.</p>
<p><strong>4. Continuar donde lo dejaste</strong> — Si tienes un documento a medias, selecciona lo que tienes y pídele que "Continúe escribiendo".</p>
<p><strong>5. Generar tablas y listas</strong> — "Crea una tabla comparativa de [X opciones] con las siguientes columnas: [columnas]".</p>
<h2>Notion AI vs ChatGPT: ¿cuándo usar cada uno?</h2>
<p>Usa <strong>Notion AI</strong> cuando ya tienes información en Notion y quieres procesarla o ampliarla sin salir del flujo de trabajo. Usa <strong>ChatGPT</strong> para tareas más complejas, conversaciones largas o cuando necesitas información actualizada de internet.</p>
<h2>Conclusión</h2>
<p>Notion AI es especialmente poderoso para equipos que ya usan Notion como base de conocimiento. La IA tiene acceso a todo tu contenido, lo que la hace mucho más contextual que usar un asistente externo.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art7 ═══ -->
<div class="page" id="page-art7">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1655720031554-a929595ffad7?w=1400&q=85" alt="Comparativa entre asistentes de inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--purple-l);color:var(--purple)">Comparativa</span>
    </div>
    <h1>ChatGPT vs Gemini vs Claude: ¿cuál es el mejor en 2025?</h1>
    <p class="lead">Comparativa honesta entre ChatGPT, Google Gemini y Claude en 2025. Descubre cuál es mejor para escribir, analizar documentos, programar y uso diario.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">15 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">9 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>En 2025, los tres grandes asistentes de IA — ChatGPT de OpenAI, Gemini de Google y Claude de Anthropic — son herramientas maduras y potentes. Pero no son iguales. Esta comparativa te ayuda a elegir el que mejor se adapta a lo que necesitas.</p>
<h2>ChatGPT (OpenAI)</h2>
<p>El más popular y versátil. Con GPT-4o en la versión gratuita, es excelente para tareas generales: redactar, resumir, programar, analizar. Su punto fuerte es la amplia disponibilidad de plugins e integraciones.</p>
<p><strong>Mejor para:</strong> uso general, programación, integración con otras herramientas, crear imágenes con DALL-E.</p>
<p><strong>Limitación:</strong> puede "alucinar" información con más frecuencia que sus competidores.</p>
<h2>Google Gemini</h2>
<p>La apuesta de Google, integrado directamente con el ecosistema Google (Gmail, Docs, Drive). Su mayor ventaja es el acceso a información actualizada de internet en tiempo real.</p>
<p><strong>Mejor para:</strong> búsqueda de información actual, integración con Google Workspace, usuarios que ya viven en el ecosistema Google.</p>
<p><strong>Limitación:</strong> en tareas de escritura creativa y análisis profundo, queda por detrás de los otros dos.</p>
<h2>Claude (Anthropic)</h2>
<p>El más refinado para tareas de escritura y análisis de documentos largos. Claude destaca por su capacidad de procesar documentos extensos y por la calidad y matiz de sus textos.</p>
<p><strong>Mejor para:</strong> análisis de documentos, escritura de alta calidad, tareas que requieren razonamiento profundo.</p>
<p><strong>Limitación:</strong> menos integraciones con herramientas externas que ChatGPT.</p>
<h2>Tabla resumen</h2>
<p>Para escritura creativa: <strong>Claude</strong>. Para programación: <strong>ChatGPT</strong>. Para información actualizada: <strong>Gemini</strong>. Para uso diario general: <strong>ChatGPT</strong> (versión gratuita más generosa). Para analizar documentos largos: <strong>Claude</strong>.</p>
<h2>Conclusión</h2>
<p>No hay un ganador absoluto. La estrategia más inteligente es usar ChatGPT o Claude como base y recurrir a Gemini cuando necesites información muy reciente. Los tres tienen versión gratuita, así que puedes probarlos sin coste.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art8 ═══ -->
<div class="page" id="page-art8">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1499750310107-5fef28a66643?w=1400&q=85" alt="Persona creando su currículum con inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--blue-l);color:var(--blue)">Trabajo</span>
    </div>
    <h1>Cómo crear un currículum perfecto con ChatGPT: paso a paso</h1>
    <p class="lead">Cómo usar ChatGPT para crear o mejorar tu currículum, adaptarlo a cada oferta de trabajo y escribir una carta de presentación que destaque.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">16 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">7 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>El currículum es tu primera impresión. Y ChatGPT puede ayudarte a que sea una impresión memorable, adaptada a cada oferta y libre de los errores más comunes.</p>
<h2>Antes de empezar: lo que necesitas preparar</h2>
<p>Antes de pedirle ayuda a ChatGPT, prepara: tu historial de trabajo (empresas, cargos, fechas), tus logros más importantes con datos concretos, y la oferta de trabajo a la que vas a aplicar.</p>
<h2>Prompt para crear el CV desde cero</h2>
<div class="prompt-box">Actúa como experto en recursos humanos. Crea un currículum profesional para [puesto] basándote en esta información: [experiencia]. El resultado debe tener: datos de contacto, perfil profesional de 3 líneas, experiencia con logros cuantificables, formación y habilidades. Usa verbos de acción.</div>
<h2>Adaptar el CV a una oferta concreta</h2>
<p>Este es el uso más potente. Las empresas usan sistemas automáticos (ATS) que filtran CVs por palabras clave. ChatGPT puede optimizar tu CV para pasar ese filtro:</p>
<div class="prompt-box">Tengo este CV: [CV]. Y esta oferta de trabajo: [oferta]. Adapta mi CV para esta posición: resalta las experiencias más relevantes, añade las palabras clave de la oferta y ajusta el perfil profesional. Sin inventar nada que no esté en mi CV original.</div>
<h2>Carta de presentación</h2>
<div class="prompt-box">Escribe una carta de presentación para esta oferta: [oferta]. Mi experiencia relevante: [experiencia]. Tono: profesional pero cercano. Estructura: gancho inicial impactante, por qué encajo en este puesto, qué puedo aportarles, cierre con llamada a la acción. Máximo 3 párrafos.</div>
<h2>Preparar la entrevista</h2>
<div class="prompt-box">Basándote en esta oferta: [oferta] y mi CV: [CV], ¿qué preguntas difíciles me harán probablemente en la entrevista? Dame también la respuesta ideal para cada una usando el método STAR.</div>
<h2>Conclusión</h2>
<p>ChatGPT no va a conseguirte el trabajo — eso depende de ti. Pero sí puede ayudarte a presentarte de la mejor forma posible y maximizar tus posibilidades de llegar a la entrevista.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art9 ═══ -->
<div class="page" id="page-art9">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1512941937669-90a1b58e7e9c?w=1400&q=85" alt="Imágenes generadas con inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--purple-l);color:var(--purple)">Imágenes IA</span>
    </div>
    <h1>Cómo usar Midjourney en español: guía para principiantes</h1>
    <p class="lead">Aprende a usar Midjourney para generar imágenes impresionantes con inteligencia artificial. Guía completa en español con prompts, comandos y trucos.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">16 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">9 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Midjourney es la herramienta de generación de imágenes con IA más popular del mundo. Con los prompts correctos, puedes crear ilustraciones, fotos realistas, diseños y arte de altísima calidad sin saber dibujar.</p>
<h2>Cómo acceder a Midjourney</h2>
<p>Midjourney funciona a través de Discord. Necesitas: 1) Crear cuenta en Discord (discord.com), 2) Acceder al servidor de Midjourney (midjourney.com → "Join the Beta"), 3) Ir a cualquier canal #newbies y escribir el comando /imagine.</p>
<p>La versión gratuita te da unas 25 imágenes. Los planes de pago empiezan desde 10$/mes.</p>
<h2>Cómo escribir prompts para Midjourney</h2>
<p>A diferencia de ChatGPT, en Midjourney los prompts son descripciones visuales. Cuanto más detallado seas, mejores resultados obtendrás:</p>
<div class="prompt-box">/imagine [descripción del sujeto], [estilo artístico], [iluminación], [composición], [calidad] --ar 16:9 --v 6</div>
<p>Ejemplo real:</p>
<div class="prompt-box">/imagine professional woman working on laptop in modern office, natural light from window, editorial photography style, shallow depth of field, 4k --ar 16:9 --v 6</div>
<h2>Parámetros más útiles</h2>
<p><strong>--ar 16:9</strong> — proporción horizontal (para pantallas). <strong>--ar 1:1</strong> cuadrado. <strong>--ar 9:16</strong> vertical.</p>
<p><strong>--v 6</strong> — versión 6, la más reciente y realista.</p>
<p><strong>--q 2</strong> — máxima calidad (usa más créditos).</p>
<p><strong>--no texto</strong> — excluye elementos del resultado.</p>
<h2>Trucos para mejores resultados</h2>
<p>Añade estilos artísticos: "cinematic", "watercolor", "oil painting", "photorealistic". Especifica la iluminación: "golden hour", "studio lighting", "neon lights". Incluye la cámara si quieres algo fotográfico: "shot with 35mm lens", "wide angle".</p>
<h2>Alternativas gratuitas</h2>
<p>Si no quieres pagar, prueba: <strong>DALL-E 3</strong> (integrado en ChatGPT gratuito), <strong>Adobe Firefly</strong> (gratuito con cuenta Adobe), <strong>Stable Diffusion</strong> (gratis pero más complejo).</p>
<h2>Conclusión</h2>
<p>Midjourney tiene una curva de aprendizaje, pero una vez que dominas los prompts básicos, el nivel de las imágenes que puedes crear es increíble. Empieza con prompts simples e irás refinando con la práctica.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art10 ═══ -->
<div class="page" id="page-art10">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf?w=1400&q=85" alt="Freelancer trabajando con herramientas de inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--amber-l);color:var(--amber)">Freelancers</span>
    </div>
    <h1>Las mejores herramientas de IA para freelancers en 2025</h1>
    <p class="lead">Las herramientas de IA que todo freelancer debería conocer en 2025 para trabajar más rápido, conseguir más clientes y ganar más dinero.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">17 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">8 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Como freelancer, el tiempo es tu recurso más valioso. Las herramientas de IA pueden ayudarte a producir más en menos horas, lo que se traduce directamente en más ingresos o más tiempo libre.</p>
<h2>Para redactar y crear contenido</h2>
<p><strong>ChatGPT / Claude</strong> — Para borradores de artículos, copys, emails y cualquier texto. Ahorra horas de redacción.</p>
<p><strong>Grammarly</strong> — Corrección avanzada con IA para inglés. Imprescindible si trabajas con clientes internacionales.</p>
<h2>Para diseño y visual</h2>
<p><strong>Canva IA</strong> — Genera diseños, fondos y elementos visuales con IA. Gratis con cuenta básica.</p>
<p><strong>Midjourney / DALL-E</strong> — Para imágenes únicas para tus proyectos o clientes.</p>
<p><strong>Remove.bg</strong> — Elimina fondos de imágenes al instante con IA. Gratis para resolución básica.</p>
<h2>Para productividad y gestión</h2>
<p><strong>Notion AI</strong> — Organiza proyectos, notas y clientes con IA integrada.</p>
<p><strong>Otter.ai</strong> — Transcribe automáticamente tus llamadas con clientes. Nunca más tomar notas manualmente.</p>
<p><strong>Fireflies.ai</strong> — Similar a Otter, con integración directa en Zoom y Google Meet.</p>
<h2>Para código y desarrollo</h2>
<p><strong>GitHub Copilot</strong> — IA que completa código en tiempo real. Esencial para desarrolladores freelance.</p>
<p><strong>Cursor</strong> — Editor de código con IA que entiende todo tu proyecto.</p>
<h2>Para conseguir clientes</h2>
<p><strong>ChatGPT para propuestas</strong> — Genera propuestas personalizadas para cada cliente en minutos.</p>
<div class="prompt-box">Escribe una propuesta de proyecto para [cliente] que busca [servicio]. Mi experiencia en este área: [experiencia]. Presupuesto estimado: [precio]. Tono: profesional y orientado a resultados.</div>
<h2>Conclusión</h2>
<p>No necesitas usar todas estas herramientas. Empieza por las que resuelven tu mayor problema hoy: si tardas mucho en redactar, empieza por ChatGPT. Si el diseño es tu cuello de botella, empieza por Canva IA. Una herramienta bien usada ya cambia todo.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art11 ═══ -->
<div class="page" id="page-art11">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?w=1400&q=85" alt="Creación de contenido para redes sociales con IA"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--amber-l);color:var(--amber)">Marketing</span>
    </div>
    <h1>Cómo crear contenido para redes sociales con inteligencia artificial</h1>
    <p class="lead">Cómo usar la inteligencia artificial para crear contenido de calidad para Instagram, LinkedIn, TikTok y Twitter. Prompts listos para cada red social.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">17 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">7 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Crear contenido para redes sociales de forma consistente es agotador. La IA no solo acelera el proceso — también puede ayudarte a superar el bloqueo creativo y mantener una presencia constante sin quemarte.</p>
<h2>La estrategia correcta: IA como copiloto, no como piloto</h2>
<p>El error más común es pedirle a ChatGPT que publique directamente lo que genera. El contenido que funciona en redes tiene tu voz, tu historia, tu perspectiva. Usa la IA para generar ideas, estructuras y borradores — luego personalízalo.</p>
<h2>Para LinkedIn</h2>
<div class="prompt-box">Escribe un post de LinkedIn sobre [lección aprendida / logro / opinión sobre tendencia]. Estructura: primera línea impactante que haga parar el scroll, desarrollo en 3-4 párrafos cortos con salto de línea entre cada uno, conclusión con pregunta a la audiencia. Tono: cercano y profesional. Sin emojis excesivos.</div>
<h2>Para Instagram</h2>
<div class="prompt-box">Crea 5 ideas de carrusel de Instagram sobre [tema] para [tipo de cuenta]. Para cada idea incluye: título del carrusel, estructura de las 7 diapositivas y caption con hashtags relevantes. Tono: [educativo/inspiracional/entretenido].</div>
<h2>Para TikTok y Reels</h2>
<div class="prompt-box">Dame 10 ideas de vídeos cortos (60 segundos) sobre [nicho] que tengan potencial viral. Para cada idea: gancho de los primeros 3 segundos, estructura del vídeo y llamada a la acción final.</div>
<h2>Para Twitter/X</h2>
<div class="prompt-box">Escribe un hilo de Twitter sobre [tema]. El primer tweet debe ser un gancho impactante. Desarrolla el tema en 7-8 tweets concisos. El último tweet debe tener una llamada a la acción para seguirme o guardar el hilo.</div>
<h2>Planificar un mes de contenido en 1 hora</h2>
<div class="prompt-box">Crea un calendario de contenido para [red social] durante 30 días sobre [nicho]. Varía entre: posts educativos, de entretenimiento, personales y de venta. 1 post al día.</div>
<h2>Conclusión</h2>
<p>Con estas plantillas puedes planificar un mes de contenido en menos de una hora. La clave está en personalizar cada pieza con tu voz antes de publicarla — la IA te da el 80% del trabajo, tú pones el 20% que lo hace único.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art12 ═══ -->
<div class="page" id="page-art12">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1553729459-efe14ef6055d?w=1400&q=85" alt="Persona ganando dinero con inteligencia artificial online"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--teal-l);color:var(--teal)">Ingresos</span>
    </div>
    <h1>Cómo ganar dinero con inteligencia artificial en 2025: 10 formas reales</h1>
    <p class="lead">10 formas reales y probadas de ganar dinero usando inteligencia artificial en 2025. Desde freelancing hasta crear productos digitales, sin necesidad de ser programador.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">18 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">10 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>La IA ha abierto nuevas fuentes de ingresos que hace 2 años eran imposibles. Esta guía te muestra 10 formas concretas de monetizar la IA — algunas puedes empezarlas hoy mismo.</p>
<h2>1. Freelancing con servicios potenciados por IA</h2>
<p>Ofrece servicios de redacción de contenido, diseño gráfico, traducción o programación usando IA para entregar más rápido y con mejor calidad. En Fiverr y Upwork hay mucha demanda de personas que saben usar IA.</p>
<h2>2. Crear y vender prompts</h2>
<p>Existe un mercado creciente de prompts especializados en plataformas como PromptBase. Un buen prompt para un nicho específico puede venderse entre 2 y 10 dólares, y puedes venderlo miles de veces.</p>
<h2>3. Crear un blog de nicho con AdSense</h2>
<p>Como estás haciendo con AprendeIA: un blog sobre un tema específico, monetizado con Google AdSense y contenido generado y revisado con ayuda de IA. La barrera de entrada es muy baja.</p>
<h2>4. Crear cursos online</h2>
<p>Enseña a otros a usar las herramientas de IA que tú ya dominas. Plataformas como Udemy o Gumroad permiten vender cursos sin infraestructura propia. El tema "cómo usar ChatGPT para X" sigue teniendo enorme demanda.</p>
<h2>5. Agencia de contenido con IA</h2>
<p>Muchas empresas necesitan contenido — artículos, posts, newsletters — pero no tienen tiempo ni personal. Puedes montar una micro-agencia tú solo usando IA para producir a escala.</p>
<h2>6. Automatización de procesos para empresas</h2>
<p>Herramientas como Make o Zapier combinadas con ChatGPT permiten automatizar flujos de trabajo empresariales. Cada automatización que diseñas puede facturarse como proyecto o servicio recurrente.</p>
<h2>7. Canal de YouTube sobre IA</h2>
<p>El contenido sobre IA en español sigue siendo escaso en YouTube. Un canal con tutoriales prácticos puede monetizarse con AdSense, afiliados y sponsors en relativamente poco tiempo.</p>
<h2>8. Crear ebooks y guías digitales</h2>
<p>Escribe y vende guías sobre temas específicos usando IA para acelerar la producción. En Gumroad o Payhip puedes venderlos directamente sin intermediarios.</p>
<h2>9. Consultoría de IA para pymes</h2>
<p>La mayoría de las pequeñas empresas no sabe cómo implementar IA en sus procesos. Si tú sí lo sabes, puedes ofrecer sesiones de consultoría a 50-100€/hora.</p>
<h2>10. Crear herramientas y aplicaciones simples</h2>
<p>Con herramientas no-code como Bubble o Glide, puedes crear aplicaciones web sencillas que usen la API de ChatGPT y cobrar suscripción mensual.</p>
<h2>Conclusión</h2>
<p>No necesitas ser programador ni tener capital. Necesitas aprender bien las herramientas, elegir un modelo de negocio y empezar. El mejor momento para empezar era ayer. El segundo mejor momento es hoy.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art13 ═══ -->
<div class="page" id="page-art13">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1434030216411-0b793f4b4173?w=1400&q=85" alt="Persona aprendiendo un idioma con inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--purple-l);color:var(--purple)">Educación</span>
    </div>
    <h1>Cómo usar ChatGPT para aprender un idioma más rápido</h1>
    <p class="lead">ChatGPT es el profesor de idiomas más paciente y disponible del mundo. Aprende cómo usarlo para practicar conversación, corregir errores y acelerar tu aprendizaje.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">18 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">7 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Aprender un idioma con ChatGPT no reemplaza a un profesor humano, pero lo complementa de una forma que ninguna app de idiomas puede igualar: responde en tiempo real, adapta el nivel exactamente a ti y nunca se cansa de explicar lo mismo.</p>
<h2>Practicar conversación</h2>
<div class="prompt-box">Quiero practicar inglés conversacional. Actúa como un nativo amigable. Habla conmigo sobre [tema cotidiano]. Usa vocabulario nivel [B1/B2/C1]. Cuando cometa errores gramaticales, corrígeme al final de cada respuesta con una explicación breve.</div>
<h2>Aprender vocabulario en contexto</h2>
<div class="prompt-box">Dame 10 palabras en inglés del campo semántico de [tema: negocios/tecnología/cocina]. Para cada palabra: definición, ejemplo de uso en una frase natural y una frase de ejemplo en contexto real.</div>
<h2>Corregir tus textos</h2>
<div class="prompt-box">Corrige este texto en inglés. Para cada error: señala el error, da la corrección y explica la regla gramatical que aplica. Al final, dame una versión corregida completa: [tu texto].</div>
<h2>Preparar vocabulario para situaciones específicas</h2>
<div class="prompt-box">Voy a tener una entrevista de trabajo en inglés para un puesto de [puesto]. Dame las 20 expresiones y frases más útiles para esta situación, con pronunciación aproximada en español y ejemplo de uso.</div>
<h2>Simulación de situaciones reales</h2>
<div class="prompt-box">Simula una conversación en inglés en [situación: restaurante/aeropuerto/reunión de negocios]. Tú eres [personaje] y yo soy el cliente/pasajero/colega. Empieza tú y responde de forma natural.</div>
<h2>Trucos para aprender más rápido</h2>
<p>Practica 15 minutos diarios en lugar de 2 horas una vez a la semana. Pídele que use un vocabulario ligeramente por encima de tu nivel actual para ir estirando tu capacidad. Cuando no entendas algo, pídele que lo explique de otra manera.</p>
<h2>Conclusión</h2>
<p>ChatGPT es especialmente útil para las dos cosas que más cuesta practicar fuera del aula: la conversación sin vergüenza y la corrección inmediata de errores. Combínalo con escuchar podcasts y ver series en el idioma y tu progreso se acelerará notablemente.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art14 ═══ -->
<div class="page" id="page-art14">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?w=1400&q=85" alt="Errores comunes al usar inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--blue-l);color:var(--blue)">ChatGPT</span>
    </div>
    <h1>10 errores comunes al usar ChatGPT (y cómo evitarlos)</h1>
    <p class="lead">Los 10 errores más frecuentes que cometen los principiantes al usar ChatGPT — y los prompts correctos para obtener resultados mucho mejores.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">19 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">6 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Después de usar ChatGPT, muchos usuarios se frustran porque los resultados no son lo que esperaban. En la mayoría de los casos, el problema no es la herramienta — es cómo se usa. Estos son los 10 errores más comunes y cómo corregirlos.</p>
<h2>Error 1: Prompts demasiado vagos</h2>
<p><strong>Mal:</strong> "Escribe algo sobre marketing digital"</p>
<p><strong>Bien:</strong> "Escribe un artículo de 800 palabras sobre las 5 tendencias de marketing digital más importantes para pymes en 2025. Tono divulgativo, con ejemplos prácticos."</p>
<h2>Error 2: No dar contexto</h2>
<p>ChatGPT no sabe quién eres ni para qué necesitas el resultado. Díselo siempre: "Soy diseñadora freelance especializada en branding para startups. Necesito..."</p>
<h2>Error 3: Aceptar la primera respuesta</h2>
<p>La primera respuesta raramente es la mejor. Di: "Hazlo más corto", "Usa un tono más informal", "Añade ejemplos concretos". ChatGPT mejora con las iteraciones.</p>
<h2>Error 4: No indicar el formato</h2>
<p>Si quieres una lista, pide una lista. Si quieres una tabla, pide una tabla. Si quieres párrafos cortos, dilo. Sin instrucciones de formato, ChatGPT elige por defecto.</p>
<h2>Error 5: Confiar ciegamente en la información</h2>
<p>ChatGPT puede inventar datos, citas o hechos con total convicción. Siempre verifica la información importante, especialmente fechas, estadísticas y nombres propios.</p>
<h2>Error 6: No aprovechar los roles</h2>
<p>Decirle "Actúa como experto en X" mejora significativamente la calidad de las respuestas. "Actúa como abogado especialista en contratos freelance" da resultados muy diferentes a simplemente preguntar sobre contratos.</p>
<h2>Error 7: Conversaciones demasiado largas sin reiniciar</h2>
<p>En conversaciones muy largas, ChatGPT "olvida" el contexto inicial. Si cambias de tema o necesitas un enfoque fresco, empieza una nueva conversación.</p>
<h2>Error 8: Pedir demasiado en un solo prompt</h2>
<p>Divide las tareas complejas en pasos. Primero pide el esquema, luego desarrolla cada sección por separado. Los resultados serán mucho mejores.</p>
<h2>Error 9: No personalizar el resultado</h2>
<p>El texto que genera ChatGPT tiene un estilo reconocible. Siempre edítalo con tu voz, tus ejemplos y tu perspectiva antes de publicarlo o enviarlo.</p>
<h2>Error 10: Rendirse después del primer rechazo</h2>
<p>Si ChatGPT rechaza una petición, reformúlala. En muchos casos, un pequeño cambio en la forma de preguntar obtiene el resultado que buscabas.</p>
<h2>Conclusión</h2>
<p>ChatGPT es una herramienta de diálogo. Cuanto mejor seas comunicando lo que necesitas, mejores serán los resultados. Trátatelo como a un colaborador muy capaz al que le tienes que dar instrucciones claras.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══ ARTÍCULO: art15 ═══ -->
<div class="page" id="page-art15">
  <div style="max-width:740px;margin:0 auto;padding:28px 48px 0">
    <button class="back-btn" onclick="showPage('guias')">← Volver a guías</button>
  </div>
  <div class="article-hero">
    <div class="article-hero-img"><img src="https://images.unsplash.com/photo-1515187029135-18ee286d815b?w=1400&q=85" alt="Presentación creada con inteligencia artificial"></div>
    <div class="article-tag-row">
      <span class="article-tag-pill" style="background:var(--teal-l);color:var(--teal)">Productividad</span>
    </div>
    <h1>Cómo hacer una presentación de PowerPoint con inteligencia artificial</h1>
    <p class="lead">Aprende a crear presentaciones profesionales en minutos usando inteligencia artificial. De la idea al PowerPoint listo para presentar con ChatGPT y herramientas IA.</p>
    <div class="article-meta-bar">
      <div class="article-author">
        <div class="author-ava"><img src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?w=80&q=80" alt="Autor"></div>
        <span class="author-name">Equipo AprendeIA</span>
      </div>
      <span class="article-date">19 mayo 2025</span>
      <span class="card-meta-dot"></span>
      <span class="article-read">7 min de lectura</span>
    </div>
  </div>
  <div class="article-body">
    
<p>Crear una presentación que quede bien lleva horas. Con las herramientas de IA adecuadas, puedes reducir ese tiempo a minutos — y el resultado puede ser incluso mejor.</p>
<h2>El flujo de trabajo completo</h2>
<p>El proceso con IA tiene 3 pasos: 1) ChatGPT para el contenido y estructura, 2) una herramienta IA para el diseño, 3) tú para revisar y personalizar.</p>
<h2>Paso 1: Generar el esquema con ChatGPT</h2>
<div class="prompt-box">Crea el esquema de una presentación de [X] diapositivas sobre [tema] para [audiencia: directivos/clientes/equipo]. Objetivo de la presentación: [convencer/informar/formar]. Para cada diapositiva incluye: título, puntos clave (máximo 3) y sugerencia visual.</div>
<h2>Paso 2: Desarrollar el contenido de cada diapositiva</h2>
<div class="prompt-box">Para la diapositiva "[título]" de mi presentación, desarrolla el contenido. Texto para el speaker: 3-4 frases que el presentador dirá en voz alta. Texto en pantalla: máximo 20 palabras. Sugerencia de imagen o gráfico.</div>
<h2>Herramientas IA para diseñar la presentación</h2>
<p><strong>Gamma.app</strong> — La mejor opción. Pega el texto y genera una presentación visualmente atractiva automáticamente. Gratuito para empezar.</p>
<p><strong>Canva IA</strong> — Genera diapositivas con IA desde texto. Enorme variedad de plantillas.</p>
<p><strong>Beautiful.ai</strong> — Diseño automático inteligente que ajusta los layouts solos.</p>
<p><strong>Tome.app</strong> — Especialmente bueno para presentaciones narrativas.</p>
<h2>Crear la presentación en Gamma</h2>
<p>Ve a gamma.app → "New AI" → pega el esquema que generaste con ChatGPT → elige el estilo visual → genera. En menos de 2 minutos tendrás una presentación completa que puedes editar diapositiva por diapositiva.</p>
<h2>Trucos para presentaciones que impresionan</h2>
<p>Usa datos concretos: ChatGPT puede ayudarte a buscar estadísticas relevantes. Cada diapositiva debe tener una sola idea principal. Las imágenes reales funcionan mejor que los iconos para audiencias ejecutivas.</p>
<h2>Conclusión</h2>
<p>Lo que antes llevaba medio día ahora puede hacerse en una hora. El tiempo que ahorras en el diseño y la estructura puedes invertirlo en lo que realmente importa: preparar cómo vas a contarlo.</p>

  </div>
  <footer><div class="footer-inner"><span class="footer-brand">Aprende<span>IA</span>.net</span><ul class="footer-links"><li><a href="#" onclick="showPage('home')">Inicio</a></li><li><a href="#" onclick="showPage('guias')">Guías</a></li><li><a href="#" onclick="showPage('privacidad')">Privacidad</a></li></ul><span class="footer-copy">© 2025 AprendeIA.net</span></div></footer>
</div>

<!-- ═══════════════════════════════ COOKIE BANNER ═══════════════════════════════ -->
<div id="cookie-banner" style="position:fixed;bottom:0;left:0;right:0;z-index:9999;background:var(--ink);padding:16px 32px;display:flex;align-items:center;justify-content:space-between;gap:20px;flex-wrap:wrap;border-top:3px solid var(--blue)">
  <div style="display:flex;align-items:center;gap:14px;flex:1;min-width:260px">
    <span style="font-size:22px">🍪</span>
    <p style="font-size:13px;color:rgba(255,255,255,.8);line-height:1.5;margin:0">Usamos cookies propias y de terceros (Google Analytics y AdSense) para analizar el tráfico y mostrar publicidad relevante. <span style="color:rgba(255,255,255,.5);cursor:pointer;text-decoration:underline" onclick="showPage('aviso')">Más información</span></p>
  </div>
  <div style="display:flex;gap:8px;flex-shrink:0">
    <button onclick="rejectCookies()" style="background:none;border:1px solid rgba(255,255,255,.3);color:rgba(255,255,255,.7);padding:9px 18px;border-radius:var(--r-sm);font-size:13px;cursor:pointer;font-family:inherit;transition:all .15s" onmouseover="this.style.borderColor='rgba(255,255,255,.6)'" onmouseout="this.style.borderColor='rgba(255,255,255,.3)'">Solo necesarias</button>
    <button onclick="acceptCookies()" style="background:var(--blue);color:white;border:none;padding:9px 20px;border-radius:var(--r-sm);font-size:13px;font-weight:500;cursor:pointer;font-family:inherit;transition:background .15s" onmouseover="this.style.background='#1d4ed8'" onmouseout="this.style.background='#2563eb'">Aceptar todas</button>
  </div>
</div>

<script>
function showPage(id) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.getElementById('page-' + id).classList.add('active');
  document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
  const btn = document.getElementById('btn-' + id);
  if (btn) btn.classList.add('active');
  window.scrollTo({ top: 0, behavior: 'smooth' });
}

function copyPrompt(btn) {
  const text = btn.previousElementSibling.textContent;
  navigator.clipboard.writeText(text).then(() => {
    btn.textContent = '¡Copiado!';
    btn.classList.add('copied');
    setTimeout(() => { btn.textContent = 'Copiar prompt'; btn.classList.remove('copied'); }, 2000);
  });
}

function subscribeNL(inputId) {
  const input = document.getElementById(inputId);
  const email = input.value.trim();
  if (!email || !email.includes('@')) {
    input.style.borderColor = '#ef4444';
    setTimeout(() => input.style.borderColor = '', 1500);
    return;
  }
  input.value = '';
  input.placeholder = '✓ ¡Suscrito! Revisa tu correo';
  input.style.borderColor = '#10b981';
}

function sendContact() {
  const name = document.getElementById('contact-name').value.trim();
  const email = document.getElementById('contact-email').value.trim();
  const msg = document.getElementById('contact-msg').value.trim();
  if (!name || !email || !msg) return;
  document.getElementById('contact-ok').style.display = 'block';
  document.getElementById('contact-name').value = '';
  document.getElementById('contact-email').value = '';
  document.getElementById('contact-msg').value = '';
}

function acceptCookies() {
  localStorage.setItem('cookies', 'accepted');
  document.getElementById('cookie-banner').style.display = 'none';
}

function rejectCookies() {
  localStorage.setItem('cookies', 'rejected');
  document.getElementById('cookie-banner').style.display = 'none';
}

if (localStorage.getItem('cookies')) {
  document.getElementById('cookie-banner').style.display = 'none';
}
</script>
</body>
</html>
