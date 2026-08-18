---
layout: home
---
<main>
  <section class="hero hero-split" aria-label="Introduction">
    <div class="hero-body">
      <h1 class="title">Hi, I'm Kavitha Kannan, a biologist and science writer.</h1>
      <p class="lede">I love biology, and I have a PhD on bees, so I happily answer to "bee-girl." </p>
      <p class="lede">These days I write science stories about the cool things animals do, what's going on in their brains when they do them, the hows and whys behind their lives, and why any of it matters for ours. </p>
     <p class="lede">Off the page, I draw comics, watch birds, and have recently taken up running.</p>
    </div>
    <div class="hero-media">
      <img class="avatar" src="/KavithaKannan_biology-no-bg.jpg" alt="Portrait of Kavitha Kannan">
    </div>
  </section>
  <section class="section" aria-labelledby="focus">
    <h2 id="focus" class="h2">Interests</h2>
    <ul class="chips" role="list">
      <li>Bees</li>
      <li>Pollinators</li>
      <li>Behaviour</li>
      <li>Brains</li>
      <li>Ecology</li>
      <li>Evolution</li>
      <li>Conservation science</li>
      <li>Agriculture</li>
      <li>Bio-inspired tech</li>
    </ul>
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
  .title { font-size:clamp(1.45rem,1.2rem + 1.2vw,2rem); line-height:1.25; margin:0 0 10px; }
  .lede { font-size:1.05rem; margin:0 0 14px; }
  .section { max-width:var(--maxw); margin:12px auto 0; padding:16px; }
  .h2 { font-size:1.15rem; font-weight:700; letter-spacing:.01em; margin:0 0 10px; }
  .section p { margin:0 0 14px; }
  .chips { display:flex; flex-wrap:wrap; gap:8px; padding:0; margin:8px 0 0; list-style:none; }
  .chips li { border: none; background: #f3f1ec; color: #4b4a45; border-radius: 6px; cursor: default; }
  .recent .outlet { color:var(--muted); font-size:.9rem; font-style:italic; }
  .recent .more { margin-top:4px; }
  .recent .more a { color:var(--link); font-weight:600; text-decoration:none; }
  .recent .more a:hover { text-decoration:underline; }
  @media (max-width:640px) { .hero-split { grid-template-columns:1fr; text-align:center; } .hero-media { justify-self:center; grid-row:1; } }
</style>
