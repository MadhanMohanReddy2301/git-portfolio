---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

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
  - block: collection
    content:
      title: Projects
      text: I am highly interested in AI, machine learning, and generative AI projects. I developed a “Chat with PDF” application that uses advanced AI models to interact with PDF documents, making document search and retrieval efficient and user-friendly. My AI/ML projects on GitHub and fine-tuned models on Hugging Face showcase my practical skills and dedication. These projects have greatly enhanced my knowledge and passion for innovation in this exciting field.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: resume-skills
    content:
      title: Skills
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
---
