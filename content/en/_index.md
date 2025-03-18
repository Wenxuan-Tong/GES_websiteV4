---
# Use site title as homepage title
title:
date: 2025-03-14
type: landing

sections:
  - block: hero
    content:
      title: |
        **NCEPU Gravity Energy Storage Team**
      image:
        filename: image.png
      text: |
        <br>
        The NCEPU Gravity Energy Storage Team, affiliated with the State Key Laboratory of New Energy Power Systems, is dedicated to developing innovative energy storage solutions and contributing Chinese wisdom to global energy transition.
    design:
      columns: '2'
      css_class: text-center
  
  - block: markdown
    content:
      title: Research Areas
      text: |
        ### Power Plant Operation Control and Configuration Optimization
        Developing optimized control strategies for gravity storage systems to improve operational efficiency and reliability.

        ### Hybrid Energy Storage System Design
        Investigating synergistic operation mechanisms between gravity storage and other storage forms to achieve multi-energy complementarity.

        ### Gravity Storage Potential and Comprehensive Benefit Assessment
        Analyzing gravity storage application potential in different geographical environments and evaluating its economic and environmental benefits.

        ### Intelligent Technology Applications
        Applying artificial intelligence technologies to the design, operation, and maintenance of gravity storage systems.
    design:
      columns: '2'
      background:
        image: 
          filename: 
          filters:
            brightness: 0.7
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: '2'

  - block: markdown
    content:
      title: Join Us
      text: |
        We always welcome talented individuals to join our team and explore innovative developments in gravity storage technology together.
        
        {{% cta cta_link="./contact/" cta_text="Learn More →" %}}
    design:
      columns: '1'
---
