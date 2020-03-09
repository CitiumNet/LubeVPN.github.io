---
layout: page
title: 順道VPN
subtitle: Anonymity & Circumvention
bigimg: /img/rain3.jpg
googlefonts: ["Noto Sans HK"]


forms:
  - to: amonic@gmail.com
    subject: New submission!
    redirect: /
    form_engine: formspree
    placeholders: false
    fields:
      - name: name
        input_type: text
        placeholder: Name
        required: true
      - name: email
        input_type: email
        placeholder: Email address
        required: true
      - name: sex
        input_type: radio
        placeholder: male
        required: true
      - name: sex
        input_type: radio
        placeholder: female
        required: true
      - name: message
        input_type: textarea
        placeholder: Message
        required: false
      - name: terms
        input_type: checkbox
        placeholder: I accept the terms and conditions
        required: true
      - name: submit
        input_type: submit
        placeholder: Submit form
        required: true

---

{% if page.forms[0] %}{% include form.html form="1" %}{% endif %}