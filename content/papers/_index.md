---
title: Papers
summary: paper
type: landing


sections:
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: card
      columns: 2
      spacing:
        padding: ['20px', '0', '20px', '0']
      

  - block: collection
    content:
      title: Conference paper
      text: ''
      filters:
        folders:
          - publications/journal-article
        exclude_featured: false
    design:
      view: citation


  - block: collection
    content:
      title: Conference paper
      text: ''
      filters:
        folders:
          - publications/conference-paper
        exclude_featured: false
    design:
      view: citation


---