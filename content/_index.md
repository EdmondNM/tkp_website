---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: slider
    content:
      slides:
        - title: CityUHK - TKP GenAI Programme
          content: Venue City University of Hong Kong
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: bg-cityu.svg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: Lunch & Learn ☕️
          content: 'Share your knowledge with the group and explore exciting new topics together!'
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: bg-cityu.svg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: World-Class Semiconductor Lab
          content: 'Just opened last month!'
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: bg-cityu.svg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Click Here to Join Us
            url: https://cityu.qualtrics.com/jfe/form/SV_3mTlBHfWesJgV14?Q_CHL=qr
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

sections:
  - block: hero-slide
    content:
      images:
        - "image (2).png"
        - "image (1).png"
        - "image (3).png"
        - "image (4).png"
        - "image (5).png"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "transparent"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-cityu.svg
          filters:
            brightness: 1.0
            
  - block: features
    id: vision
    content:
      title: Our Vision
      text: Objectives for Ethical, Inclusive, and Transformative Learning
      items:
        - name: Foundations of Generative AI
          icon: magnifying-glass
          description: Develop a comprehensive understanding of the fundamental concepts and mechanisms underlying generative AI.
        - name: Ethical and Legal Compliance
          icon: bolt
          description: Learn to utilize generative AI ethically and in compliance with legal guidelines.
        - name: Quality, Safety & Inclusion
          icon: sparkles
          description: Acquire various techniques to ensure that generative AI models provide high-quality, accurate, unbiased and inclusive answers which also safeguard data safety and privacy.
        - name: Boosting Academic Self-Efficacy
          icon: code-bracket
          description: Enhance academic self-efficacy, leading to improvements in learning and academic achievement.
        - name: Student Empowerment & Service
          icon: star
          description: Empower university students to be trainers, to serve and contribute to the community.
        - name: Innovative & Interactive Learning
          icon: rectangle-group
          description: Engage teachers and students in the process of inspirational, interactive, and innovative learning, contributing to school development.

  - block: schedule
    id: schedule
    content:
      title: "Schedule"
      text: "Detailed Schedules for 2nd cohort"
      items:
        - date: "Jun 21"
          description: "Opening"
        - date: "Jun 28"
          description: "Session 2"
        - date: "Jul 5"
          description: "Session 3"
        - date: "Jul 12"
          description: "Session 4"
        - date: "Jul 19"
          description: "Session 5"
        - date: "Jul 26"
          description: "Session 6"
        - date: "Aug 2"
          description: "Session 7"
        - date: "Aug 16"
          description: "Closing"
      third_cohort_text: "Detailed Schedules for 3rd cohort"
      third_cohort_items:
        - date: "Sep 6"
          description: "Opening"
        - date: "Sep 13"
          description: "Session 2"
        - date: "Sep 20"
          description: "Session 3"
        - date: "Sep 27"
          description: "Session 4"
        - date: "Oct 11"
          description: "Session 5"
        - date: "Oct 18"
          description: "Session 6"
        - date: "Oct 25"
          description: "Session 7"
        - date: "Nov 8"
          description: "Closing"
  - block: stats
    content:
      items:
        - statistic: "400+"
          description: |
            Students
        - statistic: "20+"
          description: |
            Teachers from CityUHK
        - statistic: "10+"
          description: |
            Secondary schools
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: logos
    id: organizer
    content:
      title: Organizers
      text: This project is co-organized by Department of [Data Science](https://www.ds.cityu.edu.hk) / [Electrical Engineering](https://www.ee.cityu.edu.hk) / [Social and Behavioural Sciences](https://www.ssweb.cityu.edu.hk), City University of Hong Kong.
      logo_folder: organizers
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  - block: sponsor
    id: sponsor
    content:
      title: Sponsors
      text: This project is sponsored by Tin Ka Ping Foundation.
      icon: tinkapinglogo400b.png
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  - block: contact-us
    id: contacts
    content:
      title: Contacts
      text: For inquiries, reach us at
      items:
        - name: Email
          #icon: envelope
          description: yourproject@gmail.com
        - name: Instagram
          icon: IG.png
          action:
            text: Follow us on Instagram
            url: https://www.instagram.com/cityuhk_tkp_genai
#  - block: cta-image-paragraph
#    id: solutions
#    content:
#      items:
#        - title: Build your future-proof website
#          text: As easy as 1, 2, 3!
#          feature_icon: check
#          features:
#            - "Future-proof - edit your content in text files"
#            - "Website is generated by a single app, Hugo"
#            - "No JavaScript knowledge required"
#          # Upload image to `assets/media/` and reference the filename here
#          image: build-website.png
#          button:
#            text: Get Started
#            url: https://hugoblox.com/templates/
#        - title: Large Community
#          text: Join our large community on Discord - ask questions and get live responses
#          feature_icon: bolt
#          features:
#            - "Dedicated support channel"
#            - "3,000+ users on Discord"
#            - "Share your site and get feedback"
#          # Upload image to `assets/media/` and reference the filename here
#          image: coffee.jpg
#          button:
#            text: Join Discord
#            url: https://discord.gg/z8wNYzb
#    design:
#      # Section background color (CSS class)
#      css_class: "bg-gray-100 dark:bg-gray-900"
#  - block: testimonials
#    content:
#      title: ""
#      text: ""
#      items:
#        - name: "Hugo Smith"
#          role: "Marketing Executive at X"
#          # Upload image to `assets/media/` and reference the filename here
#          image: "testimonial-1.jpg"
#          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
#    design:
#      spacing:
#        # Reduce bottom spacing so the testimonial appears vertically centered between sections
#        padding: ["6rem", 0, 0, 0]
#  - block: cta-card
#    content:
#      title: Build your future-proof website
#      text: As easy as 1, 2, 3!
#      button:
#        text: Get Started
#        url: https://hugoblox.com/templates/
#    design:
#      card:
#        # Card background color (CSS class)
#        css_class: "bg-primary-700"
#        css_style: ""
---
