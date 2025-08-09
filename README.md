<img width="1919" height="1021" alt="image" src="https://github.com/user-attachments/assets/d6c9e235-e247-442b-865e-6219753994b3" />


<!DOCTYPE html>
<html>
<head>
  <title>Click Counter</title>
</head>
<body>

  <button onclick="count++ ; document.getElementById('count').innerText = count + ' clicks'">Click me!</button>
  <p id="count">0 clicks</p>

  <script>
    let count = 0;
  </script>

</body>
</html>
