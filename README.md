# Serprise-for-u<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เซอร์ไพรส์สำหรับที่รัก 💖</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>ถึงคนพิเศษของเค้า 💕</h1>
        <p>ที่รักรู้มั้ยว่าเค้ารักที่รักแค่ไหน? 🥰</p>

        <!-- ปุ่มเล่นเพลง -->
        <button onclick="playMusic()">กดเล่นเพลง 🎶</button>
        <audio id="loveSong" src="เพลงของหนู.mp3"></audio>

        <!-- คำถามให้แฟนตอบ -->
        <h2>คำถามพิเศษสำหรับที่รัก 💖</h2>
        <p>ที่รักคิดว่าเค้ารักที่รักขนาดไหน?</p>
        <input type="text" id="answer" placeholder="พิมพ์คำตอบที่นี่">
        <button onclick="checkAnswer()">ส่งคำตอบ</button>

        <p id="result"></p>
    </div>

    <script src="script.js"></script>
</body>
</html>
