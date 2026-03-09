---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-03-04
type: landing

design:
  spacing: '0'

sections:
  # 1. HERO SECTION
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: false
      typewriter:
        enable: true
        prefix: "I am a"
        strings:
          - "Biomedical Engineer"
          - "PhD Researcher"
          - "Robotics Enthusiast"
          - "Maker & DIYer"
        type_speed: 40
        delete_speed: 40
        pause_time: 1000
      cta_buttons:
        - text: View My Projects
          url: "#project"
          icon: arrow-down
        - text: Get In Touch
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["2rem", "0", "0rem", "0"]
  
  # 2. PORTFOLIO SECTION
  - block: portfolio
    id: project
    content:
      title: "Featured projects"
      subtitle: "Bridging the gap between engineering, robotics, and maker culture"
      count: 0
      filters:
        folders:
          - project
      buttons:
        - name: All
          tag: '*'
        - name: Robotics
          tag: Robotics
        - name: Research
          tag: Research 
        - name: Maker & DIY
          tag: Maker
      default_button_index: 0
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Visual Tech Stack
  - block: tech-stack
    id: skills
    content:
      title: "Core Skills & Tech Stack"
      subtitle: "Software, robotics, and hands-on laboratory skills"
      categories:
        - name: Software & Languages
          items:
            - name: Python
              icon: devicon/python
            - name: C/C++
              icon: devicon/cplusplus
            - name: Java
              icon: devicon/java
            - name: MATLAB
              icon: devicon/matlab
            - name: Arduino
              icon: devicon/arduino
        - name: Engineering & Robotics
          items:
            - name: Robotic surgery
              icon: fas/surgery
            - name: Robotic control
              icon: fas/robot  
            - name: KUKA LBR Med
              icon: fas/robotMed
            - name: SolidWorks
              icon: fas/CAD
            - name: Microcontroller programming
              icon: fas/ucontroller
            - name: Knee Biomechanics
              icon: fas/knee

        - name: Lab & Prototyping
          items:
            - name: 3D Printing
              icon: fas/print
            - name: Sensor Calibration
              icon: fas/sensor
            - name: Soldering (incl. SMD)
              icon: fas/solder
            - name: Mechanical Assembly
              icon: fas/mechanincs
            - name: Electronic Prototyping
              icon: fas/electronics

        - name: Language & other skills 
          items:
            - name: Italian (native)
              icon: fas/italian
            - name: English (C1)
              icon: fas/english
            - name: Spanish (A2) 
              icon: fas/spanish
            - name: Volunteer EMT & driver
              icon: fas/ambulance
            - name: BLSD operator and trainer
              icon: fas/dae
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

# Experience Timeline
  - block: resume-experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
        
  # 3. CONTACT SECTION
  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Open to new collaborations and opportunities"
      text: |-
        Whether you are looking for a robotics engineer, want to discuss biomechanics, or just share a DIY project idea, feel free to reach out!
      email: lore.maggi.1996@gmail.com
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # 4. CTA CARD (CV DOWNLOAD)
  - block: cta-card
    content:
      title: "Looking for a pdf version?"
      text: |-
        Download my resume via the following link:
      button:
        text: 'Download CV'
        url: uploads/MaggiLorenzo_CVeng.pdf
        new_tab: true
    design:
      card:
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
        text_color: dark
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
