#this is html


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My First Web Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- 🟢 Story 1: Header Section -->
  <header>
    <h1>Welcome to My Web Page</h1>
  </header>

  <!-- 🟢 Story 1 & 3: About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      Hello! I am learning to build websites using HTML and CSS. This is my very first project and I’m excited to share it with you!
    </p>
  </section>

  <!-- 🟢 Story 1 & 4: Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <ul>
      <li>📧 Email: example@email.com</li>
      <li>📞 Phone: +1234567890</li>
    </ul>
    <button class="contact-button">Contact Me</button>
  </section>
</body>
</html>



#this is css


/* Style for the entire body */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  color: #333;
}

/* 🟢 Story 2: Header styling */
header {
  background-color: #0077cc;
  color: white;
  padding: 20px;
  text-align: center;
}

/* 🟢 Story 3: About section styling */
#about p {
  color: #444;
  line-height: 1.6;
}

/* 🟢 Story 5: Button styling */
.contact-button {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #0077cc;
  color: white;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease, box-shadow 0.3s ease;
}

.contact-button:hover {
  background-color: #005fa3;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
}

section {
  padding: 20px;
}
