---
title: Body Notes Journal
slug: /
sections:
  - type: GenericSection
    elementId: notify
    colors: "bg-[radial-gradient(circle_at_20%_20%,#f6eddd,#efddc9,#e8d1b4)] text-[#2b241a]"
    styles:
      self:
        flexDirection: col
        alignItems: center
        justifyContent: center
        padding:
          - pt-6
          - pb-6
          - pl-6
          - pr-6
      subtitle:
        textAlign: center
      text:
        textAlign: center
    subtitle: Register to get the publication email.
    media:
      elementId: notify-form
      type: FormBlock
      fields:
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your best email
          isRequired: true
          width: full
          type: EmailFormControl
      submitButton:
        type: SubmitButtonFormControl
        label: Notify me
        showIcon: true
        iconPosition: right
        style: primary
        className: "bg-[#2b241a] text-[#f6eddd] shadow-lg hover:opacity-90 transition px-6 py-3 rounded-full"
      styles:
        self:
          padding:
            - pt-4
            - pb-4
            - pl-4
            - pr-4
          borderWidth: 1
          borderStyle: solid
          borderRadius: x-large
          margin:
            - mt-10
  - type: CarouselSection
    elementId: gallery
    subtitle: Flip through the spreads and research highlights
    variant: dots-nav
    colors: "bg-[radial-gradient(circle_at_10%_30%,#f6eddd,#efddc9,#e8d1b4)] text-[#2b241a]"
    styles:
      self:
        padding:
          - pt-10
          - pb-16
          - pl-4
          - pr-4
      subtitle:
        textAlign: center
    items:
      - image:
          url: /images/body-notes-01.png
          altText: Comparison of Body Notes with typical journals
          type: ImageBlock
          imageClassName: "w-full h-auto rounded-2xl shadow-md"
          styles:
            self:
              borderRadius: large
        colors: "bg-[#f6eddd] text-[#2b241a]"
        styles:
          self:
            flexDirection: col
            padding:
              - pt-4
              - pb-4
              - pl-4
              - pr-4
            borderRadius: x-large
            textAlign: center
      - image:
          url: /images/body-notes-02.png
          altText: Research citations that inform the journal
          type: ImageBlock
          imageClassName: "w-full h-auto rounded-2xl shadow-md"
          styles:
            self:
              borderRadius: large
        colors: "bg-[#f6eddd] text-[#2b241a]"
        styles:
          self:
            flexDirection: col
            padding:
              - pt-4
              - pb-4
              - pl-4
              - pr-4
            borderRadius: x-large
            textAlign: center
      - image:
          url: /images/body-notes-03.png
          altText: Body Notes cover with leaf artwork
          type: ImageBlock
          imageClassName: "w-full h-auto rounded-2xl shadow-md"
          styles:
            self:
              borderRadius: large
        colors: "bg-[#f6eddd] text-[#2b241a]"
        styles:
          self:
            flexDirection: col
            padding:
              - pt-4
              - pb-4
              - pl-4
              - pr-4
            borderRadius: x-large
            textAlign: center
      - image:
          url: /images/body-notes-04.png
          altText: Guided body awareness prompts spread
          type: ImageBlock
          imageClassName: "w-full h-auto rounded-2xl shadow-md"
          styles:
            self:
              borderRadius: large
        colors: "bg-[#f6eddd] text-[#2b241a]"
        styles:
          self:
            flexDirection: col
            padding:
              - pt-4
              - pb-4
              - pl-4
              - pr-4
            borderRadius: x-large
            textAlign: center
      - image:
          url: /images/body-notes-05.png
          altText: Journal spread with creative prompts
          type: ImageBlock
          imageClassName: "w-full h-auto rounded-2xl shadow-md"
          styles:
            self:
              borderRadius: large
        colors: "bg-[#f6eddd] text-[#2b241a]"
        styles:
          self:
            flexDirection: col
            padding:
              - pt-4
              - pb-4
              - pl-4
              - pr-4
            borderRadius: x-large
            textAlign: center
      - image:
          url: /images/body-notes-06.png
          altText: Daily reflection questions spread
          type: ImageBlock
          imageClassName: "w-full h-auto rounded-2xl shadow-md"
          styles:
            self:
              borderRadius: large
        colors: "bg-[#f6eddd] text-[#2b241a]"
        styles:
          self:
            flexDirection: col
            padding:
              - pt-4
              - pb-4
              - pl-4
              - pr-4
            borderRadius: x-large
            textAlign: center
  - type: GenericSection
    colors: "bg-[radial-gradient(circle_at_80%_80%,#f6eddd,#efddc9,#e8d1b4)] text-[#2b241a]"
    styles:
      self:
        flexDirection: col
        alignItems: center
        justifyContent: center
        padding:
          - pt-6
          - pb-16
          - pl-6
          - pr-6
      text:
        textAlign: center
    title:
      text: Body Notes — Guided Journal for Clarity & Reflection
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    text: >-
      Calm, research-backed pages with body-map check-ins, creative space, and
      weekly reflections you can finish in five minutes. No spam—just the
      release announcement.
seo:
  metaTitle: Body Notes Journal — publication alert
  metaDescription: Join the publication notification list for Body Notes, a research-backed guided journal with calming layouts, body-mapping, and five-minute pages.
  socialImage: /images/body-notes-01.png
  type: Seo
type: PageLayout
---
