<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PLP Advanced HTML5 Demo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 40px;
      background-color: #f9f9f9;
    }
    h1, h2 {
      color: #333;
    }
    table {
      border-collapse: collapse;
      width: 100%;
      margin-top: 15px;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 8px 12px;
      text-align: left;
    }
    th {
      background-color: #f0f0f0;
    }
    form {
      background-color: #fff;
      padding: 20px;
      margin-top: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      max-width: 500px;
    }
    label {
      font-weight: bold;
    }
    input, select {
      margin-bottom: 15px;
      width: 100%;
      padding: 8px;
      box-sizing: border-box;
    }
  </style>
</head>
<body>

  <!-- Main heading -->
  <header>
    <h1>Welcome to Our HTML5 Showcase</h1>
    <p>Demonstrating ordered lists, images, tables, forms, and media in HTML5.</p>
  </header>

  <!-- Ordered list with roman numerals -->
  <section>
    <h2>HTML Topics in Roman Numerals</h2>
    <ol type="I">
      <li>Introduction to HTML</li>
      <li>Semantic Elements</li>
      <li>Forms and Validation</li>
      <li>Embedding Multimedia</li>
      <li>HTML Tables</li>
    </ol>
  </section>

  <!-- External image from Pexels -->
  <section>
    <h2>Beautiful Landscape from Pexels</h2>
    <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" 
         alt="A scenic mountain landscape from Pexels" 
         width="600" />
  </section>

  <!-- Contact table -->
  <section>
    <h2>Our Team Contacts</h2>
    <table>
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
          <td>Grace Mwangi</td>
          <td>123 Forest Lane, Nairobi</td>
          <td>+254 700 123456</td>
          <td>grace@example.com</td>
        </tr>
        <tr>
          <td>James Ouma</td>
          <td>456 River Road, Kisumu</td>
          <td>+254 701 654321</td>
          <td>james@example.com</td>
        </tr>
        <tr>
          <td>Esther Wanjiru</td>
          <td>789 Beach Ave, Mombasa</td>
          <td>+254 702 789012</td>
          <td>esther@example.com</td>
        </tr>
        <tr>
          <td>Kevin Otieno</td>
          <td>321 Sunset Blvd, Eldoret</td>
          <td>+254 703 345678</td>
          <td>kevin@example.com</td>
        </tr>
        <tr>
          <td>Linda Njeri</td>
          <td>147 Hilltop Rd, Nakuru</td>
          <td>+254 704 987654</td>
          <td>linda@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration form -->
  <section>
    <h2>Register with Us</h2>
    <form action="#" method="post">
      <!-- Full name input -->
      <label for="fullname">Full Name:</label>
      <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required />

      <!-- Email input -->
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter a valid email" required />

      <!-- Password input -->
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6" />

      <!-- Date input -->
      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required />

      <!-- Dropdown selection -->
      <label for="country">Country:</label>
      <select id="country" name="country" required>
        <option value="">--Select your country--</option>
        <option value="kenya">Kenya</option>
        <option value="uganda">Uganda</option>
        <option value="tanzania">Tanzania</option>
      </select>

      <!-- Radio buttons -->
      <label>Gender:</label>
      <input type="radio" id="male" name="gender" value="male" required />
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="female" />
      <label for="female">Female</label>

      <!-- Checkboxes -->
      <label>Interests:</label>
      <input type="checkbox" id="tech" name="interests" value="technology" />
      <label for="tech">Technology</label>
      <input type="checkbox" id="art" name="interests" value="art" />
      <label for="art">Art</label>
      <input type="checkbox" id="sports" name="interests" value="sports" />
      <label for="sports">Sports</label>

      <!-- Submit button -->
      <br /><br />
      <input type="submit" value="Register" />
    </form>
  </section>

  <!-- Multimedia elements -->
  <section>
    <h2>Enjoy Some Media</h2>

    <h3>Audio Sample:</h3>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg" />
      Your browser does not support the audio element.
    </audio>

    <h3>Video Sample:</h3>
    <video width="600" controls>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 PLP Web Technologies Classroom</p>
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Advanced HTML5 Features</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f4f4f4;
    }
    table, th, td {
      border: 1px solid #333;
      border-collapse: collapse;
      padding: 8px;
    }
    th {
      background-color: #ddd;
    }
    form {
      background-color: #fff;
      padding: 20px;
      border-radius: 6px;
      max-width: 500px;
    }
  </style>
</head>
<body>

  <!-- Heading -->
  <h1>HTML5 Features Demonstration</h1>

  <!-- Ordered List with Roman Numerals -->
  <h2>Ordered List (Roman Numerals)</h2>
  <ol type="I">
    <li>Introduction to HTML5</li>
    <li>HTML5 Structure</li>
    <li>Tables and Forms</li>
    <li>Multimedia Elements</li>
    <li>Form Validation</li>
  </ol>

  <!-- External Image from Pexels -->
  <h2>External Image</h2>
  <img src="https://images.pexels.com/photos/207983/pexels-photo-207983.jpeg" 
       alt="Beautiful nature from Pexels" 
       width="600" />

  <!-- Table of Contacts -->
  <h2>Contacts Table</h2>
  <table>
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
        <td>Alice Johnson</td>
        <td>123 Maple Street</td>
        <td>+254 700 111 222</td>
        <td>alice@example.com</td>
      </tr>
      <tr>
        <td>Brian Kimani</td>
        <td>45 Ngong Road</td>
        <td>+254 701 333 444</td>
        <td>brian@example.com</td>
      </tr>
      <tr>
        <td>Cynthia Wanjiku</td>
        <td>78 Riverside Drive</td>
        <td>+254 702 555 666</td>
        <td>cynthia@example.com</td>
      </tr>
      <tr>
        <td>David Otieno</td>
        <td>99 Moi Avenue</td>
        <td>+254 703 777 888</td>
        <td>david@example.com</td>
      </tr>
      <tr>
        <td>Esther Njeri</td>
        <td>12 Kenyatta Avenue</td>
        <td>+254 704 999 000</td>
        <td>esther@example.com</td>
      </tr>
    </tbody>
  </table>

  <!-- Registration Form -->
  <h2>Registration Form</h2>
  <form action="#" method="POST">
    <!-- Name -->
    <label for="fullname">Full Name:</label><br />
    <input type="text" id="fullname" name="fullname" placeholder="John Doe" required /><br /><br />

    <!-- Email -->
    <label for="email">Email:</label><br />
    <input type="email" id="email" name="email" placeholder="john@example.com" required /><br /><br />

    <!-- Password -->
    <label for="password">Password:</label><br />
    <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6" /><br /><br />

    <!-- Date of Birth -->
    <label for="dob">Date of Birth:</label><br />
    <input type="date" id="dob" name="dob" required /><br /><br />

    <!-- Dropdown -->
    <label for="country">Select your Country:</label><br />
    <select id="country" name="country" required>
      <option value="">--Select--</option>
      <option value="kenya">Kenya</option>
      <option value="uganda">Uganda</option>
      <option value="tanzania">Tanzania</option>
    </select><br /><br />

    <!-- Radio Buttons -->
    <label>Gender:</label><br />
    <input type="radio" id="male" name="gender" value="male" required />
    <label for="male">Male</label><br />
    <input type="radio" id="female" name="gender" value="female" />
    <label for="female">Female</label><br /><br />

    <!-- Checkboxes -->
    <label>Select your Interests:</label><br />
    <input type="checkbox" id="coding" name="interests" value="coding" />
    <label for="coding">Coding</label><br />
    <input type="checkbox" id="music" name="interests" value="music" />
    <label for="music">Music</label><br />
    <input type="checkbox" id="sports" name="interests" value="sports" />
    <label for="sports">Sports</label><br /><br />

    <!-- Submit -->
    <input type="submit" value="Register" />
  </form>

  <!-- Multimedia Elements -->
  <h2>Multimedia Section</h2>
  <h3>Audio</h3>
  <audio controls>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg" />
    Your browser does not support the audio element.
  </audio>

  <h3>Video</h3>
  <video width="640" height="360" controls>
    <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4" />
    Your browser does not support the video tag.
  </video>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Advanced HTML5 Demo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    table, th, td {
      border: 1px solid #ccc;
      border-collapse: collapse;
      padding: 8px;
    }
    table {
      width: 100%;
      margin-top: 1em;
    }
    form {
      margin-top: 2em;
    }
    label {
      display: block;
      margin-top: 1em;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>Welcome to My Advanced HTML5 Page</h1>
    <p>This page demonstrates images, lists, tables, forms, and multimedia elements.</p>
  </header>

  <!-- Ordered List Section -->
  <section>
    <h2>Technologies I’m Learning</h2>
    <ol type="I">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript</li>
      <li>Git & GitHub</li>
      <li>Responsive Design</li>
    </ol>
  </section>

  <!-- Image Section -->
  <section>
    <h2>Featured Image</h2>
    <img src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg" 
         alt="Laptop on desk" 
         width="600" />
  </section>

  <!-- Table Section -->
  <section>
    <h2>Contact List</h2>
    <table>
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
          <td>John Doe</td>
          <td>Nairobi, Kenya</td>
          <td>+254712345678</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>Jane Smith</td>
          <td>Mombasa, Kenya</td>
          <td>+254798765432</td>
          <td>jane@example.com</td>
        </tr>
        <tr>
          <td>Ali Mwangi</td>
          <td>Kisumu, Kenya</td>
          <td>+254701234567</td>
          <td>ali@example.com</td>
        </tr>
        <tr>
          <td>Grace Njeri</td>
          <td>Nakuru, Kenya</td>
          <td>+254722334455</td>
          <td>grace@example.com</td>
        </tr>
        <tr>
          <td>Brian Otieno</td>
          <td>Eldoret, Kenya</td>
          <td>+254733112233</td>
          <td>brian@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form Section -->
  <section>

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
