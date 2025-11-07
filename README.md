# bk-007bettadarasamma.github.io
<!DOCTYPE html>
<html lang="kn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>🙏 ಬೆಟ್ಟದಾರಸಮ್ಮ ದೇವಿ 🙏</title>
  <style>
    body {
      margin: 0;
      font-family: "Tunga", Arial, sans-serif;
      background: linear-gradient(to right, #ffcccc, #ffe6cc, #ffffcc, #e6ffe6, #e6f7ff);
      text-align: center;
    }
    header {
      background: darkred;
      color: white;
      padding: 20px;
      font-size: 32px;
      font-weight: bold;
    }
    p {
      font-size: 20px;
      color: darkblue;
      margin: 15px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }
    .gallery img {
      width: 300px;
      height: 250px;
      object-fit: cover;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(0,0,0,0.4);
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    footer {
      background: #333;
      color: white;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>🙏 ಶ್ರೀ ಬೆಟ್ಟದಾರಸಮ್ಮ ದೇವಿ 🙏</header>

  <p>ಈ ವೆಬ್‌ಸೈಟ್ ಬೆಟ್ಟದಾರಸಮ್ಮ ಅಮ್ಮನಿಗೆ ಸಮರ್ಪಿತವಾಗಿದೆ. 🌸</p>

  <div class="gallery">
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/36/Hindu_Goddess.jpg" alt="Devi Photo 1">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/11/Durga_Maa.jpg" alt="Devi Photo 2">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Hindu_goddess.jpg" alt="Devi Photo 3">
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Durga_Mata.jpg" alt="Devi Photo 4">
  </div>

  <footer>
    © 2025 | Bettadarasamma Devi Website | Created with ❤️
  <footer/>
<head>
  <meta charset="utf-8">
  <title>SSLC Result Lookup</title>
</head>
<body>
  <h2>Enter Name and Quiz ID</h2>
  <input id="name" placeholder="Name">
  <input id="quiz" placeholder="Quiz ID">
  <button onclick="getResult()">View Result</button>
  <pre id="out"></pre>

<script>
async function getResult(){
  const name = document.getElementById('name').value;
  const quiz = document.getElementById('quiz').value;
  const res = await fetch(`/api/result?quiz_id=${encodeURIComponent(quiz)}&name=${encodeURIComponent(name)}`);
  const data = await res.json();
  document.getElementById('out').textContent = JSON.stringify(data, null, 2);
}
</script>
</body>
</html>
</body>
</html>
