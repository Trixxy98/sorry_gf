<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>I’m Sorry, My Love 💔</title>
  <link href="https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Quicksand:wght@400;600&display=swap" rel="stylesheet">

  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      background: radial-gradient(circle at top, #ffd1dc, #ffeaea);
      font-family: 'Quicksand', sans-serif;
      height: 100vh;
      overflow: hidden;
      position: relative;
      animation: bgPulse 6s infinite alternate;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 20px;
      text-align: center;
    }

    @keyframes bgPulse {
      0% { background: radial-gradient(circle at top, #ffd1dc, #ffeaea); }
      100% { background: radial-gradient(circle at bottom, #ffc0cb, #ffebee); }
    }

    h1 {
      font-size: 3em;
      color: #d10000;
      margin-bottom: 20px;
      animation: fadeInDown 2s ease-out;
      font-family: 'Pacifico', cursive;
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-50px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .typing {
      font-size: 1.3em;
      color: #555;
      overflow: hidden;
      white-space: nowrap;
      border-right: 3px solid #555;
      width: 0;
      animation: typing 4s steps(50, end) forwards, blink 0.75s step-end infinite;
      max-width: 100%;
      font-family: 'Indie Flower', cursive;
  font-weight: 400;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink {
      50% { border-color: transparent }
    }

    .heart {
      width: 100px;
      height: 90px;
      position: relative;
      margin: 30px auto;
      animation: beat 1s infinite ease-in-out;
    }

    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 100px;
      height: 90px;
      background: red;
      border-radius: 50%;
    }

    .heart::before {
      top: 0;
      left: 50px;
      transform: rotate(-45deg);
      transform-origin: left bottom;
    }

    .heart::after {
      top: 0;
      left: 0;
      transform: rotate(45deg);
      transform-origin: right bottom;
    }

    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.3); }
    }

    button {
      margin-top: 25px;
      padding: 14px 28px;
      background: #ff4d4d;
      border: none;
      border-radius: 30px;
      font-size: 1.1em;
      color: white;
      cursor: pointer;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      transition: transform 0.3s ease, background 0.3s;
    }

    button:hover {
      background: #e60000;
      transform: scale(1.1) rotate(-1deg);
    }

    #message {
      margin-top: 30px;
      font-size: 1.2em;
      color: #333;
      max-width: 600px;
      display: none;
      animation: slideInUp 1s ease forwards;
      font-family: 'Indie Flower', cursive;
  font-weight: 400;
    }

    @keyframes slideInUp {
      from { opacity: 0; transform: translateY(50px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .floating-hearts {
      position: absolute;
      width: 100%;
      height: 100%;
      pointer-events: none;
      overflow: hidden;
    }

    .floating-hearts span {
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      transform: rotate(45deg);
      animation: floatUp 10s linear infinite;
    }

    .floating-hearts span::before,
    .floating-hearts span::after {
      content: "";
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      border-radius: 50%;
    }

    .floating-hearts span::before { top: -10px; left: 0; }
    .floating-hearts span::after { left: -10px; top: 0; }

    @keyframes floatUp {
      0% { transform: translateY(100vh) rotate(45deg); opacity: 1; }
      100% { transform: translateY(-10vh) rotate(45deg); opacity: 0; }
    }

    .music-control {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #ffe6e6;
      padding: 10px 16px;
      border-radius: 20px;
      border: none;
      cursor: pointer;
      font-size: 0.9em;
      animation: pulseBtn 2s infinite;
    }

    @keyframes pulseBtn {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }

    @media (max-width: 600px) {
      h1 { font-size: 2em; }
      .typing { font-size: 1em; }
      button, .music-control { font-size: 1em; }
      #message { font-size: 1em; }
    }

    .stickers {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 2;
}

.sticker {
  position: absolute;
  width: 60px;
  animation: bounceSticker 4s infinite ease-in-out;
}

@keyframes bounceSticker {
  0% { transform: translateY(0) rotate(0deg); opacity: 1; }
  50% { transform: translateY(-20px) rotate(5deg); opacity: 0.8; }
  100% { transform: translateY(0) rotate(-5deg); opacity: 1; }
}

  </style>
</head>
<body>

  <!-- Animated floating hearts -->
  <div class="floating-hearts">
    <span style="left: 10%; animation-delay: 0s;"></span>
    <span style="left: 30%; animation-delay: 2s;"></span>
    <span style="left: 50%; animation-delay: 4s;"></span>
    <span style="left: 70%; animation-delay: 1s;"></span>
    <span style="left: 90%; animation-delay: 3s;"></span>
  </div>

  <!-- Apology message -->
  <h1>I’m So Sorry 💔</h1>
  <div class="typing">Please forgive me, sayang...</div>
  <div class="heart"></div>

  <button onclick="showMessage()">Tap here to read my heart 💌</button>

  <div id="message">
    <p>
      I know I hurt you, and I'm so deeply sorry. 💔<br><br>
      I dah buat banyak salah dengan you, Im sorry sayang<br>
      You're the light of my life, and I can't imagine my world without you.<br>
      I promise to grow, to learn, and to always cherish you. <br><br>
      Please give me another chance to love you better. 💖
    </p>
  </div>

  <!-- Cute Sticker Animation -->
<div class="stickers">
  <img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" class="sticker" style="top: 10%; left: 5%;">
  <img src="https://media.giphy.com/media/l3vR3odA1M7XVLrUY/giphy.gif" class="sticker" style="top: 50%; left: 70%;">
  <img src="https://media.giphy.com/media/QvBoMEcQ7DQXK/giphy.gif" class="sticker" style="top: 80%; left: 20%;">
  <img src="https://media.giphy.com/media/yFQ0ywscgobJK/giphy.gif" class="sticker" style="top: 30%; left: 85%;">
</div>


  <!-- Background music -->
  <audio id="bgMusic" autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-love.mp3" type="audio/mp3">
    Your browser does not support the audio element.
  </audio>

  <button class="music-control" onclick="toggleMusic()">🔊 Music</button>

  <script>
    function showMessage() {
  const msg = document.getElementById("message");
  msg.style.display = "block";

  // Trigger confetti burst
  confetti({
    particleCount: 150,
    spread: 100,
    origin: { y: 0.6 }
  });
}



    const music = document.getElementById("bgMusic");
    const control = document.querySelector(".music-control");

    function toggleMusic() {
      if (music.paused) {
        music.play();
        control.textContent = "🔊 Music";
      } else {
        music.pause();
        control.textContent = "🔇 Muted";
      }
    }

    
  </script>
  <!-- Confetti Script -->
<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>

</body>
</html>

