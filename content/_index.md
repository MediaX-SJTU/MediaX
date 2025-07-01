---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: contact
    content:
      # title: |
      #   MediaX Research Group
        
      # image:
      #   filename: welcome.jpg
      text: |-
        
        # Welcome to MediaX@SJTU (上交智能媒体组)  


        **MediaX** is a research group of Cooperative Medianet Innovation Center at **Shanghai Jiao Tong University**. We target top-tier research at the intersection of **computer vision**, **machine learning**, and **generative intelligent media**.  


        We aim to push the boundaries of **multi-modal media (2D/3D/4D)** in the following areas:  
        - Generation  
        - Restoration and Enhancement  
        - Reconstruction and Compression  
        - Quality Assessment  


        Our mission is to develop intelligent systems that can understand, model, and manipulate complex human-centric visual content, enabling the high-quality and efficient creation of next-generation intelligent media.  


        ## 🎯 Research Focus  

        - **Image and Video Restoration & Enhancement**  
          High-resolution (4K/8K) quality restoration, super-resolution, and controllable editing of visual content.  

        - **2D/3D/4D Generation, Representation & Compression**  
          Efficient modeling and compact representation of dynamic scenes for immersive media.  

        - **Multi-Modal Perception & Quality Assessment**  
          Developing perceptual and semantic-aware evaluation systems for UGC, PGC, and AIGC content.  

        - **Language-Guided Generation & Understanding**  
          Leveraging vision-language models and diffusion frameworks to guide controllable generation and forgery detection.  

        - **Interactive & Automated Media Creation Systems**  
          Building collaborative, multi-agent platforms for intelligent content production and human-in-the-loop media editing.  


        ## 📢 Join Us  

        We are always looking for **self-motivated PhD students, Master's students, and undergraduate research assistants** to join our team.  
        If you're passionate about intelligent media and generative AI, please send your **CV and transcript** to: *mediax@sjtu.edu.cn*

  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
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

  - block: collection
    content:
      title: Latest prints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        # publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
