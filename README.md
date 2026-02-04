# SanValentín<3
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Para Marco 💖</title>

  <style>
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Helvetica Neue', Arial, sans-serif;
      background: linear-gradient(135deg, #fbc2eb, #a6c1ee);
      padding: 20px;
    }

    .card {
      background: #fff;
      width: 100%;
      max-width: 380px;
      padding: 28px;
      border-radius: 28px;
      box-shadow: 0 15px 35px rgba(0,0,0,0.2);
      text-align: center;
    }

    h1 {
      color: #d63384;
      font-size: 24px;
      margin-bottom: 16px;
    }

    p {
      font-size: 15px;
      line-height: 1.6;
      margin-bottom: 14px;
      color: #444;
    }

    .question {
      font-size: 18px;
      font-weight: 600;
      margin: 20px 0;
      color: #333;
    }

    button {
      width: 100%;
      padding: 14px;
      margin-top: 12px;
      border: none;
      border-radius: 999px;
      font-size: 16px;
      cursor: pointer;
    }

    .yes {
      background: #d63384;
      color: #fff;
    }

    #response {
      margin-top: 22px;
      font-size: 16px;
      font-weight: 600;
      color: #d63384;
    }
  </style>
</head>

<body>

  <div class="card">
    <h1>Para ti, Marco 💖</h1>

    <p>
      La distancia no siempre es fácil,  
      pero hay personas que valen cada kilómetro.
    </p>

    <p>
      Este <strong>14 de febrero</strong>  
      quiero tener una cita contigo,  
      a nuestra manera.
    </p>

    <div class="question">
      💌 ¿Quieres ser mi San Valentine? 💌
    </div>

    <button class="yes" onclick="accept()">Sí, quiero 💕</button>

    <div id="response"></div>
  </div>

  <script>
    function accept() {
      document.getElementById("response").innerHTML =
        "🥰 Entonces es una cita. Gracias por elegirnos 💖";
    }
  </script>

</body>
</html>
