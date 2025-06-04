# Jk
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Surprise Audio 🎵</title>
  <style>
    body {
      background-color: #1e1e1e;
      color: #fff;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }
    h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    button {
      padding: 1rem 2rem;
      font-size: 1.2rem;
      background-color: #ff4081;
      border: none;
      border-radius: 12px;
      color: white;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #e91e63;
    }
  </style>
</head>
<body>

  <h1>Tap to Listen 🔥</h1>
  <button onclick="playAudio()">Play Audio</button>

  <audio id="myAudio" loop>
    <source src="https://media.vocaroo.com/mp3/1kb2k6Q0z0lW" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <script>
    function playAudio() {
      document.getElementById("myAudio").play();
    }
  </script>

</body>
</html>
