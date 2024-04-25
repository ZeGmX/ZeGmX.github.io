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
  - block: skills
    content:
      title: Skills and Hobbies
      text: '<a href="https://github.com/ZeGmX/" target="_blank" rel="noopener"><div class="d-flex justify-content-center">
      <img src="https://github-readme-stats.vercel.app/api?username=ZeGmX&amp;show_icons=true&amp;hide=issues,contribs&amp;theme=dracula" alt="ZeGmX&amp;rsquo; stats" loading="lazy" style="margin: 20px;">
      </div></a>
      <a href="https://github.com/ZeGmX/" target="_blank" rel="noopener"><div class="d-flex justify-content-center">
      <img src="https://github-profile-trophy.vercel.app/?username=ZeGmX&amp;theme=dracula&amp;title=MultiLanguage,Commits,Experience,Stars,Repositories&amp;column=5" alt="trophy" loading="lazy"></div></a>'
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
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
        - title: PhD Candidate
          company: INSA Rennes / IRISA
          company_url: ''
          company_logo: insa
          location: Rennes, France
          date_start: '2022-10-03'
          date_end: ''
          description: |2-
              *Design of coupling schemes for ultrasound haptic rendering in virtual reality*
              
              Supervised by Maud Marchal and Claudio Pacchierotti - Rainbow team
        - title: Research-oriented internship
          company: CNRS / IRISA
          company_url: ''
          company_logo: cnrs
          location: Rennes, France
          date_start: '2022-02-01'
          date_end: '2022-07-31'
          description: |2-
              *Ultrasound haptic rendering for bimanual interactions in virtual reality*
              
              Supervised by Thomas Howard, Maud Marchal, and Claudio Pacchierotti - Rainbow team
        - title: Research-oriented internship
          company: Ultraleap
          company_url: ''
          company_logo: ultraleap
          location: Bristol, UK
          date_start: '2021-05-01'
          date_end: '2021-07-31'
          description: |2-
              *Adapting DOLPHIN (framework for the design and evaluation of ultrasound mid-air haptic stimuli, developed during my research project) to a new API enabling the control of the haptic  interfaces by Ultraleap*

              https://gitlab.com/h-reality/dolphin/-/tree/ultraleap_sensation
              
              Supervised by William Frier - Ultraleap
        - title: Research project
          company: IRISA
          company_url: ''
          company_logo: irisa
          location: Bristol, UK
          date_start: '2020-09-15'
          date_end: '2021-05-31'
          description: |2-
              *Software for the study of the perception of geometric shapes rendered using ultrasound haptic interface*

              https://gitlab.com/h-reality/dolphin
              
              Supervised by Thomas Howard, Guillaume Gicquel, Maud Marchal, and Claudio Pacchierotti - Rainbow team
        - title: Research-oriented internship
          company: IRISA
          company_url: ''
          company_logo: irisa
          location: Bristol, UK
          date_start: '2020-05-01'
          date_end: '2020-07-31'
          description: |2-
              *Implementing a multi-view stereo method for temporally consistent facial capture*

              https://github.com/ZeGmX/facial_capture_stereo
              
              Supervised by Adnane Boukhayma - MimeTIC team
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://docs.hugoblox.com/customization/#date-format
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
  #         icon: coursera
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         icon: edx
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         icon: datacamp
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
  - block: markdown
    content:
      title: Service
      subtitle: ''
      text: |2-
        - <font color="#3cb5b5">[2023 - Present]</font> Student representative to the IEEE RAS Technical Committee on Haptics 
        - <font color="#3cb5b5">[2022 - Present]</font> Reviewer
        
          **international journals**: IEEE Transactions on Visualization and Computer Graphics (TVCG), IEEE Transactions on Haptics (ToH)
        
          **international conferences**:  IEEE International Conference on Virtual Reality and 3D User Interfaces (VR), IEEE International Symposium on Mixed and Augmented Reality (ISMAR), IEEE World Haptics (WHC), IEEE Haptics Symposium, ACM International Conference on Tangible, Embedded and Embodied Interaction (TEI)

        - <font color="#3cb5b5">[July 2021]</font> Student volunteer at the IEEE World Haptics Conference (WHC)
    design:
      columns: '1'
  - block: markdown
    content:
      title: Supervision
      subtitle: ''
      text: |2-
        - <font color="#3cb5b5">[2022  - 2023]</font> Sarah Emery (M1 SIF, ENS Rennes, University of Rennes)
          
          *Dolphin3D: Rendering 3D objects using ultrasound haptic interfaces*

          Co-supervised with Thomas Howard
    design:
      columns: '1'  
  - block: markdown
    content:
      title: Teaching
      subtitle: ''
      text: |2-
        - <font color="#3cb5b5">[2024]</font> Lecture-tutorial and practical sessions • Java programing and algorithmic (INSA Rennes, STPI department, 2nd year)
        - <font color="#3cb5b5">[2023]</font> Lecture-tutorial and practical sessions • Initiation to Java programming (INSA Rennes, STPI department, 1st year)
        - <font color="#3cb5b5">[2022 - 2023]</font> Practical sessions • Design of innovative applications for health (INSA Rennes, CS department, 4th and 5th years)
        - <font color="#3cb5b5">[2022]</font> Project • Internet of things (INSA Rennes, CS department, 4th and 5th years)
    design:
      columns: '1'      
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     text: This section is under construction, but will be updated soon.
  #     filters:
  #       folders:
  #         - tmp
    #   # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
    #   default_button_index: 0
    #   # Filter toolbar (optional).
    #   # Add or remove as many filters (`filter_button` instances) as you like.
    #   # To show all items, set `tag` to "*".
    #   # To filter by a specific tag, set `tag` to an existing tag name.
    #   # To remove the toolbar, delete the entire `filter_button` block.
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Deep Learning
    #       tag: Deep Learning
    #     - name: Other
    #       tag: Demo
    # design:
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '1'
    #   view: showcase
    #   # For Showcase view, flip alternate rows?
    #   flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: featured
    content:
      title: Selected Publications
      text: |-
        {{% callout note %}}
        Browse the complete publication list [here](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
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
        If you have any questions about my research or if you would like to collaborate, feel free to contact me!
      # Contact (add or remove contact options as necessary)
      email: lendy.mulot [at] irisa.fr
      phone: +33 (0)7 84 09 04 96
      # appointment_url: 
      address:
        street: INSA Rennes, Bat. 18, Office 101
        city:
        region: 
        postcode: 35700 Rennes
        country:
        country_code:
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '48.120160'
        longitude: '-1.634515'  
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
      autolink: false
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '2'
---
