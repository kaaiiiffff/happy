<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Ishant</title>
  <style>
    body {
      margin: 0;
      background: #000;
      color: #fff;
      font-family: 'Comic Sans MS', cursive;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    h1 {
      font-size: 3em;
      color: magenta;
      text-align: center;
      animation: glow 1s ease-in-out infinite alternate;
    }

    p {
      font-size: 1.5em;
      color: lightgreen;
      text-align: center;
      margin-top: 10px;
    }

    button {
      margin-top: 20px;
      font-size: 1.2em;
      padding: 10px 20px;
      background: magenta;
      color: white;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: deeppink;
    }

    @keyframes glow {
      from { text-shadow: 0 0 10px magenta; }
      to   { text-shadow: 0 0 20px white, 0 0 30px magenta; }
    }

    canvas {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      z-index: -1;
    }
  </style>
</head>
<body>
  <canvas id="confetti"></canvas>

  <h1>🎉 HAPPY BIRTHDAY ISHANT 🎉</h1>
  <p>💖 Wishing you joy, success, and an amazing year ahead! 💖</p>

  <button onclick="showSurprise()">Click for Surprise 🎁</button>

  <!-- Background Music -->
  <audio id="bg-music" autoplay loop>
    <source src="birthday.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <script>
   function showSurprise() {
  alert("🎉 Party kab dera bhadwa!? 😂");
}

    // Confetti effect
    const canvas = document.getElementById("confetti");
    const ctx = canvas.getContext("2d");
    let W = window.innerWidth;
    let H = window.innerHeight;
    canvas.width = W;
    canvas.height = H;

    const confetti = [];

    for (let i = 0; i < 150; i++) {
      confetti.push({
        x: Math.random() * W,
        y: Math.random() * H,
        r: Math.random() * 6 + 4,
        d: Math.random() * 150 + 50,
        color: `hsl(${Math.random() * 360}, 100%, 70%)`,
        tilt: Math.random() * 10 - 10
      });
    }

    function draw() {
      ctx.clearRect(0, 0, W, H);
      confetti.forEach((c, i) => {
        ctx.beginPath();
        ctx.lineWidth = c.r;
        ctx.strokeStyle = c.color;
        ctx.moveTo(c.x + c.tilt, c.y);
        ctx.lineTo(c.x, c.y + c.tilt + 10);
        ctx.stroke();
      });
      update();
    }

    let angle = 0;

    function update() {
      angle += 0.01;
      confetti.forEach((c, i) => {
        c.y += Math.cos(angle + c.d) + 1 + c.r / 2;
        c.x += Math.sin(angle);
        if (c.y > H) {
          confetti[i] = {
            ...c,
            x: Math.random() * W,
            y: -10
          };
        }
      });
    }

    setInterval(draw, 20);

    window.addEventListener("resize", () => {
      W = window.innerWidth;
      H = window.innerHeight;
      canvas.width = W;
      canvas.height = H;
    });
  </script>
</body>
</html>
