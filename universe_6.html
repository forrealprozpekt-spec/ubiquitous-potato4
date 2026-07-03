<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Universe</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Cormorant+Garamond:ital,wght@0,500;0,600;1,500&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --void: #050308;
    --nebula-violet: #8f82d9;
    --nebula-rose: #c9a6d8;
    --nebula-teal: #8fc9c2;
    --nebula-cream: #e8e2d0;
    --star: #f5f2ff;
    --dim: rgba(245,242,255,0.55);
  }

  *{ margin:0; padding:0; box-sizing:border-box; }

  html,body{
    background: radial-gradient(ellipse at 50% 20%, #140b2e 0%, #050308 55%, #020103 100%);
    color: var(--star);
    font-family: 'Inter', sans-serif;
    overflow-x: hidden;
    scroll-behavior: smooth;
  }

  ::selection{ background: var(--nebula-violet); color: white; }

  #starfield{
    position: fixed;
    inset: 0;
    z-index: 0;
    display: block;
    width: 100vw;
    height: 100vh;
  }

  .hero{
    position: relative;
    height: 100vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 1;
  }

  .hero-caption{
    position: absolute;
    bottom: 7vh;
    left: 0; right: 0;
    text-align: center;
    z-index: 3;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    font-size: 11px;
    color: var(--dim);
    opacity: 0;
    animation: fadeUpNoX 2s ease forwards;
    animation-delay: 0.4s;
    pointer-events: none;
  }
  .hero-caption .pulse{
    display:inline-block;
    width:6px; height:6px;
    border-radius:50%;
    background: var(--nebula-cream);
    margin-right:8px;
    vertical-align:middle;
    animation: blink 1.6s ease-in-out infinite;
  }
  @keyframes blink{ 0%,100%{opacity:.25} 50%{opacity:1} }

  .hero-title{
    position: relative;
    z-index: 3;
    text-align: center;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-weight: 500;
    font-size: clamp(2rem, 6vw, 4.2rem);
    letter-spacing: 0.02em;
    max-width: 20ch;
    opacity: 0;
    color: var(--star);
    text-shadow: 0 4px 30px rgba(0,0,0,0.7);
    animation: fadeUpNoX 1.8s ease forwards;
    animation-delay: 0.7s;
    pointer-events: none;
  }

  .hero-hint{
    position: absolute;
    top: 2.4rem; left: 0; right: 0;
    text-align: center;
    z-index: 3;
    font-size: 12px;
    letter-spacing: 0.15em;
    color: var(--dim);
    opacity: 0;
    animation: fadeUpNoX 1.8s ease forwards;
    animation-delay: 1.6s;
    pointer-events: none;
  }

  .scroll-hint{
    position: absolute;
    bottom: 2.4rem; left: 50%;
    transform: translateX(-50%);
    z-index: 3;
    width: 22px; height: 36px;
    border: 1px solid rgba(245,242,255,0.3);
    border-radius: 20px;
    opacity: 0;
    animation: fadeUpX 1.5s ease forwards;
    animation-delay: 2s;
  }
  .scroll-hint::before{
    content:'';
    position:absolute;
    top:6px; left:50%;
    width:3px; height:8px;
    background: var(--nebula-teal);
    border-radius: 2px;
    transform: translateX(-50%);
    animation: scrollDot 1.8s ease infinite;
  }
  @keyframes scrollDot{ 0%{ opacity:1; top:6px;} 70%{opacity:0; top:18px;} 100%{opacity:0; top:6px;} }
  @keyframes fadeUpX{ from{ opacity:0; transform: translate(-50%,10px);} to{ opacity:1; transform: translate(-50%,0);} }
  @keyframes fadeUpNoX{ from{opacity:0; transform:translateY(10px);} to{opacity:1; transform:translateY(0);} }

  .reveal{
    position: relative;
    z-index: 1;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 8vh 6vw;
    gap: 2.2rem;
  }

  .eyebrow{
    font-size: 12px;
    letter-spacing: 0.4em;
    text-transform: uppercase;
    color: var(--nebula-teal);
    opacity: 0.85;
  }

  .reveal h2{
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 600;
    font-size: clamp(1.6rem, 4.2vw, 2.9rem);
    max-width: 16ch;
    line-height: 1.25;
    color: var(--star);
  }

  .reveal p.sub{
    max-width: 46ch;
    color: var(--dim);
    font-size: 1.02rem;
    line-height: 1.7;
  }

  .summon-btn{
    position: relative;
    margin-top: 1rem;
    padding: 1rem 2.6rem;
    border-radius: 999px;
    border: 1px solid rgba(245,242,255,0.25);
    background: linear-gradient(120deg, rgba(143,130,217,0.16), rgba(143,201,194,0.16));
    color: var(--star);
    font-family: 'Space Grotesk', sans-serif;
    font-size: 0.95rem;
    letter-spacing: 0.04em;
    cursor: pointer;
    overflow: hidden;
    transition: transform .35s ease, box-shadow .35s ease, border-color .35s ease;
  }
  .summon-btn:hover{
    transform: translateY(-2px) scale(1.03);
    box-shadow: 0 0 40px rgba(143,130,217,0.3), 0 0 80px rgba(143,201,194,0.12);
    border-color: rgba(245,242,255,0.5);
  }
  .summon-btn:active{ transform: translateY(0) scale(0.98); }

  .final-wrap{
    position: relative;
    z-index: 1;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 6vh 6vw;
  }

  .final-card{
    position: relative;
    z-index: 2;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1.6rem;
    opacity: 0;
    transform: scale(0.85);
    transition: opacity 1s cubic-bezier(.2,.9,.3,1), transform 1s cubic-bezier(.2,.9,.3,1);
  }
  .final-card.show{ opacity: 1; transform: scale(1); }

  .final-eyebrow{
    font-size: 12px;
    letter-spacing: 0.5em;
    text-transform: uppercase;
    color: var(--nebula-cream);
  }

  .final-message{
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 700;
    font-size: clamp(1.7rem, 6vw, 3.6rem);
    line-height: 1.35;
    max-width: 18ch;
    background: linear-gradient(100deg, var(--nebula-cream) 0%, var(--nebula-rose) 35%, var(--nebula-violet) 65%, var(--nebula-teal) 100%);
    background-size: 220% auto;
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    animation: shimmer 6s linear infinite;
  }
  @keyframes shimmer{ to{ background-position: -220% center; } }

  .final-sub{
    color: var(--dim);
    font-size: 1rem;
    max-width: 40ch;
  }

  .sparkle-row{ font-size: 1.4rem; letter-spacing: 0.6rem; opacity: 0.9; }

  .games{
    position: relative;
    z-index: 1;
    padding: 8vh 6vw 12vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 4rem;
  }

  .games-title{
    text-align: center;
    font-family: 'Cormorant Garamond', serif;
    font-style: italic;
    font-size: clamp(1.8rem, 4vw, 2.6rem);
    color: var(--star);
  }
  .games-title span{ color: var(--nebula-teal); font-style: normal; }

  .game-grid{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
    gap: 2.4rem;
    width: 100%;
    max-width: 1100px;
  }

  .game-card{
    background: linear-gradient(160deg, rgba(143,130,217,0.06), rgba(10,7,20,0.4));
    border: 1px solid rgba(245,242,255,0.1);
    border-radius: 20px;
    padding: 1.8rem;
    backdrop-filter: blur(6px);
  }

  .game-card h3{
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.15rem;
    margin-bottom: 0.4rem;
    color: var(--star);
  }
  .game-card p{
    color: var(--dim);
    font-size: 0.9rem;
    margin-bottom: 1.2rem;
    line-height: 1.55;
  }

  .mini-btn{
    padding: 0.55rem 1.3rem;
    border-radius: 999px;
    border: 1px solid rgba(245,242,255,0.25);
    background: rgba(143,130,217,0.15);
    color: var(--star);
    font-family: 'Space Grotesk', sans-serif;
    font-size: 0.8rem;
    cursor: pointer;
    transition: all .25s ease;
  }
  .mini-btn:hover{ background: rgba(143,130,217,0.28); border-color: rgba(245,242,255,0.5); }

  /* ---- Game 1: Constellation Memory Match ---- */
  .memory-grid{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 0.6rem;
    margin-bottom: 1.1rem;
  }
  .memory-card{
    aspect-ratio: 1;
    border-radius: 10px;
    background: rgba(143,130,217,0.12);
    border: 1px solid rgba(245,242,255,0.15);
    display: flex; align-items:center; justify-content:center;
    font-size: 1.5rem;
    cursor: pointer;
    user-select: none;
    transition: background .25s ease, transform .2s ease, opacity .3s ease;
  }
  .memory-card.flipped{ background: rgba(143,201,194,0.18); transform: scale(1.04); }
  .memory-card.matched{ opacity: 0.35; cursor: default; }
  .memory-hud{
    display:flex; justify-content: space-between; align-items:center;
    font-family: 'Space Grotesk', sans-serif;
    font-size: 0.85rem;
    color: var(--dim);
  }
  .memory-hud b{ color: var(--nebula-cream); }

  /* ---- Game 2: Wish Typer ---- */
  .typer-word{
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1.6rem;
    letter-spacing: 0.05em;
    text-align: center;
    margin: 1.4rem 0 1rem;
    color: var(--nebula-cream);
    min-height: 2.2rem;
  }
  .typer-word span.typed{ color: var(--nebula-teal); }
  .typer-input{
    width: 100%;
    padding: 0.7rem 1rem;
    border-radius: 10px;
    border: 1px solid rgba(245,242,255,0.2);
    background: rgba(255,255,255,0.04);
    color: var(--star);
    font-family: 'Space Grotesk', sans-serif;
    font-size: 1rem;
    outline: none;
    margin-bottom: 1rem;
  }
  .typer-input:focus{ border-color: rgba(143,201,194,0.6); }
  .typer-hud{
    display:flex; justify-content: space-between; align-items:center;
    font-family: 'Space Grotesk', sans-serif;
    font-size: 0.85rem;
    color: var(--dim);
  }
  .typer-hud b{ color: var(--nebula-cream); }

  footer{
    position: relative;
    z-index: 1;
    text-align: center;
    padding: 3rem 1rem 4rem;
    color: rgba(245,242,255,0.3);
    font-size: 0.75rem;
    letter-spacing: 0.1em;
  }

  @media (max-width: 640px){
    .final-message{ max-width: 15ch; }
  }
</style>
</head>
<body>

<canvas id="starfield"></canvas>

<section class="hero">
  <div class="hero-hint">move your cursor across the sky</div>
  <div class="hero-title">the universe, quietly watching</div>
  <div class="hero-caption"><span class="pulse"></span>the stars drift with you</div>
  <div class="scroll-hint"></div>
</section>

<section class="reveal">
  <div class="eyebrow">Chapter One</div>
  <h2>Every atom in you was once inside a star.</h2>
  <p class="sub">Hydrogen became helium, dust became galaxies, galaxies became you — reading this, on a screen, waiting for something. It took the entire universe fourteen billion years to get here. Let's see what it has to say.</p>
  <button class="summon-btn" id="summonBtn">✦ Ask the universe ✦</button>
</section>

<section class="final-wrap" id="finalWrap">
  <div class="final-card" id="finalCard">
    <div class="final-eyebrow">a message, from everything</div>
    <div class="final-message">ab to universe ne bhi kehdiya, vn dedo sweetie</div>
    <div class="sparkle-row">✦ ⋆ ✦ ⋆ ✦</div>
    <p class="final-sub">140 billion galaxies got together and agreed. You can't argue with the entire cosmos.</p>
  </div>
</section>

<section class="games">
  <h2 class="games-title">while you <span>think about it</span> — two tiny games</h2>
  <div class="game-grid">

    <!-- Game 1: Constellation Memory Match -->
    <div class="game-card">
      <h3>✶ Constellation Match</h3>
      <p>Flip two cards at a time and find every matching pair of cosmic symbols.</p>
      <div class="memory-grid" id="memoryGrid"></div>
      <div class="memory-hud">
        <span>Moves: <b id="memoryMoves">0</b></span>
        <span id="memoryStatus">Find the pairs</span>
        <button class="mini-btn" id="memoryReset">Reset</button>
      </div>
    </div>

    <!-- Game 2: Wish Typer -->
    <div class="game-card">
      <h3>✶ Wish Typer</h3>
      <p>Type each falling word before the timer runs out. Speed matters, typos don't.</p>
      <div class="typer-word" id="typerWord">press start</div>
      <input class="typer-input" id="typerInput" type="text" placeholder="type here..." disabled>
      <div class="typer-hud">
        <span>Score: <b id="typerScore">0</b></span>
        <span id="typerTime">Ready</span>
        <button class="mini-btn" id="typerStart">Start</button>
      </div>
    </div>

  </div>
</section>

<footer>made of stardust, mostly for fun</footer>

<script>
/* =========================================================
   INTERACTIVE STARFIELD — stars drift with parallax depth,
   like a camera panning as the cursor moves. Stars closer
   to the "camera" (larger, brighter) shift more; distant
   stars barely move, giving real depth.
   ========================================================= */
(function starfield(){
  const canvas = document.getElementById('starfield');
  const ctx = canvas.getContext('2d');
  let W, H;
  let stars = [];
  let mouseX = 0, mouseY = 0;
  let camX = 0, camY = 0;

  function resize(){
    W = canvas.width = window.innerWidth;
    H = canvas.height = window.innerHeight;
    mouseX = W/2; mouseY = H/2;
    buildStars();
  }

  function buildStars(){
    const count = Math.floor((W*H) / 6000);
    stars = [];
    for(let i=0;i<count;i++){
      stars.push({
        x: Math.random()*W,
        y: Math.random()*H,
        depth: Math.random()*0.85 + 0.15,   // 0.15 (far) -> 1 (near)
        r: Math.random()*1.5 + 0.4,
        baseAlpha: Math.random()*0.5 + 0.25,
        twinkleSpeed: Math.random()*0.02 + 0.005,
        twinkleOffset: Math.random()*Math.PI*2
      });
    }
  }

  window.addEventListener('resize', resize);
  window.addEventListener('mousemove', e=>{ mouseX = e.clientX; mouseY = e.clientY; });
  window.addEventListener('touchmove', e=>{
    if(e.touches[0]){ mouseX = e.touches[0].clientX; mouseY = e.touches[0].clientY; }
  }, {passive:true});

  let t = 0;
  function draw(){
    t += 1;
    ctx.clearRect(0,0,W,H);

    // camera offset eases toward the cursor position (relative to center)
    const targetX = (mouseX - W/2) * -0.06;
    const targetY = (mouseY - H/2) * -0.06;
    camX += (targetX - camX) * 0.05;
    camY += (targetY - camY) * 0.05;

    stars.forEach(s=>{
      const px = s.x + camX * s.depth;
      const py = s.y + camY * s.depth;

      const twinkle = s.baseAlpha + Math.sin(t*s.twinkleSpeed + s.twinkleOffset) * 0.2;

      ctx.beginPath();
      ctx.arc(px, py, s.r * (0.7 + s.depth*0.6), 0, Math.PI*2);
      ctx.fillStyle = '#f5f2ff';
      ctx.globalAlpha = Math.max(twinkle, 0);
      ctx.fill();
      ctx.globalAlpha = 1;
    });

    requestAnimationFrame(draw);
  }

  resize();
  requestAnimationFrame(draw);
})();

/* =========================================================
   SUMMON BUTTON -> reveal final message
   ========================================================= */
(function finalReveal(){
  const btn = document.getElementById('summonBtn');
  const finalWrap = document.getElementById('finalWrap');
  const finalCard = document.getElementById('finalCard');

  btn.addEventListener('click', ()=>{
    finalWrap.scrollIntoView({behavior:'smooth'});
    setTimeout(()=>{ finalCard.classList.add('show'); }, 500);
  });
})();

/* =========================================================
   GAME 1 — Constellation Memory Match
   ========================================================= */
(function memoryGame(){
  const grid = document.getElementById('memoryGrid');
  const movesEl = document.getElementById('memoryMoves');
  const statusEl = document.getElementById('memoryStatus');
  const resetBtn = document.getElementById('memoryReset');

  const symbols = ['✦','☄','◑','✧','☾','⟡','✵','◍'];
  let cards = [], flipped = [], matchedCount = 0, moves = 0, lock = false;

  function shuffle(arr){
    for(let i=arr.length-1;i>0;i--){
      const j = Math.floor(Math.random()*(i+1));
      [arr[i],arr[j]] = [arr[j],arr[i]];
    }
    return arr;
  }

  function build(){
    grid.innerHTML = '';
    cards = shuffle([...symbols, ...symbols]);
    flipped = []; matchedCount = 0; moves = 0; lock = false;
    movesEl.textContent = 0;
    statusEl.textContent = 'Find the pairs';

    cards.forEach((sym, i)=>{
      const card = document.createElement('div');
      card.className = 'memory-card';
      card.dataset.symbol = sym;
      card.dataset.index = i;
      card.textContent = '';
      card.addEventListener('click', ()=> flipCard(card));
      grid.appendChild(card);
    });
  }

  function flipCard(card){
    if(lock) return;
    if(card.classList.contains('flipped') || card.classList.contains('matched')) return;
    card.classList.add('flipped');
    card.textContent = card.dataset.symbol;
    flipped.push(card);

    if(flipped.length === 2){
      moves++;
      movesEl.textContent = moves;
      lock = true;
      const [a,b] = flipped;
      if(a.dataset.symbol === b.dataset.symbol){
        a.classList.add('matched');
        b.classList.add('matched');
        matchedCount += 2;
        flipped = [];
        lock = false;
        if(matchedCount === cards.length){
          statusEl.textContent = `Solved in ${moves} moves ✦`;
        }
      } else {
        setTimeout(()=>{
          a.classList.remove('flipped'); a.textContent = '';
          b.classList.remove('flipped'); b.textContent = '';
          flipped = [];
          lock = false;
        }, 700);
      }
    }
  }

  resetBtn.addEventListener('click', build);
  build();
})();

/* =========================================================
   GAME 2 — Wish Typer
   ========================================================= */
(function wishTyper(){
  const wordEl = document.getElementById('typerWord');
  const input = document.getElementById('typerInput');
  const scoreEl = document.getElementById('typerScore');
  const timeEl = document.getElementById('typerTime');
  const startBtn = document.getElementById('typerStart');

  const words = ['stardust','galaxy','orbit','nebula','comet','cosmos','meteor','wish','sonaaa','universe','glow','drift','aurora','celestial','moonlight'];

  let current = '', score = 0, timeLeft = 20, running = false, countdownId;

  function nextWord(){
    current = words[Math.floor(Math.random()*words.length)];
    renderWord('');
  }

  function renderWord(typedPrefix){
    let html = '';
    for(let i=0;i<current.length;i++){
      if(i < typedPrefix.length && typedPrefix[i] === current[i]){
        html += `<span class="typed">${current[i]}</span>`;
      } else {
        html += current[i];
      }
    }
    wordEl.innerHTML = html;
  }

  input.addEventListener('input', ()=>{
    if(!running) return;
    const val = input.value;
    renderWord(val);
    if(val === current){
      score++;
      scoreEl.textContent = score;
      input.value = '';
      nextWord();
    }
  });

  function startGame(){
    score = 0; scoreEl.textContent = 0;
    timeLeft = 20;
    running = true;
    input.disabled = false;
    input.value = '';
    input.focus();
    startBtn.textContent = 'Restart';
    timeEl.textContent = timeLeft + 's';
    nextWord();

    clearInterval(countdownId);
    countdownId = setInterval(()=>{
      timeLeft--;
      timeEl.textContent = timeLeft + 's';
      if(timeLeft <= 0){
        clearInterval(countdownId);
        running = false;
        input.disabled = true;
        timeEl.textContent = `Final score: ${score}`;
        wordEl.textContent = 'time\'s up ✦';
      }
    }, 1000);
  }

  startBtn.addEventListener('click', startGame);
})();
</script>
</body>
</html>
