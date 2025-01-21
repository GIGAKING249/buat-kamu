# buat-kamu
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tebak-Tebakan Cinta</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="login" id="login">
            <h1>Masukkan Password</h1>
            <input type="password" id="password" placeholder="Password">
            <button onclick="checkPassword()">Masuk</button>
            <p id="error" class="hidden">Password salah, coba lagi!</p>
  </div>
    <div class="game hidden" id="game">
            <h1>Tebak-Tebakan Cinta</h1>
            <p id="question"></p>
            <input type="text" id="answer" placeholder="Jawaban kamu">
            <button onclick="checkAnswer()">Jawab</button>
            <p id="feedback"></p>
    </div>
      <div class="result hidden" id="result">
            <h1>❤️ Aku cuma cinta kamu ❤️</h1>
            <p>Kamu itu jawaban dari semua pertanyaanku.</p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
