<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Chào mừng bạn!</title>
  <style>
    body {
      background: linear-gradient(135deg, #f0f8ff, #d0e6ff);
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
      animation: fadeIn 1s ease-in;
      text-align: center;
    }

    h1 {
      color: #2c3e50;
      font-size: 3em;
      animation: slideIn 1.2s ease-out forwards;
      opacity: 0;
    }

    p {
      font-size: 1.3em;
      color: #555;
      margin-top: 10px;
      animation: fadeIn 2s ease-in;
    }

    @keyframes slideIn {
      0% {
        transform: translateY(40px);
        opacity: 0;
      }
      100% {
        transform: translateY(0);
        opacity: 1;
      }
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
  <script>
    setTimeout(function() {
      window.location.href = "https://drive.google.com/drive/folders/123Ci5ApE6S0fM9IRGcon4KzY2Ks3pZ1M?usp=drive_link";
    }, 4000);
  </script>
</head>
<body>
  <h1>🎉 Chào mừng bạn!</h1>
  <p>Chúng tôi đang đưa bạn đến tài liệu cần thiết...</p>
</body>
</html>
