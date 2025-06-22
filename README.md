<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunshine Public School - Admission Registration</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #eef6ff;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #0b3d91;
      color: white;
      text-align: center;
      padding: 30px 15px;
    }

    header h1 {
      margin: 0;
      font-size: 32px;
    }

    header p {
      margin-top: 8px;
      font-size: 16px;
    }

    main {
      max-width: 700px;
      margin: 40px auto;
      background-color: #ffffff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 12px rgba(0, 0, 0, 0.1);
    }

    label {
      font-weight: bold;
      display: block;
      margin-top: 20px;
    }

    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 16px;
    }

    button {
      margin-top: 25px;
      padding: 12px 20px;
      background-color: #0b3d91;
      color: white;
      font-size: 16px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    button:hover {
      background-color: #072b6b;
    }

    footer {
      text-align: center;
      background-color: #0b3d91;
      color: white;
      padding: 15px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      main {
        margin: 20px;
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Sunshine Public School</h1>
    <p>Online Admission Registration Form</p>
  </header>

  <!-- Admission Form -->
  <main>
    <form action="#" method="post">
      <label for="name">Student's Full Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required>

      <label for="class">Class Applying For:</label>
      <select id="class" name="class" required>
        <option value="">-- Select Class --</option>
        <option value="Nursery">Nursery</option>
        <option value="LKG">LKG</option>
        <option value="UKG">UKG</option>
        <option value="1st">1st Grade</option>
        <option value="2nd">2nd Grade</option>
        <option value="3rd">3rd Grade</option>
        <option value="4th">4th Grade</option>
        <option value="5th">5th Grade</option>
        <!-- Add more classes if needed -->
      </select>

      <label for="gender">Gender:</label>
      <select id="gender" name="gender" required>
        <option value="">-- Select Gender --</option>
        <option value="Male">Male</option>
        <option value="Female">Female</option>
        <option value="Other">Other</option>
      </select>

      <label for="parent">Parent/Guardian's Name:</label>
      <input type="text" id="parent" name="parent" required>

      <label for="email">Parent's Email Address:</label>
      <input type="email" id="email" name="email">

      <label for="phone">Phone Number:</label>
      <input type="tel" id="phone" name="phone" placeholder="e.g. 9876543210" required pattern="[0-9]{10}">

      <label for="address">Residential Address:</label>
      <textarea id="address" name="address" rows="3" required></textarea>

      <button type="submit">Submit Registration</button>
    </form>
  </main>

  <!-- Footer -->
  <footer>
    &copy; 2025 Sunshine Public School. All Rights Reserved.
  </footer>

</body>
</html>
