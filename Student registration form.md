<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration</title>
</head>
<body>

    <h2>Student Registration Form</h2>

    <form action="#" method="post">
        <fieldset>
            <legend>Personal Information</legend>

            <label for="fullName">Student Full Name:</label>
            <input type="text" id="fullName" name="fullName" required><br><br>

            <label for="address">Address:</label><br>
            <textarea id="address" name="address" rows="4" cols="50"></textarea><br><br>

            <label for="mobile">Mobile Number:</label>
            <input type="tel" id="mobile" name="mobile" required><br><br>

            <label for="email">Email Id:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required><br><br>
        </fieldset>

        <fieldset>
            <legend>Academic Information</legend>

            <label for="department">Department Name:</label>
            <select id="department" name="department">
                <option value="cs">Computer Science</option>
                <option value="it">Information Technology</option>
                <option value="ece">Electronics and Communication</option>
                <option value="me">Mechanical Engineering</option>
            </select><br><br>

            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br><br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <label>Hobbies:</label><br>
            <input type="checkbox" id="reading" name="hobbies" value="reading">
            <label for="reading">Reading</label><br>
            <input type="checkbox" id="sports" name="hobbies" value="sports">
            <label for="sports">Sports</label><br>
            <input type="checkbox" id="music" name="hobbies" value="music">
            <label for="music">Music</label><br><br>
        </fieldset>

        <fieldset>
            <legend>Additional Information</legend>

            <label for="photo">Upload Photo:</label>
            <input type="file" id="photo" name="photo"><br><br>

            <input type="submit" value="Submit">
        </fieldset>
    </form>

</body>
</html>
