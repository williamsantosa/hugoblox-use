---
# Leave the homepage title empty to use the site title
title: 'William Santosa'
date: 
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        folders:
          - post
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
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Software Engineering Intern
          company: Roblox
          company_url: 'https://www.roblox.com/'
          company_logo: roblox
          location: San Mateo, CA
          date_start: '2024-06-18'
          date_end: ''
          description: |2-
              I’ve played Roblox since 2011 and have always wanted to work with them! Excited for this upcoming summer! ٩(^ᗜ^ )و
        - title: Software Engineering Intern
          company: Maxar Technologies
          company_url: 'https://www.maxar.com/'
          company_logo: maxar
          location: San Jose, CA
          date_start: '2022-06-01'
          date_end: '2022-09-01'
          description: At Maxar I designed and developed a database installation tool for the new Intelsat satellites launched by SpaceX. 🚀 I automated and optimized weekly database installations of telemetry data and learned about CI/CD, Agile, pull requests, code reviews, and unit/manual testing.
        - title: Research Assistant
          company: Santa Cruz Institute of Particle Physics
          company_url: ''
          company_logo: scipp
          location: Santa Cruz, CA
          date_start: '2022-03-01'
          date_end: '2022-06-01'
          description: Here I worked with Professor Jason Nielsen to create a machine learning program with neural networks that identifies factors correlating to the formation of the Higgs Boson with an approximately 80% validation accuracy from sample size of 200,000+ events.
        - title: Peer Navigator
          company: University of California, Santa Cruz
          company_url: ''
          company_logo: ucsc-seal
          location: Santa Cruz, CA
          date_start: '2021-06-01'
          date_end: '2021-12-01'
          description: I held weekly office hours to help frosh acclimate to university and homework. Graded and gave feedback to 50+ students from pool of 200+ weekly. Planned and supervised university affiliated events.
        - title: Instructor & Coach
          company: Koo's Martial Arts
          company_url: ''
          company_logo: koos
          location: Dublin, CA
          date_start: '2017-07-01'
          date_end: '2021-08-31'
          description: Taught students forms, techniques, and hard-working philosophy of Taekwondo. 🥋 Supervised and coached students at tournaments and events.
    design:
      columns: '2'
  - block: experience
    id: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Master of Science in Computer Science
          company: University of California, Los Angeles
          company_url: 'https://www.ucla.edu/'
          company_logo: ucla-seal
          location: Los Angeles, CA
          date_start: '2023-09-01'
          date_end: ''
          description: |2-
              Learning new things and meeting people 🙂
        - title: Bachelor of Science in Computer Science
          company: University of California, Santa Cruz
          company_url: 'https://www.maxar.com/'
          company_logo: maxar
          location: Santa Cruz, CA
          date_start: '2020-07-01'
          date_end: '2023-06-01'
          description: Graduated with Highest Honors in Major. Coursework includes Database Systems, Computational Models and Analysis of Algorithms, Principles of Computer System Design, Computer Architecture, and Computer Graphics.
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      email: williamwsantosa@gmail.com
      phone: +1 925 399 7269
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
