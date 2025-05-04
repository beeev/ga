---
title: Get in touch
seo:
  title: Contact
  description: Get in touch through email or social media! Let me know how I can help.
---

<form
  action="https://formspree.io/f/mqaqpvka"
  method="POST"
  class="max-w-md mx-auto space-y-4"
>
  <label class="block">
    <span class="font-medium">Your name</span>
    <input
      type="text"
      name="name"
      required
      class="mt-1 block w-full rounded border px-3 py-2"
    />
  </label>

  <label class="block">
    <span class="font-medium">Your email</span>
    <input
      type="email"
      name="email"
      required
      class="mt-1 block w-full rounded border px-3 py-2"
    />
  </label>

  <label class="block">
    <span class="font-medium">Message</span>
    <textarea
      name="message"
      rows="5"
      required
      class="mt-1 block w-full rounded border px-3 py-2"
    ></textarea>
  </label>
  <button
    type="submit"
    class="bg-black text-white px-4 py-2 rounded hover:bg-gray-800 transition"
  >
    Send message
  </button>
</form>