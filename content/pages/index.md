---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: ''
    colors: colors-a
    title: We do fishing differently
    subtitle: Fresh. Better. Faster
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
      - type: Button
        label: Learn More
        url: /
        style: secondary
        showIcon: true
        icon: arrowRight
    feature:
      type: ImageBlock
      url: /images/fredrik-ohlander-CbeApl8sxxw-unsplash.jpg
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: center
        margin:
          - mt-8
          - mb-8
      text:
        textAlign: center
      actions:
        justifyContent: center
  - elementId: ''
    colors: colors-a
    quote: >
      ## “It’s great to see someone taking action while still maintaining a
      sustainbale fish supply to home cooks. ”
    name: Johnna Doe
    title: Head chef at Parks
    backgroundImage:
      url: /images/BG.png
      altText: Product Marketing Manager Quote
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      title:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
    type: QuoteSection
  - type: FeaturedPostsSection
    elementId: ''
    variant: variant-a
    colors: colors-a
    title: Upcoming adventures
    subtitle: 'Like we said, it''s more than just fishing'
    actions: []
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    styles:
      self:
        height: screen
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        justifyContent: center
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-12
      actions:
        justifyContent: center
---
