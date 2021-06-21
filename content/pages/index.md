---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m Alex Wang...'
    subtitle: >-
      A Sixth Form student at Wilson's School. I am a maths and technology
      enthusiast who loves studying and learning.
    actions:
      - label: More About Me
        url: /about
        style: primary
    image: /images/kind-cabbage.jpg
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
  - type: features_section
    title: My Articles
    features:
      - title: Technology
        content: >
          Articles following current trends in the technology industry as well
          as explaining fundamental computer science principles.
        actions:
          - label: View articles
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/CPU Graphic.jpg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Mathematics
        content: |
          Mathematical topics explained with interesting puzzles and solutions.
        actions:
          - label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/Math beauty.jpg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: My Projects and Experiences
        content: >
          Walk-throughs of my previous academic projects and experiences with
          detailed explanations.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: /images/code-coding-computer-data-574071-1-scaled.jpg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
    section_id: /articles
  - type: grid_section
    grid_items:
      - title_align: left
        content: >+
          ## Personal Blog


          Check out my personal blog for an insight into my life outside school.
          Articles on music, cooking and travel.

        content_align: left
        actions:
          - label: lorem-ipsum
            url: '#'
            style: link
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: false
            type: action
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
        type: grid_item
      - title_align: left
        content: >
          ## Tuition


          I offer Maths and English tuition for students in KS2, KS3 and KS4. I
          have helped numerous students prepare for 11+ and 13+ exams as well as
          UKMT challenges. Check out my page for more details.
        content_align: left
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
        type: grid_item
      - title_align: left
        content: >
          ## The Philomath Club


          The Philomath Club is a community which I co-founded for students who
          love learning and increasing their knowledge of mathematics, computer
          science and engineering. We provide free curriculum-linked resources
          of a Post-16 level to help with exams, extra-curricular competitions
          and university admissions.
        content_align: left
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: false
        type: grid_item
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
    actions:
      - label: lorem-ipsum
        url: '#'
        style: link
        has_icon: false
        icon: arrow-left
        icon_position: right
        new_window: false
        no_follow: false
        type: action
      - label: lorem-ipsum
        url: '#'
        style: link
        has_icon: false
        icon: arrow-left
        icon_position: right
        new_window: false
        no_follow: false
        type: action
  - type: form_section
    content: >
      ## Let's talk


      If you would like to contact me with any enquiries, please use the form
      below.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Stackbit Personal Theme
  description: The preview of the Personal theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Personal Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Personal theme
      keyName: property
    - name: 'og:image'
      value: images/personal-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Personal Theme
    - name: 'twitter:description'
      value: The preview of the Personal theme
    - name: 'twitter:image'
      value: images/personal-preview.png
      relativeUrl: true
layout: advanced
---
