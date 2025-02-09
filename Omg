<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Proposal for Nishika ❤️</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      text-align: center;
      background: linear-gradient(to bottom, #ffe6f0, #ffcccc);
      color: #333;
      padding: 20px;
    }
    .question-container {
      display: none;
      animation: fadeIn 1.5s ease-in-out;
    }
    .active {
      display: block;
    }
    h1 {
      font-size: 3rem;
      color: #d81b60;
      animation: fadeInDown 2s;
    }
    p {
      font-size: 1.5rem;
      margin: 15px 0;
    }
    .shayari {
      font-style: italic;
      font-size: 1.3rem;
      color: #880e4f;
      animation: fadeInUp 2s;
    }
    button {
      padding: 15px 30px;
      font-size: 1.2rem;
      color: white;
      background-color: #c2185b;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      margin: 10px;
      transition: background-color 0.3s, transform 0.2s;
    }
    button:hover {
      background-color: #880e4f;
      transform: scale(1.05);
    }
    .gif {
      width: 350px;
      height: auto;
      margin: 20px auto;
      border-radius: 10px;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <audio id="bg-music" loop>
    <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mpeg">
  </audio>

  <div class="question-container active" id="question1">
    <h1>Hey Nishika! 😊</h1>
    <p class="shayari">"Teri muskurahat se roshan meri duniya hai,<br> Har pal tera saath hi meri tamanna hai."</p>
    <button onclick="nextQuestion('question2')">Suno, Vishal! 💬</button>
  </div>

  <div class="question-container" id="question2">
    <h1>Ek Sawaal Puchhun? 💭</h1>
    <p class="shayari">"Tumhare bina zindagi adhoori si lagti hai,<br> Kya tum meri zindagi poori karogi?"</p>
    <button onclick="nextQuestion('question3')">Haan, zaroor! 😊</button>
  </div>

  <div class="question-container" id="question3">
    <h1>Mujhe Ek Baat Kehni Hai... 🌹</h1>
    <p class="shayari">"Zindagi ki har ek subah tumhari muskan se shuru ho,<br> Aur har ek raat tumhari baahon mein khatam ho."</p>
    <p>Nishika, kya tum Vishal ki zindagi ka hamesha ke liye hissa banogi? ❤️</p>
    <button onclick="nextQuestion('question4')">Aur batao! 🌟</button>
  </div>

  <div class="question-container" id="question4">
    <h1>Aakhri Sawaal... 💍</h1>
    <p class="shayari">"Main tumhe har pal khush rakhna chahta hoon,<br> Kya tum mujhe apne dil ka humsafar banaogi?"</p>
    <img src="https://media.giphy.com/media/l2SpYuv1gVBhGbsLe/giphy.gif" alt="Proposal GIF" class="gif">
    <button onclick="finalStep()">Haan, Vishal! 💖</button>
  </div>

  <div class="question-container" id="final">
    <h1>Shukriya, Nishika! 🎉</h1>
    <p class="shayari">"Ab har ek khushi tumhare sang hai,<br> Har ek sapna sirf hamara hai."</p>
    <p>Thank you for saying yes! Vishal is now the happiest person in the world. 🥰</p>
    <p>Yeh safar ab hamesha ke liye hum dono ka hai! ❤️</p>
    <canvas id="confetti-canvas"></canvas>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.4.0/dist/confetti.browser.min.js"></script>
  <script>
    function nextQuestion(nextId) {
      document.querySelectorAll('.question-container').forEach(container => {
        container.classList.remove('active');
      });
      document.getElementById(nextId).classList.add('active');
    }

    function finalStep() {
      nextQuestion('final');
      playConfetti();
    }

    function playConfetti() {
      confetti({
        particleCount: 100,
        spread: 70,
        origin: { y: 0.6 }
      });
      document.getElementById('bg-music').play();
    }
  </script>

</body>
</html>
