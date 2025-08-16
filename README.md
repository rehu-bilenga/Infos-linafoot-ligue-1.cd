<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Infos Linafoot Ligue 1 — 100% sport en RDC et Afrique : matchs du jour, Linafoot, CHAN, classements et actus." />
  <title>Infos Linafoot Ligue 1 — 100% Sport</title>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      /* Palette Bleu & Blanc (avec option Rouge via le bouton) */
      --bg:#f6f9ff;
      --surface:#ffffff;
      --text:#0b1220;
      --muted:#56607a;
      --primary:#2563eb;  /* bleu */
      --primary-2:#3b82f6;
      --primary-3:#1e3a8a;
      --accent:#f59e0b;   /* clin d'oeil à l'étoile du drapeau */
      --ring:rgba(37,99,235,.25);
      --shadow:0 10px 30px rgba(2,6,23,.08);
      --radius:18px;
    }
    .red{ /* Variante Rouge & Blanc */
      --bg:#f9fafb; --surface:#ffffff; --text:#101418; --muted:#6b7280;
      --primary:#dc2626; --primary-2:#ef4444; --primary-3:#7f1d1d;
      --accent:#f59e0b; --ring:rgba(220,38,38,.25);
    }*{box-sizing:border-box}
html,body{height:100%}
body{margin:0; font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial; background:var(--bg); color:var(--text)}
a{color:inherit; text-decoration:none}
img{max-width:100%; display:block}
.container{width:min(1200px,92%); margin-inline:auto}

/* Header */
header{position:sticky; top:0; z-index:40; background:rgba(255,255,255,.8); backdrop-filter:saturate(180%) blur(10px); border-bottom:1px solid #e5e7eb}
.nav{display:flex; align-items:center; justify-content:space-between; gap:1rem; padding:.9rem 0}
.brand{display:flex; align-items:center; gap:.7rem}
.logo{width:42px; height:42px}
.brand-name{font-weight:800; letter-spacing:.2px}
.brand-name em{font-style:normal; color:var(--primary)}
.nav-actions{display:flex; gap:.5rem; align-items:center}
.btn{border:1px solid #e5e7eb; background:var(--surface); padding:.6rem .85rem; border-radius:12px; cursor:pointer; transition:.2s; box-shadow:var(--shadow)}
.btn:hover{transform:translateY(-1px)}
.btn-primary{border:none; background:linear-gradient(135deg, var(--primary), var(--primary-2)); color:#fff; font-weight:700}
input[type="search"]{width:100%; padding:.7rem .9rem; border-radius:12px; border:1px solid #e5e7eb; background:var(--surface)}

/* Hero */
.hero{padding:1.2rem 0 1.4rem}
.hero-grid{display:grid; grid-template-columns:1.35fr .9fr; gap:1.2rem}
.hero-card{border-radius:var(--radius); background:radial-gradient(900px 260px at 0% 0%, color-mix(in oklab, var(--primary-2) 18%, transparent), transparent 60%), var(--surface); box-shadow:var(--shadow); padding:1.2rem}
.tag{display:inline-flex; align-items:center; gap:.35rem; padding:.25rem .55rem; border-radius:999px; background:color-mix(in oklab, var(--primary) 12%, transparent); color:var(--primary-3); font-weight:700}
.meta{color:var(--muted)}

/* Sections */
section{margin:1.2rem 0}
.section-title{display:flex; align-items:center; justify-content:space-between; margin:.2rem 0 .8rem}
.section-title h2{margin:0; font-size:1.2rem}
.chips{display:flex; gap:.4rem; flex-wrap:wrap}
.chip{padding:.25rem .55rem; border-radius:999px; background:#eef2ff; color:var(--primary-3); font-size:.8rem}

/* Grids */
.news-grid{display:grid; grid-template-columns:repeat(3,1fr); gap:1rem}
.card{background:var(--surface); border:1px solid #e5e7eb; border-radius:16px; overflow:hidden; box-shadow:var(--shadow); display:flex; flex-direction:column}
.card .p{padding:1rem}
.card h3{margin:.2rem 0 .4rem; font-size:1rem}

/* Scores */
.scores{display:grid; grid-template-columns:repeat(2,1fr); gap:.9rem}
.score-card{background:var(--surface); border:1px solid #e5e7eb; border-radius:16px; padding:.9rem; box-shadow:var(--shadow); display:flex; flex-direction:column; gap:.6rem}
.status{font-size:.86rem; color:var(--muted)}
.teams{display:grid; grid-template-columns:1fr auto 1fr; align-items:center; gap:.4rem}
.team{display:flex; align-items:center; gap:.45rem; font-weight:600}
.badge{width:22px; height:22px; border-radius:7px; background:linear-gradient(135deg, var(--primary), var(--primary-2)); color:#fff; display:grid; place-items:center; font-size:.78rem}
.score{font-size:1.15rem; font-weight:800}

/* Tables */
table{width:100%; border-collapse:collapse; background:var(--surface); border:1px solid #e5e7eb; border-radius:16px; overflow:hidden; box-shadow:var(--shadow)}
thead th{font-size:.9rem; text-align:left; background:#f3f4f6; padding:.7rem .8rem}
tbody td{padding:.6rem .8rem; border-top:1px solid #e5e7eb}

/* Footer */
footer{margin-top:2rem; padding:1.2rem 0; border-top:1px solid #e5e7eb; color:var(--muted)}

/* Responsive */
@media (max-width:1000px){
  .hero-grid{grid-template-columns:1fr}
  .news-grid{grid-template-columns:repeat(2,1fr)}
}
@media (max-width:640px){
  .news-grid{grid-template-columns:1fr}
  .nav{flex-wrap:wrap}
  .scores{grid-template-columns:1fr}
}

  </style>
</head>
<body>
  <header>
    <div class="container nav" role="navigation" aria-label="Navigation principale">
      <a class="brand" href="#" aria-label="Infos Linafoot Ligue 1 — Accueil">
        <!-- Logo : ballon + étoile RDC stylisés en SVG -->
        <svg class="logo" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <defs>
            <linearGradient id="lg" x1="0" x2="1" y1="0" y2="1">
              <stop offset="0%" stop-color="#2563eb"/>
              <stop offset="100%" stop-color="#3b82f6"/>
            </linearGradient>
            <filter id="ds" x="-20%" y="-20%" width="140%" height="140%">
              <feDropShadow dx="0" dy="6" stdDeviation="4" flood-color="#000" flood-opacity=".12"/>
            </filter>
          </defs>
          <rect x="4" y="4" width="56" height="56" rx="16" fill="url(#lg)" filter="url(#ds)"/>
          <!-- ballon minimal -->
          <circle cx="32" cy="32" r="12" fill="#fff"/>
          <path d="M32 20l5 4-2 6h-6l-2-6z" fill="#111827"/>
          <!-- étoile or (RDC) -->
          <g transform="translate(46,14) scale(.75)">
            <path fill="#f59e0b" d="M6 0l1.76 5.42H14l-4.64 3.37L11.12 14 6 10.7 0.88 14l1.76-5.21L-2 5.42h6.24z"/>
          </g>
          <title>Infos Linafoot Ligue 1 — logo</title>
        </svg>
        <span class="brand-name">Infos <em>Linafoot Ligue 1</em></span>
      </a>
      <form class="search" role="search" aria-label="Recherche" onsubmit="event.preventDefault()">
        <input id="search" type="search" placeholder="Rechercher un club, joueur, pays…" />
      </form>
      <div class="nav-actions">
        <button class="btn" id="switchPalette" title="Basculer Bleu/Rouge">Bleu/Rouge</button>
        <button class="btn btn-primary" id="subscribeBtn">S'abonner</button>
      </div>
    </div>
  </header>  <main>
    <!-- HERO + MATCHS DU JOUR (CHAN) -->
    <section class="hero container">
      <div class="hero-grid">
        <article class="hero-card" aria-labelledby="headline-title">
          <div class="tag">À la une — Aujourd'hui</div>
          <h1 id="headline-title" style="margin:.35rem 0 .6rem">Matchs du jour en Afrique & CHAN</h1>
          <p class="meta">16 août 2025 • Heures converties automatiquement pour Kinshasa</p>
          <div style="display:flex; gap:.6rem; margin-top:.6rem">
            <button class="btn btn-primary" onclick="scrollToSection('chanToday')">Voir les matchs CHAN</button>
            <button class="btn" onclick="scrollToSection('linafoot')">Infos Linafoot</button>
          </div>
        </article>
        <aside class="hero-card">
          <div class="section-title"><h2 style="margin:0">Matchs CHAN — Aujourd'hui</h2><span class="chip" id="todayCount">0 match</span></div>
          <div class="scores" id="chanToday"></div>
        </aside>
      </div>
    </section><!-- ACTUS LINAFOOT -->
<section class="container" id="linafoot" aria-labelledby="linafoot-title">
  <div class="section-title">
    <h2 id="linafoot-title">Infos — Linafoot Ligue 1 (RDC)</h2>
    <div class="chips">
      <span class="chip">RDC</span>
      <span class="chip">TP Mazembe</span>
      <span class="chip">AS Vita Club</span>
      <span class="chip">Saint-Éloi Lupopo</span>
    </div>
  </div>
  <div class="news-grid" id="newsGrid"></div>
</section>

<!-- CLASSEMENTS CHAN (par groupes) -->
<section class="container" aria-labelledby="classement-title">
  <div class="section-title"><h2 id="classement-title">Classements — CHAN (groupes)</h2></div>
  <div class="news-grid">
    <div class="card"><div class="p"><h3>Groupe A</h3><table><thead><tr><th>#</th><th>Équipe</th><th>Pts</th><th>J</th><th>G</th><th>N</th><th>P</th><th>BM</th><th>BE</th></tr></thead><tbody id="grpA"></tbody></table></div></div>
    <div class="card"><div class="p"><h3>Groupe B</h3><table><thead><tr><th>#</th><th>Équipe</th><th>Pts</th><th>J</th><th>G</th><th>N</th><th>P</th><th>BM</th><th>BE</th></tr></thead><tbody id="grpB"></tbody></table></div></div>
    <div class="card"><div class="p"><h3>Groupe C</h3><table><thead><tr><th>#</th><th>Équipe</th><th>Pts</th><th>J</th><th>G</th><th>N</th><th>P</th><th>BM</th><th>BE</th></tr></thead><tbody id="grpC"></tbody></table></div></div>
    <div class="card"><div class="p"><h3>Groupe D</h3><table><thead><tr><th>#</th><th>Équipe</th><th>Pts</th><th>J</th><th>G</th><th>N</th><th>P</th><th>BM</th><th>BE</th></tr></thead><tbody id="grpD"></tbody></table></div></div>
  </div>
  <p class="meta" style="margin-top:.6rem">Note : données démo faciles à mettre à jour dans le tableau JS ci-dessous.</p>
</section>

  </main>  <footer>
    <div class="container">
      <div style="display:flex; justify-content:space-between; align-items:flex-start; gap:1rem; flex-wrap:wrap">
        <div style="display:flex; align-items:center; gap:.6rem">
          <svg width="28" height="28" viewBox="0 0 64 64" aria-hidden="true">
            <use href="#logo"/>
          </svg>
          <strong>Infos Linafoot Ligue 1</strong>
        </div>
        <form id="newsletter" style="display:flex; gap:.5rem; flex-wrap:wrap" onsubmit="subscribe(event)">
          <input required name="email" type="email" placeholder="Email — alertes buts & actus" />
          <button class="btn btn-primary" type="submit">S'abonner</button>
        </form>
      </div>
      <p style="margin:.6rem 0 0; font-size:.92rem">© <span id="year"></span> Infos Linafoot Ligue 1. Démo front‑end (HTML/CSS/JS).</p>
    </div>
  </footer>  <script>
    // ====== Palette switch Bleu/Rouge ======
    const root = document.documentElement;
    const switchBtn = document.getElementById('switchPalette');
    let palette = localStorage.getItem('palette2') || 'blue';
    function applyPalette(){
      if(palette==='red'){ root.classList.add('red'); } else { root.classList.remove('red'); }
    }
    switchBtn.addEventListener('click', ()=>{ palette = palette==='red'?'blue':'red'; localStorage.setItem('palette2', palette); applyPalette(); });
    applyPalette();

    // ====== Helpers ======
    function scrollToSection(id){ document.getElementById(id)?.scrollIntoView({behavior:'smooth'}); }
    function localTimeFromUTC(hours, minutes){
      // Construit une date UTC puis l'affiche pour Kinshasa
      const d = new Date(Date.UTC(2025, 7, 16, hours, minutes, 0)); // 16 août 2025 (mois indexé à 0 => 7 pour août)
      const opts = {hour:'2-digit', minute:'2-digit', timeZone:'Africa/Kinshasa'};
      return new Intl.DateTimeFormat('fr-FR', opts).format(d);
    }

    // ====== Données (démo MAJ 16/08/2025) ======
    // Matchs du jour CHAN (confirmés dans la presse/CAF)
    const chanToday = [
      {home:'Centrafrique', away:'Tanzanie', comp:'CHAN — Groupe A', kick_utc:'17:00'},
      {home:'Burkina Faso', away:'Madagascar', comp:'CHAN — Groupe B', kick_utc:'17:00'}
    ];

    // Actus Linafoot (cartes démo)
    const news = [
      {title:"Play-offs : calendrier et enjeux", img:"https://images.unsplash.com/photo-1517927033932-b3d18e61fb3a?q=80&w=1200&auto=format&fit=crop", tag:"RDC", time:"Aujourd'hui"},
      {title:"TP Mazembe : focus sur la forme", img:"https://images.unsplash.com/photo-1521417531039-95f66f8a45c3?q=80&w=1200&auto=format&fit=crop", tag:"Mazembe", time:"Cette semaine"},
      {title:"V.Club : jeunes talents à suivre", img:"https://images.unsplash.com/photo-1521412644187-c49fa049e84d?q=80&w=1200&auto=format&fit=crop", tag:"V.Club", time:"Hier"}
    ];

    // Classements CHAN (saisir/mettre à jour facilement)
    const standings = {
      A: [
        // Exemple : {team:'Kenya', pts:7, j:3, g:2, n:1, p:0, bm:5, be:2}
      ],
      B: [
      ],
      C: [
      ],
      D: [
      ]
    };

    // ====== Rendus ======
    function renderChanToday(){
      const cont = document.getElementById('chanToday');
      cont.innerHTML = '';
      chanToday.forEach(m=>{
        const [hh, mm] = m.kick_utc.split(':').map(Number);
        const local = localTimeFromUTC(hh, mm);
        const card = document.createElement('div');
        card.className = 'score-card';
        card.innerHTML = `
          <div class="status">${m.comp} • Coup d'envoi (UTC) ${m.kick_utc} • <strong>${local} (Kinshasa)</strong></div>
          <div class="teams">
            <div class="team"><span class="badge">H</span> ${m.home}</div>
            <div class="score">vs</div>
            <div class="team" style="justify-content:flex-end">${m.away} <span class="badge">A</span></div>
          </div>`;
        cont.appendChild(card);
      });
      document.getElementById('todayCount').textContent = `${chanToday.length} matchs`;
    }

    function renderNews(filter=''){
      const grid = document.getElementById('newsGrid');
      grid.innerHTML = '';
      news.filter(n => n.title.toLowerCase().includes(filter.toLowerCase()) || n.tag.toLowerCase().includes(filter.toLowerCase()))
          .forEach(n=>{
            const card = document.createElement('article');
            card.className = 'card';
            card.innerHTML = `
              <img alt="${n.tag}" src="${n.img}" loading="lazy"/>
              <div class="p">
                <span class="chip">${n.tag}</span>
                <h3>${n.title}</h3>
                <p class="meta" style="color:var(--muted)">${n.time}</p>
              </div>`;
            grid.appendChild(card);
          });
    }

    function renderStandings(){
      const map = {A:'grpA', B:'grpB', C:'grpC', D:'grpD'};
      Object.entries(map).forEach(([g, id])=>{
        const tb = document.getElementById(id);
        tb.innerHTML = '';
        const rows = standings[g];
        if(!rows || rows.length===0){
          const tr = document.createElement('tr');
          const td = document.createElement('td');
          td.colSpan = 9; td.innerHTML = '<em class="meta">À compléter — saisir les scores du dernier tour pour voir le classement.</em>';
          tr.appendChild(td); tb.appendChild(tr); return;
        }
        rows.sort((a,b)=> b.pts - a.pts || (b.bm-b.be) - (a.bm-a.be));
        rows.forEach((t,i)=>{
          const tr = document.createElement('tr');
          tr.innerHTML = `<td>${i+1}</td><td>${t.team}</td><td><strong>${t.pts}</strong></td><td>${t.j}</td><td>${t.g}</td><td>${t.n}</td><td>${t.p}</td><td>${t.bm}</td><td>${t.be}</td>`;
          tb.appendChild(tr);
        });
      });
    }

    // Recherche
    document.getElementById('search').addEventListener('input', e=>renderNews(e.target.value));

    // Newsletter (démo)
    function subscribe(e){
      e.preventDefault();
      const email = new FormData(e.target).get('email');
      alert(`Merci ! Alerte activée pour ${email}.`);
      e.target.reset();
    }

    // CTA header
    document.getElementById('subscribeBtn').addEventListener('click', ()=>{
      document.getElementById('newsletter').scrollIntoView({behavior:'smooth'});
    });

    // Init
    document.getElementById('year').textContent = new Date().getFullYear();
    renderChanToday();
    renderNews();
    renderStandings();
  </script></body>
</html>
