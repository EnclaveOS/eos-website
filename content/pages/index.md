---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: UXIfy Your Phone!
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      A Netlify Create website is a git repo that you own. Every code commit is
      instantly reflected in the visual editor and since every visual edit is a
      git commit, git workflows and collaboration just work.
    actions:
      - label: Get EnclaveOS
        altText: ''
        url: /
        showIcon: true
        icon: chevronRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
    badge:
      label: EnclaveOS
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
    media:
      type: VideoBlock
      title: Title of the video
      url: 'https://files.catbox.moe/li2lmv.mp4'
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '4:3'
      styles:
        self:
          padding:
            - pt-0
            - pb-0
            - pl-0
            - pr-0
          borderColor: border-light
          borderStyle: solid
          borderWidth: 0
          borderRadius: none
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
