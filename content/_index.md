---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
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
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I'm a applied scientist of team Trust Sensitive C&Intelligence at Amazon. I have a board interest in machine learning area especially applied machine learning in NLP, CV, Cyber-Physical Systems such robotics and power system. Meanwhile, I am intereted in data security and privacy especially differential privacy as well. In addition, I have a solid background of embedded systems and other electronic devices. Looking forward to design and make something special in life
        
        Please reach out to collaborate 😃
    design:
      columns: '1'

---
