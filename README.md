# Students-status-tracker
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Registration Form</title>
  <link rel="stylesheet" href="style1.css"> 
</head>
<body>
  <div class="container">
    <h2>Registration Form</h2>
    <form action="registration_process.php" method="POST">
      <label for="username">Username:</label>
      <input type="text" id="username" name="username" required>

  <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

  <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>

  <label for="confirm_password">Confirm Password:</label>
      <input type="password" id="confirm_password" name="confirm_password" required>

  <button  type="submit"><a href="index3.html"><span></span>Register</a></button>

  </form>
  </div>
</body>
</html>
