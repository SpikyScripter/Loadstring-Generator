<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>⚡ Loadstring Generator — Ultra Pro</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --accent:#7c3aed;
      --accent-2:#ff0000;
      --muted:#cdd6f4;
    }

    *{box-sizing:border-box;margin:0;padding:0}

    body{
      font-family:'Poppins';
      color:white;
      display:flex;
      justify-content:center;
      align-items:flex-start;
      min-height:100vh;
      padding:20px;
      background:url('https://i.pinimg.com/originals/8c/28/c1/8c28c17d9ff89204434d5ee0e499e99f.jpg') center/cover fixed;
      position:relative;
      overflow-y:auto;
    }

    .lightning{
      position:fixed;
      inset:0;
      background:url('https://i.imgur.com/0KX4p8I.png') center/cover;
      mix-blend-mode:screen;
      opacity:0.16;
      animation:flash 6s infinite ease-in-out;
      pointer-events:none;
      z-index:0;
      filter:hue-rotate(0deg) saturate(200%) brightness(1.2) sepia(1) hue-rotate(-20deg);
    }

    @keyframes flash{
      0%,100%{opacity:0.15}
      50%{opacity:0.35}
    }

    .overlay{
      position:fixed;
      inset:0;
      background:rgba(0,0,0,0.65);
      backdrop-filter:blur(4px);
      z-index:1;
    }

    .wrapper{
      position:relative;
      z-index:2;
      display:grid;
      grid-template-columns:1fr 1fr;
      grid-template-rows:auto auto;
      gap:30px;
      width:100%;
      max-width:1200px;
      justify-items:center;
      align-items:start;
    }

    .card{
      padding:24px;
      width:100%;
      max-width:500px;
      border-radius:18px;
      background:rgba(0,0,0,0.7);
      border:1px solid rgba(255,255,255,0.08);
      backdrop-filter:blur(12px) saturate(140%);
      box-shadow:0 10px 50px rgba(0,0,0,0.8);
      display:flex;
      flex-direction:column;
      gap:15px;
    }

    .logo{
      width:65px;height:65px;border-radius:16px;
      background:linear-gradient(135deg,#3b0764,#8b0000);
      display:flex;align-items:center;justify-content:center;
      font-weight:700;font-size:22px;
      margin-bottom:10px;
      box-shadow:0 6px 20px rgba(0,0,0,0.5);
    }

    h1{font-size:24px;margin-bottom:6px;text-align:center}
    p.lead{color:var(--muted);margin-bottom:15px;text-align:center}

    textarea,input{
      width:100%;padding:12px;
      border-radius:10px;
      background:rgba(0,0,0,0.6);
      border:1px solid rgba(255,255,255,0.1);
      color:white;font-size:15px;
    }

    .btn{
      padding:12px 18px;
      border:none;border-radius:12px;
      background: linear-gradient(90deg, #000000, #333333, #8b0000);
      -webkit-background-clip: text;
      color: transparent;
      font-weight:700;
      cursor:pointer;
      box-shadow:0 6px 22px rgba(139,0,0,0.5);
      transition:0.2s;
      align-self:center;
      text-align:center;
    }

    .btn:hover{transform:scale(1.05)}

    .preview{
      background:rgba(0,0,0,0.75);
      padding:16px;
      border-radius:14px;
      border:1px solid rgba(255,255,255,0.15);
      white-space:pre-wrap;
      font-size:14px;
      backdrop-filter:blur(8px);
      max-height:300px;
      overflow:auto;
    }

    .spiky-title{
      font-size:48px;
      font-weight:800;
      background:linear-gradient(90deg, #ffffff, #000000);
      -webkit-background-clip:text;
      color:transparent;
      text-transform:uppercase;
      letter-spacing:4px;
      margin-bottom:15px;
      text-align:center;
    }

    .section{
      grid-column:1 / -1;
      text-align:center;
      font-size:24px;
      font-weight:700;
      margin-top:15px;
      background: linear-gradient(90deg, #ffffff, #000000, #8b0000);
      -webkit-background-clip: text;
      color: transparent;
      padding:10px;
      border-radius:12px;
    }

    @media(max-width:900px){
      .wrapper{grid-template-columns:1fr;grid-template-rows:auto;gap:20px;}
      .card{max-width:90%;}
      .spiky-title{font-size:36px;}
      .section{font-size:20px;}
    }
  </style>
</head>
<body>
<div class="overlay"></div>
<div class="lightning"></div>

<div class="wrapper">

  <div class="card" id="inputCard">
    <div class="logo"><img src="https://pm1.aminoapps.com/7514/103424abac09eddb062221439985d20c9a722f30r1-278-278v2_00.jpg" style="width:100%;height:100%;object-fit:cover;border-radius:16px;"/></div>
    <h1 class="spiky-title">Spiky Scripter</h1>
    <h1>Loadstring Generator</h1>
    <p class="lead">Convierte tu código a loadstring automáticamente.</p>

    <label>Inserta tu código:</label>
    <textarea id="codeInput" rows="6" placeholder="Pega tu código aquí..."></textarea>

    <button class="btn" onclick="convert()" id="convertBtn">Convertir a Loadstring</button>
  </div>

  <div class="card">
    <h1>Resultado</h1>
    <div class="preview" id="output">Aquí aparecerá tu loadstring...</div>
    <button class="btn" id="newCodeBtn" style="display:none; margin-top:10px;" onclick="resetInput()">Generar otro código</button>
    <div class="section">
      Páginas soportadas: Github & Pastefy
    </div>
  </div>

</div>

<script>
function convert(){
  const code=document.getElementById('codeInput').value.trim();
  const output=document.getElementById('output');
  const newBtn=document.getElementById('newCodeBtn');

  if(!code){
    output.innerText = "Error: No ingresaste ningún enlace o código.";
    newBtn.style.display = 'inline-block';
    return;
  }

  const allowed1 = "https://gist.github.com/";
  const allowed2 = "https://pastefy.app/";

  if(!(code.startsWith(allowed1) || code.startsWith(allowed2))){
    output.innerText = "❌ Error: Solo se permiten enlaces de GITHUB (gist.github.com) y PASTEFY (pastefy.app).";
    newBtn.style.display = 'inline-block';
    return;
  }

  const encoded=btoa(code);
  const result=`loadstring(game:HttpGet("https://example.com/?data=${encoded}"))()`;
  output.innerText=result;
  newBtn.style.display = 'inline-block';
}

function resetInput(){
  document.getElementById('codeInput').value = '';
  document.getElementById('output').innerText = 'Aquí aparecerá tu loadstring...';
  document.getElementById('newCodeBtn').style.display = 'none';
}
</script>

</body>
</html>
