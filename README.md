<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Para Xiomara ❤️</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:Georgia,"Times New Roman",serif;background:#09070b;color:#fff;overflow-x:hidden}
section{min-height:100svh;display:flex;align-items:center;justify-content:center;padding:45px 20px;position:relative;overflow:hidden}
.bg{position:absolute;inset:0;background:radial-gradient(circle at 20% 20%,rgba(255,83,125,.2),transparent 30%),radial-gradient(circle at 85% 75%,rgba(165,65,255,.16),transparent 30%),linear-gradient(145deg,#09070b,#21101b 55%,#08060a)}
.content{position:relative;z-index:3;width:min(760px,100%);text-align:center}
.kicker{text-transform:uppercase;letter-spacing:4px;font-size:.68rem;color:#e6a6b8;margin-bottom:18px}
h1{font-size:clamp(3rem,14vw,6.5rem);line-height:.9;margin-bottom:20px}
h1 span,.pink{color:#ff8daa}
.subtitle{color:#eadfe5;line-height:1.75;font-size:1.04rem}
.btn{border:1px solid rgba(255,255,255,.22);background:rgba(255,255,255,.08);color:#fff;padding:14px 24px;border-radius:999px;cursor:pointer;font-size:1rem;margin-top:28px;backdrop-filter:blur(12px);transition:.3s}
.btn:active{transform:scale(.96)}
.btn:hover{background:rgba(255,110,145,.18);transform:translateY(-2px)}
.primary{background:#d95373;border-color:#d95373}
.heart{font-size:4rem;animation:pulse 1.5s infinite}
@keyframes pulse{50%{transform:scale(1.12)}}

/* SOBRE */
.envelope-area{height:300px;display:flex;align-items:center;justify-content:center;cursor:pointer}
.envelope{width:min(330px,82vw);height:215px;position:relative;filter:drop-shadow(0 25px 35px #0008)}
.env-back{position:absolute;inset:0;background:#96334f;border-radius:10px}
.env-front{position:absolute;bottom:0;left:0;width:0;height:0;border-left:165px solid transparent;border-right:165px solid transparent;border-bottom:115px solid #c65270;z-index:4}
.env-flap{position:absolute;top:0;left:0;width:0;height:0;border-left:165px solid transparent;border-right:165px solid transparent;border-top:125px solid #dc6a86;transform-origin:top;z-index:5;transition:1s}
.env-paper{position:absolute;left:8%;width:84%;height:82%;top:8%;background:#fff8f1;color:#35121c;padding:25px 15px;border-radius:5px;z-index:2;display:flex;align-items:center;justify-content:center;font-size:1.1rem;transition:1s}
.envelope.open .env-flap{transform:rotateX(180deg);z-index:1}
.envelope.open .env-paper{transform:translateY(-100px)}
.tap{color:#e8b5c4;font-size:.9rem;margin-top:-8px}

/* CARTA */
.card{background:rgba(255,255,255,.065);border:1px solid rgba(255,255,255,.12);border-radius:26px;padding:32px 24px;backdrop-filter:blur(15px);box-shadow:0 20px 70px #0007;text-align:left}
.card h2{text-align:center;color:#ffacbf;font-size:2rem;margin-bottom:22px}
.letter{font-size:1.04rem;line-height:1.9;color:#eee}
.letter p{margin-bottom:17px}
.signature{text-align:right;color:#ff9db5;font-size:1.25rem;margin-top:25px}

/* RECUERDOS */
.memory-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:28px}
.memory{height:190px;border-radius:20px;position:relative;overflow:hidden;background:linear-gradient(145deg,#562139,#1a1018);border:1px solid #ffffff18;display:flex;align-items:flex-end;text-align:left;padding:18px}
.memory:before{content:"📷";position:absolute;inset:0;display:grid;place-items:center;font-size:3rem;opacity:.18}
.memory div{position:relative;z-index:2}
.memory b{font-size:1.05rem}
.memory small{display:block;color:#d9c0c8;margin-top:5px;line-height:1.4}
@media(max-width:650px){.memory-grid{grid-template-columns:1fr}.memory{height:145px}}

/* TIMELINE */
.timeline{text-align:left;margin-top:30px}
.titem{display:flex;gap:16px;margin:22px 0}
.dot{width:12px;height:12px;background:#ff7f9e;border-radius:50%;margin-top:7px;box-shadow:0 0 18px #ff6688;flex:none}
.titem h3{font-size:1.1rem;color:#ffadc0;margin-bottom:5px}
.titem p{color:#d8ccd1;line-height:1.6}

/* FINAL */
.final h2{font-size:clamp(2.2rem,9vw,4.2rem);line-height:1;margin-bottom:20px}
.answers{display:flex;justify-content:center;gap:12px;flex-wrap:wrap}
#response{min-height:55px;margin-top:24px;color:#ffb4c6;font-size:1.2rem;line-height:1.6}
.float-heart{position:fixed;bottom:-40px;z-index:50;pointer-events:none;animation:rise 4s linear forwards}
@keyframes rise{to{transform:translateY(-115vh) rotate(30deg);opacity:0}}
footer{text-align:center;color:#806f77;font-size:.75rem;padding:25px}

/* Indicador */
.down{margin-top:35px;animation:bounce 1.8s infinite;color:#dba5b4;font-size:.9rem}
@keyframes bounce{50%{transform:translateY(7px)}}
</style>
</head>

<body>

<section id="inicio">
<div class="bg"></div>
<div class="content">
  <div class="heart">♡</div>
  <div class="kicker">Esta página es solamente para ti</div>
  <h1>Hola,<br><span>Xiomara</span> ❤️</h1>
  <p class="subtitle">Preparé algo pequeño para ti... pero antes de abrirlo, quiero que sepas que cada detalle de esta página fue pensado con mucho cariño.</p>
  <button class="btn primary" onclick="go('sobre')">Tengo algo para ti 💌</button>
  <div class="down">↓ hay una sorpresa esperándote ↓</div>
</div>
</section>

<section id="sobre">
<div class="bg"></div>
<div class="content">
  <div class="kicker">Primera sorpresa</div>
  <h2 style="font-size:2rem;margin-bottom:5px">Un mensaje solo para ti</h2>
  <p class="subtitle">Toca el sobre.</p>
  <div class="envelope-area" onclick="openEnvelope()">
    <div class="envelope" id="envelope">
      <div class="env-back"></div>
      <div class="env-paper">Xiomara, hay algo que quiero decirte... ❤️</div>
      <div class="env-flap"></div>
      <div class="env-front"></div>
    </div>
  </div>
  <div class="tap" id="tap">Toca el sobre para abrirlo</div>
  <button class="btn" id="continueBtn" style="display:none" onclick="go('carta')">Ahora sí, quiero leerla →</button>
</div>
</section>

<section id="carta">
<div class="bg"></div>
<div class="content">
<div class="card">
  <div class="kicker">Para Xiomara</div>
  <h2>Lo que quiero decirte</h2>
  <div class="letter">
    <p>Amor,</p>
    <p>Hoy quería hacer algo diferente. No quería simplemente mandarte un mensaje por WhatsApp y ya. Quería preparar un pequeño lugar donde pudieras encontrar unas palabras hechas especialmente para ti.</p>
    <p>Xiomara, desde que llegaste a mi vida has dejado momentos que guardo con mucho cariño. Las risas, las conversaciones, las ocurrencias y hasta esos pequeños momentos que quizá parecen simples, para mí terminan siendo parte de nuestra historia.</p>
    <p>No voy a decirte que todo siempre será perfecto, porque una relación también está hecha de aprender, entenderse y seguir creciendo. Pero sí puedo decirte que valoro muchísimo todo lo que hemos vivido y la persona que eres.</p>
    <p>Quiero seguir conociéndote, seguir compartiendo contigo y seguir creando recuerdos que algún día podamos mirar hacia atrás y decir: <i>“qué bonito todo lo que vivimos juntos”.</i></p>
    <p>Gracias por estar, por ser tú y por formar parte de mi vida. Esta página puede terminar aquí, pero espero que nuestra historia tenga todavía muchísimas páginas por escribir.</p>
    <div class="signature">Con mucho cariño,<br><b>Erick ❤️</b></div>
  </div>
</div>
<button class="btn primary" onclick="go('recuerdos')">Continuar nuestra historia ✨</button>
</div>
</section>

<section id="recuerdos">
<div class="bg"></div>
<div class="content">
  <div class="kicker">Capítulos que me gustan</div>
  <h2 style="font-size:2.5rem">Nuestros recuerdos</h2>
  <p class="subtitle">Esta parte está preparada para que después pongamos fotos reales de ustedes.</p>
  <div class="memory-grid">
    <div class="memory"><div><b>Una sonrisa</b><small>Uno de esos momentos que quisiera guardar para siempre.</small></div></div>
    <div class="memory"><div><b>Nuestras locuras</b><small>Porque contigo hasta lo más sencillo puede convertirse en un recuerdo.</small></div></div>
    <div class="memory"><div><b>Un momento especial</b><small>Uno más de tantos que todavía nos quedan por vivir.</small></div></div>
  </div>
  <button class="btn" onclick="go('historia')">Hay algo más ↓</button>
</div>
</section>

<section id="historia">
<div class="bg"></div>
<div class="content">
  <div class="kicker">Y si seguimos...</div>
  <h2 style="font-size:2.6rem">Todavía quedan capítulos.</h2>
  <div class="timeline">
    <div class="titem"><div class="dot"></div><div><h3>Lo que ya vivimos</h3><p>Todo lo que nos ha traído hasta aquí forma parte de nuestra historia.</p></div></div>
    <div class="titem"><div class="dot"></div><div><h3>Lo que estamos viviendo</h3><p>Los días normales, las risas y esos momentos que solamente nosotros entendemos.</p></div></div>
    <div class="titem"><div class="dot"></div><div><h3>Lo que todavía falta</h3><p>Viajes, aventuras, fotos, abrazos, conversaciones y muchísimas historias más.</p></div></div>
  </div>
  <button class="btn primary" onclick="go('final')">Llegamos al final... ❤️</button>
</div>
</section>

<section id="final">
<div class="bg"></div>
<div class="content">
  <div class="heart">♥</div>
  <div class="kicker">Última pregunta</div>
  <h2>¿Seguimos escribiendo nuestra historia, Xiomara?</h2>
  <p class="subtitle">Porque yo todavía tengo muchas páginas que quisiera llenar contigo.</p>
  <div class="answers">
    <button class="btn primary" onclick="yes()">Sí, contigo ❤️</button>
    <button class="btn" onclick="maybe()">Obviamente 😌</button>
  </div>
  <div id="response"></div>
</div>
</section>

<footer>Hecho especialmente para Xiomara · Erick ❤️</footer>

<script>
function go(id){
  document.getElementById(id).scrollIntoView({behavior:"smooth",block:"start"});
}

function openEnvelope(){
  const e=document.getElementById("envelope");
  e.classList.add("open");
  document.getElementById("tap").textContent="La carta está abierta ❤️";
  document.getElementById("continueBtn").style.display="inline-block";
  setTimeout(()=>go("carta"),1200);
}

function hearts(n=45){
  for(let i=0;i<n;i++){
    setTimeout(()=>{
      const h=document.createElement("div");
      h.className="float-heart";
      h.textContent=["❤️","💕","💗","💖","♥","✨"][Math.floor(Math.random()*6)];
      h.style.left=Math.random()*100+"vw";
      h.style.fontSize=(16+Math.random()*26)+"px";
      h.style.animationDuration=(3+Math.random()*3)+"s";
      document.body.appendChild(h);
      setTimeout(()=>h.remove(),6500);
    },i*65);
  }
}

function yes(){
  document.getElementById("response").innerHTML="Entonces queda escrito aquí: <b>seguimos. ❤️</b><br>Y espero que esta historia nos regale muchísimos momentos más.";
  hearts(60);
}
function maybe(){
  document.getElementById("response").innerHTML="Sabía que ibas a decir eso... 😌❤️<br>Entonces seguimos escribiendo.";
  hearts(40);
}
</script>
</body>
</html>
