<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Concierto con mi chiquito 💘</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: url('https://www.enwallpaper.com/wp-content/uploads/2023/12/ivan-cornejo-wallpaper-3.webp') no-repeat center center fixed;
      background-size: cover;
      color: white;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      backdrop-filter: brightness(0.5);
    }

    .content {
      background: rgba(0, 0, 0, 0.6);
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 0 15px rgba(255, 192, 203, 0.7);
      max-width: 90%;
      animation: fadeIn 1s ease;
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    p {
      font-size: 1.2rem;
      margin-bottom: 1.5rem;
    }

    .buttons {
      display: flex;
      gap: 2rem;
      justify-content: center;
      position: relative;
    }

    button {
      padding: 0.8rem 1.5rem;
      font-size: 1rem;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .yes {
      background-color: #ff69b4;
      color: white;
    }

    .yes:hover {
      background-color: #ff1493;
    }

    .no {
      background-color: #444;
      color: white;
      position: absolute;
    }

    .hidden {
      display: none;
    }

    .heart {
      position: absolute;
      top: 50%;
      left: 50%;
      font-size: 2rem;
      color: red;
      animation: floatHearts 1.5s infinite ease-in-out;
    }

    @keyframes floatHearts {
      0% {
        transform: translate(-50%, 0);
        opacity: 1;
      }
      50% {
        transform: translate(-50%, -100px);
        opacity: 0.5;
      }
      100% {
        transform: translate(-50%, 0);
        opacity: 1;
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="content">
    <h1>¿Aceptarías ir al concierto de Iván Cornejo conmigo? 🎤</h1>
    <div class="buttons">
      <button class="yes" onclick="showMessage()">Sí 💖</button>
      <button class="no" id="noBtn">No 💔</button>
    </div>
    <div id="specialMessage" class="hidden">
      <p style="margin-top: 2rem; font-size: 1.3rem;">
        Gracias por ser parte de esta aventura conmigo.<br/>
        Te amo mucho mi chiquito, gracias. 💘
      </p>
    </div>
    <div id="heartsContainer" class="hidden">
      <span class="heart">❤</span>
      <span class="heart">❤</span>
      <span class="heart">❤</span>
      <span class="heart">❤</span>
    </div>
  </div>

  <script>
    const noBtn = document.getElementById('noBtn');
    const message = document.getElementById('specialMessage');
    const heartsContainer = document.getElementById('heartsContainer');

    noBtn.addEventListener('mouseover', () => {
      const x = Math.random() * 200 - 100;
      const y = Math.random() * 200 - 100;
      noBtn.style.transform = translate(${x}px, ${y}px);
    });

    function showMessage() {
      message.classList.remove('hidden');
      heartsContainer.classList.remove('hidden');
      setTimeout(() => {
        const hearts = document.querySelectorAll('.heart');
        hearts.forEach((heart, index) => {
          heart.style.animation = floatHearts 1.5s ${index * 0.2}s infinite ease-in-out;
        });
      }, 500);
    }
  </script>
</body>
</html>
