![Screenshot_20250511-183358](https://github.com/user-attachments/assets/a380f53d-b9f5-44fc-90e5-11d3a4c383e8)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>¿Juli, quieres ser mi novia?</title>
  <style>
    body {
      background-color: #fff0f5;
      font-family: "Comic Sans MS", cursive;
      text-align: center;
      padding-top: 100px;
    }

    h1 {
      color: #d63384;
    }

    button {
      padding: 15px 25px;
      font-size: 18px;
      margin: 20px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s;
    }

    #yesBtn {
      background-color: #ff69b4;
      color: white;
    }

    #noBtn {
      background-color: #f0f0f0;
      color: #333;
      position: relative;
    }

    #message {
      font-size: 24px;
      color: #e83e8c;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <h1>💌 Juli, ¿quieres ser mi novia? 🥺</h1>

  <button id="yesBtn">Sí 💗</button>
  <button id="noBtn">No 😳</button>

  <div id="message"></div>

  <script>
    const yesBtn = document.getElementById("yesBtn");
    const noBtn = document.getElementById("noBtn");
    const message = document.getElementById("message");

    yesBtn.addEventListener("click", () => {
      message.textContent = "¡Ya sabía que querías ser mi novia! 💖✨";
    });

    noBtn.addEventListener("mouseover", () => {
      const x = Math.random() * (window.innerWidth - 100);
      const y = Math.random() * (window.innerHeight - 100);
      noBtn.style.position = "absolute";
      noBtn.style.left = `${x}px`;
      noBtn.style.top = `${y}px`;
    });
  </script>

</body>
</html>![0d74806cb18b69603c8470f23e67ede3](https://github.com/user-attachments/assets/9634a565-ba49-4121-97c4-c1a074846922)
# declaracion
