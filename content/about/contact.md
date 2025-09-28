---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: 연락하기
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Location coordinates
  coordinates:
    latitude: '35.8469'
    longitude: '127.1293'

  # Email form provider
  form:
    provider: netlify
    formspree:
      id: pung4905@naver.com
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: '1'
---
