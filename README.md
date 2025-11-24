<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ronaldo Refrigeração — Instalação e Manutenção de Ar-Condicionado</title>

  <!-- SEO metas -->
  <meta name="description" content="Ronaldo Refrigeração — Instalação, manutenção, higienização e reparos de ar-condicionado com técnicos certificados. Orçamento rápido via WhatsApp." />
  <meta name="keywords" content="ar-condicionado, instalação, manutenção, higienização, recarga de gás, Ronaldo Refrigeração" />
  <link rel="canonical" href="https://www.seusite.com.br/" />

  <!-- Open Graph -->
  <meta property="og:type" content="business.business" />
  <meta property="og:title" content="Ronaldo Refrigeração — Instalação e Manutenção" />
  <meta property="og:description" content="Instalação, manutenção, higienização e recarga de gás. Atendimento profissional e rápido." />
  <meta property="og:image" content="https://images.unsplash.com/photo-1582719478250-6f627d5f3f13?q=80&w=1200&auto=format&fit=crop&s=placeholder" />
  <meta property="og:url" content="https://www.seusite.com.br/" />
  <meta property="og:site_name" content="Ronaldo Refrigeração" />

  <!-- Twitter card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Ronaldo Refrigeração — Instalação e Manutenção" />
  <meta name="twitter:description" content="Orçamento rápido via WhatsApp. Serviços profissionais de climatização." />
  <meta name="twitter:image" content="https://images.unsplash.com/photo-1582719478250-6f627d5f3f13?q=80&w=1200&auto=format&fit=crop&s=placeholder" />

  <!-- LocalBusiness JSON-LD (preencha 'sameAs' e address conforme necessário) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "name": "Ronaldo Refrigeração",
    "image": "https://images.unsplash.com/photo-1582719478250-6f627d5f3f13?q=80&w=1200&auto=format&fit=crop&s=placeholder",
    "telephone": "+556192983613",
    "email": "contato@ronaldorefrigeracao.com.br",
    "address": {
      "@type": "PostalAddress",
      "streetAddress": "Av. Exemplo, 1234",
      "addressLocality": "Brasília",
      "addressRegion": "DF",
      "postalCode": "70000-000",
      "addressCountry": "BR"
    },
    "url": "https://www.seusite.com.br/",
    "sameAs": ["https://www.instagram.com/ronaldo_souuzaa"]
  }
  </script>

  <!-- Tailwind CDN for rapid prototyping -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Feather icons -->
  <script src="https://unpkg.com/feather-icons"></script>

  <style>
    :root{
      --accent: #3B82F6;           /* azul tecnológico */
      --accent-boost: #3dd5f3;
      --bg: #f8fafc;              /* branco gelo */
      --surface: #ffffff;
      --text: #1e293b;            /* chumbo */
      --muted: rgba(30,41,59,0.65);
      --card-radius: 14px;
    }
    /* Dark theme vars (applied when .dark on <html>) */
    :root.dark {
      --bg: #0f172a;              /* very dark */
      --surface: #0b1220;
      --text: #e6eef8;
      --muted: rgba(230,238,248,0.72);
    }

    html,body{
      height:100%;
      margin:0;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: var(--bg);
      color: var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    /* header */
    header.site-header{
      background: linear-gradient(180deg, rgba(255,255,255,0.6), rgba(255,255,255,0.3));
      backdrop-filter: blur(6px);
    }
    :root.dark header.site-header{
      background: linear-gradient(180deg, rgba(8,10,18,0.55), rgba(8,10,18,0.35));
    }

    /* logo snowflake box */
    .logo-box{
      width:40px;height:40px;border-radius:10px;
      display:inline-flex;align-items:center;justify-content:center;
      background:linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.01));
      border: 1px solid rgba(255,255,255,0.04);
    }
    :root.dark .logo-box{
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border: 1px solid rgba(255,255,255,0.04);
    }

    /* hero */
    .hero {
      min-height: 420px;
      display:flex;
      align-items:center;
      position:relative;
      overflow:hidden;
      border-bottom:1px solid rgba(0,0,0,0.04);
    }
    .hero .hero-bg {
      position:absolute; inset:0; background-size:cover; background-position:center;
      z-index:0;
      filter: saturate(.95) contrast(.95);
    }
    .hero .overlay {
      position:absolute; inset:0; background: linear-gradient(90deg, rgba(2,6,23,0.6), rgba(2,6,23,0.18));
      z-index:1;
    }
    :root.dark .hero .overlay {
      background: linear-gradient(90deg, rgba(2,6,23,0.78), rgba(2,6,23,0.28));
    }
    .hero .content{ position:relative; z-index:2; }

    /* service card / accordion */
    .service-card {
      border-radius: var(--card-radius);
      background: var(--surface);
      padding:1.15rem;
      box-shadow: 0 8px 24px rgba(16,24,40,0.06);
      border:1px solid rgba(15,23,42,0.04);
      transition: transform .25s ease, box-shadow .25s ease;
      overflow:hidden;
    }
    .service-card:hover{ transform: translateY(-8px); box-shadow:0 20px 46px rgba(16,24,40,0.08); }

    .icon-circle{ width:56px;height:56px;border-radius:12px;display:flex;align-items:center;justify-content:center;
      background: linear-gradient(180deg, rgba(59,130,246,0.12), rgba(59,130,246,0.06));
      border:1px solid rgba(59,130,246,0.06);
    }

    .accordion-content{ max-height:0; overflow:hidden; transition: max-height .45s ease, padding .3s ease; }
    .open .accordion-content{ padding-top:0.75rem; max-height: 360px; }

    /* floating whatsapp */
    .wa-fab{
      position: fixed; right:18px; bottom:18px; z-index:60;
      width:56px;height:56px;border-radius:14px; display:flex;align-items:center;justify-content:center;
      background: linear-gradient(180deg,var(--accent),var(--accent-boost)); color:white;
      box-shadow:0 12px 28px rgba(59,130,246,0.18); transition: transform .15s ease;
    }
    .wa-fab:hover{ transform: translateY(-6px); }

    /* theme toggle */
    .theme-toggle{ width:44px;height:32px;border-radius:999px; display:inline-flex;align-items:center;padding:4px; gap:6px; cursor:pointer; background:rgba(16,24,40,0.04); }
    .theme-toggle .knob{ width:24px;height:24px;border-radius:50%; background:white; box-shadow:0 4px 12px rgba(2,6,23,0.08); transition: transform .22s ease; }
    .dark .theme-toggle{ background: rgba(255,255,255,0.06); }
    .dark .theme-toggle .knob{ transform: translateX(12px); background:#0b1220; }

    /* focus styles accessibility */
    .focus-ring:focus{ outline:3px solid rgba(59,130,246,0.14); outline-offset:3px; }

    /* responsive tweaks */
    @media (max-width: 768px){
      .hero{ min-height: 360px; padding: 2.5rem 1rem; }
      .logo-box{ width:36px;height:36px; }
    }

    /* small utilities */
    .muted{ color:var(--muted); }
    a.no-underline{ text-decoration:none; }
  </style>
</head>
<body>
  <!-- Header -->
  <header class="site-header sticky top-0 z-40">
    <div class="max-w-7xl mx-auto px-6 py-3 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="logo-box" aria-hidden="true">
          <!-- Snowflake SVG logo (simple) -->
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <path d="M12 2v20M5 7l14 10M5 17l14-10" stroke="var(--accent)" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        </div>
        <div>
          <div class="text-lg font-semibold" style="color:var(--text);">Ronaldo Refrigeração</div>
          <div class="text-xs muted">Instalação • Manutenção • Higienização</div>
        </div>
      </div>

      <div class="flex items-center gap-4">
        <nav class="hidden md:flex items-center gap-5">
          <a class="text-sm hover:underline" href="#servicos">Serviços</a>
          <a class="text-sm hover:underline" href="#sobre">Sobre nós</a>
          <a class="text-sm hover:underline" href="#contato">Contato</a>
          <!-- Instagram icon (opens profile) -->
          <a href="https://www.instagram.com/ronaldo_souuzaa" class="text-[var(--accent)]" target="_blank" rel="noopener" aria-label="Instagram">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none"><path d="M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5zM12 8.5a3.5 3.5 0 1 1 0 7 3.5 3.5 0 0 1 0-7zM17.5 6.5h.01" stroke="var(--accent)" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></svg>
          </a>
        </nav>

        <!-- Theme toggle -->
        <div id="themeToggle" class="theme-toggle focus-ring" role="button" tabindex="0" aria-label="Alternar tema claro/escuro" title="Tema">
          <div class="knob"></div>
        </div>

        <!-- Mobile menu placeholder -->
        <button id="mobileBtn" class="md:hidden p-2 rounded focus-ring" aria-label="Abrir menu">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none"><path d="M3 6h18M3 12h18M3 18h18" stroke="var(--text)" stroke-width="1.6" stroke-linecap="round"/></svg>
        </button>
      </div>
    </div>
  </header>

  <!-- HERO -->
  <section class="hero">
    <!-- Background image: substitua a URL pela sua foto profissional -->
    <div class="hero-bg" style="background-image: url('https://images.unsplash.com/photo-1582719478250-6f627d5f3f13?q=80&w=1600&auto=format&fit=crop&s=placeholder');"></div>
    <div class="overlay" aria-hidden="true"></div>

    <div class="max-w-7xl mx-auto px-6 content">
      <div class="grid lg:grid-cols-2 gap-8 items-center">
        <div class="py-12">
          <h1 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold leading-tight text-white">Instalação, Manutenção e Higienização de Ar-Condicionado</h1>
          <p class="mt-4 text-white/90 max-w-xl">Técnicos certificados, atendimento rápido, garantia de qualidade. Orçamento sem compromisso.</p>
          <div class="mt-6 flex gap-3">
            <a class="px-5 py-3 rounded-lg text-sm font-semibold focus-ring" href="#contato" style="background:var(--accent); color:white; box-shadow:0 10px 28px rgba(59,130,246,0.12)">Solicitar Orçamento</a>
            <a class="px-4 py-3 rounded-lg text-sm font-medium focus-ring no-underline" href="tel:+556192983613" style="background:rgba(255,255,255,0.08); color:white; border:1px solid rgba(255,255,255,0.06)">Ligue Agora</a>
          </div>
        </div>

        <div class="hidden lg:block">
          <!-- Decorative / team image (substitua se tiver foto do técnico ou van) -->
          <div class="service-card" style="background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border: none;">
            <img src="https://images.unsplash.com/photo-1582719478250-6f627d5f3f13?q=80&w=1200&auto=format&fit=crop&s=placeholder" alt="Técnico trabalhando em ar-condicionado" class="w-full rounded-lg" />
            <p class="mt-4 muted">Equipe treinada e equipada — segurança e eficiência nos serviços.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- SERVICES -->
  <section id="servicos" class="py-14 px-6">
    <div class="max-w-7xl mx-auto">
      <div class="mb-8">
        <h2 class="text-2xl font-bold">Nossos Serviços</h2>
        <div class="w-24 h-1 rounded mt-2" style="background:var(--accent)"></div>
      </div>

      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Card 1 -->
        <article class="service-card" data-id="1" tabindex="0" aria-labelledby="s1-title">
          <div class="flex items-start gap-4">
            <div class="icon-circle" aria-hidden="true">
              <svg width="26" height="26" viewBox="0 0 24 24" fill="none"><path d="M12 2v20M5 7l14 10M5 17l14-10" stroke="var(--accent)" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
            </div>
            <div class="flex-1">
              <div class="flex items-center justify-between">
                <h3 id="s1-title" class="font-semibold">Instalação de AC (Split & Janela)</h3>
                <svg class="chev" width="18" height="18" viewBox="0 0 24 24" fill="none"><path d="M6 9l6 6 6-6" stroke="var(--muted)" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></svg>
              </div>
              <p class="mt-2 muted">Instalação segura, testes e orientação sobre a eficiência.</p>
              <div class="accordion-content mt-2 muted">
                <p>Instalamos com atenção à vedação, fixação e normas elétricas. Testes completos e garantia de serviço.</p>
                <div class="mt-3 flex gap-2">
                  <a href="tel:+556192983613" class="px-3 py-2 rounded border text-sm">Ligar</a>
                  <a href="https://wa.me/556192983613?text=Ol%C3%A1!%20Gostaria%20de%20um%20or%C3%A7amento%20para%20instala%C3%A7%C3%A3o%20de%20ar-condicionado." target="_blank" class="px-3 py-2 rounded border text-sm">WhatsApp</a>
                </div>
              </div>
            </div>
          </div>
        </article>

        <!-- Card 2 -->
        <article class="service-card" data-id="2" tabindex="0" aria-labelledby="s2-title">
          <div class="flex items-start gap-4">
            <div class="icon-circle" aria-hidden="true">
              <svg width="26" height="26" viewBox="0 0 24 24" fill="none"><path d="M3 12h18M12 3v18" stroke="var(--accent)" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
            </div>
            <div class="flex-1">
              <div class="flex items-center justify-between">
                <h3 id="s2-title" class="font-semibold">Manutenção Preventiva</h3>
                <svg class="chev" width="18" height="18" viewBox="0 0 24 24" fill="none"><path d="M6 9l6 6 6-6" stroke="var(--muted)" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></svg>
              </div>
              <p class="mt-2 muted">Planos para evitar falhas e manter a eficiência.</p>
              <div class="accordion-content mt-2 muted">
                <p>Inspeção, limpeza de serpentinas, filtros e verificação elétrica. Relatórios e planos personalizados.</p>
                <div class="mt-3 flex gap-2">
                  <a href="tel:+556192983613" class="px-3 py-2 rounded border text-sm">Ligar</a>
                  <a href="https://wa.me/556192983613?text=Ol%C3%A1!%20Quero%20informa%C3%A7%C3%B5es%20sobre%20manuten%C3%A7%C3%A3o%20preventiva." target="_blank" class="px-3 py-2 rounded border text-sm">WhatsApp</a>
                </div>
              </div>
            </div>
          </div>
        </article>

        <!-- Card 3 -->
        <article class="service-card" data-id="3" tabindex="0" aria-labelledby="s3-title">
          <div class="flex items-start gap-4">
            <div class="icon-circle" aria-hidden="true">
              <svg width="26" height="26" viewBox="0 0 24 24" fill="none"><path d="M12 2v20M5 7l14 10" stroke="var(--accent)" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
            </div>
            <div class="flex-1">
              <div class="flex items-center justify-between">
                <h3 id="s3-title" class="font-semibold">Limpeza e Higienização</h3>
                <svg class="chev" width="18" height="18" viewBox="0 0 24 24" fill="none"><path d="M6 9l6 6 6-6" stroke="var(--muted)" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></svg>
              </div>
              <p class="mt-2 muted">Remoção de fungos, bactérias e sujeira.</p>
              <div class="accordion-content mt-2 muted">
                <p>Higienização técnica com produtos específicos e emissão de relatório pós-serviço.</p>
                <div class="mt-3 flex gap-2">
                  <a href="tel:+556192983613" class="px-3 py-2 rounded border text-sm">Ligar</a>
                  <a href="https://wa.me/556192983613?text=Ol%C3%A1!%20Quero%20um%20or%C3%A7amento%20para%20higieniza%C3%A7%C3%A3o." target="_blank" class="px-3 py-2 rounded border text-sm">WhatsApp</a>
                </div>
              </div>
            </div>
          </div>
        </article>

        <!-- Card 4 -->
        <article class="service-card" data-id="4" tabindex="0" aria-labelledby="s4-title">
          <div class="flex items-start gap-4">
            <div class="icon-circle" aria-hidden="true">
              <svg width="26" height="26" viewBox="0 0 24 24" fill="none"><path d="M21 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07" stroke="var(--accent)" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
            </div>
            <div class="flex-1">
              <div class="flex items-center justify-between">
                <h3 id="s4-title" class="font-semibold">Reparos & Carga de Gás</h3>
                <svg class="chev" width="18" height="18" viewBox="0 0 24 24" fill="none"><path d="M6 9l6 6 6-6" stroke="var(--muted)" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round"/></svg>
              </div>
              <p class="mt-2 muted">Diagnóstico, peças e recarga com equipamento homologado.</p>
              <div class="accordion-content mt-2 muted">
                <p>Tratamos vazamentos, substituímos componentes e realizamos testes de estanqueidade e performance.</p>
                <div class="mt-3 flex gap-2">
                  <a href="tel:+556192983613" class="px-3 py-2 rounded border text-sm">Ligar</a>
                  <a href="https://wa.me/556192983613?text=Ol%C3%A1!%20Preciso%20de%20um%20diagn%C3%B3stico%20e%20recarga%20de%20g%C3%A1s." target="_blank" class="px-3 py-2 rounded border text-sm">WhatsApp</a>
                </div>
              </div>
            </div>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- ABOUT / SOBRE NÓS -->
  <section id="sobre" class="py-12 px-6" style="background:var(--surface);">
    <div class="max-w-5xl mx-auto">
      <div class="grid md:grid-cols-2 gap-6 items-center">
        <div>
          <h2 class="text-2xl font-bold">Sobre a Ronaldo Refrigeração</h2>
          <p class="mt-3 muted">Com anos de experiência em climatização residencial e comercial, a Ronaldo Refrigeração presta serviços com foco em segurança, eficiência e transparência. Nossa equipe é certificada e treinada para garantir o melhor resultado.</p>
          <ul class="mt-4 space-y-2">
            <li class="flex items-start gap-3"><strong class="text-[var(--accent)]">✓</strong><span class="muted">Técnicos certificados e atualizados</span></li>
            <li class="flex items-start gap-3"><strong class="text-[var(--accent)]">✓</strong><span class="muted">Atendimento rápido e orçamentos claros</span></li>
            <li class="flex items-start gap-3"><strong class="text-[var(--accent)]">✓</strong><span class="muted">Garantia de serviço quando aplicável</span></li>
          </ul>
        </div>
        <div>
          <!-- Substitua por foto da equipe/van -->
          <img src="https://images.unsplash.com/photo-1542314831-068cd1dbfeeb?q=80&w=900&auto=format&fit=crop&s=placeholder" alt="Equipe da Ronaldo Refrigeração" class="w-full rounded-lg shadow" />
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contato" class="py-14 px-6">
    <div class="max-w-4xl mx-auto">
      <div class="bg-[var(--surface)] p-6 rounded-lg service-card">
        <h3 class="text-xl font-bold">Fale com a Ronaldo Refrigeração</h3>
        <p class="muted mt-2">Atendimento rápido via WhatsApp ou ligação.</p>

        <div class="mt-4 grid md:grid-cols-2 gap-4">
          <div>
            <p class="font-semibold">WhatsApp</p>
            <a class="muted no-underline" href="https://wa.me/556192983613?text=Ol%C3%A1!%20Gostaria%20de%20um%20or%C3%A7amento%20para%20servi%C3%A7o%20de%20ar-condicionado." target="_blank">+55 61 9298-3613</a>
          </div>
          <div>
            <p class="font-semibold">Instagram</p>
            <a class="muted no-underline" href="https://www.instagram.com/ronaldo_souuzaa" target="_blank">@ronaldo_souuzaa</a>
          </div>
        </div>

        <form id="contactForm" class="mt-6 grid gap-3" onsubmit="event.preventDefault(); handleContact(event);">
          <input required name="name" placeholder="Seu nome" class="p-3 rounded border focus-ring" />
          <input required name="phone" placeholder="Telefone/WhatsApp" class="p-3 rounded border focus-ring" />
          <textarea required name="message" rows="4" placeholder="Como podemos ajudar?" class="p-3 rounded border focus-ring"></textarea>
          <div class="flex gap-3">
            <button type="submit" class="px-4 py-2 rounded text-white" style="background:var(--accent)">Enviar</button>
            <button type="reset" class="px-4 py-2 rounded border">Limpar</button>
          </div>
        </form>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="py-6 px-6" style="background:var(--surface); border-top:1px solid rgba(0,0,0,0.04);">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-3">
      <div class="flex items-center gap-3">
        <div class="logo-box" aria-hidden="true">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none"><path d="M12 2v20M5 7l14 10M5 17l14-10" stroke="var(--accent)" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
        </div>
        <div>
          <div class="font-semibold">Ronaldo Refrigeração</div>
          <div class="text-sm muted">© <span id="year"></span> Ronaldo Refrigeração — Todos os direitos reservados.</div>
        </div>
      </div>

      <div class="flex items-center gap-4">
        <a class="muted" href="https://www.instagram.com/ronaldo_souuzaa" target="_blank" rel="noopener">Instagram</a>
        <a class="muted" href="tel:+556192983613">+55 61 9298-3613</a>
      </div>
    </div>
  </footer>

  <!-- Floating WhatsApp button -->
  <a class="wa-fab" href="https://wa.me/556192983613?text=Ol%C3%A1!%20Gostaria%20de%20um%20or%C3%A7amento%20para%20servi%C3%A7o%20de%20ar-condicionado." target="_blank" aria-label="Abrir WhatsApp">
    <svg width="26" height="26" viewBox="0 0 24 24" fill="none"><path d="M21 11.5a9.5 9.5 0 1 0-2.6 6.1L22 22l-3.9-1.6A9.5 9.5 0 0 0 21 11.5zM17.2 14.1c-.3-.1-1.7-.8-2-1s-.5-.2-.8.1c-.3.3-1 1-1.2 1.2-.2.2-.4.3-.7.1-.3-.1-1.6-.6-3-1.9-1.1-1-1.9-2.2-2.1-2.5-.2-.3-.01-.5.14-.7.15-.15.33-.4.5-.6.17-.2.23-.3.35-.5.12-.2.06-.36-.04-.5-.11-.14-.8-1.9-1.07-2.6-.28-.68-.56-.6-.78-.61-.2-.01-.43-.01-.66-.01-.22 0-.57.08-.87.36-.3.28-1.14 1.12-1.14 2.72 0 1.6 1.17 3.14 1.33 3.36.16.22 2.3 3.56 5.58 4.85 3.28 1.28 3.28.86 3.86.81.58-.05 1.88-.76 2.15-1.49.27-.73.27-1.36.19-1.49-.08-.13-.27-.22-.58-.33z" fill="white"/></svg>
  </a>

  <script>
    /* ---------- Small helpers ---------- */
    const WA_NUMBER = '556192983613'; // no +, sanitized
    const IG_URL = 'https://www.instagram.com/ronaldo_souuzaa';

    // Year
    document.getElementById('year').textContent = new Date().getFullYear();

    // feather icons (if used anywhere)
    if(window.feather) try{ feather.replace(); }catch(e){}

    /* ---------- Accordion: toggle per card (accessible) ---------- */
    document.querySelectorAll('.service-card').forEach(card => {
      const chevron = card.querySelector('.chev');
      card.addEventListener('click', (e) => {
        // toggle open class; allow keyboard activation
        card.classList.toggle('open');
        const content = card.querySelector('.accordion-content');
        if(card.classList.contains('open')){
          content.style.maxHeight = content.scrollHeight + 'px';
          content.setAttribute('aria-hidden','false');
        } else {
          content.style.maxHeight = null;
          content.setAttribute('aria-hidden','true');
        }
      });

      // keyboard activation (Enter / Space)
      card.addEventListener('keydown', (ev) => {
        if(ev.key === 'Enter' || ev.key === ' ') { ev.preventDefault(); card.click(); }
      });
    });

    /* ---------- Contact form (demo) ---------- */
    function handleContact(e){
      const f = e.target;
      const data = new FormData(f);
      const payload = Object.fromEntries(data.entries());
      // In production: POST to your backend endpoint (fetch('/api/contact', {method:'POST', body: JSON.stringify(payload)}))
      alert('Obrigado! Mensagem recebida (demo). Em produção, envie para seu servidor: ' + JSON.stringify(payload));
      f.reset();
    }

    /* ---------- Theme toggle (dark/light) ---------- */
    const htmlEl = document.documentElement;
    const themeToggle = document.getElementById('themeToggle');
    // Load stored preference or system
    const saved = localStorage.getItem('rr_theme');
    if(saved === 'dark' || (!saved && window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
      htmlEl.classList.add('dark');
    }
    // Toggle handler
    function toggleTheme(){
      htmlEl.classList.toggle('dark');
      const isDark = htmlEl.classList.contains('dark');
      localStorage.setItem('rr_theme', isDark ? 'dark' : 'light');
    }
    themeToggle.addEventListener('click', toggleTheme);
    themeToggle.addEventListener('keydown', (e) => { if(e.key === 'Enter' || e.key === ' ') { e.preventDefault(); toggleTheme(); }});

    /* ---------- Mobile menu placeholder (extend as needed) ---------- */
    document.getElementById('mobileBtn').addEventListener('click', () => {
      alert('Menu móvel: implemente aqui um drawer se desejar.');
    });

    /* ---------- Accessibility: focus outlines for keyboard users ---------- */
    (function(){ let usingKeyboard = false;
      window.addEventListener('keydown', (e) => { if(e.key === 'Tab') document.body.classList.add('user-is-tabbing'); });
      window.addEventListener('mousedown', () => document.body.classList.remove('user-is-tabbing'));
    })();

    /* ---------- Optional: auto-open first service on desktop ---------- */
    if(window.innerWidth > 1024){
      const first = document.querySelector('.service-card');
      if(first) first.click();
    }
  </script>
</body>
</html>
