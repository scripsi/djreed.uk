# Contact Me

Do get in touch.

<form id="contact-form" action="https://djreed.uk/contact.php" method="post">
  <div>
    <label for="name">Your Name</label>
    <input type="text" id="name" name="visitor_name" placeholder="Firstname Lastname" pattern=[A-Z\sa-z]{3,30} required>
  </div>
  <div>
    <label for="email">Your E-mail</label>
    <input type="email" id="email" name="visitor_email" placeholder="name@example.com" required>
  </div>
  <div>
    <label for="title">Your reason for contacting me:</label>
    <input type="text" id="title" name="email_title" required placeholder="I would like to buy a print" pattern=[A-Za-z0-9\s]{3,60}>
  </div>
  <div>
    <label for="message">Your message:</label>
    <textarea id="message" name="visitor_message" placeholder="Say whatever you want." required></textarea>
  </div>
  <button type="submit">Send Message</button>
</form>
