---
title: Contact
sections:
  - type: section_contact
    template: section_contact
    section_id: contact
    title: Contact
    content: >
      Hello! We just want to say thank you in advance and we are looking forward
      to be your business partner for your data analytics needs.
    background: gray
    form_id: contactForm
    form_fields:
      - type: form_field
        template: form_field
        input_type: text
        name: name
        label: Name
        is_required: true
      - type: form_field
        template: form_field
        input_type: email
        name: email
        label: Email
        is_required: true
      - type: form_field
        template: form_field
        input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Data Integration
          - Data Warehouse
          - Business Analytics
          - Data Integration + Data Warehouse
          - Data Warehouse + Business Analytics
          - Data Integration + Data Warehouse + Business Analytics
          - FREE Consultation
      - type: form_field
        template: form_field
        input_type: textarea
        name: message
        label: Message
      - type: form_field
        template: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
template: landing
meta_title: Taleno Contact
meta_description: Taleno Data Analytics Services Contact
canonical_url: 'https://taleno.digital/contact'
---
