
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sign Up</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      display: flex;
      height: 100vh;
    }

    .left {
      flex: 1;
      background: linear-gradient(to right, #d16ba5, #86a8e7);
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
    }

    .left img {
      max-width: 90%;
      border-radius: 10px;
    }

    .right {
      flex: 1;
      padding: 60px;
       background: #fff;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
      .form-container {
      max-width: 400px;
      margin: auto;
    }

    h2 {
      margin-bottom: 30px;
      font-size: 32px;
    }

    label {
       color: darkgrey;
        display: block;
      margin-top: 15px;
      font-weight: bold;
    }

    input[type="text"],
input[type="email"],
input[type="password"] {
  width: 100%;
  padding: 10px 5px;
  border: none;
  border-bottom: 2px solid #ccc;
  background: transparent;
  font-size: 14px;
  transition: border-color 0.3s ease;
}

input[type="text"]:hover,
input[type="email"]:hover,
input[type="password"]:hover {
  border-bottom: 2px solid #d16ba5;
}

input:focus {
  border-bottom: 2px solid #86a8e7;
  outline: none;
}

    .checkbox {
      margin-top: 20px;
      display: flex;
      align-items: center;
    }

    .checkbox input {
      margin-right: 10px;
      accent-color: #b3708f;
    }

  .button {
  background: linear-gradient(to right, #d16ba5, #86a8e7);
  color: white;
  border: none;
  padding: 12px 20px;
  border-radius: 25px;
  cursor: pointer;
  font-size: 16px;
  display: block;
  text-align: center;
  text-decoration: none;
  width: 100%;
}
.button:hover {
  color: #572a45;
}
    .signin-link {
      margin-top: 15px;
    }

    .signin-link a {
      color: #666;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="left">
    <!-- Image side -->
    <img src="IMG_0563.jpeg" alt="User">
  </div>
  <div class="right">
    <h2>Sign Up</h2>
    <form>
      <label>Full Name</label>
      <input type="text" placeholder="Haji Bhola" required>

      <label>Email</label>
      <input type="email" placeholder="Haji-Bhola@example.com" required>

      <label>Username</label>
      <input type="text" placeholder="hajibhola" required>

      <label>Password</label>
      <input type="password" placeholder="**********" required>

      <label>Repeat Password</label>
      <input type="password" placeholder="**********" required>

      <div class="checkbox">
        <input type="checkbox" required>
        <span>I agree to the <a href="#">Terms of User</a></span>
      </div>

       <div class="buttons">
    <a href="signup.html" class="button">Sign Up</a>
    </div>

      <div class="signin-link">
        Already have an account? <a href="signin.html">Sign in →</a>
      </div>
    </form>
  </div>
</body>
</html>