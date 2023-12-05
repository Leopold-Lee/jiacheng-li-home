---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: pub
    content:
      title: Publications and Pantents
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
  - block: experience
    id: exp
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
        - title: Data analyst intern 
          company: Auristione
          company_url: 'https://auristone.com/'
          company_logo: auristone
          location: Singapore
          date_start: '2023-08-07'
          date_end: ''
          description: |2-
              Responsibilities include:
              * Enhanced data quality, contributing to robust model outcomes
              * Built ML models using gene features for predicting cancer types
        - title: Teaching assistant (Java Programming and Computer Organization)
          company: SUSTech Computer Science Department
          company_url: ''
          company_logo: sustech
          location: Shenzhen
          date_start: '2021-08-07'
          date_end: '2022-12-31'
          description: |2-
              Responsibilities include:
              * Developed lesson plans and assignments, answering questions of students
              * Managed assignment deployment on an online judge 
        - title: Senior tutor
          company: SUSTech Administrative College
          company_url: ''
          company_logo: sustech
          location: Shenzhen，China
          date_start: '2021-09-01'
          date_end: '2022-06-02'
          description: |2-
              Responsibilities include:
              * Guided and mentored a group of 30 freshman students
              * Orchestrated various college activities
    design:
      columns: '2'
  - block: accomplishments
    id: acc
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Southern University of Science and Technology
          organization_url: https://www.sustech.edu.cn/en/
          title: First Class Scholarship
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2021-01-01'
          description: |2-
              * Smoothing the electromyographic signals to control prosthetic limbs
              * Combination of deep learning and traditional signal processing.
          organization: Southern University of Science and Technology
          organization_url: https://www.sustech.edu.cn/en/
          title: 'Best Innovation award in the Global Engineer Talent Research and Innovation Summer School'
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: ''
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: |2-
              * Led a team in a teaching volunteer program, benefiting 100+ children
              * Orchestrated curriculum scheduling and managed volunteer coordination
          organization: Guangdong Provincial Department of Education
          organization_url: http://www.moe.gov.cn/jyb_xwfb/xw_zt/moe_357/jyzt_2019n/2019_zt27/jyjs/guangdong/
          title: 'Outstanding Volunteer in Summer Social Practice'
          url: ''
    design:
      columns: '2'
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
---
