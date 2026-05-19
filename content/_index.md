---
title: ""
summary: ""
date: "2022-10-24"
type: "landing"
sections:
  - block: "hero"
    content:
      title: ""
      primary_action:
        url: "mailto:hello@datallurgy.com?subject= I am interested in services"
        text: "Contact me!"
        style: "gradient"
      secondary_action:
        url: "/services/"
        text: "Tell me more!"
      text: "I can help your concentrator<br>run at peak perfomance<br>with the assets you already have."
      eyebrow: "WHAT?"
    ce: "section-a5b50abf"
    design:
      size: "viewport"
      alignment: "center"
      no_padding: false
    As: "section-1eb3d2fd"
  - block: "resume-biography-3"
    content:
      username: "me"
      text: |-
        • 🍀 <a href="https://mse.mst.edu/undergraduateprograms/metallurgicalengineering/" target="_blank" rel="noopener noreferrer">Miner</a> and 🦅 <a href="https://masterdatascience.ubc.ca/" target="_blank" rel="noopener noreferrer">Thunderbird</a><br>
        • ⚒ Metallurgist and Mineral Processing Engineer<br>
        • 🧩 Data/Problem Solving/Optimization Nerd<br>
        • 🦘 <a href="https://www.jeroo.org/" target="_blank" rel="noopener noreferrer">Jeroo</a> Survivor <br>
        • 🎧 Audiophile <br>
        • 🥃 Bourbon Enthusiast<br>
        • 🧜‍♀️ Slightly Eccentric <br>
      headings:
        interests: ""
        about: "Hi, I'm Allyson! 👋"
        education: ""
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: "md"
      avatar:
        size: "medium"
        shape: "circle"
    ce: "section-8aded4ee"
    id: "bio"
    As: "section-161bc0ab"
  
  #- block: "resume-experience"
  #  content:
  #    username: "me"
  #  ce: "section-experience"
  #  id: "experience"
  #  As: "section-2ec3f8fe"
  
  - block: "collection"
    content:
      title: "Highlighted Projects"
      count: 3
      filters:
        folders:
          - "projects"
        featured_only: true
      order: "desc"
    design:
      view: "article-grid"
      columns: 3
    ce: "section-projects"
    id: "projects"
    As: "section-22e68d2f"
  - block: "collection"
    content:
      title: "Talks & Panels"
      count: 2
      filters:
        folders:
          - "events"
        featured_only: true
    design:
      view: "article-grid"
      columns: 2
    ce: "section-talks"
    id: "talks"
    As: "section-038a3921"
  - block: "collection"
    content:
      title: "Publications"
      text: ""
      filters:
        folders:
          - "publications"
        featured_only: true
    design:
      view: "citation"
    ce: "section-publications"
    id: "publications"
    As: "section-c8a78487"
---
