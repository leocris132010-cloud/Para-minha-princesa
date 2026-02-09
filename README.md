<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Leonardo ❤️ Manuela</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial, sans-serif;
}

body{
  min-height:100vh;
  background:radial-gradient(circle at top,#3a215c,#0b051a);
  color:#fff;
  overflow-x:hidden;
  text-align:center;
}

/* SEÇÕES */
section{
  padding:50px 20px;
}

/* TÍTULOS */
h1{ font-size:2.4em; }
h1 span{ color:#d9b3ff; }
h2{ color:#d9b3ff; margin-bottom:25px; }

/* CONTADOR ESTILIZADO */
.counter{
  display:flex;
  flex-direction:column;
  align-items:center;
  gap:20px;
  margin:40px 0;
}

.time-cards{
  display:flex;
  gap:20px;
}

.time-card{
  background:rgba(217,179,255,0.2);
  padding:20px 30px;
  border-radius:18px;
  box-shadow:0 0 15px rgba(217,179,255,.5);
  min-width:80px;
}

.time-card span{
  display:block;
  font-size:2em;
  font-weight:bold;
  color:#fff;
}

.time-card small{
  display:block;
  margin-top:5px;
  font-size:0.9em;
  color:#d9b3ff;
}

.total{
  margin-top:15px;
  font-size:1.2em;
  color:#d9b3ff;
  font-weight:bold;
}

/* SEPARADOR */
.separador{
  display:flex;
  align-items:center;
  justify-content:center;
  gap:15px;
  margin:70px auto;
  max-width:380px;
}
.separador::before,
.separador::after{
  content:"";
  flex:1;
  height:1px;
  background:linear-gradient(to right,transparent,#d9b3ff,transparent);
}
.separador span{
  font-size:1.5em;
}

/* MÚSICA */
.music iframe{
  border-radius:18px;
  box-shadow:0 0 20px rgba(217,179,255,.5);
  height:300px; /* altura maior */
  width:100%;
}

/* MOMENTOS */
.momentos{
  max-width:360px;
  margin:0 auto;
}
.galeria{
  display:flex;
  flex-direction:column;
  gap:25px;
}
.galeria img{
  width:100%;
  border-radius:18px;
  box-shadow:0 0 20px rgba(217,179,255,.4);
}
.texto-momento{
  padding:20px;
  background:rgba(255,255,255,.08);
  border-radius:18px;
  font-size:1.15em;
  line-height:1.6em;
  box-shadow:0 0 18px rgba(217,179,255,.3);
}

/* CARTA */
.carta{
  max-width:750px;
  margin:0 auto;
  padding:30px;
  background:rgba(255,255,255,.08);
  border-radius:22px;
  font-size:1.15em;
  line-height:1.7em;
  box-shadow:0 0 25px rgba(217,179,255,.45);
  text-align:left;
  white-space:pre-wrap;
}

/* LINHA DO TEMPO */
.historia{
  max-width:360px;
  margin:0 auto;
  position:relative;
  padding-left:20px;
}

.historia::before{
  content:"";
  position:absolute;
  left:50%;
  transform:translateX(-50%);
  top:0;
  bottom:0;
  width:2px;
  background:linear-gradient(to bottom,transparent,#d9b3ff,transparent);
}

.evento{
  position:relative;
  margin-bottom:60px;
  width:50%;
  padding:0 20px;
}

.evento:nth-child(odd){
  left:0;
  text-align:right;
}
.evento:nth-child(even){
  left:50%;
  text-align:left;
}

.evento::before{
  content:"❤️";
  position:absolute;
  top:10px;
  font-size:1.2em;
}

.evento:nth-child(odd)::before{
  right:-15px;
}
.evento:nth-child(even)::before{
  left:-15px;
}

.data-topo{
  margin-bottom:10px;
  font-size:.95em;
  opacity:.9;
}

.evento img{
  width:100%;
  border-radius:20px;
  box-shadow:0 0 22px rgba(217,179,255,.5);
}

</style>
</head>

<body>

<!-- TOPO -->
<section>
  <h1>Leonardo <span>❤️</span> Manuela</h1>
  <p>Nosso amor cresce no tempo e nos detalhes ✨</p>
</section>

<!-- CONTADOR ESTILIZADO -->
<section class="counter">
  <div class="time-cards">
    <div class="time-card">
      <span id="y">0</span>
      <small>Anos</small>
    </div>
    <div class="time-card">
      <span id="m">0</span>
      <small>Meses</small>
    </div>
    <div class="time-card">
      <span id="d">0</span>
      <small>Dias</small>
    </div>
  </div>
  <div class="total" id="total">✨ 0 dias de amor ✨</div>
</section>

<div class="separador"><span>🎵</span></div>

<!-- MÚSICA -->
<section class="music">
  <h2>Nossa Música</h2>
  <iframe
    src="https://open.spotify.com/embed/track/6ZnVSNNryDmF0w1j73Fndd"
    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture">
  </iframe>
</section>

<div class="separador"><span>📸</span></div>

<!-- MOMENTOS -->
<section class="momentos">
  <h2>💜 Momentos Marcantes 💜</h2>
  <div class="galeria">
    <img src="https://lh3.googleusercontent.com/d/1BEuF9lI8TEFkyNEw9mZ1FtbRiPF1FPpO">

    <div class="texto-momento">
      Todos os momentos que nós passamos foram marcantes,  
      mas existem alguns que estão cravados na memória  
      até o dia da nossa morte.
    </div>

    <img src="https://lh3.googleusercontent.com/d/1NJ6vGmb_82ZwYbBCJFKQDLRkFgrTs3UF">
  </div>
</section>

<div class="separador"><span>💌</span></div>

<!-- CARTA -->
<section>
  <h2>Minha Carta</h2>
  <div class="carta">
Eu nunca namorei antes, nunca fui muito bom nessas coisas. Sempre fui tímido, sem experiência, sem alguém pra me ensinar como tudo funciona. Por isso, todos os dias eu tento aprender e melhorar por você. Em gestos simples, como puxar a cadeira pra você sentar, em te tratar com cuidado, em tentar passar o máximo de confiança possível pra que você nunca se sinta desconfortável ao meu lado.

Nunca tive alguém pra conversar sobre relacionamento, sobre amor ou sobre como cuidar de alguém. A única coisa que eu sempre levei comigo foi o que minha mãe me ensinou: mulher se trata com respeito e carinho. É isso que eu tento fazer todos os dias, mesmo errando às vezes.

Eu sei que não sou perfeito, sei que tenho defeitos e que erro bastante. Mas tudo o que faço é com verdade. Eu me esforço, eu tento, eu aprendo. Porque, mesmo sem saber tudo, eu quero ser o melhor pra você. Quero construir algo bonito, com respeito, cuidado e amor, pensando sempre no nosso futuro e fazendo o meu melhor pra que ele seja o melhor possível.

Tenho tanto orgulho de você, de quem você é, do que você conquista e da forma como me inspira todos os dias. E mesmo que o tempo passe, eu quero que nosso amor seja eterno, que nosso namoro dure não só por agora, mas pela vida inteira, como se cada momento juntos fosse só o começo de uma história sem fim.

Para sempre nós dois. 💜
  </div>
</section>

<div class="separador"><span>🕒</span></div>

<!-- LINHA DO TEMPO -->
<section class="historia">
  <h2>Nossa História</h2>

  <div class="evento">
    <div class="data-topo">📅 04/11/2025</div>
    <img src="https://lh3.googleusercontent.com/d/1JIXp05JmHpV13ropozDPM1My_nFS8-UX">
  </div>

  <div class="evento">
    <div class="data-topo">📅 06/12/2025</div>
    <img src="https://lh3.googleusercontent.com/d/1z70xF60UAySFFronGG1lb5mfb2-d7MBD">
  </div>

  <div class="evento">
    <div class="data-topo">📅 12/12/2025</div>
    <img src="https://lh3.googleusercontent.com/d/1-ZvtF5A3cUEDtyyRXBXFTaJW1FjpHG-_">
  </div>

  <div class="evento">
    <div class="data-topo">📅 31/12/2025</div>
    <img src="https://drive.google.com/uc?export=view&id=1srETpgjLRwRIBeWzf2wARt7Tq2f0hnA0">
  </div>

</section>

<script>
const start = new Date(2025,11,6);

setInterval(()=>{
  const n = new Date();
  let y = n.getFullYear() - start.getFullYear();
  let m = n.getMonth() - start.getMonth();
  let d = n.getDate() - start.getDate();

  if(d < 0){
    m--;
    d += new Date(n.getFullYear(), n.getMonth(), 0).getDate();
  }
  if(m < 0){
    y--;
    m += 12;
  }

  document.getElementById('y').innerText = y;
  document.getElementById('m').innerText = m;
  document.getElementById('d').innerText = d;

  document.getElementById('total').innerText =
    `✨ ${Math.floor((n-start)/86400000)} dias de amor ✨`;
},1000);
</script>

</body>
</html>
