# week1-1-
<html>
<head>
    <meta charset="UTF-8">
    <title>Student Registration Form</title>
</head>
<body>
    <form action="/submit" method="post">

    <label for ="name">Student Name:</label>
    <input type ="text" id="name" name="student_name" required><br><br>

    <label for ="roll no">Roll Number:</label>
    <input type="text" id="roll no" name="roll no" required><br><br>

    <label for ="email">Email:</label>
    <input type="text" id ="Email" name="Email" required><br><br>

    <label>Gender:</label>
    <input type="radio" id="male" name="gender" value="Male" required>
    <label for="male">Male</label>
    <input type="radio" id="Female" name="gender" value="Female" required>
    <label for="Female">Female</label>
    <input type="radio" id="other" name="gender" value="other" required>
    <label for="other">Other</label><br><br>

    <label for="branch">Branch:</label>
    <select id="branch" name="branch" required>
        <option value="">--SELECT BRANCH--</option>
        <option value="IT">Inf</option>
        <option value="ece">Electric</option>



        # Student Registration Form

This project is a simple HTML form used to collect student information, including name, roll number, email, gender, and branch. It is designed to submit the data using the POST method to a backend server (e.g., using PHP, Node.js, Flask, etc.).

## 📋 Features

- Collects:
  - Student Name
  - Roll Number
  - Email (validated)
  - Gender (Male/Female/Other)
  - Branch (select from dropdown)
- Input validation using HTML5 (`required`, `type="email"`)
- Responsive structure with clean HTML

## 💡 Usage

1. Clone or download the project folder.
2. Open `index.html` in your browser.
3. Fill in the form and click **Submit**.

> 🔧 Note: The form currently submits to `/submit`, so you'll need a server backend to process the form data.

## 🛠 Technologies Used

- HTML5
- No CSS or JavaScript (yet) — feel free to extend it

## 🔄 Future Improvements

- Add CSS styling for better UI
- Add client-side validation (JavaScript)
- Connect to a backend (PHP, Flask, Node.js)
- Save submissions to a database

## 📁 File Structure


        </select><br><br>

        <button type="submit">Submit</button>

    </form>
</body>
</html>
