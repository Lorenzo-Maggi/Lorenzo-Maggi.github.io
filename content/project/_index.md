---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: portfolio
    content:
      title: Selected Projects
      subtitle: "Bridging the gap between engineering, robotics, and maker culture"
      filters:
        folders:
          - project
      buttons:
        - name: All
          tag: '*'
        - name: Robotics
          tag: robotics
        - name: Research
          tag: research
        - name: Maker & DIY
          tag: maker
      default_button_index: 0
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
