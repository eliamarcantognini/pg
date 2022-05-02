---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Contattaci
subtitle:



content:
  # Automatically link email and phone or display as text?
  autolink: true
  # Contact details (edit or remove options as required)
    email: pgv@chiesapesaro.it
    phone: 0721331133
    address:
      street: Via Gioacchino Rossini, 56
      city: Pesaro
      region: PU
      postcode: '61121'
      country: Italy
      country_code: US
    coordinates:
      latitude: '43.9109536'
      longitude: '12.9125746'
    directions: Nel sagrato prendere la porta sulla destra e salire le scale
    office_hours:
      - 'Lunedì - Venerdì 10:00 to 13:00'
      - 'Sabato 09:00 to 10:00'

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: '1'
---
