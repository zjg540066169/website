---
title: 'Experience'
date: 2026-10-10
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  # Education (the resume-experience block renders Education from the author profile;
  # work experience is listed in its own section at the bottom of this page).
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      is_education_first: true
  - block: resume-awards
    content:
      title: Awards
      username: admin
    design:
      # Show year only
      date_format: '2006'
  - block: resume-skills
    content:
      title: Skills
      username: admin
    design:
      show_skill_percentage: false
  - block: markdown
    id: experience
    content:
      title: Experience
      text: |
        **Quantitative Developer Intern**, [WorldQuant](https://www.worldquant.com/), Beijing, China. September 2020 – December 2020.  
        Programmed data processing modules in C++.
---
