<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PPO Foam Industrial Handbook</title>
  <style>
    * { margin:0; padding:0; box-sizing:border-box; }
    body { font-family:'Montserrat', sans-serif; background:#111; overflow:hidden; }
    .slider { width:100vw; height:100vh; position:relative; }
    .slide { position:absolute; top:0; left:0; width:100%; height:100%; display:none; background:#fff; }
    .slide.active { display:block; }
    .page-num { position:absolute; bottom:20px; left:30px; font-weight:bold; font-size:24px; color:#fff; background:rgba(0,0,0,0.5); padding:8px 16px; border-radius:8px; }
    .logo { position:absolute; top:30px; left:30px; font-weight:900; font-size:28px; color:#fff; }
    .circ { position:absolute; bottom:40px; right:40px; width:80px; }
    .btn { position:absolute; top:50%; transform:translateY(-50%); background:rgba(255,98,0,0.8); color:#fff; border:none; width:60px; height:60px; font-size:30px; cursor:pointer; border-radius:50%; z-index:10; }
    #prev { left:20px; } #next { right:20px; }
    .split { display:flex; height:100%; }
    .left, .right { width:50%; position:relative; }
    .left { background:#0077C8; color:#fff; padding:80px 60px; }
    .right { background-size:cover; background-position:center; }
    .title { font-size:42px; font-weight:900; line-height:1.2; margin-bottom:30px; }
    .subtitle { font-size:28px; margin-bottom:20px; border-bottom:2px solid #fff; display:inline-block; }
    .text { font-size:18px; line-height:1.7; }
    .icon-list { display:grid; grid-template-columns:repeat(2,1fr); gap:15px; margin-top:30px; }
    .icon-item { background:rgba(255,255,255,0.2); padding:12px; border-radius:8px; font-weight:600; }
    .circle-model { position:absolute; bottom:100px; left:50%; transform:translateX(-50%); width:200px; }
    .radar { width:80%; margin:40px auto; }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&display=swap" rel="stylesheet">
</head>
<body>

<div class="slider">

  <!-- Slide 1: Cover -->
  <div class="slide active" style="background:linear-gradient(135deg,#FF6200,#FF8C33); color:#fff; text-align:center; padding-top:15%;">
    <div class="logo">PPOCore</div>
    <h1 style="font-size:60px; margin:40px 0;">WE'RE ALWAYS<br>AT THE CORE OF<br>YOUR INDUSTRIAL<br>INNOVATION</h1>
    <img src="https://images.unsplash.com/photo-1581092580496-e0d23cbdf1dc?w=1920" style="width:100%; position:absolute; bottom:0; left:0;">
    <img src="https://i.imgur.com/0Y5fX5P.png" class="circ">
    <div class="page-num">1</div>
  </div>

  <!-- Slide 2: Company Intro Left -->
  <div class="slide">
    <div class="split">
      <div class="left">
        <h2 class="title">ALWAYS AT THE<br>CORE OF YOUR<br>SOLUTION</h2>
        <p class="text">
          Founded in Sweden in 1950. Ever since the beginning, and throughout our steady development into a global company, we have been dedicated to constant innovation and promoting a widespread adoption of structural <strong>PPO foam materials</strong>.<br><br>
          Our PPO foam solutions have been used in automotive, transportation, construction, and industrial applications for decades, qualified according to ISO 16702, UL94, and automotive OEM standards.<br><br>
          With a complete range of high-performance PPO foam, finishing options, and kitting operations — combined with engineering services and expertise — we present the most valuable offering in the sandwich composite industry.
        </p>
        <div class="page-num">2</div>
      </div>
      <div class="right" style="background-image:url('https://images.unsplash.com/photo-1581092160600-7e21b2d67f1d?w=1920');"></div>
    </div>
  </div>

  <!-- Slide 3: Industrial Advantage Right -->
  <div class="slide">
    <div class="split">
      <div class="left" style="background:#0077C8;">
        <div class="page-num">3</div>
      </div>
      <div class="right" style="background:linear-gradient(rgba(0,0,0,0.4),rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1581093450021-4a7360e9a6b5?w=1920'); background-size:cover; color:#fff; padding:80px 60px;">
        <h2 class="title">THE ULTIMATE<br>ENGINEERING<br>SOLUTION</h2>
        <p class="text">
          The volume and number of industrial applications using PPO foam composites is growing steadily — from <strong>electric vehicle battery trays</strong>, <strong>train interiors</strong>, <strong>insulated building panels</strong>, to <strong>cryogenic tanks</strong>.<br><br>
          Sandwich composites with PPO foam are lighter, stronger, and more thermally stable than aluminum, steel, or traditional insulation materials.<br><br>
          → Reduce vehicle weight by <strong>15-30%</strong><br>
          → Improve thermal insulation by <strong>40%</strong><br>
          → Extend service life in harsh environments<br><br>
          We have the widest portfolio of PPO foam grades and the design capabilities to optimize your application.
        </p>
      </div>
    </div>
  </div>

  <!-- Slide 4: Sandwich Tech Left -->
  <div class="slide">
    <div class="split">
      <div class="left">
        <h2 class="title">MAKE THE MOST<br>OF YOUR<br>APPLICATION</h2>
        <h3 class="subtitle">THE SANDWICH TECHNOLOGY</h3>
        <p class="text">
          Composite materials combine two or more materials with significantly different properties to form a superior structure.<br><br>
          Two thin, strong skins (GFRP/CFRP/metal) are bonded to a lightweight <strong>PPO foam core</strong>. This minimizes weight while maximizing stiffness and strength.<br><br>
          Result:<br>
          → Highest stiffness-to-weight ratio<br>
          → Excellent thermal & dimensional stability<br>
          → All advantages of metal — none of the weight or corrosion
        </p>
        <div class="page-num">4</div>
      </div>
      <div class="right" style="background-image:url('https://images.unsplash.com/photo-1581093450021-4a7360e9a6b5?w=1920');"></div>
    </div>
  </div>

  <!-- Slide 5: Core Mastery Right -->
  <div class="slide">
    <div class="split">
      <div class="left" style="background:#f5f5f5; color:#333; padding:80px 60px;">
        <h3 class="subtitle">MASTERS OF PPO FOAM CORE</h3>
        <p class="text">
          In a sandwich panel:<br>
          • Skins take tension/compression<br>
          • <strong>PPO core</strong> carries shear loads<br><br>
          Our closed-cell PPO foam:<br>
          → Absorbs dynamic loads<br>
          → Resists water, chemicals, creep<br>
          → Stable up to <strong>120°C</strong> (HT grades)<br><br>
          Add functional grades for:<br>
          → Fire resistance (UL94 V-0)<br>
          → Radar transparency<br>
          → Impact absorption
        </p>
        <div style="margin-top:40px;">
          <img src="https://i.imgur.com/3JkL9pX.png" style="width:100%;">
        </div>
        <div class="page-num" style="color:#333; background:rgba(0,0,0,0.1);">5</div>
      </div>
      <div class="right" style="background:#fff; display:flex; align-items:center; justify-content:center;">
        <div class="icon-list">
          <div class="icon-item">LIGHTWEIGHT</div>
          <div class="icon-item">STRONG</div>
          <div class="icon-item">CREEP RESISTANT</div>
          <div class="icon-item">FATIGUE RESISTANT</div>
          <div class="icon-item">FIRE RESISTANT</div>
          <div class="icon-item">IMPACT PERFORMANCE</div>
          <div class="icon-item">CHEMICAL RESISTANT</div>
          <div class="icon-item">NONCORROSIVE</div>
          <div class="icon-item">INSULATING</div>
          <div class="icon-item">RADAR TRANSPARENT</div>
          <div class="icon-item">SUSTAINABLE</div>
          <div class="icon-item">FLEXIBILITY</div>
          <div class="icon-item">HIGH THERMAL STABILITY</div>
          <div class="icon-item">DIMENSIONAL STABILITY</div>
        </div>
      </div>
    </div>
  </div>

  <!-- Slide 6-7: Circular Economy -->
  <div class="slide">
    <div class="split">
      <div class="left" style="background:#00A65A; color:#fff;">
        <h2 class="title">LET'S GET<br>CIRCULAR</h2>
        <p class="text">
          We are the only foam core supplier reducing carbon footprint in line with <strong>Science Based Targets</strong> — approved by UN Global Compact.<br><br>
          We work across Scope 3 to help suppliers decarbonize — a chain effect that benefits your LCA.
        </p>
        <img src="https://i.imgur.com/0Y5fX5P.png" class="circle-model">
        <div class="page-num">6</div>
      </div>
      <div class="right" style="background-image:url('https://images.unsplash.com/photo-1504280390367-361e9d2f3a3e?w=1920');"></div>
    </div>
  </div>

  <div class="slide">
    <div class="split">
      <div class="left" style="background:#fff; color:#333; padding:80px 60px;">
        <h3 class="subtitle">YOUR BENEFITS</h3>
        <p class="text">
          • Use recycled PPO foam → reduce Scope 3<br>
          • Lighter weight → lower fuel/energy use<br>
          • 30+ year lifespan → better LCA<br>
          • Transparent composition → easy recycling<br><br>
          We provide material passports for circular certification.
        </p>
        <div class="page-num" style="color:#333;">7</div>
      </div>
      <div class="right" style="background-image:url('https://images.unsplash.com/photo-1581092921461-7d7e0f332d3f?w=1920');"></div>
    </div>
  </div>

  <!-- Slide 8-9: Kitting -->
  <div class="slide" style="background:#FF6200; color:#fff; padding:80px;">
    <h2 class="title">OPTIMIZE EFFICIENCY,<br>COST, WEIGHT, AND<br>QUALITY WITH PPO<br>KITTING SOLUTIONS</h2>
    <div style="display:flex; gap:40px; margin-top:40px;">
      <div style="flex:1;">
        <h3>WHAT IS A KIT?</h3>
        <p>A tailor-shaped set of PPO foam elements — pre-cut via CNC into 2D/3D shapes, numbered, and delivered with assembly drawings.</p>
        <ul style="margin-top:20px;">
          <li>Shorten lay-up time by 40%</li>
          <li>Reduce waste & labor</li>
          <li>Improve surface quality</li>
          <li>Recover factory space</li>
        </ul>
      </div>
      <div style="flex:1;">
        <h3>WHY FROM US?</h3>
        <p>In-house CNC & engineering. On-site measurement & co-design. Flow/perforation finishes optimized for RTM/VARTM.</p>
      </div>
    </div>
    <div class="page-num">8</div>
  </div>

  <!-- Slide 10: Cases -->
  <div class="slide" style="padding:80px; background:#f8f8f8;">
    <h2 style="text-align:center; color:#0077C8; margin-bottom:40px;">SUCCESS STORIES</h2>
    <div style="display:grid; grid-template-columns:repeat(3,1fr); gap:30px;">
      <div style="background:#fff; padding:20px; border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.1);">
        <h3>EV Battery Tray</h3>
        <p><strong>-28% weight</strong><br>UL94 V-0 compliant</p>
      </div>
      <div style="background:#fff; padding:20px; border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.1);">
        <h3>Train Side Panel</h3>
        <p><strong>-35% weight</strong><br>EN 45545 certified</p>
      </div>
      <div style="background:#fff; padding:20px; border-radius:12px; box-shadow:0 4px 12px rgba(0,0,0,0.1);">
        <h3>Cold Chain Container</h3>
        <p><strong>R-value +42%</strong><br>25-year lifespan</p>
      </div>
    </div>
    <div class="page-num">9</div>
  </div>

  <!-- Slide 11: Contact -->
  <div class="slide" style="background:linear-gradient(135deg,#FF6200,#FF8C33); color:#fff; text-align:center; padding-top:15%;">
    <h1 style="font-size:60px;">AT THE CORE<br>OF YOUR<br>PERFORMANCE</h1>
    <p style="font-size:24px; margin:40px 0;">Let’s co-create lighter, stronger, and more sustainable industrial solutions with PPO foam.</p>
    <div style="font-size:20px;">
      <p>contact@ppocore.com | +86 400 820 1234</p>
      <p>www.ppocore.com</p>
    </div>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://ppocore.com" style="margin-top:40px;">
    <div class="page-num">10</div>
  </div>

</div>

<button id="prev" class="btn">‹</button>
<button id="next" class="btn">›</button>

<script>
  const slides = document.querySelectorAll('.slide');
  let current = 0;
  document.getElementById('next').addEventListener('click', () => {
    slides[current].classList.remove('active');
    current = (current + 1) % slides.length;
    slides[current].classList.add('active');
  });
  document.getElementById('prev').addEventListener('click', () => {
    slides[current].classList.remove('active');
    current = (current - 1 + slides.length) % slides.length;
    slides[current].classList.add('active');
  });
  // Keyboard support
  document.addEventListener('keydown', e => {
    if (e.key === 'ArrowRight') document.getElementById('next').click();
    if (e.key === 'ArrowLeft') document.getElementById('prev').click();
  });
</script>

</body>
</html>
