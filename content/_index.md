---
title: "Home"
date: 2025-06-10
type: landing

design:
  # Default section spacing
  spacing: "6rem"
  background:
    image:
      filename: iridiscenceDark.jpg

sections:
  - block: hero-with-stats
    content:
      title: <span class="text-3d">SALA '26</span>
      text: <span class="text-3d-subtle">**Summit of AI in LatAm**</span>
      details: "<span class=\"text-3d-subtle\">March 9-12, 2026 | USFQ - Quito, Ecuador</span>"
      primary_action:
        text: "Registration Closed"
        url: https://docs.google.com/forms/d/e/1FAIpQLScQp8GfLSdhmhW6mc4SggVgOa_SxYPmPGlaVLqS93Lur17ZZA/viewform
        # icon: ticket
      #items:
      #  #- name: "Speakers"
      #  #  description: "300+"
      #  #- name: "Attendees"
      #  #  description: "4,000+"
      #  - name: "Venue"
      #    description: "USFQ"
      #  - name: "Location"
      #    description: "Quito, Ecuador"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      #css_class: "bg-gradient-to-r from-rose-100 to-teal-100"
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: panecillo.jpg
          filters:
            brightness: 1.0
  # - block: countdown
  #   content:
  #     title: "Hurry, Limited Availability"
  #     text: "EARLY BIRD PRICING ENDS IN"
  #     text_after: "SAVE UP TO $1,000!"
  #     date: "2000-01-01 00:00:00"
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-primary-500"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: CATALYSING AI IN LATIN AMERICA
          text: SALA brings together the Latin American artificial intelligence (AI) ecosystem. Emphasizing the interaction between actors based in Latin America and abroad, as well as the academic, government, and industrial communities, in order to catalyze the development, adaptation and use of AI in the region.
          image: riiaa2024Dragon.jpg
        - title: TRANSFORM
          text: Looking to the future and recognizing an increasingly transformative role for AI, SALA is organized by a group of academics and professionals from Latin American countries, seeking to bring together existing communities and groups in the field. This meeting aims to be an important complement to other conferences, emphasizing the interaction between groups based both in Latin America and abroad, as well as between the communities dedicated to research and practice.
          image: riiaa2024Panel2.jpg
        - title: LEARN
          text: Learn from world-experts in the field of AI about a diversity of topics. SALA combines lectures with hands-on practical sessions to maximize information sharing.
          image: jose2024.jpg
          #button:
          #  text: Get Tickets
          #  url: https://www.eventbrite.com/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: people
    id: confirmed-speakers
    content:
      title: Confirmed Speakers
      text: ""
      user_groups: ["ConfirmedSpeakers"]
    design:
      show_role: true
      show_social: true
      show_interests: false
  # - block: markdown
  #   id: agenda
  #   content:
  #     title: Agenda
  #     text: To be announced in late 2025, stay tuned! #|
        # **DAY 1**
        # {style="padding-top: 2rem"}
        # {{< table path="schedule.csv" header="true" >}}

        # **DAY 2**
        # {style="padding-top: 2rem"}

        # {{< table path="schedule.csv" header="true" >}}
  #- block: testimonials
  #  content:
  #    title: ""
  #    text: ""
  #    items:
  #      - name: "Alice Smith"
  #        role: "Researcher at X"
  #        # Upload image to `assets/media/` and reference the filename here
  #        image: "testimonial-1.jpg"
  #        text: "It has to be the most insightful conference I've ever attended!"
  #  design:
  #    spacing:
  #      # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #      padding: ["6rem", 0, 0, 0]
  - block: sponsors-tiered
    id: sponsors
    content:
      title: "Sponsors"
      text: "Thanks to our sponsors for making this incredible event possible!"
      tiers:
        - name: "VISIONARY"
          logos:
            - "sponsors/Google.svg"
            - "sponsors/Google_DeepMind_logo-modified.svg"
        - name: "PIONEER"
          logos:
            - "sponsors/apple_horizontal.svg"
        - name: "CATALYST"
          logos:
            - "sponsors/hopper dean-modified.png"
            - "sponsors/mbzuai_logo.png"
            - "sponsors/USFQ-Logo.png"
        - name: "IMPACT"
          logos:
            - "sponsors/Amazon_logo.svg"
            - "sponsors/mila_logo.png"
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]
  #  design:
  #    # Section background color (CSS class)
  #    css_class: "bg-black"
  #      # Card background color (CSS class)
  #      css_class: "bg-primary-700"
  #      css_style: ""
  #- block: cta-image-paragraph
  #  id: pastSponsors
  #  content:
  #    items:
  #    - title: Sponsors
  #      text: Thanks to our sponsors for making this incredible event possible!
  #      image: pastSponsors.png
  #  design:
  #    # Section background color (CSS class)
  #    css_class: "bg-black"
  #      # Card background color (CSS class)
  #      css_class: "bg-primary-700"
  #      css_style: ""
  #- block: newsletter
  #  content:
  #    title: "Stay up to date"
  #    text: "Be the first to receive conference updates such as added speakers, deadlines, and ticket deals."
  #    text_cta: "Sign up to our newsletter 🔥"
  #    button:
  #      text: "Subscribe"
  #    convertkit:
  #      form_id: ""
  #      msg_subscribed: "Success! Please check your email to confirm your subscription."
  #  design:
  #    card:
  #      # Card background color (CSS class)
  #      css_class: "bg-primary-700"
  #      css_style: ""
---
