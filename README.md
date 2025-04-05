⁶# Advanced HTML5 Elements and Forms

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
    <title>HTML5 Features Sketch</title>
</head>
<body>

    <!-- Ordered list (Roman numerals) -->
    <ol type="I">
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ol>

    <!-- External image -->
    <img src="IMAGE_URL_HERE" alt="Example Image">

    <!-- Table of contacts -->
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>...</td>
            <td>...</td>
            <td>...</td>
            <td>...</td>
        </tr>
        <!-- Add more rows as needed -->
    </table>

    <!-- Registration form -->
    <form>
        <label>Name:</label>
        <input type="text" required><br>

        <label>Email:</label>
        <input type="email" required><br>

        <label>Password:</label>
        <input type="password" required><br>

        <label>Date:</label>
        <input type="date" required><br>

        <!-- Dropdown -->
        <select required>
            <option value="">Select</option>
            <option>Option 1</option>
        </select><br>

        <!-- Radio buttons -->
        <input type="radio" name="option" required> Option 1<br>
        <input type="radio" name="option"> Option 2<br>

        <!-- Checkboxes -->
        <input type="checkbox"> Checkbox 1<br>
        <input type="checkbox"> Checkbox 2<br>

        <input type="submit" value="Submit">
    </form>

    <!-- Audio -->
    <audio controls>
        <source src="AUDIO_URL_HERE" type="audio/mpeg">
    </audio>

    <!-- Video -->
    <video controls width="400">
        <source src="VIDEO_URL_HERE" type="video/mp4">
    </video>

</body>
</html>







