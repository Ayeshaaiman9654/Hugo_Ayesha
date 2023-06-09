---
# Leave the homepage title empty to use the site title
title:
date: 2023-04-14
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: Communication
  #         description: 60%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Investigative 
  #         description: 80%
  #         icon: chalkboard-teacher
  #         icon_pack: fa
  #       - name: Analytical thinking
  #         description: 80%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD Research Scholar
          company: Jamia Millia Islamia
          company_url: 'https://www.jmi.ac.in/'
          company_logo: cap2
          location: New Delhi, India
          date_start: '2021-09-01'
          date_end: ''
          #description: |2-
              #Responsibilities include:

              #* Analysing
              #* Modelling
              #* Deploying
        - title: M.Sc. Biochemistry 
          company: Jamia Millia Islamia
          company_url: 'https://www.jmi.ac.in/'
          company_logo: cap2
          location: New Delhi, India
          date_start: '2018-08-01'
          date_end: '2020-07-31'
          #description: Taught electronic engineering and researched semiconductor physics.
    #design:
      #columns: '2'
  # - block: Ph.D. Research
  #   content:
  #     title: 'Ph.D. Research'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
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
      title: Ph.D. Research
      filters:
        folders:
          - project

    design:
      columns: '1'
      view: compact



  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Seminars & conferences
      text: |-
            - “Understand & Explore The World of Fluorescence”, Theory and skill development,<br> 25th -27th May 2022, [IIT Delhi](https://home.iitd.ac.in/)<br>
            - Poster presentation in National seminar on Biophysics, Biophysika 2023, [JMI Delhi](https://www.jmi.ac.in/)<br>
            - INDO-SINGAPORE WORKSHOP on [“Cardiovascular Diseases: An Insight to New Advances and their Translational Application”](https://www.jmi.ac.in/upload/publication/pr1_English_2021October11.pdf) 24th – 29th SEPTEMBER, 2021
            - Poster presentation in NCIACS-2023, [JMI Delhi](https://www.jmi.ac.in/)<br>

      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: card
  - block: collection
    id: recentpublications
    content:
      title: Recent Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications][def].
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation

  - block: collection
    id: talks
    content:
      title: Teaching and Mentorship
      text: |-
            - Teaching @ [Meera Bai Institute of Technology(MBIT), Delhi](http://revenue.delhi.gov.in/wps/wcm/connect/DOIT_MBIT/mbit/home)<br>
            Subject: Physical Health and Hygiene;
            Program: Diploma in Medical Lab Technology, Sem VI;
            Joining: January 2023-ongoing
            - Teaching @ [Jamia Millia Islamia, Delhi](https://www.jmi.ac.in)<br>
            Subject: Lab Course II, Immunology;
            Program: M.Sc. Biochemistry, Sem II;
            Joining: February 2023-ongoing
            - Mentored Alina Athar, M. Sc.Biosciences @ [Jamia Millia Islamia, Delhi](https://www.jmi.ac.in)<br>
            - Mentored Afreen, Centre for Interdisciplinary Research in Basic Sciences @ [Jamia Millia Islamia, Delhi](https://www.jmi.ac.in)<br>
            - Mentored Saba Rana,Department of Biotechnology @ [Graphic Era University](https://www.geu.ac.in/)

      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: card
  # - block: collection
  #   id: talks
  #   content:
  #     title: Teaching and Mentorship
  #     filters:
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
        For further questions, please do not hesitate to contact me via filling the details below.
      # Contact (add or remove contact options as necessary)
      email: Ayesha2100384@st.jmi.ac.in
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: Prof. Seemi Farhat Basir's lab 
        city: Lab No. 407, Department of Biosciences
        region: Jamia Millia Islamia, New Delhi
        postcode: '110025'
        country: India
        #country_code: US
      #directions: Enter Building  and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday to Saturday from 10:00 am to 6:00 pm'
      #   # - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
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


[def]: ./publication/