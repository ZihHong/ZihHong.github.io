---
title: "Papers"
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
      view: article-grid
      columns: 2
  
  
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications/journal-article
        exclude_featured: false
    design:
      view: citation


  - block: collection
    content:
      title: Conference papers
      text: ''
      filters:
        folders:
          - publications/conference-paper
        exclude_featured: false
    design:
      view: citation


---