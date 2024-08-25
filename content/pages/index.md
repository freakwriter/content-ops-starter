---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Knowledge management coaching
      color: text-dark
      type: TitleBlock
    subtitle: 'With your tools, on your timeline'
    text: >
      **knowledge management** *(n):* the framework or process an organization
      uses to identify, store, organize, and share information


      **sass** *(n):* an appealingly exciting, lively, or spirited quality


      Knowledge management can seem deceptively simple. But doing it—and
      particularly doing it well—can be challenging.


      Building or overhauling a knowledge management program or knowledge base
      can seem intimidating.


      Live with Sass is here to make it both less challenging and more sassy and
      joyful.
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Add some sass
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
      text:
        textAlign: left
  - title:
      text: Services
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: What I offer
    items:
      - title: Knowledge strategy
        tagline: Strategy with sass
        subtitle: Craft a vision and plan for success
        text: >
          We'll define a strategy that makes sense for your needs and determine
          tooling and process requirements to support that strategy.
        image:
          url: /images/randy-fath-G1yhU1Ej-9A-unsplash.jpg
          altText: >-
            A wooden chessboard set for the start of a match. One black pawn
            stands in line with the white pawns.
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Content strategy
        tagline: Content with sass
        subtitle: Match knowledge strategy with reality
        text: >
          Choose the tools that meet your requirements, formalize your style
          guide, and define content types and templates.
        image:
          url: /images/jan-mellstrom-tofagMI_UCM-unsplash.jpg
          altText: 'Five stacks of worn books, many with Italian titles.'
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Maintenance & upkeep
        tagline: Processes with sass
        subtitle: Knowledge base care and feeding
        text: >
          Define metadata and processes now that will keep updating and
          maintaining your content stress-free.
        image:
          url: /images/mike-newbry-7LsSwWhBRaQ-unsplash.jpg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - posts:
      - content/pages/blog/needs-before-tools.md
    showThumbnail: true
    showDate: true
    showAuthor: false
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
    title:
      type: TitleBlock
      text: Recent blog posts
      color: text-dark
    showExcerpt: true
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Interested?
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Live with Sass
  metaDescription: Knowledge management coaching with a bit of sass
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
