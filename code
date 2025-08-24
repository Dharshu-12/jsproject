<!DOCTYPE html>
<html>
<head>
  <title>Digital Clock</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: black;
      color: lime;
      font-size: 50px;
      font-family: monospace;
    }
    #clock {
      padding: 20px;
      border: 3px solid lime;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <div id="clock"></div>

  <script>
    function updateClock() {
      let now = new Date();
      let h = String(now.getHours()).padStart(2, '0');
      let m = String(now.getMinutes()).padStart(2, '0');
      let s = String(now.getSeconds()).padStart(2, '0');
      document.getElementById("clock").innerText = `${h}:${m}:${s}`;
    }

    setInterval(updateClock, 1000);
    updateClock(); // call once at start
  </script>
</body>
</html>
