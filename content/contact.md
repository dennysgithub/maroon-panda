---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Kontakt & Offertförfrågan
    content: >
      Skicka ett snabbt meddelande där du beskriver ditt ärende i korthet så
      återkopplar vi snart vi kan.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Namn
        is_required: true
      - input_type: email
        name: email
        label: E-post
        is_required: true
      - input_type: select
        name: subject
        label: Ämne
        default_value: Vänligen välj
        options:
          - Inomhusmålning
          - Fasadmålning
          - Takmålning
          - Annan typ av målning
      - input_type: textarea
        name: message
        label: Message
      - input_type: checkbox
        name: consent
        label: >-
          Jag förstår att det här formuläret lagrar min skickade information så
          att jag kan kontaktas.
        is_required: true
    submit_label: Skicka meddelande
seo:
  title: Måleri Mölndal | Kontakt & Offertförfrågan
  description: Ta kontakt för att få en snabb offertförfrågan av oss.
  extra:
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
