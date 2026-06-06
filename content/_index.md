---
# Leave the homepage title empty to use the site title
title: ''
summary: 'Academic portfolio of Yakun Liu, focusing on AI music generation, electroacoustic composition, real-time interactive systems, and audio-visual new media art.'
date: 2026-06-06
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About
        education: Education
        interests: Research Interests
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
      title: 'Research Profile'
      subtitle: 'AI music generation, electroacoustic composition, and interactive media systems'
      text: |-
        Yakun Liu's work connects musical creativity with artificial intelligence, real-time interaction, and new media performance. His research investigates deep learning-based symbolic music generation, the design of human-computer interaction systems for live musical contexts, and audio-visual cross-modal mapping for immersive artistic creation.

        Current projects include GRU-based real-time jam-session systems, AI-assisted reconstruction of endangered Guqin melodies, XR electroacoustic performance environments, and VR dual-stage concerts enabled by campus network and 5G convergence technology.
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
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: Research Projects
      text: Selected research and creative technology projects in AI music, XR performance, digital heritage, and networked concerts.
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
      show_date: true
      show_read_time: false
      show_read_more: false
---
