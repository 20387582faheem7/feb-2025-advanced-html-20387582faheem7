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
    <title>Advanced HTML5 Elements and Forms</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to Advanced HTML5 Elements</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Steps to Register</h2>
        <ol type="I">
            <li>Enter your personal details.</li>
            <li>Choose your account type.</li>
            <li>Agree to the terms and conditions.</li>
            <li>Submit the registration form.</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Sample Image</h2>
        <img src="https://www.pexels.com/photo/nature-landscape-123456/" alt="Beautiful Nature" width="500">
    </section>

    <!-- Contact Table -->
    <section>
        <h2>Contact List</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Main Street, Nairobi</td>
                <td>+254712345678</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm Street, Mombasa</td>
                <td>+254798765432</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>David Brown</td>
                <td>789 Pine Street, Kisumu</td>
                <td>+254723456789</td>
                <td>david@example.com</td>
            </tr>
            <tr>
                <td>Alice Johnson</td>
                <td>101 Oak Avenue, Eldoret</td>
                <td>+254745678901</td>
                <td>alice@example.com</td>
            </tr>
            <tr>
                <td>Chris Martin</td>
                <td>202 Cedar Lane, Nakuru</td>
                <td>+254765432109</td>
                <td>chris@example.com</td>
            </tr>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="submit.php" method="POST">
            <!-- Name Field -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter a strong password" required>
            <br><br>

            <!-- Date Field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>

            <!-- Dropdown (Select Box) -->
            <label for="country">Select Country:</label>
            <select id="country" name="country">
                <option value="kenya">Kenya</option>
                <option value="uganda">Uganda</option>
                <option value="tanzania">Tanzania</option>
                <option value="rwanda">Rwanda</option>
            </select>
            <br><br>

            <!-- Radio Buttons -->
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
            <br><br>

            <!-- Checkboxes -->
            <label>Interests:</label>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label>
            <br><br>

            <!-- Submit Button -->
            <input type="submit" value="Register">
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Advanced HTML5 Forms</p>
    </footer>

</body>
</html>

