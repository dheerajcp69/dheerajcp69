<html>
  <head>
    <meta charset="UTF-8" />
    <script src="script.js"></script>
    <link rel="stylesheet" type="text/css" href="styles.css" />
  </head>
  <body onload="document.registration.userid.focus();">
    <h1>Registration Form</h1>
    Use tab keys to move from one input field to the next.
    <form name="registration" onSubmit="return formValidation();">
      <ul>
        <li><label for="userid">User id:</label></li>
        <li><input type="text" name="userid" size="12" /></li>
        <li><label for="passid">Password:</label></li>
        <li><input type="password" name="passid" size="12" /></li>
        <li><label for="username">User Name:</label></li>
        <li><input type="text" name="username" size="50" /></li>
        <li><label for="email">Email:</label></li>
        <li><input type="text" name="email" size="50" /></li>
        <li><label for="phonenumber">Phone Number:</label></li>
        <li><input type="text" name="phonenumber" size="10" /></li>
        <li><input type="submit" name="submit" value="Submit" /></li>
      </ul>
    </form>
  </body>
</html>
