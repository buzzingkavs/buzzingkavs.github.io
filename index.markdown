---
layout: home
---

<main>
  <section class="hero hero-split" aria-label="Introduction">
    <div class="hero-body">
      <p class="eyebrow">Science writer · Insect biologist</p>
      <h1 class="title">I’m Kavitha Kannan - a science writer and insect biologist based in Strasbourg.</h1>
      <p class="lede">I write about animal behaviour, ecology, evolution, and the natural world, drawing on seven years of hands-on research in behavioural experiments, fieldwork, and data analysis.</p>
      <p class="cta"><a class="inline" href="mailto:kavithakannan1994@gmail.com">Get in touch →</a></p>
    </div>
    <div class="hero-media">
      <img class="avatar" src="/KavithaKannan_biology.jpg" alt="Portrait of Kavitha Kannan">
    </div>
  </section>

  <section class="section" aria-labelledby="what">
    <h2 id="what" class="h2">What I do</h2>
    <p>I turn scientific ideas into clear, lively stories for general audiences. My work is rooted in insect behaviour and neurobiology, with a particular affection for bees and the small lives that make ecosystems work.</p>
  </section>

  <section class="section" aria-labelledby="focus">
    <h2 id="focus" class="h2">Areas of interest</h2>
    <ul class="chips" role="list">
      <li>Animal behaviour</li>
      <li>Insects</li>
      <li>Ecology</li>
      <li>Evolution</li>
      <li>Neurobiology</li>
      <li>Fieldwork</li>
    </ul>
  </section>

  <section class="section" aria-labelledby="news">
    <h2 id="news" class="h2">Recent writing</h2>
    <ul class="news-list" role="list">
      <li><time datetime="2026">2026</time><p><strong>“Kingmakers: meet the insects that make India’s famed mangoes”</strong> — a reported feature on wild insect pollinators and mango yield, published in <em>The Hindu</em>.</p></li>
      <li><time datetime="2026">Next</time><p><strong>“The Bees that Choose to Sting”</strong> — a feature for Club SciWri on doctoral research into honeybee defensive behaviour.</p></li>
    </ul>
  </section>
</main>

<style>
  :root { --ink:#111; --muted:#6b7280; --link:#2a7ae2; --maxw:46rem; }
  .hero-split { display:grid; grid-template-columns:1fr 190px; align-items:center; gap:28px; max-width:var(--maxw); margin:0 auto 32px; }
  .hero-media { justify-self:end; }
  .avatar { width:clamp(145px, 22vw, 210px); aspect-ratio:1; object-fit:cover; object-position:center; border-radius:50%; box-shadow:0 4px 18px rgba(0,0,0,.16); }
  .eyebrow { color:var(--muted); margin:0 0 6px; font-size:1rem; }
  .title { font-size:clamp(1.45rem,1.2rem + 1.2vw,2rem); line-height:1.25; margin:0 0 10px; }
  .lede { font-size:1.05rem; margin:0 0 14px; }
  .cta { margin:0; } .inline { color:var(--link); font-weight:600; text-decoration:none; } .inline:hover { text-decoration:underline; }
  .section { max-width:var(--maxw); margin:12px auto 0; padding:16px; }
  .h2 { font-size:1.15rem; font-weight:700; letter-spacing:.01em; margin:0 0 10px; }
  .section p { margin:0; }
  .chips { display:flex; flex-wrap:wrap; gap:8px; padding:0; margin:8px 0 0; list-style:none; }
  .chips li { padding:6px 10px; border:1px solid #d9dce1; border-radius:999px; font-size:.95rem; }
  .news-list { list-style:none; margin:12px 0 0; padding:0; display:grid; gap:18px; }
  .news-list li { display:grid; grid-template-columns:5ch 1fr; gap:16px; }
  .news-list time { color:var(--muted); font-size:.9rem; }
  @media (max-width:640px) { .hero-split { grid-template-columns:1fr; text-align:center; } .hero-media { justify-self:center; grid-row:1; } }
</style>
