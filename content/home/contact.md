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
  email: njgrieshop@mail.missouri.edu
  address:
    street: 146 Middlebush Hall
    city: Columbia
    region: MO
    postcode: '65211'
    country: United States
    country_code: US
    Office: '37'
  coordinates:
    latitude: '38.9462052'
    longitude: '-92.329116'
  office_hours:
    - 'Tuesday 08:30 to 10:00'
    - 'Wednesday 13:00 to 14:30'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
