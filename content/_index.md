---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      featured_only: true
      text:
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: |-
        [more..](/publication/ "more publications")
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
      background:
        # Choose colors such as from https://html-color-codes.info
        gradient_start: '#4bb4e3'
        gradient_end: '#2b94c3'
        # The gradient angle from 0-360 degrees
        gradient_angle: 180
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
  - block: contact
    id: contacts
    content:
      title: Contact
      subtitle:
      # text: |-
        # Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: leonardkkh@cau.ac.kr
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 84 Heukseok-ro
        city: Dongjak-gu, Seoul
        region: South Korea
        postcode: '06974'
        # country: South Korea
        country_code: KR
      directions: Room# 312, The 2nd Engineering Bldg (Bldg# 208)
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
