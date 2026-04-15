---
---
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |
        Welcome to the [Lab Name].

        We are a research group at [University / Institute].

        Our work focuses on:
        - Topic 1
        - Topic 2
        - Topic 3
      button:
        text: Explore Research
        url: /research/
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research'
      text: |-
        Our lab investigates:

        - Area 1
        - Area 2
        - Area 3

        We combine theory, data analysis, and experiments to address key challenges in our field.
    design:
      columns: '1'

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
      title: Recent Publications
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: news
    content:
      title: News
      page_type: blog
      count: 5
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
