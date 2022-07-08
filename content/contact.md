---
title: Contact
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >-
      Let’s create something amazing together.<br>

      Complete our contact form or send us an email at
      <info@sawacmedia.com>.


      ***



    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: e.g. Stephen
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: e.g. stephen@mail.com
        is_required: true
      - input_type: select
        name: subject
        label: What services are you looking for?
        default_value: Please select
        options:
          - Logo Design
          - Brand Identity Design
          - Web and Search Engine Optimization
          - Content Creation
          - Web Design
      - input_type: textarea
        name: message
        label: Message
        default_value: Kindly tell us a bit about yourself, your project, timeline and budget
      - input_type: select
        name: medium
        label: How did you hear about us?
        default_value: Please select
        options:
          - Instagram
          - Pinterest
          - Medium
          - Behance
          - Word of mouth
          - Other
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
