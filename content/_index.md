---
# Leave the homepage title empty to use the site title
title: Binyamin Cooper
date: 2022-10-24
type: landing

sections:
#  - block: hero
#    content:
#      title: Hugo Academic Theme
#      image:
#        filename: hero-academic.png
#      cta:
#        label: '**Get Started**'
#        url: https://wowchemy.com/templates/
#      cta_alt:
#        label: Ask a question
#        url: https://discord.gg/z8wNYzb
#      cta_note:
#        label: >-

  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
#  - block: features
#    content:
#      title: Skills
#      items:
#        - name: R
#          description: 90%
#          icon: r-project
#          icon_pack: fab
#        - name: Statistics
#          description: 100%
#          icon: chart-line
#          icon_pack: fas
#        - name: Photography
#          description: 10%
#          icon: camera-retro
#          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Post-Doctoral Fellow
          company: Tepper School of Business, Carnegie Mellon University
          company_url: 'https://www.cmu.edu/tepper/faculty-and-research/academic-areas/organizational-behavior-and-theory/index.html'
          company_logo: 
          location: 
          date_start: '2020-08-16'
          date_end: ''
          description: |2-
             Three-year post-doctoral fellowship at the [Collaboration and Conflict Research Lab (CCRL)](https://www.cmu.edu/tepper/faculty-and-research/research/collaboration-conflict/index.html), working with **[Dr. Laurie R. Weingart](https://www.cmu.edu/tepper/faculty-and-research/faculty-by-area/profiles/weingart-laurie.html)** and **[Dr. Taya R. Cohen](https://www.cmu.edu/tepper/faculty-and-research/faculty-by-area/profiles/cohen-taya.html)**. 

             Research topics include:
             * Exploring The Nature of Honesty in The Workplace (as part of the [Honesty Project](https://honestyproject.philosophy.wfu.edu/meet-the-team/))
             * Balancing Honesty with Benevolence to Deliver Difficult Feedback
             * Teasing as "a Social Lubricant" in Teams

        - title: Organizational Consultant
          company: Tmurot TPS
          company_url: 'https://www.tmurot.com/tmurot/english/e-index.html'
          company_logo: 
          location: Petah Tikva, Israel
          date_start: '2013-07-01'
          date_end: '2015-07-31'
          description: |2-
             Coordinated performance and satisfaction evaluation processes for 14 clients on a yearly and/or quarterly basis. Clients included companies in the high-tech, healthcare, auto and financial industries (e.g., banking, insurance and credit companies).
          design:
      columns: '2'
#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
#      # Accomplishments.
#      #   Add/remove as many `item` blocks below as you like.
#      #   `title`, `organization`, and `date_start` are the required parameters.
#      #   Leave other parameters empty if not required.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Current Priority Projects
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
        - name: Workplace mistreatment
          tag: Workplace mistreatment
        - name: Honesty
          tag: Honesty
        - name: Resilience
          tag: Resilience
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#       folders:
#         - event
#   design:
#     columns: '2'
#     view: compact
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please feel free to reach out with any questions or requests.
      # Contact (add or remove contact options as necessary)
      email: bcoop@cmu.edu
      coordinates:
        latitude: '40.445066'
        longitude: '-79.945322'
#      phone: 888 888 88 88
#      appointment_url: 'https://calendly.com'
      address:
        street: 4765 Forbes Ave
        city: Pittsburgh
        region: PA
        postcode: '15213'
        country: United States
        country_code: US
      directions: Enter Building, take elevator to Floor 5, turn right and head to Office 5238
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Message me on Twitter
          link: 'https://twitter.com/BinyaminCooper'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
