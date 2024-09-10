<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>لعبة الذكاء</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="game-container">
        <h1>لعبة الذكاء</h1>
        <div id="question">سؤال سيظهر هنا</div>
        <div id="timer">المؤقت: <span id="time">30</span> ثواني</div>
        <div id="answers">
            <button class="answer-btn" onclick="checkAnswer(1)">إجابة 1</button>
            <button class="answer-btn" onclick="checkAnswer(2)">إجابة 2</button>
            <button class="answer-btn" onclick="checkAnswer(3)">إجابة 3</button>
            <button class="answer-btn" onclick="checkAnswer(4)">إجابة 4</button>
        </div>
        <div id="result"></div>
        <button id="next-btn" onclick="nextQuestion()">السؤال التالي</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
