---
title: Home
layout: PageLayout
colors: colors-d
backgroundImage:
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-d
    backgroundSize: inset
    title: I’m a AUTOMATION TESTER
    subtitle: >-
      Currently Im a full time Automation Tester at 20fifty. We building
      solutions or thinking about the impact that Cloud Computing and AI has and
      will continue to have on the world and society. 
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
          - pt-20
          - pb-20
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Posts
    showFeaturedImage: true
    actions:
      - type: Link
        label: See all posts
        url: /blog
        iconPosition: right
        icon: apple
    posts:
      - content/pages/blog/post-seven.md
      - content/pages/blog/post-six.md
      - content/pages/blog/post-one.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
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
          - pt-7
          - pb-7
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    showAuthor: true
  - type: FeaturedPostsSection
    colors: colors-f
    elementId: ''
    showDate: true
    showAuthor: true
    showExcerpt: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-a
    actions:
      - type: Link
        label: See all posts
        altText: See all posts
        url: /blog
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    title: 'Blog Posts:'
    subtitle: null
    posts:
      - content/pages/blog/post-five.md
      - content/pages/blog/post-four.md
---
