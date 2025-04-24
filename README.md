Answer

<!-- index.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Ordered list with roman numerals -->
    <ol type="I">
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
        <li>Item 4</li>
        <li>Item 5</li>
    </ol>

    <!-- External image from pexels.com -->
    <img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="External Image">

    <!-- Table of 5 contacts -->
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Main St</td>
            <td>1234567890</td>
            <td>johndoe@example.com</td>
        </tr>
        <tr>
            <td>Jane Doe</td>
            <td>456 Park Ave</td>
            <td>9876543210</td>
            <td>janedoe@example.com</td>
        </tr>
        <tr>
            <td>Mike Smith</td>
            <td>789 Oak St</td>
            <td>5551234567</td>
            <td>mikesmith@example.com</td>
        </tr>
        <tr>
            <td>Emily Johnson</td>
            <td>321 Maple St</td>
            <td>9012345678</td>
            <td>emilyjohnson@example.com</td>
        </tr>
        <tr>
            <td>David Brown</td>
            <td>901 Broadway</td>
            <td>1112223333</td>
            <td>davidbrown@example.com</td>
        </tr>
    </table>

    <!-- Registration form -->
    <form id="registration-form">
        <h2>Registration Form</h2>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required pattern=".{8,}"><br><br>
        
        <label for="date">Date:</label>
        <input type="date" id="date" name="date" required><br><br>
        
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="USA">USA</option>
            <option value="Canada">Canada</option>
            <option value="UK">UK</option>
        </select><br><br>
        
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>
        
        <label for="interests">Interests:</label>
        <input type="checkbox" id="reading" name="interests[]" value="reading">
        <label for="reading">Reading</label>
        <input type="checkbox" id="writing" name="interests[]" value="writing">
        <label for="writing">Writing</label>
        <input type="checkbox" id="coding" name="interests[]" value="coding">
        <label for="coding">Coding</label><br><br>
        
        <input type="submit" value="Register">
    </form>

    <script src="script.js"></script>
</body>
</html>





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







