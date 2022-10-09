---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: shriya.atmak@gmail.com
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: DM Me
      link: 'https://linkedin.com/in/shriya-atmakuri'

design:
  columns: '2'
---
