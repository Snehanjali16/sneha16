# sneha16<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Profile</title>
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <div class="container">
    <h1>Student Information</h1>
    <ul>
      <li><strong>Name:</strong> Ummulkhairi Ahmad</li>
      <li><strong>Profession:</strong> Student</li>
      <li><strong>Hobbies:</strong> Sewing, Surfing the internet, Coding</li>
      <li><strong>Introduction to Web Application Course:</strong> This course introduces you to a sub-discipline of software engineering that deals with concepts, methods, languages, and tools to develop web-based systems.</li>
    </ul>

    <h2>Examination Time Table</h2>
    <table>
      <tr>
        <th>Course</th>
        <th>Date</th>
        <th>Time</th>
      </tr>
      <tr>
        <td>Web Application</td>
        <td>September 08, 2023</td>
        <td>9:00 am – 12:00 pm</td>
      </tr>
      <tr>
        <td>System Analysis</td>
        <td>September 10, 2023</td>
        <td>9:00 am – 12:00 pm</td>
      </tr>
      <tr>
        <td>Concept of Programming</td>
        <td>September 12, 2023</td>
        <td>9:00 am – 12:00 pm</td>
      </tr>
      <tr>
        <td>Mathematical Modelling</td>
        <td>September 14, 2023</td>
        <td>9:00 am – 12:00 pm</td>
      </tr>
      <tr>
        <td>Computer Architecture</td>
        <td>September 16, 2023</td>
        <td>9:00 am – 12:00 pm</td>
      </tr>
    </table>

    <h2>Exam Registration</h2>
    <form id="examForm">
      <label for="registrationNumber">Registration Number:</label>
      <input type="text" id="registrationNumber" name="registrationNumber" required>
      <br>
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>
      <br>
      <label>Will you take the exam?</label>
      <label for="yesOption">
        <input type="radio" id="yesOption" name="examOption" value="Yes"> Yes
      </label>
      <label for="noOption">
        <input type="radio" id="noOption" name="examOption" value="No"> No
      </label>
      <br>
      <label for="examCenter">Select Exam Center:</label>
      <select id="examCenter" name="examCenter">
        <option value="London">London</option>
        <option value="Abuja">Abuja</option>
        <option value="Dubai">Dubai</option>
        <option value="Zaria">Zaria</option>
      </select>
      <br>
      <input type="submit" value="Submit">
    </form>
  </div>
  <script src="script.js"></script>
</body>

</html>
