---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-10-12
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
       My research integrates spatial statistics, remote sensing, and machine learning to model how urban green infrastructure contributes to residents’ wellbeing, and to optimally allocate these spaces for enhanced ecosystem services, sustainability, and environmental efficiency. I develop data-driven approaches to evaluate and optimise the environmental performance of cities, contributing to the advancement of sustainable urban development and the UN Sustainable Development Goals (SDGs).
       
       Please reach out to collaborate 😃
    design:
      columns: '1'
  

---
