---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        
      email: quantum@iitj.ac.in
      phone: 0291-2801602
      address:
        street: NH 62, Surpura Bypass Rd
        city: Jodhpur
        region: JDH
        postcode: '342030'
        country: India
        country_code: IN
      coordinates:
        latitude: '26.4710'
        longitude: '73.1134'
      directions: Enter **Student of Administartion** Building and take the stairs to Office IDRP on Floor 1
      office_hours:
        - 'Weekdays 10:00 to 17:00'
        - 'Weekends 10:00 to 13:00'
      appointment_url: 'https://iitj.ac.in/qic/'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
