# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Practice Page</title>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>My Roman Numeral List</h2>
        <ol type="I">
            <li>Learn HTML</li>
            <li>Practice CSS</li>
            <li>Understand JavaScript</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Beautiful Scenery</h2>
        <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" 
             alt="Nature from Pexels" 
             width="500">
    </section>

    <!-- Contact Table -->
    <section>
        <h2>Contact List</h2>
        <table border="1" cellpadding="10">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John </td>
                    <td>123 Main St</td>
                    <td>Mogadisho</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane </td>
                    <td>Nairobi</td>
                    <td>+2345678901</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Mike </td>
                    <td>Addis Abba</td>
                    <td>+3456789012</td>
                    <td>mike@example.com</td>
                </tr>
                <tr>
                    <td>Sara Lee</td>
                    <td>kinshasa</td>
                    <td>+4567890123</td>
                    <td>sara@example.com</td>
                </tr>
                <tr>
                    <td>Emma Brown</td>
                    <td>Puntland</td>
                    <td>+5678901234</td>
                    <td>emma@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>Registration Form</h2>
        <form>
            <!-- Name -->
            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <!-- Email -->
            <label for="email">Email Address:</label><br>
            <input type="email" id="email" name="email" placeholder="you@example.com" required><br><br>

            <!-- Password -->
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="Choose a strong password" minlength="6" required><br><br>

            <!-- Date -->
            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required><br><br>

            <!-- Dropdown -->
            <label for="country">Country:</label><br>
            <select id="country" name="country" required>
                <option value="">--Select--</option>
                <option value="us">Kenya</option>
                <option value="uk">United Kingdom</option>
                <option value="ca">Somalia</option>
                <option value="au">Australia</option>
            </select><br><br>

            <!-- Radio Buttons -->
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br><br>

            <!-- Checkboxes -->
            <label>Interests:</label><br>
            <input type="checkbox" id="coding" name="interest" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="design" name="interest" value="design">
            <label for="design">Design</label>
            <input type="checkbox" id="reading" name="interest" value="reading">
            <label for="reading">Reading</label><br><br>
            <input type="submit" value="Register">
        </form>
    </section>

</body>
</html>
