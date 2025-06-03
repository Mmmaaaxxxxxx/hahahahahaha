<!DOCTYPE html>
<html>
<head>
  <title>Babaannemi Ye</title>
  <style>
    body {
      background-color: black;
      font-family: sans-serif;
      text-align: center;
      padding-top: 20%;
    }
    h1 {
      font-size: 3em;
      color: white;
      transition: color 0.5s;
    }
  </style>
  <script>
    function randomColor() {
      const colors = ["#ff6b6b", "#feca57", "#1dd1a1", "#54a0ff", "#5f27cd", "#ffffff"];
      const color = colors[Math.floor(Math.random() * colors.length)];
      document.getElementById("text").style.color = color;
    }
    setInterval(randomColor, 1000);
  </script>
</head>
<body>
  <h1 id="text">babaannemi ye</h1>
</body>
</html>
