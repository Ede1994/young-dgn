---
# Leave the homepage title empty to use the site title
title:
date: 2024-02-21
type: landing

sections:
  - block: hero
    content:
      title: |
        YoungDGN
        Arbeitskreis der Deutschen Gesellschaft für Nuklearmedizin e.V.
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Wir sind ein Zusammenschluss junger Nukis und wir glühen für unser Fach! :-)

        Unsere Initiative entstand im Rahmen der von der DGN angestoßenen Task Force „Zukunft Nuklearmedizin“. Die Young DGN Initiative geht letztlich auf den vielfachen Wunsch nach der Gründung einer eigenen DGN-Nachwuchsorganisation zurück. Here we are!

        Unsere Türen stehen ärztlichem Personal, Kolleginnen und Kollegen aus der Radiopharmazie, Medizinphysik sowie anderen assoziierten Naturwissenschaften, MTRs, Pflegenden, Studierenden und Auszubildenden offen.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---