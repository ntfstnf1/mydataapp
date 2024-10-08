<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QR 코드 페이지</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .qr-container {
            display: flex;
            gap: 20px;
        }
        .qr-code {
            text-align: center;
        }
        img {
            width: 150px;
            height: 150px;
        }
    </style>
</head>
<body>
    <div class="qr-container">
        <div class="qr-code">
            <img src="D:\download\나의건강기록_IOS.png" alt="QR 코드 1">
            <p>나의 건강 기록 iOS</p>
        </div>
        <div class="qr-code">
            <img src="D:\download\나의건강기록_안드로이드.png" alt="QR 코드 2">
            <p>나의 건강 기록 안드로이드</p>
        </div>
        <div class="qr-code">
            <img src="D:\download\플러스.png" alt="QR 코드 3">
            <p>플러스 기능</p>
        </div>
    </div>
</body>
</html>
