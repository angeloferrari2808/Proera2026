<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PROERA</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display",
      "Segoe UI", sans-serif;
    }

    body{
      background:#f5f5f7;
      color:#1d1d1f;
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      padding:20px;
    }

    .container{
      width:100%;
      max-width:700px;
      background:white;
      border-radius:28px;
      padding:40px;
      box-shadow:0 10px 30px rgba(0,0,0,0.08);
      text-align:center;
    }

    .logo{
      font-size:48px;
      font-weight:700;
      letter-spacing:2px;
      margin-bottom:10px;
    }

    .subtitle{
      color:#6e6e73;
      font-size:18px;
      margin-bottom:35px;
    }

    .input-area{
      display:flex;
      flex-direction:column;
      gap:20px;
    }

    textarea{
      width:100%;
      height:180px;
      border:none;
      resize:none;
      padding:20px;
      border-radius:20px;
      background:#f2f2f2;
      font-size:16px;
      outline:none;
      transition:0.3s;
    }

    textarea:focus{
      background:#ebebeb;
      box-shadow:0 0 0 3px rgba(0,113,227,0.2);
    }

    button{
      border:none;
      background:#0071e3;
      color:white;
      padding:16px;
      border-radius:14px;
      font-size:16px;
      font-weight:600;
      cursor:pointer;
      transition:0.3s;
    }

    button:hover{
      background:#0062c4;
      transform:translateY(-2px);
    }

    footer{
      margin-top:25px;
      color:#86868b;
      font-size:14px;
    }

    @media(max-width:600px){
      .container{
        padding:28px;
      }

      .logo{
        font-size:36px;
      }
    }
  </style>
</head>

<body>

  <div class="container">
    <h1 class="logo">PROERA</h1>

    <p class="subtitle">
      Digite sua dúvida acadêmica abaixo.
    </p>

    <div class="input-area">
      <textarea placeholder="Ex: Explique a Revolução Francesa de forma simples..."></textarea>

      <button>Enviar dúvida</button>
    </div>

    <footer>
      © 2026 PROERA
    </footer>
  </div>

</body>
</html>
