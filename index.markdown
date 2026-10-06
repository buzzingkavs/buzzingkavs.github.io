---
layout: home
---
<main>
  <section class="hero hero-split" aria-label="Introduction">
    <div class="hero-body">
      <h1 class="title">Hi, I'm Kavitha Kannan, a biologist and science communicator.</h1>
      <p class="lede">Ever since middle school, I have loved biology, whether it's the mysterious chemical properties of a rare plant, why animals behave the way they do, or what's going on in their brains and in ours, in healthy and not-so-healthy conditions. Over the past 10 years, I've been on an academic adventure, hopping countries, working on really cool projects, and picking up a bachelor's in Natural Sciences, a master's in Neuroscience, and a PhD on honey bee behaviour and neurobiology.</p>
      <p class="lede">I've really enjoyed being behind the science: running experiments, untangling tricky datasets, and following my curiosity into the nitty-gritty details. But I've come to realise I love talking about science even more. I like finding the analogy or story that makes a complex idea click, and showing how it connects to everyday life.</p>
      <p class="lede">These days I write articles and features for magazines and newspapers, and I'm reviving my Instagram page as a space for science, comics and a bit of fun. I write about brains, behaviour, health and the natural world: how they work, the hows and whys behind them, and why any of it matters for us. What ties it all together is curiosity, a sense of adventure, and wanting to give back to the community through writing, science communication and mentoring.</p>
      <p class="lede">I'm open to roles where science meets people: communication, editorial, marketing, research or coordination.</p>
      <p class="lede">This page's name, BuzzingKavs, comes from my love for all things buzzing: bees and other insects, a busy brain, and yes, phones (yay for communication!). Kavs is a nickname that goes back to school.</p>
      <p class="lede">Off the page, I draw comics, watch birds, and have recently taken up running.</p>
    </div>
    <div class="hero-media">
      <img class="avatar" src="/KavithaKannan_biology-no-bg.jpg" alt="Portrait of Kavitha Kannan">
    </div>
  </section>
  <section class="section" aria-labelledby="focus">
    <h2 id="focus" class="h2">Interests</h2>
    <ul class="chips" role="list">
      <li>Brains</li>
      <li>Behaviour</li>
      <li>Health</li>
      <li>Ecology</li>
      <li>Evolution</li>
      <li>Conservation science</li>
      <li>Pollinators</li>
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
