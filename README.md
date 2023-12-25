
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Go Out With Me?</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 100px;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      margin: 10px;
      cursor: pointer;
    }

    #noBtn {
      background-color: red;
      color: white;
    }

    #yesBtn {
      background-color: green;
      color: white;
    }
  </style>
</head>
<body>

  <h1>Want to go out with me?</h1>

  <button id="noBtn" onclick="changeButton()">No</button>
  <button id="yesBtn" style="display: none;" onclick="alert('Great!')">Yes</button>

  <script>
    function changeButton() {
      var noButton = document.getElementById('noBtn');
      var yesButton = document.getElementById('yesBtn');

      noButton.style.display = 'none';
      yesButton.style.display = 'inline-block';
    }
  </script>

</body>
</html>
