<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Generator Angka</title>
</head>
<body>
  <h1>Angka Acak</h1>
  <button onclick="generate()">Generate</button>
  <p id="output"></p>

  <script>
    function generate() {
      const random = Math.floor(Math.random() * 100) + 1;
      document.getElementById('output').innerText = 'Angka: ' + random;
    }
  </script>
</body>
</html>
