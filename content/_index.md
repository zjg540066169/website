---
# Leave the homepage title empty to use the site title
title: 'Jungang Zou'
date: 2026-10-10
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
      button:
        text: Download CV
        url: uploads/resume.pdf
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
    id: news
    content:
      title: "Recent Highlights"
      text: |
        - **Dec 2026** — Invited talk on AI4BayesCode at the Technology and Artificial Intelligence Learning Seminar (TAILS), Montana State University (forthcoming).
        - **Aug 2026** — Invited talk on Bayesian propensity score predictive inference at the SILVER Lab Meeting, Department of Epidemiology and Public Health, University of Maryland School of Medicine.
        - **Aug 2026** — Our Bayesian MI-LASSO paper won the **ASA Student Paper Competition Award** of the ASA GSS/SRMS/SSS Sections at JSM 2026, where I also chaired the session *Sampling, Weighting, Missing Data and Variance Estimation*.
        - **Aug 2026** — AI4BayesCode received a **Paper Award at STAI-X 2026** (one of 9 awards selected from all 54 accepted papers) and was invited for a live demonstration at the Stats Up AI community table at JSM 2026.
        - **Jun 2026** — Received the **Outstanding Doctoral Teaching Assistant Award** from the Department of Biostatistics, Columbia University.
        - **Jun 2026** — Presented a poster at the IMSI workshop *New Horizons on Model Transportability and Data Integration* (Chicago, IL) with a travel award.
        - **Mar 2026** — Contributed talk at ENAR 2026 (Indianapolis, IN) on generalizing treatment effects from trials to EHR populations.

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
