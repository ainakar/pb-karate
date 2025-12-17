---
title: 'Home'
date: 2025-12-11
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Politeknik Brunei Karate Club
      text: Karate Archive from 2021 until Now
      primary_action:
        text: Find Us
        url: https://www.instagram.com/pb.karate?igsh=azNkMzc5eHR4bzlp
        icon: rocket-launch
      secondary_action:
        text: Find out more
        url: https://pb-karate.notion.site/Politeknik-Brunei-Karate-Club-6e5aa6c5ee704017b939c3a4e0267aee
      # announcement:
      #   text: "Welcome!"
      #   link:
      #     text: "A word from the club's founder"
      #     url: "https://ainakar.github.io/pb-karate/blog/welcome/"
    design:
    #   spacing:
    #     padding: [0, 0, 0, 0]
    #     margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: generations.jpeg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]
  # - block: features
  #   id: features
  #   content:
  #     title: Features
  #     text: Build your site with blocks 🧱
  #     items:
  #       - name: Optimized SEO
  #         icon: magnifying-glass
  #         description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
  #       - name: Fast
  #         icon: bolt
  #         description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
  #       - name: Easy
  #         icon: sparkles
  #         description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
  #       - name: No-Code
  #         icon: code-bracket
  #         description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
  #       - name: Highly Rated
  #         icon: star
  #         description: Rated 5-stars by the community.
  #       - name: Swappable Blocks
  #         icon: rectangle-group
  #         description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: athletes
    content:
      items:
        - title: Danial Qays bin Haji Suhardy (Intake 13 July)
          text: Karate has been life changing for me. From a kid with dreams to competing on an international level representing my country in less than 2 years. Building strength and confidence with every punch, kick and kiai (shout). It has benefitted me in more ways than I could imagine and being able to express myself through martial arts. Every punch thrown with speed, every kick landing with precision and every technique done with intent. Karate has taught me courage, discipline and self-control.
          feature_icon: trophy
          features:
            - "Bronze medal for kumite at Interscheme tournament"
            - "Bronze medal for kumite at Shitokai Open (-67kg senior category)"
            - "Silver medal for kumite in BSRC mini tournament (-67kg senior category)"
            - "Participated in North Borneo Open kumite(-67kg senior category)"
            - "Silver medal for kumite in Rengokai Open (-67kg senior category)"
            - "Participated in 12th SEAKF Brunei Darussalam (-67kg U21 category)"
            - "Silver medal in kata at BSRC mini tournament"
            - "Bronze medal in kumite at BSRC mini tournament (-67kg senior category)"
          # Upload image to `assets/media/` and reference the filename here
          image: qays.jpeg
          # button:
          #   text: Get Started
          #   url: https://hugoblox.com/templates/
        # - title: Large Community
        #   text: Join our large community on Discord - ask questions and get live responses
        #   feature_icon: bolt
        #   features:
        #     - "Dedicated support channel"
        #     - "3,000+ users on Discord"
        #     - "Share your site and get feedback"
        #   # Upload image to `assets/media/` and reference the filename here
        #   image: coffee.jpg
        #   button:
        #     text: Join Discord
        #     url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    id: members
    content:
      title: ""
      text: ""
      items:
        - name: "Syifa' Haliah binti Haji Hamdani"
          role: "Club President 2025/2026 (Intake 13 January)"
          # Upload image to `assets/media/` and reference the filename here
          image: "syifa.jpeg"
          text: "PBKC has helped shape the person I am today. I didn’t expect to stay for this long, but the support from our Shihan and everyone in the dojo kept pushing me to continue improving myself. Being surrounded by people who are passionate about karate motivated me to grow more confident, both physically and mentally. PBKC truly feels like a second family, bringing together people from different backgrounds through one shared sport."
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Siti Nurhalimah Zafirah @Nurjannah binti Mohammed Suffian"
          role: "Club President 2024/2025 (Intake 13 July)"
          # Upload image to `assets/media/` and reference the filename here
          image: "zafii.jpeg"
          text: "Given the chance and opportunity to lead the club has been incredible. Through it, I've learned a lot, from leadership to strengthening camaraderie with my teammates. I'm truly grateful for the opportunity to serve and contribute to the club's growth, helping it flourish and grow stronger for the next generation to come. OSS!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Welcome to our blogsite!
      # text: To our blogsite!
      button:
        text: A word from the club's founder
        url: blog/welcome/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---
