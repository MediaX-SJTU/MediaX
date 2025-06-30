---
title: Contact
date: 2025-6-30

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Looking for self-motivated students (PhD, Master and Undergraduate RA) working with me. For prospective students, please send your resume and transcript to the email.
      email: mediax@sjtu.edu.cn
      address:
        street: 上海交通大学电子信息楼群5号楼303A
        city: 上海市闵行区东川路800号
        country: China
        country_code: CN
      directions: https://github.com/MediaX-SJTU
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendly.com'
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
          # size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
