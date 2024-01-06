---
# Leave the homepage title empty to use the site title
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"
  
sections:  
  - block: hero
    content:
      title: |
        Quantum Computing
        Innovators Group
      text: 🧱 Unlock the limitless possibilities of quantum computing 🧱
      primary_action:
        text: Know More
        url: https://iitj.ac.in/qic/
        icon: rocket-launch
      secondary_action:
        text: Read the Company Norms
        url: https://iitj.ac.in/qic/
      announcement:
        text: Latest News.
        link:
          text: Read more
          url: /posts/
      design:
        spacing:
          padding: [0, 0, 0, 0]
          margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: welcome.png
          filters:
            brightness: 0.3
      text: |
        <br>
        <div style="text-align: justify;">
        
        Since its establishment in 2023, the **Quantum Computing Innovators Group** has served as a hub of excellence dedicated to the   research, education, and practical application of Quantum Technology.
    
        </div>
    
  - block: stats
    content:
      items:
        - statistic: "1K+"
          description: |
            Websites Visits
        - statistic: "15+"
          description: |
            QCIG Group  
            Members
        - statistic: "70+"
          description: |
            QCIG Group
            community for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
    
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
        - We offer specialized certificate courses to equip people with quantum skills.
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
