---
_schema: default
title: Contact Us
description: From vision to implementation, we help you create healthier
  environments with human-centric technology use.
keywords: []
pageSections:
  - _component: page-sections/people/team-grid
    sectionLabel: ''
    eyebrow:
    heading: Our Team
    subtext: From vision to implementation, we help you create healthier
      environments with human-centric technology use.
    teamMembers:
      - name: Alex Smith
        role: Lead Developer
        bio: As a fictional representation of a real employee, I exist solely to
          demonstrate how profile information appears in this layout. My
          headshot is perfectly lit, and my description maintains the ideal
          length for this component.
        imageSource: /src/assets/images/component-docs/okta.jpg
        imageAlt: Alex Smith, CEO
      - name: Tom Rodriguez
        role: Chief Technology Officer
        bio: I'm here to show how multiple team members look when displayed together. My
          expertise includes being professionally photographed and having
          exactly two sentences of biographical text.
        imageSource: /src/assets/images/component-docs/giulio.jpg
        imageAlt: Tom Rodriguez, CTO
      - name: Helen Kim
        role: Head of Design
        bio: I demonstrate how the component handles a third profile entry. My carefully
          crafted placeholder text ensures the layout remains consistent,
          regardless of whether you're viewing on a tablet or desktop display.
        imageSource: /src/assets/images/component-docs/griffin.jpg
        imageAlt: Helen Kim, Head of Design
      - name: Emily Watson
        role: Director of Operations
        bio: I round out the team grid to demonstrate how the layout adapts to a fourth
          member. My presence here confirms that the component scales
          appropriately, maintaining visual balance across different screen
          sizes.
        imageSource: /src/assets/images/component-docs/katla.jpg
        imageAlt: Emily Watson, Director of Operations
      - name: Team member name
        role: Job title
        bio: Brief bio or description of the team member.
        imageSource: /src/assets/images/component-docs/diana.jpg
        imageAlt: Team member photo
      - name: Davit Kakava
        role: Job title
        bio: Brief bio or description of the team member.
        imageSource: /src/assets/images/component-docs/davit.jpg
        imageAlt: Team member photo
    maxContentWidth: xl
    paddingHorizontal: lg
    paddingVertical: 2xl
    colorScheme: inherit
    backgroundColor: accent
    background:
      type: image
      positionVertical: top
      positionHorizontal: center
      priority: false
      imageSource: ''
      imageAlt: ''
      overlay: 0
  - _component: page-sections/ctas/cta-form
    sectionLabel: ''
    heading: Write Us
    subtext: |-
      You can contact us about more information on our services:

      &nbsp;
    formAction: ./
    formBlocks:
      - _component: building-blocks/forms/input
        label: Name
        name: name
        type: text
        required: true
        iconColor: default
        iconPosition: before
      - _component: building-blocks/forms/input
        label: Email
        name: email
        type: email
        required: true
        iconColor: default
        iconPosition: before
      - _component: building-blocks/forms/textarea
        label: Message
        name: message
        required: true
      - _component: building-blocks/forms/submit
        text: Send message
        variant: primary
        size: md
        iconColor: default
        iconPosition: before
        hideText: false
        disabled: false
    imageSource: /src/assets/images/component-docs/phone.svg
    imageAlt: Get in touch
    reverse: false
    maxContentWidth: xl
    paddingHorizontal: none
    paddingVertical: 6xl
    colorScheme: inherit
    backgroundColor: none
    background:
      type: image
      positionVertical: center
      positionHorizontal: center
      priority: false
      imageSource: ''
      imageAlt: ''
      overlay: 0
---
