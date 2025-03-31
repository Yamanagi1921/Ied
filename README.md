<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kartu Ucapan Selamat Hari Raya Idul Fitri</title>
    <style>
        body {
            font-family: dari komunitas coding  javascript;
            background-color: #f0f8ff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .card {
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            padding: 20px;
            text-align: center;
            width: 300px;
        }
        h1 {
            color: #4CAF50;
        }
        p {
            font-size: 18px;
            color: #333;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            padding: 10px 15px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<div class="card">
    <h1>Selamat Hari Raya Idul Fitri!</h1>
    <p>Semoga hari yang suci ini membawa kedamaian dan kebahagiaan.</p>
    <button onclick="showMessage()">Ucapan</button>
    <p id="message" style="display:none; margin-top: 10px; color: #4CAF50;"></p>
</div>

<script>
    function showMessage() {
        const messageElement = document.getElementById('message');
        messageElement.innerText = "Taqabbalallahu minna wa minkum. Selamat Idul Fitri!";
        messageElement.style.display = 'block';
    }
</script>

</body>
  </html>
