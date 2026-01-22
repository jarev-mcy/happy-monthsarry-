<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Hi my wifey</title>

  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #ffe6e6;
      font-family: 'Arial', sans-serif;
    }

    .container {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
    }

    h1 { 
      color: #ff4d4d; 
    }

    input {
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 5px;
      width: 200px;
    }

    button {
      padding: 10px 20px;
      background-color: #8b4513;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #a0522d;
    }

    #love-letter {
      margin-top: 20px;
      color: #8b4513;
      font-size: 18px;
    }

    .hidden {
      display: none;
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>Login</h1>

    <form id="login-form">
      <input type="text" id="name" placeholder="Enter your name">
      <br><br>
      <button type="button" onclick="login()">Log In</button>
    </form>

    <div id="love-letter" class="hidden">
      <p>I love you so so much 🥹❤️.</p>
    </div>
  </div>

  <script>
    function login() {
      const name = document.getElementById('name').value;

      if (name === 'princess') {
        document.getElementById('login-form').classList.add('hidden');
        document.getElementById('love-letter').classList.remove('hidden');
      } else {
        alert('Invalid name! Only princess can log in.');
      }
    }
  </script>

</body>
</html>
