<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Selamat Pagi Sayang!</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: linear-gradient(135deg, #f9d423, #ff4e50);
      color: white;
      text-align: center;
    }
    .container {
      padding: 20px;
      background: rgba(0, 0, 0, 0.3);
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    #message {
      display: none;
      margin-top: 20px;
      font-size: 1.2rem;
      color: #f3f3f3;
    }
    button {
      background-color: #ff5722;
      border: none;
      padding: 10px 20px;
      color: white;
      font-size: 1rem;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #e64a19;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Selamat Pagi Sayang!</h1>
    <p>Klik tombol di bawah ini yaa...untuk memulai harimu dengan semangat.</p>
    <button onclick="showMessage()">Klik untuk Semangat!</button>
    <div id="message">Semangat menjalani hari ini gyalita Ingat, setiap langkah kecil mendekatkanmu pada impian besar. :)</div>
  </div>

  <script>
    function showMessage() {
      document.getElementById('message').style.display = 'block';
    }
  </script>
</body>
</html>
