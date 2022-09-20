---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 75

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: 0
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: wangjiaqi@sjtu.edu.cn
  phone: +86 15858113517
  address:
    street: 800 Dongchuan RD
    city: Shanghai
    region: 
    postcode: '200240'
    country: China
    country_code: CHN
  coordinates:
    latitude: '31.0220'
    longitude: '121.4251'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/ivy_clashroyale'

design:
  columns: '2'
---
