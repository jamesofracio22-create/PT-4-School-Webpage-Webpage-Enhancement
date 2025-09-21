<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunnydale School</title>
  <style>
    /* General Styling */
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
    }

    /* Page Title */
    h1 {
      font-size: 24px;
      font-weight: bold;
      color: #1E90FF;
    }

    /* Section Headings */
    h2 {
      margin-top: 20px;
    }

    /* Different colors for each section */
    #mission h2 {
      color: #32CD32;
    }
    #upcoming-events h2 {
      color: #FFA07A;
    }
    #contact h2 {
      color: #20B2AA;
    }

    /* Style with ID for upcoming-events */
    #upcoming-events {
      background-color: #FFFFE0;
      padding: 10px;
      border-radius: 5px;
    }

    /* Outdoor events styling */
    .outdoor {
      background-color: #AFEEEE;
      padding: 5px;
      border: 1px solid #B0E0E6;
      border-radius: 3px;
    }

    /* Contact box styling */
    .contact-box {
      background-color: #f8f3f3;
      padding: 10px;
      border-radius: 5px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <!-- Title -->
  <h1>Sunnydale School</h1>

  <!-- Mission Section -->
  <section id="mission">
    <h2>Mission Statement</h2>
    <p>At Sunnydale School, we are committed to providing a nurturing and challenging environment that empowers students to become lifelong learners and responsible citizens.</p>
  </section>

  <!-- Upcoming Events Section -->
  <section id="upcoming-events">
    <h2>Upcoming Events</h2>
    <ul>
      <li data-event-type="indoor" title="Event Type: Indoor">Science Fair - <span style="font-weight:bold; color:red;">June 10</span></li>
      <li class="outdoor" data-event-type="outdoor" title="Event Type: Outdoor">Art Exhibition - <span style="font-weight:bold; color:red;">June 15</span></li>
      <li class="outdoor" data-event-type="outdoor" title="Event Type: Outdoor">Sports Day - <span style="font-weight:bold; color:red;">June 20</span></li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-box">
      <p>Email: <a href="mailto:info@sunnydale.edu" title="Click to copy email">info@sunnydale.edu</a></p>
      <p>Phone: <a href="tel:+1234567890" title="Click to copy phone">+1 (234) 567-890</a></p>
    </div>
    <!-- Imagine clicking here shows a message: "Thanks for reaching out!" -->
  </section>
</body>
</html>
