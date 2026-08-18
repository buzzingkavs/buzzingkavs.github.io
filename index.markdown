---
layout: home
---
<main>
  <section class="hero hero-split" aria-label="Introduction">
    <div class="hero-body">
      <p class="eyebrow">Science writer · Insect biologist</p>
      <h1 class="title">I'm Kavitha Kannan, an insect biologist and science writer.</h1>
      <p class="lede">I write about animal behaviour, ecology, and evolution for general readers, drawing on seven years of hands-on research in behavioural experiments, fieldwork, and data analysis.</p>
      <p class="cta">
        <a class="btn" href="/writing/">Read my writing →</a>
      </p>
    </div>
    <div class="hero-media">
      <img class="avatar" src="/KavithaKannan_biology.jpg" alt="Portrait of Kavitha Kannan">
    </div>
  </section>
  <section class="section" aria-labelledby="news">
    <h2 id="news" class="h2">Recent writing</h2>
    <div class="recent">
      <p><strong><a href="https://www.thehindu.com/sci-tech/energy-and-environment/kingmakers-meet-the-insects-that-make-india-famed-mangoes/article71141108.ece">Kingmakers: meet the insects that make India's famed mangoes</a></strong><br>
      <span class="outlet">The Hindu</span></p>
      <p><strong><a href="https://www.asianscientist.com/2026/08/environment/wax-the-secret-ingredient-in-making-a-honeybee-queen/">Wax: the secret ingredient in making a honeybee queen</a></strong><br>
      <span class="outlet">Asian Scientist</span></p>
      <p class="more"><a href="/writing/">All writing →</a></p>
    </div>
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
  .cta { margin:0; display:flex; flex-wrap:wrap; align-items:center; gap:14px; }
  .btn { display:inline-block; background:var(--link); color:#fff; font-weight:600; text-decoration:none; padding:9px 16px; border-radius:8px; }
  .btn:hover { opacity:.9; }
  .section { max-width:var(--maxw); margin:12px auto 0; padding:16px; }
  .h2 { font-size:1.15rem; font-weight:700; letter-spacing:.01em; margin:0 0 10px; }
  .section p { margin:0 0 14px; }
  .recent .outlet { color:var(--muted); font-size:.9rem; font-style:italic; }
  .recent .more { margin-top:4px; }
  .recent .more a { color:var(--link); font-weight:600; text-decoration:none; }
  .recent .more a:hover { text-decoration:underline; }
  @media (max-width:640px) { .hero-split { grid-template-columns:1fr; text-align:center; } .hero-media { justify-self:center; grid-row:1; } .cta { justify-content:center; } }
</style>
