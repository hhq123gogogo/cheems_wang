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
  email: test@example.org
  phone: +31 0628473583
  address:
    street: Science Park 904
    city: Amsterdam
    region: CA
    postcode: '1098 XH Amsterdam'
    country: the Netherlands
    country_code: NL
  coordinates:
    latitude: '52.3544'
    longitude: '4.9557'
  directions: Enter Lab42 Building and Find Office 420 on Floor 4
  office_hours:
    - 'Weekdays 8:00 to 20:00'
    - 'Weekends 10:00 to 18:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/albertw24045555'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
