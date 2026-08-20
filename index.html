<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Spare/Ware Open — Tournament Desk</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;600;700&family=Inter:wght@400;500;600&family=Space+Mono:wght@400;700&display=swap');

  :root{
    --bg: #0A0C12;
    --panel: #12151E;
    --panel-2: #171B27;
    --cyan: #3FD8E3;
    --violet: #9B5CFF;
    --magenta: #E23FC4;
    --grad: linear-gradient(135deg, var(--cyan), var(--violet) 55%, var(--magenta));
    --ink: #ECEEF5;
    --text-dim: #767E92;
    --danger: #E8548A;
    --ok: #3FE3B0;
    --radius: 3px;
  }

  *{ box-sizing: border-box; margin:0; padding:0; }

  body{
    background: var(--bg);
    color: var(--ink);
    font-family: 'Inter', sans-serif;
    min-height: 100vh;
    background-image:
      radial-gradient(ellipse 900px 500px at 15% -10%, rgba(63,216,227,0.08), transparent 60%),
      radial-gradient(ellipse 900px 500px at 85% 10%, rgba(226,63,196,0.07), transparent 60%);
    background-attachment: fixed;
  }

  header{
    background: var(--panel);
    border-bottom: 1px solid rgba(255,255,255,0.08);
    padding: 34px 24px 22px;
    text-align: center;
    position: relative;
    overflow: hidden;
  }

  header::after{
    content: "";
    position: absolute;
    top: -40%; left: 50%;
    width: 2px; height: 220%;
    background: var(--grad);
    opacity: 0.35;
    transform: translateX(-50%) rotate(20deg);
  }

  .logo-mark{
    width: 40px; height: 40px;
    margin: 0 auto 14px;
    display: block;
  }

  h1{
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 700;
    font-size: clamp(26px, 5vw, 42px);
    letter-spacing: -0.5px;
    text-transform: uppercase;
    color: var(--ink);
    position: relative;
  }
  h1 span{
    background: var(--grad);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
  }

  .subtitle{
    font-family: 'Space Mono', monospace;
    font-size: 13px;
    color: var(--text-dim);
    margin-top: 6px;
    letter-spacing: 2px;
    text-transform: uppercase;
  }

  nav{
    display: flex;
    justify-content: center;
    gap: 4px;
    background: var(--panel);
    padding: 0 12px;
    border-bottom: 1px solid rgba(255,255,255,0.08);
    flex-wrap: wrap;
  }

  nav button{
    background: none;
    border: none;
    color: var(--text-dim);
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 600;
    font-size: 14px;
    letter-spacing: .3px;
    text-transform: uppercase;
    padding: 14px 18px;
    cursor: pointer;
    border-bottom: 2px solid transparent;
    transition: color .15s, border-color .15s;
  }
  nav button:hover{ color: var(--ink); }
  nav button.active{
    color: var(--ink);
    border-image: var(--grad) 1;
    border-bottom: 2px solid;
    border-bottom-color: var(--violet);
  }

  main{
    max-width: 920px;
    margin: 0 auto;
    padding: 32px 20px 80px;
  }

  .panel{ display: none; animation: fade .2s ease; }
  .panel.active{ display: block; }
  @keyframes fade{ from{opacity:0; transform: translateY(4px);} to{opacity:1; transform: translateY(0);} }

  .card{
    background: var(--panel);
    border: 1px solid rgba(255,255,255,0.08);
    border-radius: var(--radius);
    padding: 24px;
    margin-bottom: 20px;
    position: relative;
    clip-path: polygon(0 0, calc(100% - 18px) 0, 100% 18px, 100% 100%, 0 100%);
  }
  .card::before{
    content: "";
    position: absolute;
    top: 0; right: 0;
    width: 18px; height: 18px;
    background: var(--grad);
    opacity: 0.5;
    clip-path: polygon(100% 0, 0 0, 100% 100%);
  }

  .card h2{
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 600;
    letter-spacing: .2px;
    font-size: 19px;
    margin-bottom: 4px;
    color: var(--ink);
  }
  .card .hint{ color: var(--text-dim); font-size: 13px; margin-bottom: 18px; }

  label{
    display:block;
    font-size: 12px;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--text-dim);
    margin-bottom: 6px;
    margin-top: 16px;
  }
  label:first-of-type{ margin-top: 0; }

  input[type=text], input[type=number], input[type=datetime-local], textarea, select{
    width: 100%;
    background: var(--bg);
    border: 1px solid rgba(255,255,255,0.12);
    color: var(--ink);
    padding: 10px 12px;
    border-radius: var(--radius);
    font-family: 'Inter', sans-serif;
    font-size: 15px;
  }
  input:focus, textarea:focus, select:focus{
    outline: 2px solid var(--violet);
    outline-offset: 1px;
  }

  .games-grid{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 12px;
  }
  .games-grid input{ text-align: center; font-family: 'Space Mono', monospace; font-size: 18px; }

  .total-readout{
    margin-top: 16px;
    font-family: 'Space Mono', monospace;
    font-size: 15px;
    color: var(--text-dim);
  }
  .total-readout b{
    background: var(--grad);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    font-size: 20px;
  }

  .checklist{ display: flex; flex-direction: column; gap: 10px; margin-top: 4px; }
  .checklist label{
    display: flex; align-items: center; gap: 10px;
    text-transform: none; letter-spacing: 0; font-size: 14px; color: var(--ink);
    margin: 0; cursor: pointer;
  }
  .checklist input[type=checkbox]{ width: 18px; height: 18px; accent-color: var(--violet); }

  .btn{
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: .5px;
    font-size: 14px;
    border: none;
    border-radius: var(--radius);
    padding: 12px 22px;
    cursor: pointer;
    transition: filter .15s, transform .1s;
  }
  .btn:hover{ filter: brightness(1.12); }
  .btn:active{ transform: scale(0.98); }
  .btn-primary{ background: var(--grad); color: #0A0C12; }
  .btn-ghost{ background: transparent; color: var(--text-dim); border: 1px solid rgba(255,255,255,0.2); }
  .btn-small{ padding: 6px 12px; font-size: 12px; }

  .row{ display:flex; gap: 12px; margin-top: 20px; flex-wrap: wrap; }

  table{ width: 100%; border-collapse: collapse; font-size: 14px; }
  th{
    text-align: left; font-family: 'Space Grotesk', sans-serif; font-weight: 600; text-transform: uppercase;
    letter-spacing: .5px; font-size: 12px; color: var(--text-dim);
    padding: 10px 8px; border-bottom: 2px solid rgba(255,255,255,0.15);
  }
  td{ padding: 10px 8px; border-bottom: 1px solid rgba(255,255,255,0.06); vertical-align: middle; }
  tr:hover td{ background: rgba(255,255,255,0.03); }

  .status{
    display: inline-block; padding: 3px 10px; border-radius: 20px; font-size: 11px;
    text-transform: uppercase; letter-spacing: .5px; font-family: 'Space Grotesk', sans-serif; font-weight: 600;
  }
  .status.pending{ background: rgba(155,92,255,0.18); color: var(--violet); }
  .status.verified{ background: rgba(63,227,176,0.18); color: var(--ok); }
  .status.disqualified{ background: rgba(232,84,138,0.18); color: var(--danger); }

  select.status-select{ width: auto; padding: 4px 8px; font-size: 12px; }

  .rank-list{ display: flex; flex-direction: column; gap: 8px; }
  .rank-row{
    display: grid;
    grid-template-columns: 44px 1fr auto;
    align-items: center;
    background: var(--bg);
    border-radius: var(--radius);
    padding: 12px 16px;
    border-left: 3px solid transparent;
  }
  .rank-row.gold{ border-left: 3px solid; border-image: var(--grad) 1; background: linear-gradient(90deg, rgba(155,92,255,0.08), transparent 40%); }
  .rank-row.silver{ border-left-color: rgba(255,255,255,0.35); }
  .rank-row.bronze{ border-left-color: rgba(255,255,255,0.18); }
  .rank-num{
    font-family: 'Space Mono', monospace; font-size: 20px; color: var(--text-dim);
  }
  .rank-name{ font-family: 'Space Grotesk', sans-serif; font-weight: 600; font-size: 17px; letter-spacing: .2px; }
  .rank-games{ font-size: 12px; color: var(--text-dim); font-family: 'Space Mono', monospace; margin-top: 2px; }
  .rank-total{ font-family: 'Space Mono', monospace; font-size: 22px; font-weight: 700;
    background: var(--grad); -webkit-background-clip: text; background-clip: text; color: transparent; }

  .empty{ text-align: center; color: var(--text-dim); padding: 40px 0; font-family: 'Space Mono', monospace; }

  .actions{ display:flex; gap: 6px; }

  .rules-box{
    font-size: 13px; color: var(--text-dim); line-height: 1.6;
    background: var(--bg); border-radius: var(--radius); padding: 14px 16px; margin-top: 10px;
    border-left: 2px solid var(--violet);
  }

  footer{
    text-align: center; padding: 24px; color: var(--text-dim); font-size: 12px;
    font-family: 'Space Mono', monospace;
  }

  @media (max-width: 560px){
    .games-grid{ grid-template-columns: repeat(2,1fr); }
    table, thead, tbody, th, td, tr{ display: block; }
    thead{ display:none; }
    tr{ border-bottom: 1px solid rgba(255,255,255,0.1); padding: 10px 0; }
    td{ border: none; padding: 4px 0; }
    td::before{ content: attr(data-label); display:block; font-size: 10px; text-transform: uppercase; color: var(--text-dim); letter-spacing: .5px; }
  }
  .auth-overlay{
    position: fixed; inset: 0;
    background: rgba(6,7,11,0.82);
    backdrop-filter: blur(6px);
    display: none;
    align-items: center; justify-content: center;
    z-index: 100;
    padding: 20px;
  }
  .auth-overlay.show{ display: flex; }
  .auth-box{
    background: var(--panel);
    border: 1px solid rgba(255,255,255,0.1);
    border-radius: var(--radius);
    padding: 28px;
    width: 100%;
    max-width: 320px;
    text-align: center;
  }
  .auth-box h2{
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 600;
    font-size: 19px;
    margin-bottom: 6px;
  }
  .auth-box .hint{ color: var(--text-dim); font-size: 13px; margin-bottom: 16px; }
  .auth-box input{
    width: 100%;
    background: var(--bg);
    border: 1px solid rgba(255,255,255,0.12);
    color: var(--ink);
    padding: 10px 12px;
    border-radius: var(--radius);
    font-family: 'Inter', sans-serif;
    font-size: 15px;
    text-align: center;
  }
  .auth-box input:focus{ outline: 2px solid var(--violet); outline-offset: 1px; }
  .auth-box .row{ justify-content: center; }
  .auth-error{ color: var(--danger); font-size: 12px; margin-top: 8px; min-height: 16px; }

  .admin-footer-link{
    display: inline-block; margin-top: 18px; font-size: 12px; color: var(--text-dim);
    background: none; border: none; cursor: pointer; text-decoration: underline;
    font-family: 'Inter', sans-serif;
  }
  .admin-footer-link:hover{ color: var(--ink); }
</style>
</head>
<body>

<header>
  <svg class="logo-mark" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="ringGrad" x1="4" y1="4" x2="36" y2="36" gradientUnits="userSpaceOnUse">
        <stop offset="0" stop-color="#3FD8E3"/>
        <stop offset="0.55" stop-color="#9B5CFF"/>
        <stop offset="1" stop-color="#E23FC4"/>
      </linearGradient>
    </defs>
    <circle cx="20" cy="20" r="15" stroke="url(#ringGrad)" stroke-width="2.5"/>
    <line x1="10" y1="30" x2="30" y2="10" stroke="url(#ringGrad)" stroke-width="2.5" stroke-linecap="round"/>
  </svg>
  <h1>Spare<span>/</span>Ware <span>Open</span></h1>
  <div class="subtitle">Tournament Desk — Score Verification & Standings</div>
</header>

<nav>
  <button class="tab-btn" data-tab="add">Log Submission</button>
  <button class="tab-btn" data-tab="all">All Submissions</button>
  <button class="tab-btn active" data-tab="board">Leaderboard</button>
</nav>

<main>

  <!-- ADD ENTRY -->
  <section class="panel" id="panel-add">
    <div class="card">
      <h2>New Score Submission</h2>
      <div class="hint">Log a bowler's series after checking their videos against the tournament rules.</div>

      <label for="f-name">Bowler name / Discord handle</label>
      <input type="text" id="f-name" placeholder="e.g. pinbuster_99">

      <label>Game scores</label>
      <div class="games-grid">
        <input type="number" id="f-g1" placeholder="G1" min="0" max="300">
        <input type="number" id="f-g2" placeholder="G2" min="0" max="300">
        <input type="number" id="f-g3" placeholder="G3" min="0" max="300">
        <input type="number" id="f-g4" placeholder="G4" min="0" max="300">
      </div>
      <div class="total-readout">Series total: <b id="f-total">0</b></div>

      <label for="f-submitted">Submitted (date &amp; time)</label>
      <input type="datetime-local" id="f-submitted">

      <label>Verification checklist</label>
      <div class="checklist">
        <label><input type="checkbox" id="c1"> All 5 timestamp papers shown</label>
        <label><input type="checkbox" id="c2"> 4 uncut videos, each showing timestamp then first ball</label>
        <label><input type="checkbox" id="c3"> Final video shows 5th timestamp + full scoring screen (or printout)</label>
        <label><input type="checkbox" id="c4"> All 4 games and series total clearly legible</label>
        <label><input type="checkbox" id="c5"> Submitted via Tournament Forum before deadline</label>
      </div>

      <label for="f-notes">Notes (optional)</label>
      <textarea id="f-notes" rows="2" placeholder="Anything unusual about this submission..."></textarea>

      <div class="row">
        <button class="btn btn-primary" id="save-btn">Save Submission</button>
        <button class="btn btn-ghost" id="clear-btn">Clear Form</button>
      </div>
    </div>

    <div class="card">
      <h2>Rules Reference</h2>
      <div class="rules-box">
        A submission is disqualified if any video is cut or edited between showing the timestamp
        and the first ball, if a timestamp paper is missing, or if the final scoring screen doesn't
        clearly show all 4 games and the series total. Scores must be submitted through the
        Tournament Forum only, within 1 week of the tournament start date. Late submissions don't count.
      </div>
      <button class="admin-footer-link" id="change-pw-btn">Change admin password</button>
    </div>
  </section>

  <!-- ALL SUBMISSIONS -->
  <section class="panel" id="panel-all">
    <div class="card">
      <h2>All Submissions</h2>
      <div class="hint">Update verification status as you review each bowler's videos.</div>
      <div class="row" style="margin-top:0; margin-bottom:16px; align-items:center;">
        <input type="text" id="search-box" placeholder="Search by name..." style="flex:1; min-width:180px;">
        <button class="btn btn-ghost" id="export-btn">Export CSV</button>
      </div>
      <div id="all-table-wrap"></div>
    </div>
  </section>

  <!-- LEADERBOARD -->
  <section class="panel active" id="panel-board">
    <div class="card">
      <h2>Standings</h2>
      <div class="hint">Verified series totals only, highest to lowest.</div>
      <div id="board-wrap"></div>
    </div>
  </section>

</main>

<footer>SPARE/WARE OPEN · Tournament record keeping · Data saved automatically</footer>

<div id="auth-overlay" class="auth-overlay">
  <div class="auth-box">
    <svg class="logo-mark" style="margin-bottom:10px;" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
      <circle cx="20" cy="20" r="15" stroke="url(#ringGrad)" stroke-width="2.5"/>
      <line x1="10" y1="30" x2="30" y2="10" stroke="url(#ringGrad)" stroke-width="2.5" stroke-linecap="round"/>
    </svg>
    <h2>Admin Access</h2>
    <div class="hint">Enter the tournament desk password to continue.</div>
    <input type="password" id="auth-input" placeholder="Password" autocomplete="off">
    <div id="auth-error" class="auth-error"></div>
    <div class="row" style="margin-top:14px;">
      <button class="btn btn-primary" id="auth-submit">Unlock</button>
      <button class="btn btn-ghost" id="auth-cancel">Cancel</button>
    </div>
  </div>
</div>

<script>
const STORAGE_KEY = 'spare-ware-open:entries';
const PW_KEY = 'spare-ware-open:admin-password';
const DEFAULT_PASSWORD = 'sparewareopen';
let entries = [];
let editingId = null;
let searchTerm = '';
let isAuthed = false;
let adminPassword = DEFAULT_PASSWORD;
let pendingTab = null;

function uid(){ return 'e' + Date.now() + Math.random().toString(16).slice(2,6); }

async function loadPassword(){
  try{
    const res = await window.storage.get(PW_KEY, true);
    adminPassword = res ? res.value : DEFAULT_PASSWORD;
  }catch(e){
    adminPassword = DEFAULT_PASSWORD;
  }
}

async function loadEntries(){
  try{
    const res = await window.storage.get(STORAGE_KEY, true);
    entries = res ? JSON.parse(res.value) : [];
  }catch(e){
    entries = [];
  }
  renderAll();
  renderBoard();
}

async function saveEntries(){
  try{
    await window.storage.set(STORAGE_KEY, JSON.stringify(entries), true);
  }catch(e){
    console.error('Storage error', e);
    alert('Could not save — please try again.');
  }
}

// Tabs — "board" is public, "add" and "all" require the admin password
function switchToTab(tab){
  document.querySelectorAll('.tab-btn').forEach(b=>b.classList.toggle('active', b.dataset.tab === tab));
  document.querySelectorAll('.panel').forEach(p=>p.classList.toggle('active', p.id === 'panel-'+tab));
}

function showAuthOverlay(){
  document.getElementById('auth-input').value = '';
  document.getElementById('auth-error').textContent = '';
  document.getElementById('auth-overlay').classList.add('show');
  document.getElementById('auth-input').focus();
}
function hideAuthOverlay(){
  document.getElementById('auth-overlay').classList.remove('show');
}

document.querySelectorAll('.tab-btn').forEach(btn=>{
  btn.addEventListener('click', ()=>{
    const tab = btn.dataset.tab;
    if((tab === 'add' || tab === 'all') && !isAuthed){
      pendingTab = tab;
      showAuthOverlay();
      return;
    }
    switchToTab(tab);
  });
});

document.getElementById('auth-submit').addEventListener('click', ()=>{
  const entered = document.getElementById('auth-input').value;
  if(entered === adminPassword){
    isAuthed = true;
    hideAuthOverlay();
    if(pendingTab) switchToTab(pendingTab);
    pendingTab = null;
  } else {
    document.getElementById('auth-error').textContent = 'Incorrect password. Try again.';
  }
});
document.getElementById('auth-input').addEventListener('keydown', (e)=>{
  if(e.key === 'Enter') document.getElementById('auth-submit').click();
});
document.getElementById('auth-cancel').addEventListener('click', ()=>{
  pendingTab = null;
  hideAuthOverlay();
});

document.getElementById('change-pw-btn').addEventListener('click', async ()=>{
  if(!isAuthed){ alert('Unlock the admin area first before changing the password.'); return; }
  const current = prompt('Enter the current password to confirm:');
  if(current === null) return;
  if(current !== adminPassword){ alert('That password is incorrect.'); return; }
  const next = prompt('Enter a new password:');
  if(!next) return;
  adminPassword = next;
  try{
    await window.storage.set(PW_KEY, adminPassword, true);
    alert('Password updated.');
  }catch(e){
    alert('Could not save the new password — please try again.');
  }
});

// Live total
function updateTotal(){
  const g = ['f-g1','f-g2','f-g3','f-g4'].map(id => parseInt(document.getElementById(id).value) || 0);
  document.getElementById('f-total').textContent = g.reduce((a,b)=>a+b,0);
}
['f-g1','f-g2','f-g3','f-g4'].forEach(id=>{
  document.getElementById(id).addEventListener('input', updateTotal);
});

function clearForm(){
  document.getElementById('f-name').value = '';
  ['f-g1','f-g2','f-g3','f-g4'].forEach(id => document.getElementById(id).value = '');
  document.getElementById('f-submitted').value = '';
  document.getElementById('f-notes').value = '';
  ['c1','c2','c3','c4','c5'].forEach(id => document.getElementById(id).checked = false);
  editingId = null;
  document.getElementById('save-btn').textContent = 'Save Submission';
  updateTotal();
}
document.getElementById('clear-btn').addEventListener('click', clearForm);

document.getElementById('save-btn').addEventListener('click', async ()=>{
  const name = document.getElementById('f-name').value.trim();
  if(!name){ alert('Enter a bowler name or Discord handle.'); return; }

  const games = ['f-g1','f-g2','f-g3','f-g4'].map(id => parseInt(document.getElementById(id).value));
  if(games.some(g => isNaN(g))){ alert('Enter all 4 game scores.'); return; }
  if(games.some(g => g < 0 || g > 300)){ alert('Game scores must be between 0 and 300.'); return; }

  if(!editingId){
    const dupe = entries.some(e => e.name.toLowerCase() === name.toLowerCase());
    if(dupe && !confirm(`"${name}" already has a submission logged. Save this as an additional entry anyway?`)) return;
  }

  const checklist = {
    papers: document.getElementById('c1').checked,
    videos: document.getElementById('c2').checked,
    finalScreen: document.getElementById('c3').checked,
    legible: document.getElementById('c4').checked,
    onTime: document.getElementById('c5').checked,
  };

  if(editingId){
    const entry = entries.find(x => x.id === editingId);
    entry.name = name;
    entry.games = games;
    entry.total = games.reduce((a,b)=>a+b,0);
    entry.submitted = document.getElementById('f-submitted').value || null;
    entry.notes = document.getElementById('f-notes').value.trim();
    entry.checklist = checklist;
    editingId = null;
    document.getElementById('save-btn').textContent = 'Save Submission';
  } else {
    entries.push({
      id: uid(),
      name,
      games,
      total: games.reduce((a,b)=>a+b,0),
      submitted: document.getElementById('f-submitted').value || null,
      notes: document.getElementById('f-notes').value.trim(),
      checklist,
      status: 'pending',
      logged: new Date().toISOString(),
    });
  }

  await saveEntries();
  clearForm();
  renderAll();
  renderBoard();
  document.querySelector('[data-tab="all"]').click();
});

function statusLabel(s){
  return s === 'verified' ? 'Verified' : s === 'disqualified' ? 'Disqualified' : 'Pending';
}

function renderAll(){
  const wrap = document.getElementById('all-table-wrap');
  if(entries.length === 0){
    wrap.innerHTML = '<div class="empty">No submissions logged yet.</div>';
    return;
  }
  const filtered = entries.filter(e => e.name.toLowerCase().includes(searchTerm.toLowerCase()));
  if(filtered.length === 0){
    wrap.innerHTML = '<div class="empty">No submissions match that search.</div>';
    return;
  }
  const sorted = [...filtered].sort((a,b) => new Date(b.logged) - new Date(a.logged));
  wrap.innerHTML = `
    <table>
      <thead>
        <tr><th>Bowler</th><th>Games</th><th>Total</th><th>Checklist</th><th>Status</th><th>Notes</th><th></th></tr>
      </thead>
      <tbody>
        ${sorted.map(e => `
          <tr>
            <td data-label="Bowler">${escapeHtml(e.name)}</td>
            <td data-label="Games">${e.games.join(' · ')}</td>
            <td data-label="Total"><b>${e.total}</b></td>
            <td data-label="Checklist">${Object.values(e.checklist).filter(Boolean).length}/5</td>
            <td data-label="Status">
              <select class="status-select" data-id="${e.id}">
                <option value="pending" ${e.status==='pending'?'selected':''}>Pending</option>
                <option value="verified" ${e.status==='verified'?'selected':''}>Verified</option>
                <option value="disqualified" ${e.status==='disqualified'?'selected':''}>Disqualified</option>
              </select>
            </td>
            <td data-label="Notes">${escapeHtml(e.notes || '—')}</td>
            <td data-label="">
              <div class="actions">
                <button class="btn btn-ghost btn-small edit-btn" data-id="${e.id}">Edit</button>
                <button class="btn btn-ghost btn-small delete-btn" data-id="${e.id}">Delete</button>
              </div>
            </td>
          </tr>
        `).join('')}
      </tbody>
    </table>
  `;

  wrap.querySelectorAll('.status-select').forEach(sel=>{
    sel.addEventListener('change', async ()=>{
      const entry = entries.find(x => x.id === sel.dataset.id);
      entry.status = sel.value;
      await saveEntries();
      renderBoard();
    });
  });
  wrap.querySelectorAll('.delete-btn').forEach(btn=>{
    btn.addEventListener('click', async ()=>{
      if(!confirm('Delete this submission?')) return;
      entries = entries.filter(x => x.id !== btn.dataset.id);
      await saveEntries();
      renderAll();
      renderBoard();
    });
  });
  wrap.querySelectorAll('.edit-btn').forEach(btn=>{
    btn.addEventListener('click', ()=>{
      const entry = entries.find(x => x.id === btn.dataset.id);
      editingId = entry.id;
      document.getElementById('f-name').value = entry.name;
      document.getElementById('f-g1').value = entry.games[0];
      document.getElementById('f-g2').value = entry.games[1];
      document.getElementById('f-g3').value = entry.games[2];
      document.getElementById('f-g4').value = entry.games[3];
      document.getElementById('f-submitted').value = entry.submitted || '';
      document.getElementById('f-notes').value = entry.notes || '';
      document.getElementById('c1').checked = entry.checklist.papers;
      document.getElementById('c2').checked = entry.checklist.videos;
      document.getElementById('c3').checked = entry.checklist.finalScreen;
      document.getElementById('c4').checked = entry.checklist.legible;
      document.getElementById('c5').checked = entry.checklist.onTime;
      updateTotal();
      document.getElementById('save-btn').textContent = 'Update Submission';
      document.querySelector('[data-tab="add"]').click();
    });
  });
}

document.getElementById('search-box').addEventListener('input', (e)=>{
  searchTerm = e.target.value;
  renderAll();
});

document.getElementById('export-btn').addEventListener('click', ()=>{
  if(entries.length === 0){ alert('No submissions to export.'); return; }
  const header = ['Name','Game 1','Game 2','Game 3','Game 4','Total','Status','Submitted','Notes'];
  const rows = entries.map(e => [
    e.name, e.games[0], e.games[1], e.games[2], e.games[3], e.total,
    statusLabel(e.status), e.submitted || '', (e.notes||'').replace(/"/g,'""')
  ]);
  const csv = [header, ...rows]
    .map(r => r.map(v => `"${v}"`).join(','))
    .join('\n');
  const blob = new Blob([csv], {type: 'text/csv'});
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a');
  a.href = url;
  a.download = 'spare-ware-open-submissions.csv';
  a.click();
  URL.revokeObjectURL(url);
});

function renderBoard(){
  const wrap = document.getElementById('board-wrap');
  const verified = entries.filter(e => e.status === 'verified').sort((a,b) => b.total - a.total);
  if(verified.length === 0){
    wrap.innerHTML = '<div class="empty">No verified scores yet. Verify submissions in the "All Submissions" tab to populate standings.</div>';
    return;
  }
  const medalClass = i => i===0?'gold':i===1?'silver':i===2?'bronze':'';
  wrap.innerHTML = `<div class="rank-list">
    ${verified.map((e,i)=>`
      <div class="rank-row ${medalClass(i)}">
        <div class="rank-num">#${i+1}</div>
        <div>
          <div class="rank-name">${escapeHtml(e.name)}</div>
          <div class="rank-games">${e.games.join(' · ')}</div>
        </div>
        <div class="rank-total">${e.total}</div>
      </div>
    `).join('')}
  </div>`;
}

function escapeHtml(str){
  const div = document.createElement('div');
  div.textContent = str;
  return div.innerHTML;
}

loadPassword();
loadEntries();
</script>

</body>
</html>
