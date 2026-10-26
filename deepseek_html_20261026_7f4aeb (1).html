<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>✨ Value Naga — Dragon Adventures</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',system-ui,sans-serif}
  body{background:radial-gradient(circle at 20% 30%,#0b0e1a,#010101);color:#eaeef5;min-height:100vh;padding:2rem 1.5rem;display:flex;flex-direction:column;align-items:center}
  .container{width:100%;max-width:1400px;position:relative;z-index:2}
  .hero{text-align:center;margin-bottom:2.5rem}
  .hero h1{font-size:3rem;font-weight:700;background:linear-gradient(135deg,#ffd966,#f7b32b,#ff9f1c);-webkit-background-clip:text;background-clip:text;color:transparent;display:flex;align-items:center;justify-content:center;gap:12px}
  .hero p{color:#a0aec0;font-size:1.1rem;margin-top:6px}
  .controls{display:flex;flex-wrap:wrap;justify-content:space-between;align-items:center;gap:1.2rem;margin-bottom:2.5rem;background:rgba(20,25,40,.7);backdrop-filter:blur(12px);padding:1rem 1.8rem;border-radius:80px;border:1px solid rgba(255,215,0,.15);box-shadow:0 15px 35px -10px rgba(0,0,0,.7)}
  .filter-group{display:flex;flex-wrap:wrap;gap:.6rem}
  .filter-btn{background:transparent;border:1.5px solid rgba(255,215,0,.2);color:#b0b8c5;padding:.6rem 1.4rem;border-radius:40px;font-weight:600;font-size:.85rem;cursor:pointer;transition:all .25s;display:flex;align-items:center;gap:6px}
  .filter-btn:hover{border-color:#ffd966;color:#ffd966;background:rgba(255,215,0,.05);transform:translateY(-2px)}
  .filter-btn.active{background:linear-gradient(135deg,#f7b32b,#ff9f1c);border-color:#f7b32b;color:#0b0e1a;font-weight:700;box-shadow:0 0 20px rgba(247,179,43,.4)}
  .search-wrapper{position:relative;min-width:240px;flex:1 1 240px}
  .search-wrapper i{position:absolute;left:18px;top:50%;transform:translateY(-50%);color:#6b7a8f}
  .search-wrapper input{width:100%;padding:.8rem 1.2rem .8rem 2.8rem;border-radius:50px;border:1.5px solid rgba(255,255,255,.08);background:rgba(10,15,25,.8);color:#f0f4fa;font-size:.95rem;outline:none;transition:all .25s}
  .search-wrapper input:focus{border-color:#ffd966;box-shadow:0 0 0 4px rgba(255,215,0,.1)}
  .dragon-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(210px,1fr));gap:1.5rem}
  .dragon-card{background:linear-gradient(145deg,#121826,#0b0e15);border-radius:24px;padding:1.3rem 1rem 1.2rem;display:flex;flex-direction:column;align-items:center;text-align:center;border:1px solid rgba(255,215,0,.08);box-shadow:0 20px 30px -15px rgba(0,0,0,.8);transition:all .3s cubic-bezier(.2,.9,.4,1);cursor:pointer;position:relative;overflow:hidden}
  .dragon-card:hover{transform:translateY(-8px) scale(1.02);border-color:rgba(255,215,0,.4);box-shadow:0 28px 40px -12px #000,0 0 25px rgba(247,179,43,.2)}
  .dragon-img{width:110px;height:110px;background:radial-gradient(circle at 30% 30%,#2a3348,#131a28);border-radius:50%;display:flex;align-items:center;justify-content:center;margin-bottom:.9rem;border:2px solid rgba(255,215,0,.15);box-shadow:inset 0 0 20px rgba(0,0,0,.7),0 8px 12px -5px #000;transition:transform .3s,border-color .3s}
  .dragon-card:hover .dragon-img{transform:scale(1.05);border-color:rgba(255,215,0,.5)}
  .dragon-img i{font-size:3.5rem;color:#f7b32b;filter:drop-shadow(0 0 8px rgba(247,179,43,.6));transition:transform .3s}
  .dragon-card:hover .dragon-img i{transform:scale(1.1) rotate(3deg)}
  .dragon-name{font-size:1.2rem;font-weight:700;color:#fff6e5;margin-bottom:4px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;max-width:100%}
  .dragon-price{font-size:1.1rem;font-weight:800;color:#ffd966;background:rgba(0,0,0,.5);padding:4px 12px;border-radius:40px;margin:6px 0 8px;display:inline-flex;align-items:center;gap:5px;border:1px solid rgba(255,215,0,.2)}
  .dragon-rarity{font-size:.75rem;text-transform:uppercase;letter-spacing:1px;font-weight:700;padding:4px 14px;border-radius:40px;background:rgba(255,255,255,.05);border:1px solid rgba(255,255,255,.1);color:#b0c4de;display:inline-flex;align-items:center;gap:5px;margin-top:4px}
  .modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.85);backdrop-filter:blur(10px);display:flex;align-items:center;justify-content:center;padding:1.5rem;z-index:1000;opacity:0;visibility:hidden;transition:opacity .3s,visibility .3s}
  .modal-overlay.active{opacity:1;visibility:visible}
  .modal-card{background:linear-gradient(145deg,#141c2c,#0a0f18);max-width:580px;width:100%;border-radius:38px;padding:2rem;border:1px solid rgba(255,215,0,.2);box-shadow:0 40px 60px -15px #000,0 0 60px rgba(247,179,43,.15);transform:scale(.9) translateY(20px);transition:transform .35s cubic-bezier(.2,.9,.3,1.1),opacity .3s;position:relative;color:#eef3fc}
  .modal-overlay.active .modal-card{transform:scale(1) translateY(0)}
  .modal-close{position:absolute;top:18px;right:22px;background:rgba(255,255,255,.05);border:none;color:#9aaabb;font-size:1.8rem;width:40px;height:40px;border-radius:50%;display:flex;align-items:center;justify-content:center;cursor:pointer;transition:all .2s}
  .modal-close:hover{background:rgba(255,215,0,.15);color:#ffd966;transform:rotate(90deg)}
  .modal-header{display:flex;align-items:center;gap:1.2rem;margin-bottom:1.8rem;padding-right:2rem}
  .modal-icon{width:80px;height:80px;background:radial-gradient(circle at 30% 30%,#2a3348,#131a28);border-radius:30px;display:flex;align-items:center;justify-content:center;border:2px solid #ffd96633}
  .modal-icon i{font-size:3.2rem;color:#f7b32b;filter:drop-shadow(0 0 10px #f7b32b)}
  .modal-title h2{font-size:2rem;font-weight:800;color:#fff6e0}
  .modal-rarity{font-size:.75rem;text-transform:uppercase;letter-spacing:1.5px;font-weight:700;color:#ffd966;background:rgba(255,215,0,.1);display:inline-block;padding:3px 14px;border-radius:40px;margin-top:6px;border:1px solid #ffd96644}
  .modal-price{background:rgba(0,0,0,.4);border-radius:24px;padding:.9rem 1.4rem;display:flex;align-items:center;justify-content:space-between;margin-bottom:1.6rem;border:1px solid rgba(255,215,0,.2)}
  .modal-price .label{color:#9aaabb;font-size:.9rem}
  .modal-price .value{font-size:1.8rem;font-weight:800;color:#ffd966;display:flex;align-items:center;gap:8px}
  .modal-section{margin-bottom:1.5rem}
  .modal-section h4{font-size:.85rem;text-transform:uppercase;letter-spacing:1.5px;color:#9aaabb;margin-bottom:8px;display:flex;align-items:center;gap:8px}
  .modal-section h4 i{color:#f7b32b}
  .modal-section p{color:#ccd9eb;font-size:1rem;line-height:1.6;background:rgba(255,255,255,.02);padding:.9rem 1.2rem;border-radius:18px;border-left:4px solid #f7b32b}
  .empty-state{grid-column:1/-1;text-align:center;padding:4rem 1rem;color:#6b7a8f;font-size:1.2rem;display:flex;flex-direction:column;align-items:center;gap:1rem}
  .empty-state i{font-size:4rem;opacity:.3;color:#f7b32b}
  @media(max-width:700px){body{padding:1.2rem .8rem}.hero h1{font-size:2.2rem}.controls{flex-direction:column;align-items:stretch;border-radius:40px;padding:1rem}.filter-group{justify-content:center}.dragon-grid{grid-template-columns:repeat(auto-fill,minmax(160px,1fr));gap:1rem}.dragon-img{width:85px;height:85px}.dragon-img i{font-size:2.8rem}.dragon-name{font-size:1rem}.modal-card{padding:1.6rem}.modal-header{flex-direction:column;text-align:center;gap:.7rem;padding-right:0}.modal-title h2{font-size:1.7rem}}
</style>
</head>
<body>
<div class="container">
  <div class="hero">
    <h1><i class="fas fa-dragon"></i> Value Naga <i class="fas fa-gem"></i></h1>
    <p>Koleksi nilai naga Dragon Adventures • Oktober 2026</p>
  </div>
  <div class="controls">
    <div class="filter-group">
      <button class="filter-btn active" data-filter="all"><i class="fas fa-globe"></i> Semua</button>
      <button class="filter-btn" data-filter="season"><i class="fas fa-calendar-alt"></i> Naga Season</button>
      <button class="filter-btn" data-filter="event"><i class="fas fa-star"></i> Naga Event</button>
      <button class="filter-btn" data-filter="world"><i class="fas fa-tree"></i> Naga Dunia</button>
    </div>
    <div class="search-wrapper">
      <i class="fas fa-search"></i>
      <input type="text" id="searchInput" placeholder="Cari nama naga...">
    </div>
  </div>
  <div class="dragon-grid" id="dragonGrid"></div>
</div>

<div class="modal-overlay" id="modalOverlay">
  <div class="modal-card">
    <button class="modal-close" id="modalClose"><i class="fas fa-times"></i></button>
    <div class="modal-header">
      <div class="modal-icon"><i class="fas fa-dragon" id="modalIcon"></i></div>
      <div class="modal-title">
        <h2 id="modalName">—</h2>
        <span class="modal-rarity" id="modalRarity">—</span>
      </div>
    </div>
    <div class="modal-price">
      <span class="label"><i class="fas fa-coins"></i> Harga Coin</span>
      <span class="value" id="modalPrice"><i class="fas fa-coins"></i> —</span>
    </div>
    <div class="modal-section">
      <h4><i class="fas fa-map-signs"></i> Cara Mendapatkan</h4>
      <p id="modalHow">—</p>
    </div>
    <div class="modal-section">
      <h4><i class="fas fa-scroll"></i> Deskripsi</h4>
      <p id="modalDesc">—</p>
    </div>
  </div>
</div>

<script>
const dragonsData = [
  {name:"Veidreki",price:"50M - 60M",rarity:"Season • Relic",category:"season",how:"Season 1 (Relic) — tidak dapat diperoleh lagi.",desc:"Naga legendaris dengan nilai tertinggi di Dragon Adventures."},
  {name:"Alatura",price:"28M - 35M",rarity:"Season • Legendary",category:"season",how:"Season 2 (Legendary) — sudah tidak tersedia.",desc:"Naga season legendaris dengan sayap megah."},
  {name:"Amaris",price:"10M",rarity:"Season • Legendary",category:"season",how:"Season 3 (Legendary) — tidak dapat diperoleh lagi.",desc:"Naga season legendaris dengan aura elegan."},
  {name:"Tianma",price:"1M - 1.5M",rarity:"Event • Legendary",category:"event",how:"Event spesial (Legendary).",desc:"Naga event legendaris dengan nilai tinggi."},
  {name:"Saurium",price:"1K - 3K",rarity:"World • Common",category:"world",how:"Dunia (World) — eksplorasi dunia.",desc:"Naga dunia common populer."}
  // 👉 Tambahkan semua data dari daftar sebelumnya di sini (copy dari jawaban pertama)
];

function rarityIcon(r){
  if(r.includes('Relic'))return'fa-gem';
  if(r.includes('Legendary'))return'fa-crown';
  if(r.includes('Epic'))return'fa-star';
  if(r.includes('Rare'))return'fa-circle';
  return'fa-dot-circle';
}

const grid=document.getElementById('dragonGrid');
const searchInput=document.getElementById('searchInput');
const filterBtns=document.querySelectorAll('.filter-btn');
const modalOverlay=document.getElementById('modalOverlay');
const modalClose=document.getElementById('modalClose');
let currentFilter='all',currentSearch='';

function render(){
  const list=dragonsData.filter(d=>
    (currentFilter==='all'||d.category===currentFilter) &&
    d.name.toLowerCase().includes(currentSearch.toLowerCase().trim())
  );
  if(!list.length){
    grid.innerHTML='<div class="empty-state"><i class="fas fa-dragon"></i><p>Tidak ada naga yang cocok.</p></div>';
    return;
  }
  grid.innerHTML=list.map(d=>`
    <div class="dragon-card" data-name="${d.name}">
      <div class="dragon-img"><i class="fas fa-dragon"></i></div>
      <div class="dragon-name">${d.name}</div>
      <div class="dragon-price"><i class="fas fa-coins"></i> ${d.price}</div>
      <div class="dragon-rarity"><i class="fas ${rarityIcon(d.rarity)}"></i> ${d.rarity}</div>
    </div>`).join('');

  document.querySelectorAll('.dragon-card').forEach(card=>{
    card.addEventListener('click',()=>{
      const dragon=dragonsData.find(x=>x.name===card.dataset.name);
      if(!dragon)return;
      document.getElementById('modalName').textContent=dragon.name;
      document.getElementById('modalRarity').textContent=dragon.rarity;
      document.getElementById('modalPrice').innerHTML='<i class="fas fa-coins"></i> '+dragon.price;
      document.getElementById('modalHow').textContent=dragon.how;
      document.getElementById('modalDesc').textContent=dragon.desc;
      modalOverlay.classList.add('active');
    });
  });
}

filterBtns.forEach(btn=>{
  btn.addEventListener('click',()=>{
    filterBtns.forEach(b=>b.classList.remove('active'));
    btn.classList.add('active');
    currentFilter=btn.dataset.filter;
    render();
  });
});

searchInput.addEventListener('input',e=>{currentSearch=e.target.value;render();});
modalClose.addEventListener('click',()=>modalOverlay.classList.remove('active'));
modalOverlay.addEventListener('click',e=>{if(e.target===modalOverlay)modalOverlay.classList.remove('active')});

render();
</script>
</body>
</html>
