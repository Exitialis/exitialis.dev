---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
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
      title: '📝 Мой блог'
      subtitle: ''
      text: |-
        Я TechLead в Авито, крупнейшем классифайде в России. Веду блог по разработке, руководству, инженерии и прочим технологическим вещами. Также, рассказываю про свой жизненный опыт абсолютно во всех сферах.

        Веду обучающие курсы в разных компаниях, и предоставляю услуги ментора. Можете связаться со мной, если вам интересно. [Мой профиль на GetMentor](https://getmentor.dev/mentor/neshadin-ivan-2688) 😃
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
    id: talks
    content:
      title: Публичные выступления
      filters:
        folders:
          - events
    design:
      view: article-grid
      columns: 4
---
