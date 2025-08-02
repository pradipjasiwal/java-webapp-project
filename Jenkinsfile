<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Spider Hanging on Wall</title>
  <style>
    body {
      background-color: #111;
      color: #fff;
      font-family: Arial, sans-serif;
      text-align: center;
      height: 100vh;
      margin: 0;
      overflow: hidden;
    }

    .wall {
      position: relative;
      width: 100%;
      height: 100%;
    }

    .thread {
      position: absolute;
      top: 0;
      left: 50%;
      width: 2px;
      height: 100px;
      background-color: #ccc;
      transform: translateX(-50%);
    }

    .spider {
      position: absolute;
      top: 100px;
      left: 50%;
      width: 40px;
      height: 40px;
      background-color: black;
      border-radius: 50%;
      transform: translateX(-50%);
      animation: wiggle 2s infinite ease-in-out;
    }

    .spider::before,
    .spider::after {
      content: '';
      position: absolute;
      width: 30px;
      height: 2px;
      background-color: black;
    }

    .spider::before {
      top: 10px;
      left: -30px;
      transform: rotate(45deg);
    }

    .spider::after {
      top: 10px;
      right: -30px;
      transform: rotate(-45deg);
    }

    @keyframes wiggle {
      0%, 100% { transform: translateX(-50%) rotate(0deg); }
      50% { transform: translateX(-50%) rotate(5deg); }
    }
  </style>
</head>
<body>
  <div class="wall">
    <div class="thread"></div>
    <div class="spider"></div>
  </div>
  <h1>🕷️ Beware... something crawls in the dark!</h1>
</body>
</html>
