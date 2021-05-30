---
title: Home
sections:
  - type: hero_section
    title: ADRENALINA WEB SERVICES
    content: |
      Passa dalla realtà fisica a quella online con Adrenalina
    actions:
      - label: SCOPRI
        url: /episodes
        style: secondary
    image: images/backgroung_homepage.jpeg
    image_alt: Hero section placeholder image
    media_position: left
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image: images/backgroung_homepage.jpeg
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 20
    has_border: true
  - title: 'Preventiva il tuo sito a partire da €299,99 '
    actions:
      - url: /1
        style: primary
        has_icon: false
        icon: facebook
        icon_position: right
        new_window: false
        no_follow: false
        type: action
        label: VAI AL PREVENTIVO AUTOMATICO
    grid_items: []
    grid_cols: three
    grid_gap_vert: small
    grid_gap_horiz: small
    enable_cards: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: grid_section
    background_image: images/Copy of Untitled Design.png
  - type: blog_feed_section
    title: I NOSTRI SERVIZI
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 6
    show_image: true
    show_date: true
    show_categories: false
    show_author: false
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: none
    background_image: images/pattern.svg
    background_image_repeat: repeat
    background_image_size: auto
    background_image_opacity: 98
    actions:
      - label: VEDI TUTTI
        style: secondary
        has_icon: false
        icon: apple-podcasts
        icon_position: right
        new_window: false
        no_follow: false
        type: action
        url: /episodes
  - actions: []
    grid_items:
      - title_align: left
        content: |
          # Alessandro Mallia

          Co-founder, Marketing Manager
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
        image: images/Untitled design (4).png
      - title_align: left
        content: |
          # Anas Bennar

          Co-founder, Graphic Manager
        content_align: left
        actions: []
        actions_align: left
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: left
        image_has_padding: true
        type: grid_item
        image: images/Untitled design (5).png
    grid_cols: two
    grid_gap_vert: large
    grid_gap_horiz: large
    enable_cards: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: grid_section
    title: FOUNDERS
  - type: form_section
    content: >
      ## CONTATTACI


      Hai qualche domanda sui servizi di Adrenalina o vuoi semplicemente saperne
      di più? Scrivici nella form box
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
        default_value: Il tuo nome
      - input_type: email
        name: email
        label: Email
        default_value: Il tuo indirizzo e-mail
        is_required: true
      - input_type: tel
        label: Il tuo numero di telefono
        default_value: Il tuo numero di telefono
        options: []
        is_required: false
        type: form_field
        name: Numero di telefono
      - input_type: textarea
        name: message
        label: Domanda
      - input_type: checkbox
        name: consent
        is_required: true
    submit_label: Invia
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image: images/backgroung_homepage.jpeg
    background_image_repeat: repeat
    background_image_size: cover
    background_image_opacity: 98
  - type: grid_section
    title: PARTNERS
    align: center
    grid_items:
      - image: images/logo-1.svg
        image_alt: Stackbit logo
        image_align: center
      - image: images/logo-2.svg
        image_alt: Netlify logo
        image_align: center
      - image: images/logo-3.svg
        image_alt: Sticker Mule logo
        image_align: center
      - image: images/logo-4.svg
        image_alt: GitHub logo
        image_align: center
      - image: images/logo-5.svg
        image_alt: Gatsby logo
        image_align: center
      - image: images/logo-6.svg
        image_alt: Twilio logo
        image_align: center
      - image: images/logo-7.svg
        image_alt: Contentful logo
        image_align: center
      - image: images/logo-8.svg
        image_alt: Forestry logo
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
    has_border: true
    background_color: none
    subtitle: 'Siamo sostenuti da fantastiche aziende '
seo:
  title: Stackbit Podcaster Theme
  description: The preview of the Podcaster theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Podcaster Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Podcaster theme
      keyName: property
    - name: 'og:image'
      value: images/hero.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Podcaster Theme
    - name: 'twitter:description'
      value: The preview of the Podcaster theme
    - name: 'twitter:image'
      value: images/hero.png
      relativeUrl: true
layout: advanced
---
