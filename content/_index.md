---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-06-10
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: "¡Hola! Soy Grecia Alvarez Leyva, investigadora en inteligencia artificial y ciencia de datos. Mi trabajo se centra en aprendizaje automático, procesamiento de lenguaje natural y ética en IA. Apasionada por la docencia y la tecnología responsable."
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Descargar CV
        url: uploads/CV-GreciaAlvarez.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '📚 Mi investigación'
      subtitle: ''
      text: |-
        Soy investigadora en inteligencia artificial, enfocada en aprendizaje automático, procesamiento de lenguaje natural y ética en IA. Me apasiona la docencia y la tecnología responsable, y colaboro en proyectos interdisciplinarios para aplicar IA en beneficio social.
        
        ¡Contáctame si te interesa colaborar! 😃
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publicaciones destacadas
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Publicaciones recientes
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Charlas y eventos recientes
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: news
    content:
      title: Noticias recientes
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
