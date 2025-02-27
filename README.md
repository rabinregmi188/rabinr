<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Event Registration Form</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }
    .form-container {
      width: 600px;
      margin: 30px auto;
      background: #fff;
      border: 1px solid #ccc;
      padding: 20px;
    }
    h1, h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .form-group {
      margin-bottom: 15px;
    }
    label {
      display: inline-block;
      width: 150px;
      font-weight: bold;
    }
    input[type="text"],
    input[type="email"],
    input[type="tel"],
    select,
    textarea {
      width: 400px;
      padding: 8px;
    }
    button {
      background: #a41e34;
      color: #fff;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      float: right;
    }
    button:hover {
      background: #8d172c;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h1>Computer Science Career Networking Event</h1>
    <h2>Registration Form</h2>
    <form action="#" method="GET">
      <!-- You can change this to POST and set action to a server script if you have one -->
      <div class="form-group">
        <label for="fullName">Full Name:</label>
        <input type="text" id="fullName" name="fullName" required />
      </div>

      <div class="form-group">
        <label for="emailAddress">Email Address:</label>
        <input type="email" id="emailAddress" name="emailAddress" required />
      </div>

      <div class="form-group">
        <label for="phoneNumber">Phone Number:</label>
        <input type="tel" id="phoneNumber" name="phoneNumber" required />
      </div>

      <div class="form-group">
        <label for="yearOfStudy">Year of Study:</label>
        <select id="yearOfStudy" name="yearOfStudy" required>
          <option value="">--Select--</option>
          <option value="Freshman">Freshman</option>
          <option value="Sophomore">Sophomore</option>
          <option value="Junior">Junior</option>
          <option value="Senior">Senior</option>
        </select>
      </div>

      <div class="form-group">
        <label for="areasOfInterest">Areas of Interest:</label>
        <textarea id="areasOfInterest" name="areasOfInterest" rows="3" placeholder="e.g., AI, Web Development, Cybersecurity" required></textarea>
      </div>

      <button type="submit">Submit Registration</button>
    </form>
  </div>
</body>
</html>
