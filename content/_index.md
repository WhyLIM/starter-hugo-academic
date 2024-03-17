---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: Simple and commonly used programming language
          icon: python
          icon_pack: fab
        - name: R
          description: Simpler but memory-intensive programming language
          icon: r-project
          icon_pack: fab
        - name: VUE3
          description: A web framework I'm currently learning
          icon: vuejs
          icon_pack: fab
        - name: Windows
          description: Proficient in software installation and uninstallation
          icon: windows
          icon_pack: fab
        - name: Linux
          description: I will always support [**Ubuntu**](https://ubuntu.com/) and [**Zorin**](https://zorin.com/os/), rather than *RedHat* or *CentOS*
          icon: linux
          icon_pack: fab
        - name: Photography
          description: Hobby just getting started
          icon: camera-retro
          icon_pack: fas
    # design:
    #   background:
    #     gradient_end: '#1976d2'
    #     gradient_start: '#004ba0'
    #     text_color_light: true
  - block: experience
    id: experience
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
        - title: Data Engineer
          company: Guangdong Provincial People’s Hospital (GDPH)
          company_url: ''
          company_logo: org-gdph
          location: Guangdong
          date_start: '2023-04-23'
          date_end: ''
          description: |2-
              Responsibilities include:

              - Data Management
              - Data Analysis
              - Website Building
              - Programming
        - title: Bioinformatics Student
          company: Soochow University
          company_url: ''
          company_logo: org-suda
          location: Jiangsu
          date_start: '2018-09-01'
          date_end: '2022-06-30'
          description: Study specialized courses in bioinformatics.
    design:
      columns: '2'
  - block: accomplishments
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
          date_start: '2023-12-07'
          description: |2-
            Successfully collaborated in a team to replicate a complex research paper, ***ranking 11th among 131 participating teams***.

            ![First BIO-OS Open Source Open Contest](fbosoc.jpg)
          organization: ByteDance
          organization_url: https://www.bytedance.com/en/
          title: The 11th place in the Paper Reproduction Challenge of the First BIO-OS Open Source Open Competition
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2023-12-02'
          description: |2-
            Achieved ***Second Prize*** in the 2023 Guangdong Biomedical Big Data Analysis Community Innovation Competition.

            ![2023 Guangdong Biomedical Big Data Analysis Community Innovation Competition](gbbdacic.jpg)
          organization: Guangdong Bioinformatics Society
          organization_url: http://gdbs.org.cn/index.html
          title: Second Prize in the 2023 Guangdong Biomedical Big Data Analysis Community Innovation Competition
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2020-11-21'
          description: |2-
            For successfully completing the project "Biotechnology Innovation and Practice"

            ![Biotechnology Innovation and Practice](csha.jpg)
          organization: Cold Spring Harbor Asia
          organization_url: https://www.csh-asia.org/
          title: Biotechnology Innovation and Practice
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2020-10-18'
          description: |2-
            Achieved ***Second Prize*** in the Huawei China University Student ICT Competition 2020 Jiangsu Provincial Preliminary Contest (***Undergraduate Cloud Track***).

            ![Second Prize in the Huawei ICT Competition 2020](ict.jpg)
          organization: HUAWEI
          organization_url: https://www.huawei.com/cn/
          title: 'Second Prize in the Huawei ICT Competition 2020'
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2019-09-01'
          description: |2-
            Selected as "Outstanding Volunteer of Suzhou City" during the summer volunteer service event at Suzhou Railway Station in 2019.

            ![Outstanding Volunteer of Suzhou City](zyz.jpg)
          organization: Suzhou Volunteers Association
          organization_url: http://szzyz.xcb.suzhou.com.cn/
          title: Outstanding Volunteer of Suzhou City
          url: ''
    design:
      columns: '2'
#   - block: portfolio
#     id: projects
#     content:
#       title: Projects
#       filters:
#         folders:
#           - project
#       # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#       default_button_index: 0
#       # Filter toolbar (optional).
#       # Add or remove as many filters (`filter_button` instances) as you like.
#       # To show all items, set `tag` to "*".
#       # To filter by a specific tag, set `tag` to an existing tag name.
#       # To remove the toolbar, delete the entire `filter_button` block.
#       buttons:
#         - name: All
#           tag: '*'
#         - name: Deep Learning
#           tag: Deep Learning
#         - name: Other
#           tag: Demo
#     design:
#       # Choose how many columns the section has. Valid values: '1' or '2'.
#       columns: '1'
#       view: showcase
#       # For Showcase view, flip alternate rows?
#       flip_alt_rows: false
#   - block: markdown
#     content:
#       title: Gallery
#       subtitle: ''
#       text: |-
#         {{< gallery album="demo" >}}
#     design:
#       columns: '1'
  - block: collection
    id: featured
    content:
      title: Publications
    #   text: |-
    #     {{% callout note %}}
    #     Quickly discover relevant content by [filtering publications](./publication/).
    #     {{% /callout %}}
      count: 2
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
#   - block: collection
#     content:
#       title: Recent Publications
#       text: |-
#         {{% callout note %}}
#         Quickly discover relevant content by [filtering publications](./publication/).
#         {{% /callout %}}
#       filters:
#         folders:
#           - publication
#         exclude_featured: true
#     design:
#       columns: '2'
#       view: citation
#   - block: collection
#     id: talks
#     content:
#       title: Recent & Upcoming Talks
#       filters:
#         folders:
#           - event
#     design:
#       columns: '2'
#       view: compact
#   - block: tag_cloud
#     content:
#       title: Popular Topics
#     design:
#       columns: '2'
#   - block: collection
#     id: posts
#     content:
#       title: Recent Posts
#       subtitle: ''
#       text: ''
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 5
#       # Filter on criteria
#       filters:
#         folders:
#           - post
#         author: ""
#         category: ""
#         tag: ""
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#         publication_type: ""
#       # Choose how many pages you would like to offset by
#       offset: 0
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a layout view
#       view: compact
#       columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me if you have any interest.
      # Contact (add or remove contact options as necessary)
      email: mli.bio@outlook.com
    #   phone: 888 888 88 88
    #   appointment_url: 'https://calendly.com'
      address:
        street: No. 106, Zhongshan 2nd Road
        city: Guangzhou
        region: Guangdong
        postcode: '510000'
        country: China
        country_code: CN
    #   directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday to Friday, 8:30 to 17:30'
      contact_links:
        - icon: weixin
          icon_pack: fab
          name: WeChat Me ![QRcode](wechat.png)
          link: 'https://u.wechat.com/EF3f8Xr5QG8BxZ_F422d_xA'
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
