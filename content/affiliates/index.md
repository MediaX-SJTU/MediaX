---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Industrial Support
      text: |-
        MediaX thanks our industrial partners for their support.


        <!DOCTYPE html>
        <html lang="zh-CN">
        <head>
            <meta charset="UTF-8">
            <title>商标集合展示</title>
            <style>
                /* 容器样式：用 Flex 布局实现自动换行、居中、间距控制 */
                .logo-container {
                    display: flex;       /* 开启 Flex 布局 */
                    flex-wrap: wrap;    /* 超出容器宽度时自动换行 */
                    justify-content: center; /* 水平居中排列 */
                    gap: 20px;          /* 图标之间的间距 */
                    padding: 20px;      /* 容器内边距，避免图标贴边 */
                }
                /* 图片样式：统一宽度，保持比例 */
                .logo-container img {
                    width: 120px;       /* 图标宽度（可根据需求调整） */
                    height: auto;       /* 自动保持宽高比，避免变形 */
                }
            </style>
        </head>
        <body>
            <div class="logo-container">
                <!-- Apple 图标 + 跳转 -->
                <a href="https://www.nsfc.gov.cn/" target="_blank">
                    <img src="images/nsfc.jpg" alt="Apple Logo">
                </a>
                <!-- NVIDIA 图标 + 跳转 -->
                <a href="https://stcsm.sh.gov.cn/" target="_blank">
                    <img src="images/shstcsm.png" alt="NVIDIA Logo">
                </a>
                <!-- SONY 图标 + 跳转 -->
                <a href="https://www.bilibili.com/" target="_blank">
                    <img src="images/bilibili.png" alt="SONY Logo">
                </a>
                <!-- Toyota Research Institute 图标 + 跳转 -->
                <a href="https://tv.cctv.com/live/" target="_blank">
                    <img src="images/cmg.png" alt="Toyota Research Institute Logo">
                </a>
                <!-- Google 图标 + 跳转 -->
                <a href="http://samc.comac.cc/" target="_blank">
                    <img src="images/samc.jpg" alt="Google Logo">
                </a>
                <!-- Verizon 图标 + 跳转 -->
                <a href="https://www.189.cn/" target="_blank">
                    <img src="images/chinatele.jpg" alt="Verizon Logo">
                </a>
                <!-- GM 图标 + 跳转 -->
                <a href="https://www.huawei.com/cn/" target="_blank">
                    <img src="images/huawei.png" alt="GM Logo">
                </a>
                <!-- Meta 图标 + 跳转 -->
                <a href="https://www.aliyun.com/?spm=5176.28507329.J_4VYgf18xNlTAyFFbOuOQe.d_logo.f8032868b1cDqr" target="_blank">
                    <img src="images/alibaba.png" alt="Meta Logo">
                </a>
                <!-- Picsart 图标 + 跳转 -->
                <a href="https://mall.hisense.com/" target="_blank">
                    <img src="images/hisense.png" alt="Picsart Logo">
                </a>

               
            </div>
        </body>
        </html>
      # email: mediax@sjtu.edu.cn
      # address:
      #   street: 上海交通大学电子信息楼群5号楼303A
      #   city: 上海市闵行区东川路800号
      #   country: China
      #   country_code: CN
      # directions: https://github.com/MediaX-SJTU
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # # Automatically link email and phone or display as text?
      # autolink: true
    
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
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
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: auto
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
