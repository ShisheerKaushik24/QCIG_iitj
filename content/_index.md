---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Quantum Computing
        Innovators Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Since its establishment in 2023, the **Quantum Computing Innovators Group** has served as a hub of excellence dedicated to the   research, education, and practical application of Quantum Technology.

  - block: hero
    content:
      title: |
        Welcome..!<br>
        Know More About Us
      image:
        filename: 
      text: |
        <br>
        <div style="text-align: justify;">
        We welcome you to our quantum computing community, which advances quantum technology. We promote quantum computing innovation and knowledge exchange. Our dynamic activities aim to establish a thriving ecosystem for professionals, enthusiasts, and learners. Join us for enlightening workshops, seminars, and events with in-depth discussions and hands-on experiences. We offer specialised certificate courses to equip people with quantum skills. Let's accelerate the quantum revolution and unleash quantum computing's boundless potential.
        </div>

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
