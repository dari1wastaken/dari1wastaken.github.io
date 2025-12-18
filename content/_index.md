---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: experience
    # id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Software Engineer Intern - Workload Identity in a Cloud Environment
          company: Amadeus
          company_url: 'https://amadeus.com'
          # company_logo: org-gc
          location: Villeneuve-Loubet, France
          date_start: '2023-03-01'
          date_end: '2023-09-01'
          # description: |2-
          #     * Analysing
          #     * Modelling
          #     * Deploying
        - title: Summer Intern - 5G Core Network Software Developer
          company: OpenAirInterface Software Alliance
          company_url: 'https://openairinterface.org/'
          # company_logo: org-x
          location: Sophia Antipolis, France
          date_start: '2022-06-01'
          date_end: '2020-09-01'
          # description: 
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        For any question, please contact me using the email address below.
      email: d.ferrero@tudelft.nl
      address:
        street: ECHO Building, Van Mourik Broekmanweg 5
        city: Delft
        postcode: '2628 XE'
        country: Netherlands
        country_code: NL
      directions: CS Offices, Room 02.160
      coordinates:
        latitude: '51.9995662'
        longitude: '4.3728249'  
      autolink: true
    design:
      columns: '2'
---
