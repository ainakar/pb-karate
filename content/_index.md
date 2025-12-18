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
        - title: Ruza Vivie Ainaa binti Abdullah (Intake 12 July)
          text: When I was a child, I dreamed of learning a martial art, seeing it as a simple bucket list goal and something fun to try. That small curiosity led me into karate with no expectations of where the journey would take me. Over time, what began as an interest slowly grew into a passion and a strong sense of drive. Through training, challenges, and moments of self-doubt, karate shaped me both physically and mentally. It taught me discipline, resilience, and the determination to push forward even when progress felt slow. Karate became a tool for self-growth, encouraging me to constantly strive to be a better version of myself. Taking on the role of President of the club added deeper meaning to this journey. Leadership gave me a sense of purpose and responsibility beyond my own development. It taught me how to lead by example, support others, and build a stronger community. Through this role, I learned the importance of humility, consistency, and teamwork. What started as a childhood dream has now become a defining part of who I am today, both on and off the tatami.
          feature_icon: trophy
          features:
            - "Silver medal for kumite in Shitokai Brunei Open Karate Championship 2023 (+55kg)"
            - "Silver medal for kumite in 20th Sabah State Karate Championship 2023 (+55kg)"
            - "Silver medal for kumite in Wadokai Open championship 2023 (+55kg)"
            - "Silver medal for kumite in Kejohanan Skim Karate 2023 (+55kg)"
            - "Bronze medal for kumite in Kejohanan Sukan Karate Antara Skim Skim 2022 (+55kg)"
          # Upload image to `assets/media/` and reference the filename here
          image: vivie.jpeg
          button:
            text: About Me
            url: blog/25-12-18/
        - title: Danial Qays bin Haji Suhardy (Intake 13 July)
          text: Karate has been life changing for me. From a kid with dreams to competing on an international level representing my country in less than 2 years. Building strength and confidence with every punch, kick and kiai (shout). It has benefitted me in more ways than I could imagine and being able to express myself through martial arts. Every punch thrown with speed, every kick landing with precision and every technique done with intent. Karate has taught me courage, discipline and self-control.
          feature_icon: trophy
          features:
            - "Bronze medal for kumite in Interscheme Tournament 2023"
            - "Bronze medal for kumite in Shitokai Brunei Open Karate Championship 2023 (-67kg senior category)"
            - "Participated in North Borneo Open kumite 2024 (-67kg senior category)"
            - "Silver medal for kumite in Rengokai Karate Open Championship 2024 (-67kg senior category)"
            - "Participated in 12th SEAKF Brunei Darussalam 2025 (-67kg U21 category)"
          # Upload image to `assets/media/` and reference the filename here
          image: qays.jpeg
          # button:
          #   text: About Me
          #   url: blog/
        - title: Nurain Najibah binti Md Amir Hairil (Intake 13 July)
          text: I started my karate journey when I was eight years old under Rengokai Karate, training alongside my mother, who introduced my siblings and me to the sport. Due to unforeseen circumstances, I had to stop for a while, but after entering Politeknik Brunei, I was given the chance to return to karate under Shotokan Karate and rediscover my passion. Along the way, I volunteered at tournaments, competed and won medals, and gained close friends and meaningful memories. Through both the challenges and achievements, karate helped me grow into a more disciplined, resilient, and confident person in my everyday life.
          feature_icon: trophy
          features:
            - "Silver medal for kumite in Interscheme Tournament 2023 (-55kg senior category)"
            - "Gold medal for kumite in Rengokai Karate Open Championship 2024 (+55kg senior category)"
            - "Silver medal for team kata in Chancellor's Trophy 24/25"
          # Upload image to `assets/media/` and reference the filename here
          image: ain.jpeg
          # button:
          #   text: About Me
          #   url: blog/
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
    id: welcome
    content:
      title: Welcome to our blogsite!
      text: Discover our journey, one story at a time.
      button:
        text: A word from the club's founder
        url: blog/welcome/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---
