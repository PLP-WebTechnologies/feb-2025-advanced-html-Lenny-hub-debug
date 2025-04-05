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

Happy Coding! 💻
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Lencer Achieng Website</title>
  <style>
    /* Basic styling */
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f9f9f9;
    }
    h1, h2 {
      color: #444;
    }
    form {
      background: #fff;
      padding: 1em;
      border: 1px solid #ccc;
      max-width: 400px;
    }
    form div {
      margin-bottom: 0.5em;
    }
    label {
      display: inline-block;
      width: 100px;
      font-weight: bold;
    }
    input[type="text"],
    input[type="email"],
    input[type="password"] {
      width: 200px;
      padding: 0.4em;
    }
    input[type="submit"] {
      padding: 0.6em 1em;
      background: #0066cc;
      border: none;
      color: #fff;
      cursor: pointer;
    }
    table {
      border-collapse: collapse;
      width: 50%;
      margin-top: 1em;
    }
    table, th, td {
      border: 1px solid #ccc;
      padding: 0.5em;
      text-align: left;
    }
    ul {
      list-style-type: square;
    }
  </style>
</head>
<body>
  <h1>Welcome to Lencer Achieng's Website</h1>
  <p>This webpage showcases audio, video, a registration form, an image, a table, and a list.</p>

  <!-- 1. Multimedia: Audio and Video -->
  <section>
    <h2>Multimedia</h2>
    <h3>Audio</h3>
    <!-- Replace 'sample-audio.mp3' with the path to your audio file -->
    <audio controls>
      <source src="sample-audio.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <h3>Video</h3>
    <!-- Replace 'sample-video.mp4' with the path to your video file -->
    <video width="320" height="240" controls>
      <source src="sample-video.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </section>

  <!-- 2. Registration Form with Validation -->
  <section>
    <h2>Registration Form</h2>
    <form action="#" method="post">
      <div>
        <label for="fname">First Name:</label>
        <input 
          type="text" 
          id="fname" 
          name="fname" 
          placeholder="Enter first name" 
          required
        >
      </div>
      <div>
        <label for="lname">Last Name:</label>
        <input 
          type="text" 
          id="lname" 
          name="lname" 
          placeholder="Enter last name" 
          required
        >
      </div>
      <div>
        <label for="email">Email:</label>
        <input 
          type="email" 
          id="email" 
          name="email" 
          placeholder="Enter email" 
          required
        >
      </div>
      <div>
        <label for="password">Password:</label>
        <input 
          type="password" 
          id="password" 
          name="password" 
          minlength="6" 
          required
        >
      </div>
      <div>
        <input type="submit" value="Register">
      </div>
    </form>
  </section>

  <!-- 3. Embedded Image -->
  <section>
    <h2>Our Featured Image</h2>
    <!-- Replace 'sample-image.jpg' with the path to your image -->
    <img 
      src="sample-image.jpg" 
      alt="A descriptive alt text" 
      width="400"
    >
  </section>

  <!-- 4. Embedded Table -->
  <section>
    <h2>Sample Table</h2>
    <table>
      <thead>
        <tr>
          <th>Day</th>
          <th>Activity</th>
          <th>Time</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Monday</td>
          <td>Team Meeting</td>
          <td>9:00 AM</td>
        </tr>
        <tr>
          <td>Wednesday</td>
          <td>Project Work</td>
          <td>2:00 PM</td>
        </tr>
        <tr>
          <td>Friday</td>
          <td>Presentation</td>
          <td>11:00 AM</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- 5. Create a List -->
  <section>
    <h2>Topics Covered</h2>
    <ul>
      <li>HTML Basics</li>
      <li>Embedding Multimedia</li>
      <li>Form Validation</li>
      <li>Tables and Lists</li>
      <li>Website Design Principles</li>
    </ul>
  </section>
</body>
</html>





