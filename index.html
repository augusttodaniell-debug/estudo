<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Registro de estudos</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500;600&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#EEF1E7;
    --grid-line:#D6DBC5;
    --panel:#FCFDF9;
    --ink:#1D2B36;
    --ink-soft:#5B6B63;
    --line:#C7CDB9;
    --copper:#BE6E2E;
    --copper-soft:#F1DEC9;
    --teal:#2E6B5A;
    --teal-soft:#DCEBE3;
    --blue:#2C4A6E;
    --blue-soft:#DCE6F0;
    --danger:#9E3B32;
    --radius:10px;
  }

  *{box-sizing:border-box;}

  body{
    margin:0;
    background-color:var(--bg);
    background-image:
      linear-gradient(var(--grid-line) 1px, transparent 1px),
      linear-gradient(90deg, var(--grid-line) 1px, transparent 1px);
    background-size:28px 28px;
    color:var(--ink);
    font-family:'IBM Plex Sans', sans-serif;
    padding:32px 20px 140px;
    min-height:100vh;
  }

  .wrap{ max-width:980px; margin:0 auto; }

  header{
    display:flex;
    justify-content:space-between;
    align-items:flex-end;
    flex-wrap:wrap;
    gap:16px;
    border-bottom:2px solid var(--ink);
    padding-bottom:16px;
    margin-bottom:28px;
  }

  .header-label{
    font-family:'IBM Plex Mono', monospace;
    font-size:11px;
    letter-spacing:0.14em;
    text-transform:uppercase;
    color:var(--ink-soft);
    margin:0 0 4px;
  }

  h1{
    font-family:'IBM Plex Mono', monospace;
    font-size:26px;
    font-weight:600;
    margin:0;
    letter-spacing:-0.01em;
  }

  .progress-block{ text-align:right; font-family:'IBM Plex Mono', monospace; }
  .progress-num{ font-size:26px; font-weight:600; }
  .progress-label{ font-size:11px; color:var(--ink-soft); text-transform:uppercase; letter-spacing:0.1em; }

  .grid{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(260px, 1fr));
    gap:16px;
  }

  .day-card{
    background:var(--panel);
    border:1px solid var(--line);
    border-radius:var(--radius);
    padding:16px 16px 14px;
    position:relative;
  }

  .day-card::before{
    content:'';
    position:absolute;
    top:0; left:16px; right:16px;
    height:1px;
    background:var(--line);
  }

  .day-head{
    display:flex;
    justify-content:space-between;
    align-items:baseline;
    margin-bottom:12px;
  }

  .day-name{
    font-family:'IBM Plex Mono', monospace;
    font-size:14px;
    font-weight:600;
    text-transform:uppercase;
    letter-spacing:0.06em;
  }

  .day-index{
    font-family:'IBM Plex Mono', monospace;
    font-size:11px;
    color:var(--ink-soft);
  }

  .item{
    display:flex;
    align-items:center;
    gap:10px;
    padding:9px 8px;
    border-radius:8px;
    margin-bottom:6px;
    transition:background 0.15s ease;
  }

  .item:hover{ background:rgba(0,0,0,0.03); }

  .check{
    width:18px; height:18px;
    border:1.5px solid var(--ink-soft);
    border-radius:4px;
    flex-shrink:0;
    display:flex;
    align-items:center;
    justify-content:center;
    cursor:pointer;
    background:var(--panel);
  }

  .check.checked{
    background:var(--teal);
    border-color:var(--teal);
  }

  .check.checked::after{
    content:'';
    width:8px; height:5px;
    border-left:2px solid #fff;
    border-bottom:2px solid #fff;
    transform:rotate(-45deg) translate(1px,-1px);
  }

  .item-label{
    flex:1;
    font-size:14px;
    cursor:pointer;
    user-select:none;
  }

  .item.done .item-label{
    color:var(--ink-soft);
    text-decoration:line-through;
  }

  .tag{
    font-family:'IBM Plex Mono', monospace;
    font-size:10px;
    padding:2px 7px;
    border-radius:5px;
    letter-spacing:0.03em;
  }

  .tag-mat{ background:var(--blue-soft); color:var(--blue); }
  .tag-fis{ background:var(--teal-soft); color:var(--teal); }
  .tag-hum{ background:var(--copper-soft); color:var(--copper); }
  .tag-rev{ background:#E6E4DA; color:var(--ink-soft); }
  .tag-out{ background:#EFE3EC; color:#7A3B63; }

  .timer-btn{
    width:26px; height:26px;
    border-radius:50%;
    border:1.5px solid var(--line);
    background:var(--panel);
    display:flex;
    align-items:center;
    justify-content:center;
    cursor:pointer;
    flex-shrink:0;
    color:var(--ink-soft);
  }

  .timer-btn:hover{ border-color:var(--copper); color:var(--copper); }
  .timer-btn.active{ background:var(--copper); border-color:var(--copper); color:#fff; }

  .timer-btn svg{ width:13px; height:13px; }

  /* Timer dock */
  #dock{
    position:fixed;
    left:0; right:0; bottom:0;
    display:flex;
    justify-content:center;
    pointer-events:none;
    padding:16px;
  }

  #dock-inner{
    pointer-events:auto;
    background:var(--ink);
    color:#fff;
    border-radius:16px;
    padding:14px 20px;
    display:flex;
    align-items:center;
    gap:18px;
    box-shadow:0 8px 28px rgba(0,0,0,0.22);
    max-width:560px;
    width:100%;
    transform:translateY(140%);
    transition:transform 0.28s ease;
  }

  #dock-inner.open{ transform:translateY(0); }

  .dial{ position:relative; width:56px; height:56px; flex-shrink:0; }
  .dial svg{ width:56px; height:56px; transform:rotate(-90deg); }
  .dial-bg{ fill:none; stroke:rgba(255,255,255,0.15); stroke-width:5; }
  .dial-fg{ fill:none; stroke:var(--copper); stroke-width:5; stroke-linecap:round; transition:stroke-dashoffset 1s linear; }
  .dial-time{
    position:absolute; inset:0;
    display:flex; align-items:center; justify-content:center;
    font-family:'IBM Plex Mono', monospace;
    font-size:12px; font-weight:500;
  }

  .dock-info{ flex:1; min-width:0; }
  .dock-subject{ font-size:14px; font-weight:500; white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
  .dock-meta{ font-family:'IBM Plex Mono', monospace; font-size:11px; color:rgba(255,255,255,0.55); margin-top:2px; }

  .dock-controls{ display:flex; gap:6px; align-items:center; flex-shrink:0; }

  .dock-controls select{
    font-family:'IBM Plex Mono', monospace;
    font-size:11px;
    background:rgba(255,255,255,0.08);
    color:#fff;
    border:1px solid rgba(255,255,255,0.2);
    border-radius:7px;
    padding:5px 6px;
  }

  .dock-btn{
    width:34px; height:34px;
    border-radius:50%;
    border:none;
    background:rgba(255,255,255,0.12);
    color:#fff;
    display:flex; align-items:center; justify-content:center;
    cursor:pointer;
  }

  .dock-btn:hover{ background:rgba(255,255,255,0.22); }
  .dock-btn svg{ width:14px; height:14px; }

  .dock-close{ background:transparent; color:rgba(255,255,255,0.5); width:24px; height:24px; }

  footer{
    max-width:980px;
    margin:32px auto 0;
    font-family:'IBM Plex Mono', monospace;
    font-size:11px;
    color:var(--ink-soft);
    text-align:center;
  }

  @media (max-width:520px){
    h1{ font-size:21px; }
    header{ align-items:flex-start; }
    .progress-block{ text-align:left; }
  }
</style>
</head>
<body>

<div class="wrap">
  <header>
    <div>
      <p class="header-label">Registro semanal &mdash; 2h/dia</p>
      <h1>Cronograma de estudos</h1>
    </div>
    <div class="progress-block">
      <div class="progress-num" id="progress-num">0/16</div>
      <div class="progress-label">Blocos concluidos</div>
    </div>
  </header>

  <div class="grid" id="grid"></div>
</div>

<footer>Toque num item para marcar. Toque no circulo pra iniciar o cronometro daquele bloco.</footer>

<div id="dock">
  <div id="dock-inner">
    <div class="dial">
      <svg viewBox="0 0 56 56">
        <circle class="dial-bg" cx="28" cy="28" r="24"></circle>
        <circle class="dial-fg" id="dial-fg" cx="28" cy="28" r="24" stroke-dasharray="150.8" stroke-dashoffset="0"></circle>
      </svg>
      <div class="dial-time" id="dial-time">25:00</div>
    </div>
    <div class="dock-info">
      <div class="dock-subject" id="dock-subject">&mdash;</div>
      <div class="dock-meta" id="dock-meta">parado</div>
    </div>
    <div class="dock-controls">
      <select id="duration-select">
        <option value="1500">25 min</option>
        <option value="3000">50 min</option>
        <option value="3600">60 min</option>
      </select>
      <button class="dock-btn" id="dock-toggle" aria-label="Iniciar ou pausar">
        <svg id="icon-play" viewBox="0 0 24 24" fill="currentColor"><path d="M8 5v14l11-7z"/></svg>
        <svg id="icon-pause" viewBox="0 0 24 24" fill="currentColor" style="display:none;"><path d="M6 5h4v14H6zm8 0h4v14h-4z"/></svg>
      </button>
      <button class="dock-btn" id="dock-reset" aria-label="Reiniciar">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 12a9 9 0 1 0 3-6.7"/><path d="M3 4v5h5"/></svg>
      </button>
      <button class="dock-btn dock-close" id="dock-close" aria-label="Fechar">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M6 6l12 12M18 6L6 18"/></svg>
      </button>
    </div>
  </div>
</div>

<script>
const DAYS = [
  { name: 'Segunda', items: [
    { id:'seg-mat', label:'Matematica \u2014 TQM', tag:'mat' },
    { id:'seg-fis', label:'Fisica \u2014 TQF', tag:'fis' },
  ]},
  { name: 'Terca', items: [
    { id:'ter-por', label:'Portugues \u2014 Novissima Gramatica', tag:'hum' },
    { id:'ter-qui', label:'Quimica \u2014 Feltre', tag:'hum' },
  ]},
  { name: 'Quarta', items: [
    { id:'qua-mat', label:'Matematica \u2014 TQM', tag:'mat' },
    { id:'qua-fis', label:'Fisica \u2014 TQF', tag:'fis' },
  ]},
  { name: 'Quinta', items: [
    { id:'qui-por', label:'Portugues \u2014 Novissima Gramatica', tag:'hum' },
    { id:'qui-qui', label:'Quimica \u2014 Feltre', tag:'hum' },
  ]},
  { name: 'Sexta', items: [
    { id:'sex-revex', label:'Revisao \u2014 TQM/TQF', tag:'rev' },
    { id:'sex-revhu', label:'Revisao \u2014 portugues/quimica', tag:'rev' },
  ]},
  { name: 'Sabado', items: [
    { id:'sab-ing', label:'Ingles', tag:'out' },
    { id:'sab-fog', label:'Foguetes', tag:'out' },
  ]},
  { name: 'Domingo', items: [
    { id:'dom-sim', label:'Simulado', tag:'out' },
    { id:'dom-pal', label:'Palavra', tag:'out' },
  ]},
];

const TAG_LABEL = { mat:'MAT', fis:'FIS', hum:'HUM', rev:'REV', out:'EXT' };

const grid = document.getElementById('grid');
let checkedState = {};

function playIcon(id){
  return `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="9"/><path d="M10 9l5 3-5 3z" fill="currentColor" stroke="none"/></svg>`;
}

function render(){
  grid.innerHTML = '';
  let doneCount = 0, total = 0;
  DAYS.forEach((day, di) => {
    const card = document.createElement('div');
    card.className = 'day-card';

    const head = document.createElement('div');
    head.className = 'day-head';
    head.innerHTML = `<span class="day-name">${day.name}</span><span class="day-index">0${di+1}</span>`;
    card.appendChild(head);

    day.items.forEach(it => {
      total++;
      const isChecked = !!checkedState[it.id];
      if (isChecked) doneCount++;

      const row = document.createElement('div');
      row.className = 'item' + (isChecked ? ' done' : '');

      const check = document.createElement('div');
      check.className = 'check' + (isChecked ? ' checked' : '');
      check.onclick = () => toggleCheck(it.id);

      const label = document.createElement('div');
      label.className = 'item-label';
      label.textContent = it.label;
      label.onclick = () => toggleCheck(it.id);

      const tag = document.createElement('span');
      tag.className = 'tag tag-' + it.tag;
      tag.textContent = TAG_LABEL[it.tag];

      const timerBtn = document.createElement('div');
      timerBtn.className = 'timer-btn' + (currentItem && currentItem.id === it.id ? ' active' : '');
      timerBtn.innerHTML = playIcon();
      timerBtn.onclick = () => startTimerFor(it, day.name);

      row.appendChild(check);
      row.appendChild(label);
      row.appendChild(tag);
      row.appendChild(timerBtn);
      card.appendChild(row);
    });

    grid.appendChild(card);
  });

  document.getElementById('progress-num').textContent = `${doneCount}/${total}`;
}

async function toggleCheck(id){
  checkedState[id] = !checkedState[id];
  render();
  try{
    await window.storage.set('checklist-state', JSON.stringify(checkedState), false);
  }catch(e){ console.error('Falha ao salvar', e); }
}

async function loadState(){
  try{
    const res = await window.storage.get('checklist-state', false);
    if (res && res.value) checkedState = JSON.parse(res.value);
  }catch(e){
    checkedState = {};
  }
  render();
}

// --- Timer ---
let currentItem = null;
let currentDayName = '';
let remaining = 1500;
let duration = 1500;
let timerHandle = null;
let running = false;

const dockInner = document.getElementById('dock-inner');
const dockSubject = document.getElementById('dock-subject');
const dockMeta = document.getElementById('dock-meta');
const dialTime = document.getElementById('dial-time');
const dialFg = document.getElementById('dial-fg');
const iconPlay = document.getElementById('icon-play');
const iconPause = document.getElementById('icon-pause');
const durationSelect = document.getElementById('duration-select');
const CIRC = 150.8;

function fmt(sec){
  const m = Math.floor(sec/60).toString().padStart(2,'0');
  const s = Math.floor(sec%60).toString().padStart(2,'0');
  return `${m}:${s}`;
}

function updateDial(){
  dialTime.textContent = fmt(remaining);
  const frac = Math.max(0, remaining/duration);
  dialFg.setAttribute('stroke-dashoffset', String(CIRC * (1-frac)));
}

function startTimerFor(item, dayName){
  currentItem = item;
  currentDayName = dayName;
  duration = parseInt(durationSelect.value, 10);
  remaining = duration;
  running = false;
  clearInterval(timerHandle);
  dockSubject.textContent = item.label;
  dockMeta.textContent = dayName + ' \u00b7 parado';
  updateDial();
  dockInner.classList.add('open');
  iconPlay.style.display = '';
  iconPause.style.display = 'none';
  render();
}

function toggleRun(){
  if (!currentItem) return;
  running = !running;
  if (running){
    iconPlay.style.display = 'none';
    iconPause.style.display = '';
    dockMeta.textContent = currentDayName + ' \u00b7 em andamento';
    timerHandle = setInterval(() => {
      remaining -= 1;
      if (remaining <= 0){
        remaining = 0;
        updateDial();
        clearInterval(timerHandle);
        running = false;
        iconPlay.style.display = '';
        iconPause.style.display = 'none';
        dockMeta.textContent = currentDayName + ' \u00b7 concluido';
        return;
      }
      updateDial();
    }, 1000);
  } else {
    clearInterval(timerHandle);
    iconPlay.style.display = '';
    iconPause.style.display = 'none';
    dockMeta.textContent = currentDayName + ' \u00b7 pausado';
  }
}

document.getElementById('dock-toggle').onclick = toggleRun;
document.getElementById('dock-reset').onclick = () => {
  clearInterval(timerHandle);
  running = false;
  remaining = duration;
  iconPlay.style.display = '';
  iconPause.style.display = 'none';
  dockMeta.textContent = currentDayName + ' \u00b7 parado';
  updateDial();
};
document.getElementById('dock-close').onclick = () => {
  clearInterval(timerHandle);
  running = false;
  currentItem = null;
  dockInner.classList.remove('open');
  render();
};
durationSelect.onchange = () => {
  if (!currentItem) return;
  duration = parseInt(durationSelect.value, 10);
  remaining = duration;
  clearInterval(timerHandle);
  running = false;
  iconPlay.style.display = '';
  iconPause.style.display = 'none';
  dockMeta.textContent = currentDayName + ' \u00b7 parado';
  updateDial();
};

loadState();
</script>
</body>
</html>
