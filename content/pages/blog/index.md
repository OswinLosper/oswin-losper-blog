---
layout: PostFeedLayout
title: Blog Posts
colors: colors-d
numOfPostsPerPage: 10
postFeed:
  colors: colors-f
  showDate: true
  showAuthor: true
  showExcerpt: true
  showFeaturedImage: true
  showReadMoreLink: true
  variant: variant-d
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
styles:
  title:
    textAlign: left
topSections:
  - type: FeaturedPostsSection
    colors: colors-f
    elementId: ''
    showDate: true
    showAuthor: false
    showExcerpt: true
    showFeaturedImage: false
    showReadMoreLink: true
    variant: variant-b
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
    title: 'Posts:'
    subtitle: null
    posts:
      - content/pages/blog/post-five.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
---
