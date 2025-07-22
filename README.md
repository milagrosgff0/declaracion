<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Una preguntita para Juli</title>
  <style>
    body {
      background: linear-gradient(to right, #ffdde1, #f8cddc);
      font-family: "Segoe UI", sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }

    h1 {
      color: #c2185b;
      font-size: 32px;
      text-align: center;
      margin-bottom: 40px;
    }

    .botones {
      display: flex;
      gap: 30px;
    }

    button {
      font-size: 20px;
      padding: 15px 30px;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    #yesBtn {
      background-color: #e91e63;
      color: white;
    }

    #noBtn {
      background-color: #eeeeee;
      color: #555;
      position: absolute;
    }

    #respuesta {
      margin-top: 50px;
      font-size: 26px;
      color: #880e4f;
      text-align: center;
    }
  </style>
</head>
<body>

  <h1>💞 Juli, ¿puedo ser tu novia?</h1>

  <div class="botones">
    <button id="yesBtn">Sí 💗</button>
    <button id="noBtn">No 😳</button>
  </div>

  <div id="respuesta"></div>

  <script>
    const yesBtn = document.getElementById("yesBtn");
    const noBtn = document.getElementById("noBtn");
    const respuesta = document.getElementById("respuesta");

    yesBtn.addEventListener("click", () => {
      respuesta.textContent = "¡Ya sabía que querías ser mi novia! 💖✨";
    });

    noBtn.addEventListener("mouseover", () => {
      const x = Math.random() * (window.innerWidth - noBtn.offsetWidth);
      const y = Math.random() * (window.innerHeight - noBtn.offsetHeight);
      noBtn.style.left = `${x}px`;
      noBtn.style.top = `${y}px`;
    });
  </script>

</body>
</html>
