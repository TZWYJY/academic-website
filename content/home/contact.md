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
  email: zhuyuan_99@163.com
  address:
    street: Department of Physics
    city: The University of Hong Kong
    region: Hong Kong
    postcode: '999077'
    country: China
    country_code: CN
   directions: CYM Physics Building, Pokfulam road.



design:
  columns: '2'
---
