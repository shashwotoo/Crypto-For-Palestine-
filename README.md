  <!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Crypto for Palestine</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #222;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #111;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    .container {
      max-width: 800px;
      margin: auto;
      padding: 40px 20px;
    }
    h1, h2, h3 {
      color: #0a0a23;
    }
    .wallet {
      margin: 30px 0;
    }
    .wallet h3 {
      margin-bottom: 10px;
    }
    .qr {
      width: 200px;
      height: 200px;
      margin-bottom: 10px;
    }
    .address {
      font-family: monospace;
      background: #eee;
      padding: 10px;
      border-radius: 5px;
      word-break: break-all;
    }
    .tracker {
      background: #e6f2ff;
      padding: 20px;
      margin-top: 40px;
      border-left: 5px solid #007BFF;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
    nav a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Crypto for Palestine</h1>
    <nav>
      <a href="#donate">Donate</a>
      <a href="#tracker">Donation Tracker</a>
    </nav>
  </header>  <div class="container" id="donate">
    <h2>Make a Difference with Crypto</h2>
    <p>Your donation helps provide urgent aid—food, shelter, and medical support—for the people of Gaza. 100% of donations go directly to those affected, with full transparency.</p><div class="wallet">
  <h3>USDT / ETH (ERC-20):</h3>
  <img src="qr-code.png" alt="MetaMask QR Code" class="qr">
  <div class="address">0x14214acA77a0863D1d70575FF34a061496DB9Eb4</div>
</div>

<div class="wallet">
  <h3>BTC:</h3>
  <div class="address">bc1qrl9md39ys89e99ssry0eagw5lhd7qrmqa09qn4</div>
</div>

  </div>  <div class="container" id="tracker">
    <h2>Donation Tracker</h2>
    <div class="tracker">
      <p><strong>Total Raised:</strong> <span id="raised">$0</span></p>
      <p><strong>Goal:</strong> $10,000</p>
      <progress id="progress" value="0" max="10000" style="width: 100%; height: 20px;"></progress>
    </div>
  </div>  <footer>
    <p>&copy; 2025 Crypto for Palestine. All rights reserved.</p>
  </footer>  <script>
    // Fake tracker logic (replace with real data or integration later)
    const totalRaised = 2650; // Example amount in USD
    document.getElementById("raised").innerText = `$${totalRaised.toLocaleString()}`;
    document.getElementById("progress").value = totalRaised;
  </script></body>
</html>
