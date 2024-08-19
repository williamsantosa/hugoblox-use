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
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 3
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
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
        - name: Pinned
          tag: Pinned
        - name: Other
          tag: Other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
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
              Unified two high-performance products handling over 220,000 total requests per second in each deployed region.\
              Implemented and contributed to design of new API endpoints and MSSQL components to migrate data from old products to new unified product.\
              Implemented and designed an exporter from old data from into new configuration as code format as an intermediary step in migrating the data.\
              Used Python requests and GitHub Action to automate and validate publishing of data from configuration as code to new MSSQL data.\
              Added endpoints to send requests across environments, collaborating with the cross environment team.
        - title: Software Engineering Intern
          company: Maxar Technologies
          company_url: 'https://www.maxar.com/'
          company_logo: maxar
          location: San Jose, CA
          date_start: '2022-06-01'
          date_end: '2022-09-01'
          description: |2-
              Designed and developed internal system feature for satellites including the Galaxy-31 and Galaxy-32 Intelsat C-band Satellites launched by SpaceX.\
              Automated and optimized weekly database installations of telemetry data using Bash scripts, Python, and unit tests.\
              Proposed and implemented persistent storage option, automatically uploading new telemetry information to physical data stores upon change.
        - title: Research Assistant
          company: Santa Cruz Institute of Particle Physics
          company_url: 'https://scipp.science.ucsc.edu/'
          company_logo: scipp
          location: Santa Cruz, CA
          date_start: '2022-03-01'
          date_end: '2022-06-01'
          description: Collaborated on machine learning program with Professor Jason Nielsen and team to identify Higgs boson particle’s correlating variables from sample size of over 200,000 events using Keras, TensorFlow, matplotlib, pandas, dBase, and Jupyter Notebook.
        - title: Peer Navigator
          company: University of California, Santa Cruz
          company_url: 'https://www.ucsc.edu/'
          company_logo: ucsc-seal
          location: Santa Cruz, CA
          date_start: '2021-06-01'
          date_end: '2021-12-01'
          description: |2-
              Held weekly office hours to help students with navigating university and homework.\
              Graded and gave feedback to over 100 students across 4 unique sections weekly.\
              Planned and supervised university events.
        - title: Instructor & Coach
          company: Koo's Martial Arts
          company_url: 'https://kootkd.square.site/'
          company_logo: koos
          location: Dublin, CA
          date_start: '2017-07-01'
          date_end: '2021-08-31'
          description: Taught over 100 students forms, techniques, and hard-working philosophy of Taekwondo. Supervised and coached at tournaments and events.
    design:
      columns: '1'
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
              Coursework includes database systems/mining, artificial intelligence/life, and computer vision.\
              Social & Wellness Director @ UCLA Association of Indonesian Americans. 
        - title: Bachelor of Science in Computer Science
          company: University of California, Santa Cruz
          company_url: 'https://www.ucsc.edu/'
          company_logo: ucsc-seal
          location: Santa Cruz, CA
          date_start: '2020-07-01'
          date_end: '2023-06-01'
          description: Summa Cum Laude, graduated with highest honors in major. Coursework includes database systems, computational models, analysis of algorithms, computer system design, computer architecture, and computer graphics.
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
