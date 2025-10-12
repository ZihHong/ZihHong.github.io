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
      columns: 1

      

  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation


  - block: collection
    content:
      title: Conference paper
      text: ''
      filters:
        folders:
          - publications
        publication_types:
          - paper-conference
        exclude_featured: false
    design:
      view: citation


---