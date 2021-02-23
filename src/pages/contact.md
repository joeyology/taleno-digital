---
title: Contact
sections:
  - type: section_contact
    template: section_contact
    section_id: contact
    title: Contact
    content: "Hello! \U0001F44B Thanks for dropping by and we are looking forward hear from you. \U0001F49A\n"
    background: gray
    form_id: contactForm
    form_fields:
      - type: form_field
        template: form_field
        input_type: text
        name: name
        label: Name
        is_required: true
        default_value: ''
        options: []
      - type: form_field
        template: form_field
        input_type: email
        name: email
        label: Email
        is_required: true
        default_value: ''
        options: []
      - type: form_field
        template: form_field
        input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Christian Life
          - Data Warehouse
          - Business Analytics
          - Data Integration + Data Warehouse
          - Data Warehouse + Business Analytics
          - Data Integration + Data Warehouse + Business Analytics
          - FREE Consultation
        is_required: false
      - type: form_field
        template: form_field
        input_type: textarea
        name: message
        label: Message
        default_value: ''
        options: []
        is_required: false
      - type: form_field
        template: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
        default_value: ''
        options: []
    submit_label: Send Message
    subtitle: ''
    form_action: ''
    hide_labels: false
template: landing
seo:
  title: Contact
  description: 'Taleno Data Analysis Services, Contact'
  type: stackbit_page_meta
  template: stackbit_page_meta
  extra:
    - name: 'og:type'
      value: website
      keyName: property
canonical_url: 'https://taleno.digital/contact'
no_index: false
---
