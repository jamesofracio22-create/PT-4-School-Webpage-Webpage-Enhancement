  <!DOCTYPE html>
  <html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunnydale School</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
    }
    h1 {
      font-size: 24px;
      font-weight: bold;
      color: #1E90FF;
    }
    h2 {
      margin-top: 20px;
    }
    #mission h2 {
      color: #32CD32;
    }
    #upcoming-events h2 {
      color: #FFA07A;
    }
    #contact h2 {
      color: #20B2AA;
    }
    #upcoming-events {
      background-color: #FFFFE0;
      padding: 10px;
      border-radius: 5px;
    }
    .outdoor {
      background-color: #AFEEEE;
      padding: 5px;
      border: 1px solid #B0E0E6;
      border-radius: 3px;
    }
    .event-date {
      font-weight: bold;
      color: red;
    }
    .contact-box {
      background-color: #f8f3f3;
      padding: 10px;
      border-radius: 5px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h1>Sunnydale School</h1>

  <section id="mission">
    <h2>Mission Statement</h2>
    <p>At Sunnydale School, we are committed to providing a nurturing and challenging environment that empowers students to become lifelong learners and responsible citizens.</p>
  </section>

  <section id="upcoming-events">
    <h2>Upcoming Events</h2>
    <ul>
      <li data-event-type="indoor">Science Fair - <span class="event-date">June 10</span></li>
      <li class="outdoor" data-event-type="outdoor">Art Exhibition - <span class="event-date">June 15</span></li>
      <li class="outdoor" data-event-type="outdoor">Sports Day - <span class="event-date">June 20</span></li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-box">
      <p>Email: <a href="mailto:info@sunnydale.edu">info@sunnydale.edu</a></p>
      <p>Phone: <a href="tel:+1234567890">+1 (234) 567-890</a></p>
    </div>
  </section>
</body>
</html>
