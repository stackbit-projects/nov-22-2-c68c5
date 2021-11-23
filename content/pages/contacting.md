---
title: Contact us
sections:
  - type: HeroSection
    title: Contact us
    text: >-
      Fill out the form below and we will get in touch within 1 business day.
      Various versions have evolved over the years, sometimes by accident,
      sometimes on purpose (injected humour and the like).
    feature:
      type: FormBlock
      action: /.netlify/functions/submission_created
      elementId: contact-form
      submitLabel: Contact
      fields:
        - type: TextFormControl
          label: Name
          placeholder: Your name
          width: 1/2
          name: Name
        - name: lorem-ipsum
          label: Name
          placeholder: Your name
          isRequired: false
          width: full
          type: EmailFormControl
        - type: TextFormControl
          label: Last name
          placeholder: Your last name
          width: 1/2
        - type: EmailFormControl
          label: Email
          placeholder: Your email
          width: full
        - type: CheckboxFormControl
          label: Sign me up to receive updates
          width: full
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
          - pl-4
          - pr-4
        alignItems: flex-start
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - colors: colors-c
    elementId: ''
    title: Featured Items
    subtitle: The section subtitle
    items:
      - type: ItemBlock
        title: Item Title
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
      - type: ItemBlock
        title: Item Title
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
      - type: ItemBlock
        title: Item Title
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
    actions:
      - type: Button
        label: Apply Now
        url: '#'
        style: primary
      - type: Button
        label: Learn More
        url: '#'
        style: secondary
    columns: 3
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
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedItemsSection
layout: PageLayout
---
