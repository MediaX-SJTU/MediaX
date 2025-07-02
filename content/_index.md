---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: contact
    content:
      # 移除冗余HTML标签，仅保留正文内容
      text: |-
        <h1>Welcome to MediaX@SJTU (上交智能媒体组)</h1>

        <p>
          <strong>MediaX</strong> is a research group under the Cooperative Medianet Innovation Center at Shanghai Jiao Tong University, focusing on cutting-edge research at the intersection of computer vision, machine learning, and generative intelligent media. We aim to advance the frontiers of multi-modal media (2D/3D/4D) across generation, restoration and enhancement, reconstruction and compression, and quality assessment. Our mission is to build intelligent systems capable of understanding, modeling, and manipulating complex human-centric visual content, enabling the high-quality and efficient creation of next-generation intelligent media.
        </p>

        <h2>🎯 Research Focus</h2>

        <ul>
          <li>
            <strong>Media Perception & Quality Assessment</strong><br/>
            Developing intelligent, multi-dimensional evaluation systems for UGC, PGC, and AIGC content.
          </li>
          <li>
            <strong>Video Restoration & Generation</strong><br/>
            Enhancing, controllably generating and editing 4K/8K video content.
          </li>
          <li>
            <strong>3D/4D Reconstruction & Generation</strong><br/>
            Leveraging 3DGS and GenAI for efficient representation and compression of immersive dynamic scenes.
          </li>
          <li>
            <strong>Intelligent Media Creation Platform</strong><br/>
             Building collaborative, multi-agent systems for automated and interactive media production.
          </li>
        </ul>

        <h2>📢 Join Us</h2>
        <p>
          We are always looking for <strong>self-motivated PhD students, Master's students, and undergraduate RA</strong> to join our team.<br/>
          If you're passionate about intelligent media and generative AI, please send your <strong>CV and transcript</strong> to: <em>mediax@sjtu.edu.cn</em>
        </p>

        <a href="mailto:mediax@sjtu.edu.cn" target="_blank">
        <i class="fas fa-envelope"></i> 联系我们
        </a>


        <a href="https://github.com/MediaX-SJTU" target="_blank">
            <i class="fab fa-github"></i> GitHub
        </a>


        <a href="https://example.com/wechat" target="_blank">
            <i class="fab fa-weixin"></i> 微信
        </a>

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