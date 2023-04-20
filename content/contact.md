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
<script src="https://unpkg.com/tailwindcss-jit-cdn"></script>
<form action={FORM_ENDPOINT} method="POST" target="_blank">
  <div class="mb-3 pt-0">
    <input
      type="text"
      placeholder="Your name"
      name="name"
      class="px-3 py-3 placeholder-gray-400 text-gray-600 relative bg-white bg-white rounded text-sm border-0 shadow outline-none focus:outline-none focus:ring w-full"
      required
    />
  </div>
  <div class="mb-3 pt-0">
    <input
      type="email"
      placeholder="Email"
      name="email"
      class="px-3 py-3 placeholder-gray-400 text-gray-600 relative bg-white bg-white rounded text-sm border-0 shadow outline-none focus:outline-none focus:ring w-full"
      required
    />
  </div>
  <div class="mb-3 pt-0">
    <input
      type="phone"
      placeholder="Phone"
      name="phone"
      class="px-3 py-3 placeholder-gray-400 text-gray-600 relative bg-white bg-white rounded text-sm border-0 shadow outline-none focus:outline-none focus:ring w-full"
      required
    />
  </div>
  <div class="mb-3 pt-0">
    <textarea
      placeholder="Your message"
      name="message"
      class="px-3 py-3 placeholder-gray-400 text-gray-600 relative bg-white bg-white rounded text-sm border-0 shadow outline-none focus:outline-none focus:ring w-full"
      required
    ></textarea>
  </div>
  <div class="mb-3 pt-0">
    <button
      class="bg-blue-500 text-white active:bg-blue-600 font-bold uppercase text-sm px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150"
      type="submit"
    >Send a message</button>
  </div>
</form>
{{< /rawhtml >}}
