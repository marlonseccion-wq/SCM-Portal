<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Google Sheet Canvases</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f9;
    }
    h1 {
      text-align: center;
    }
    .canvas-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 20px;
      max-width: 1200px;
      margin: 20px auto;
    }
    .canvas-card {
      background: #ffffff;
      border: 1px solid #e0e0e0;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      overflow: hidden;
      height: 400px;
    }
    iframe {
      width: 100%;
      height: 100%;
      border: none;
    }
  </style>
</head>
<body>

  <h1>Canvas Dashboard</h1>

  <div class="canvas-grid">
    <!-- Canvas 1 -->
    <div class="canvas-card">
      <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQWazBqgF_W-IbDVr0MVBITpQi4Qs6RliExoIs45ovh1FdS_pIFP8kydjn9i7aiom_QCQO6Ga971ADd/pubhtml?gid=620716235&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
    </div>

    <!-- Canvas 2 -->
    <div class="canvas-card">
      <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQC6fMbBI7BMUZxa3xIys2qhnquSKF8CzKUkQEKknyV07u6aod-z7u0xSrwHlCZc9bsSqiNx-dLgERr/pubhtml?gid=2123976464&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
    </div>

    <!-- Canvas 3 -->
    <div class="canvas-card">
      <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSrCSqMYFYOR_R-1ahTX8KlxDIk0USgGzVnSdb7WsZNZtijIvnXJtIjmdopeuN5HFbg-KywX8VmH82K/pubhtml?gid=36190230&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
    </div>
  </div>

</body>
</html>