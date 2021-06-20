---
title: Home
sections:
  - type: hero_section
    title: 'Hi, I’m Alex Wang...'
    subtitle: >-
      A Sixth Form student at Wilson's School. I am a maths and technology
      enthusiast who loves learning.
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
        subtitle: 'Computing, tech reviews and more'
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
        image: images/feature-1.svg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Mathematics
        subtitle: Maths outside the curriculum
        content: |
          Mathematical topics explained with interesting puzzles and solutions
        actions:
          - label: Learn More
            url: /about
            style: secondary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-2.svg
        image_alt: Feature 2 illustration
        media_position: right
        media_width: sixty
      - title: My Projects
        subtitle: Detailed reports
        content: >
          Walk-throughs of my previous projects with detailed explanations of
          the execution. Become inspired and gain insight.
        actions:
          - label: See Past Work
            url: /faq
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/feature-3.svg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: grid_section
    title: Testimonials
    subtitle: What My Clients Say
    grid_items:
      - content: >-
          Alyvia is an amazing content writer. She helped us produce microcopy
          for our apps in all levels of user touchpoints.


          **Hanson Deck,** *App Developer, Studio*
        image: images/hanson-deck.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Alyvia really understands who our customers are and what tone of voice
          to use when communicating with them.


          **Miles Tone,** *CEO, Studio*
        image: images/miles-tone.png
        image_position: left
        image_width: twenty-five
      - content: >-
          Working with Alyvia was great because she was well versed in all of
          our tools and applications, and was able to manage our store and
          campaigns without any technical glitches.


          **Eleanor Carr,** *CTO, eCommerce Business*
        image: images/eleanor-carr.png
        image_position: left
        image_width: twenty-five
      - content: >-
          I love it when a content writer can really wordsmith and create copy
          that suits the design intention and style!


          **Gordon Norman,** *Web Designer, Local Business*
        image: images/gordon-norman.png
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
