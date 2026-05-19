---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
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
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Welcome to my academic portal. As a Social and Health Psychologist, my research primarily focuses on the dynamics of stigma, psychological needs and motivation, self-compassion, perfectionism, and emotion processing.

        Utilizing advanced quantitative methodologies and mixed research methods, I aim to bridge cultural and universal approaches to deepen our understanding of psychological well-being and societal attitudes. Please feel free to explore my publications and ongoing projects.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      count: 0
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: article-grid
      columns: '2'

  - block: collection
    content:
      title: Recent Publications
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: SOHE Life / Labdan Kareler
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
    
