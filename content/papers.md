---
title: 'Papers'   # 如果這頁是「Papers」，可改成 'Papers'
date: 2025-10-12
type: landing

design:
  spacing: '5rem'

blocks:
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
