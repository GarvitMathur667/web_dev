# web_dev
<!DOCTYPE html>
<html>
<head>
  <title>Survey Form</title>
</head>
<body>
  <h1>Survey Form</h1>
  
  <form action="/submit-survey" method="post">
    <h2>Basic Questions</h2>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>

    <label for="age">Age:</label>
    <input type="number" id="age" name="age" required><br><br>

    <h2>Checkbox Questions</h2>
    <label for="interests">Interests:</label><br>
    <input type="checkbox" id="interest1" name="interests" value="sports">
    <label for="interest1">Sports</label><br>
    <input type="checkbox" id="interest2" name="interests" value="music">
    <label for="interest2">Music</label><br>
    <input type="checkbox" id="interest3" name="interests" value="art">
    <label for="interest3">Art</label><br><br>

    <h2>Radio Button Question</h2>
    <label for="gender">Gender:</label><br>
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label><br>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label><br>
    <input type="radio" id="other" name="gender" value="other">
    <label for="other">Other</label><br><br>

    <h2>Dropdown Option</h2>
    <label for="country">Country:</label>
    <select id="country" name="country">
      <option value="usa">USA</option>
      <option value="canada">Canada</option>
      <option value="uk">UK</option>
      <option value="australia">Australia</option>
    </select><br><br>

    <input type="submit" value="Submit">
  </form>
</body>
</html>
