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
