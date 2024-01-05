---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-24
type: landing

sections:  
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        
      - title: Group Icon
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: icon.png
            filters:
              brightness: 0.7
          position: center
          color: '#333'
        
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
        
  - block: hero
    content:
      title: |
        Quantum Computing
        Innovators Group
      image:
        filename: welcome.png
      text: |
        <br>
        <div style="text-align: justify;">
        
        Since its establishment in 2023, the **Quantum Computing Innovators Group** has served as a hub of excellence dedicated to the   research, education, and practical application of Quantum Technology.
    
        </div>
        
  - block: markdown
    content:
      title: |
        Welcome..!<br>
      image:
        filename: 
      text: |
        <br>
        <div style="text-align: justify;">
        
        - We welcome you to our quantum computing community, which advances quantum technology.
        - We promote quantum computing innovation and knowledge exchange.
        - Our dynamic activities aim to establish a thriving ecosystem for professionals, enthusiasts, and learners.
        - Join us for enlightening workshops, seminars, and events with in-depth discussions and hands-on experiences.
        - We offer specialised certificate courses to equip people with quantum skills.
        - Let's accelerate the quantum revolution and unleash quantum computing's boundless potential.

    
        </div>

  - block: markdown
    content:
      title: |
        Mission
      image:
        filename: 
      text: |
        <br>
        <div style="text-align: justify;">
        
        - **Our Mission:**
          - Advance the frontiers of quantum technology.
          - Foster innovation and knowledge exchange within the quantum domain, with a primary focus on quantum computing.
          - Create a vibrant ecosystem that brings together experts, enthusiasts, and learners.

        - **Initiatives:**
          - Organize insightful workshops, seminars, and events.
          - Provide a platform for in-depth discussions and hands-on experiences.

        - **Certificate Courses:**
          - Offer specialized certificate courses to empower individuals with the skills needed to navigate the quantum landscape.

        </div>
  
  - block: markdown
    content:
      title: |
        Vision
      image:
        filename: 
      text: |
        <br>
        <div style="text-align: justify;">
        
         - **Our Vision:**
          - Propel the quantum revolution forward.
          - Unlock the limitless possibilities of quantum computing.
      
        - **Community Involvement:**
          - Envision a community that drives exploration and implementation of quantum technologies.
          - Contribute to groundbreaking advancements.
      
        - **Collaboration and Inclusivity:**
          - Build a collaborative and inclusive platform.
          - Strive to be at the forefront of quantum innovation.
      
        - **Accessibility and Transformation:**
          - Make quantum computing accessible and transformative for individuals and industries alike.
    
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
