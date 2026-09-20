---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
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
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: research
    content:
      title: Research
      subtitle: ''
      text: |-
        I develop computational methods and open-source software that connect genomic and transcriptomic variation to the proteins expressed by tumors. My work focuses on making proteogenomic analysis comprehensive, reproducible, and scalable—from workflow engineering and non-canonical peptide identification to the interpretation of cancer genomes and proteomes.

        I apply these methods to questions in cancer diagnosis, prognosis, treatment response, sex differences, and neoantigen discovery. I am particularly interested in translating robust computational tools into biological and clinical insight.
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      count: 5
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: contact-info
    id: contact
    content:
      title: Contact
      subtitle: Get in touch about research or collaboration
      visit_title: Affiliation
      connect_title: Connect
      address:
        lines:
          - Cancer Genome and Epigenetics Program
          - NCI-Designated Cancer Center
          - Center for Data Science and Artificial Intelligence
          - Sanford Burnham Prebys Medical Discovery Institute
          - La Jolla, California, USA
      email: czhu@sbpdiscovery.org
      social:
        - icon: academicons/google-scholar
          url: https://scholar.google.com/citations?user=V8TcFocAAAAJ
        - icon: brands/linkedin
          url: https://www.linkedin.com/in/chenghao-zhu/
        - icon: brands/github
          url: https://github.com/zhuchcn
      map_url: https://www.google.com/maps/search/?api=1&query=Sanford+Burnham+Prebys+Medical+Discovery+Institute
      show_form: false
    design:
      spacing:
        padding: ['4rem', 0, '4rem', 0]
---
