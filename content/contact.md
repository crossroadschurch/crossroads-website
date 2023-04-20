---
title: Contact
#omit_header_text: true
description: We'd love to hear from you
featured_image: '/images/woods.jpg'
type: page
menu: main

#{{< form-contact action="https://example.com"  >}}
---


This is an example of a custom shortcode that you can put right into your content. You will need to add a form action to the shortcode to make it work. Check out [Formspree](https://formspree.io/) for a simple, free form service. 


{{< rawhtml >}}

<form name="contact" method="POST" data-netlify="true">
  <input type="hidden" name="subject" 
  value="Contact form filled out on xrd.org.uk" />
  <p>
    <label>Your Name: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Phone Number: <input type="text" name="phone" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
{{< /rawhtml >}}

