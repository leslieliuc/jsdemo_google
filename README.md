<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>實驗頁面</title>
    <style>
        /* 設定頁面背景為深藍色並帶有透明感 */
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            background-color: rgba(0, 0, 139, 0.7); /* 深藍色且透明 */
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
            color: white;
        }

        /* 設定容器，文字和按鍵顯示在中央 */
        .container {
            text-align: center;
        }

        /* 設定按鈕樣式 */
        button {
            background-color: #4CAF50; /* 按鈕顏色 */
            color: white;
            font-size: 18px;
            padding: 15px 32px;
            margin: 10px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #45a049; /* 按鈕懸停顏色 */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>請點選以下按鍵進行實驗</h1>
        <!-- 聽覺實驗按鈕，點擊後跳轉到 "audio_experiment.html" -->
        <button onclick="window.location.href='https://leslieliuc.github.io/js_audio/demo4_sound.html'">聽覺實驗</button>
        <!-- 視覺實驗按鈕，點擊後跳轉到 "visual_experiment.html" -->
        <button onclick="window.location.href='https://leslieliuc.github.io/jsdemo_google/exceldeom2.html'">視覺實驗</button>
    </div>

</body>
</html>
