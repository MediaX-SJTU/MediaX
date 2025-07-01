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
        <head>
          <meta charset="UTF-8" />
          <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
          <title>MediaX Lab @ SJTU</title>
          <style>
            body {
              font-family: Arial, sans-serif;
              line-height: 1.6;
              margin: 0;
              padding: 40px;
              background-color: #ffffff;
              color: #333333;
            }
            h1, h2, h3 {
              color: #1a1a1a;
            }
            h1 {
              font-size: 2.2em;
              margin-bottom: 10px;
            }
            h2 {
              font-size: 1.6em;
              margin-top: 40px;
            }
            ul {
    
            }
            .highlight {
              color: #c0392b;
              font-weight: bold;
            }
          </style>
        </head>
        <body>

          <h1>Welcome to MediaX@SJTU (上交智能媒体组)</h1>

          <p>
            <strong>MediaX</strong> is a research group of Cooperative Medianet Innovation Center at <strong>Shanghai Jiao Tong University</strong>.  We target  top-tier research at the intersection of 
            <span class="highlight">computer vision</span>, <span class="highlight">machine learning</span>, and <span class="highlight">generative intelligent media</span>.
          </p>

          <p>
            We aim to push the boundaries of <strong>multi-modal media (2D/3D/4D)</strong> in the following areas:
          </p>
          <ul>
            <li>Generation</li>
            <li>Restoration and Enhancement</li>
            <li>Reconstruction and Compression</li>
            <li>Quality Assessment</li>
          </ul>

          <p>
            Our mission is to develop intelligent systems that can understand, model, and manipulate complex human-centric visual content, enabling 
            the high-quality and efficient creation of next-generation intelligent media.
          </p>

          <h2>🎯 Research Focus</h2>

          <ul>
            <li>
              <strong>Image and Video Restoration & Enhancement</strong><br/>
              High-resolution (4K/8K) quality restoration, super-resolution, and controllable editing of visual content.
            </li>
            <li>
              <strong>2D/3D/4D Generation, Representation & Compression</strong><br/>
              Efficient modeling and compact representation of dynamic scenes for immersive media.
            </li>
            <li>
              <strong>Multi-Modal Perception & Quality Assessment</strong><br/>
              Developing perceptual and semantic-aware evaluation systems for UGC, PGC, and AIGC content.
            </li>
            <li>
              <strong>Language-Guided Generation & Understanding</strong><br/>
              Leveraging vision-language models and diffusion frameworks to guide controllable generation and forgery detection.
            </li>
            <li>
              <strong>Interactive & Automated Media Creation Systems</strong><br/>
              Building collaborative, multi-agent platforms for intelligent content production and human-in-the-loop media editing.
            </li>
          </ul>

          <h2>📢 Join Us</h2>
          <p>
            We are always looking for <strong>self-motivated PhD students, Master's students, and undergraduate research assistants</strong> to join our team.<br/>
            If you're passionate about intelligent media and generative AI, please send your <strong>CV and transcript</strong> to: <em>mediax@sjtu.edu.cn</em>
          </p>

        </body>
    design:
        columns: '1'


  
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
