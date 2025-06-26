---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      # title: |
      #   智能媒体课题组MediaX
        
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        智能媒体课题组（MediaX）聚焦于媒体大模型领域的研究探索，研究方向涵盖了媒体感知与评估、视频处理与生成、3/4D 生成与呈现以及新媒体智作平台等重要研究方向。其中，媒体感知与评估方向致力于构建针对 UGC、PGC 和 AIGC 内容的多维感知智能媒体质量评估理论体系；视频处理与生成方向专注于实现 4K/8K 超高清内容的修复增强以及可控的生成与编辑技术研发；3/4D 生成与呈现方向着力攻关 GenAI 驱动下的沉浸式视频高效表征、压缩及实时交互呈现相关技术；新媒体智作平台方向则致力于打造多智能体协同的自动化内容制作引擎与人机交互编辑平台。通过对以上领域的探索，课题组以媒体大模型为中心，突破多模态内容生成、增强、评估与呈现等一系列关键技术，为高质量、高效率的媒体制作提供坚实的支撑。
  
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

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
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
