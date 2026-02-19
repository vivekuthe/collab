# collab
practical 3
<!DOCTYPE html>
<html>
<head>
    <title>Registration Form</title>
    <style>
        body {
            font-family: Arial;
            background-color: #f2f2f2;
        }

        .container {
            width: 400px;
            margin: auto;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px gray;
        }

        h2 {
            text-align: center;
        }

        input, select {
            width: 100%;
            padding: 8px;
            margin: 5px 0 10px 0;
        }

        button {
            width: 100%;
            padding: 10px;
            background-color: green;
            color: white;
            border: none;
            font-size: 16px;
        }

        button:hover {
            background-color: darkgreen;
        }
    </style>
</head>

<body>

<div class="container">
    <h2>Registration Form</h2>

    <form>

        <label>Full Name:</label>
        <input type="text" name="fullname" required>

        <label>Email:</label>
        <input type="email" name="email" required>

        <label>Password:</label>
        <input type="password" name="password" required>

        <label>Gender:</label>
        <select name="gender">
            <option>Male</option>
            <option>Female</option>
            <option>Other</option>
        </select>

        <label>Mobile Number:</label>
        <input type="tel" name="mobile" required>

        <label>Date of Birth:</label>
        <input type="date" name="dob">

        <button type="submit">Register</button>

    </form>

</div>

</body>
</html>
