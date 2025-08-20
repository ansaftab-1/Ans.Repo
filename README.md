<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task-1</title>
</head>
<body>
    <h1>Contact Our company</h1>
    <p>We'd love to hear from you </p>
    <ol>
        <li>Home</li>
        <li>About</li>
        <li>Services</li>
        <li>Contact</li>
    </ol>
    <h1>Send us a Message </h1>
    <div><form>
    <fieldset>
      <legend><b>Personal Information</b></legend>

      <p>
        <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="fullname">
      </p>

      <p>
        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email">
      </p>

      <p>
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" placeholder="">
        <br>
        <small>Format: 123-456-7890</small>
      </p>

    </fieldset>
  </form></div>

  <div>
    <form action="">
        <fieldset>
            <legend>Your Message</legend>
     <label for="subject"><strong>Subject:</strong></label>
  <select id="subject" name="subject">
    <option value="general">General Inquiry</option>
  </select>
  <br>
    <label for="Message">Message</label>
    <br>
    <textarea id="Message" name="comment" rows="4" cols="50">
</textarea>
<br>
<form action="">
        <input type="checkbox">Make argent
    </form>
    <br>
    <label>Preferred contact method:</label><br>
  <label>
    <input type="radio" name="contact" value="email" checked>
    Email
  </label>
  <label>
    <input type="radio" name="contact" value="phone">
    Phone
  </label>

   </fieldset>
    </form>
  
</div>
<button>Send Message</button>
<button>Clear Form</button>
<h2>Our Location</h2>

<div><address>
  <em>123 Business Road<br>
  Business City, BC 12345<br>
  United States</em>
</address>
</div>
<div>
    <h3>office Hours</h3>
    <table border="1">
  <tr>
    <th>Day</th>
    <th>Hours</th>
  </tr>
  <tr>
    <td>Monday - Friday</td>
    <td>9:00 AM - 5:00 PM</td>
  </tr>
  <tr>
    <td>Saturday</td>
    <td>10:00 AM - 2:00 PM</td>
  </tr>
  <tr>
    <td>Sunday</td>
    <td>Closed</td>
  </tr>
</table>


</div>
<footer>
    <footer>
  <p>© 2023 Our Company. All rights reserved.</p>
  <p>
    <a href="/privacy-policy.html">Privacy Policy</a> |
    <a href="/terms-of-service.html">Terms of Service</a>
  </p>
</footer>

</footer>
</body>
</html>
