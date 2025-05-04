<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Forex Robot Signals</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #1e1e2f;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    .container {
      padding: 20px;
    }
    .signal {
      background: #fff;
      padding: 15px;
      margin-bottom: 10px;
      border-left: 5px solid green;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .signal.sell {
      border-left: 5px solid red;
    }
    .timestamp {
      font-size: 0.85rem;
      color: #888;
    }
    .pair {
      font-size: 1.2rem;
      font-weight: bold;
    }
    .type {
      font-size: 1rem;
      font-weight: bold;
    }
    .footer {
      text-align: center;
      padding: 20px;
      background: #1e1e2f;
      color: #fff;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    .footer a {
      color: #00ffff;
      text-decoration: underline;
    }
    @media (max-width: 600px) {
      .container {
        padding: 10px;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Forex Robot Live Signals</h1>
</header>

<div class="container">
  <div class="signal buy">
    <div class="timestamp">2025-05-04 10:00 UTC</div>
    <div class="pair">EUR/USD</div>
    <div class="type">BUY</div>
  </div>
  <div class="signal sell">
    <div class="timestamp">2025-05-04 09:45 UTC</div>
    <div class="pair">GBP/JPY</div>
    <div class="type">SELL</div>
  </div>
  <div class="signal buy">
    <div class="timestamp">2025-05-04 09:30 UTC</div>
    <div class="pair">USD/CHF</div>
    <div class="type">BUY</div>
  </div>
</div>

<div class="footer">
  &copy; 2025 Forex Robot. All rights reserved. |
  <a href="https://github.com/aron683/forexrobot.git" target="_blank">GitHub Repo</a>
</div>

</body>
</html>
