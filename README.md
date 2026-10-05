# cyber-lab
Ethical cybersecurity practice lab
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#0b0f19">
  <title>Cyber Lab</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0b0f19;
      color: white;
    }

    .app {
      max-width: 500px;
      min-height: 100vh;
      margin: auto;
      padding: 25px 18px;
    }

    h1 {
      margin-top: 30px;
    }

    .status {
      color: #22c55e;
    }

    .card {
      background: #151b2b;
      padding: 20px;
      border-radius: 18px;
      margin-top: 20px;
    }

    button {
      width: 100%;
      padding: 15px;
      margin-top: 12px;
      border: 0;
      border-radius: 12px;
      background: #2563eb;
      color: white;
      font-size: 16px;
    }
  </style>
</head>

<body>

<div class="app">

  <h1>🛡️ Cyber Lab</h1>

  <p class="status">● Lab Online</p>

  <div class="card">
    <h2>Ethical Hacking Lab</h2>
    <p>Practice cybersecurity using dummy test data.</p>

    <button onclick="challenge('Authentication')">
      Authentication Challenge
    </button>

    <button onclick="challenge('XSS')">
      XSS Challenge
    </button>

    <button onclick="challenge('IDOR')">
      IDOR Challenge
    </button>
  </div>

</div>

<script>
function challenge(name) {
  alert(name + " challenge started!");
}
</script>

</body>
</html>
