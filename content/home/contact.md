---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

# Contact details (edit or remove options as required)
email: ktwilcox@cornell.edu
phone: ''
address:
  street: G201 Martha Van Rensselaer Hall, Department of Psychology, Cornell University
  city: Ithaca
  region: NY
  postcode: '14853'
  country: United States
  country_code: US
office_hours:
  - ''
# appointment_url: 'https://kwilcox3.youcanbook.me'
contact_links:
  - icon: twitter
    icon_pack: fab
    name: DM me
    link: 'https://twitter.com/KTylerWilcox'
  - icon: google-scholar
    icon_pack: ai
    name: Google Scholar
    link: 'https://scholar.google.com/citations?user=zEL8yZEAAAAJ'
  - icon: researchgate
    icon_pack: fab
    name: ResearchGate
    link: 'https://www.researchgate.net/profile/Kenneth-Wilcox'
  - icon: github
    icon_pack: fab
    name: Github
    link: 'https://github.com/ktw5691'
  - icon: orcid
    icon_pack: ai
    name: ORCiD
    link: 'https://orcid.org/0000-0003-3969-0427'
  # - icon: video
  #   icon_pack: fas
  #   name: Zoom
  #   link: ''

design:
  columns: '2'
---
