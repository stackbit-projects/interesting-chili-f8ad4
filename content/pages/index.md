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
      - title: My Projects and Experience
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
    title: Testimonials
    grid_items:
      - content: >
          *Check out my personal blog for articles about cooking, music and
          travel*
        image_position: left
        image_width: twenty-five
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: large
    align: center
    background_color: secondary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
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
