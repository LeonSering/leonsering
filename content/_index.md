---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-02-05
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hey, I'm Leon!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: leon
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
        - title: Operations Research Expert (Freelancer)
          company: Optano GmbH
          company_url: 'https://optano.com/'
          company_logo:
          location: Paderborn, Germany
          date_start: '2023-05-01'
          date_end: '2023-06-30'
          description: |2-
              * consulting services in operations research and algorithm design for a line haul solution
              * implementation of a fast multi-objective routing algorithm

        - title: Postdoctoral Researcher
          company: ETH Zürich
          company_url: 'https://math.ethz.ch/ifor'
          company_logo: ETH_vector
          location: Zurich, Switzerland
          date_start: '2021-04-01'
          date_end: ''
          description: |2-
              Institute for Operations Research, Department of Mathematics:
              * leading scientific projects in collaboration with SwissPost and SBB (swiss federal railways)
              * research in operations research, efficient algorithms, meta-heuristics, and concurrency

        - title: Research Associate in Discrete Mathematics
          company: Technical University Berlin
          company_url: 'https://www3.math.tu-berlin.de/coga/'
          company_logo: TU-Berlin-Logo
          location: Berlin, Germany
          date_start: '2016-09-01'
          date_end: '2021-03-31'
          description: |2-
              Research Group: Combinatorial Optimization \& Graph Algorithm, Institute of Mathematics:
              * ECMath and MATH+ research projects: dynamic models and algorithms for equilibria in traffic networks.
              * Research goals: improve mathematical flow over time models to connect with large-scale simulations such as MATSim.
    design:
      columns: '2'

  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: leon
    design:
      columns: '1'

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
        - name: Optimization
          tag: Optimization
        - name: Small
          tag: Small
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: collection
    id: dissertation
    content:
      title: Dissertation
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: compact

  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: compact

  - block: collection
    id: travelling
    content:
      title: Travelling
      filters:
        folders:
          - travelling
    design:
      columns: '2'
      view: showcase

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to reach out for collaborative opportunities, academic discussions, or anything
        related to operations research, algorithm design, or Rust. I look forward to engaging with fellow enthusiasts
        and professionals in the field!
      # Contact (add or remove contact options as necessary)
      email: leon@sering.eu
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: Rämistrasse 101
        city: Zürich
        postcode: '8092'
        country: Switzerland
        country_code: CH
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
        #- 'Monday 10:00 to 13:00'
        #- 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '47.3769'
        longitude: '8.5482'
      #contact_links:
        #- icon: twitter
          #icon_pack: fab
          #name: DM Me
          #link: 'https://twitter.com/Twitter'
        #- icon: skype
          #icon_pack: fab
          #name: Skype Me
          #link: 'skype:echo123?call'
        #- icon: video
          #icon_pack: fas
          #name: Zoom Me
          #link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
        #provider: netlify
        #formspree:
          #id:
        #netlify:
          # Enable CAPTCHA challenge to reduce spam?
          #captcha: false
    design:
      columns: '2'
---
