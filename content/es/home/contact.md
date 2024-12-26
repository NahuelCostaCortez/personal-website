---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contacto
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
  email: costanahuel@uniovi.es
  phone: 985 182 686
  address:
    street: Edificio Polivalente - Desp. 2.6.14
    city: Gijón
    region: AS
    postcode: '33203'
    country: ESPAÑA
    country_code: ES
  coordinates:
    latitude: '43.524229'
    longitude: '-5.634248'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/nahucostacortez'

design:
  columns: '2'
---
