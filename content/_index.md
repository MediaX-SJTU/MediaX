---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: contact
    content:

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
            p {  
                font-size: 20px;  
            }  
            h1, h2, h3 {
              color: #1a1a1a;
            }
            h1 {
              font-size: 38px;
              margin-bottom: 20px;
            }
            h2 {
              font-size: 27px;
              margin-top: 40px;
            }
            ul {
              font-size: 20px;
              margin: 10px 0 20px 20px;
            }
            .highlight {
              color: #c0392b;
              font-weight: bold;
            }
          </style>
        </head>
        <body>

          <h1><strong>Welcome to MediaX@SJTU (上交智能媒体组)</strong></h1>

          <p>
            <strong>MediaX</strong> is a research group under the <a href="https://cmic.sjtu.edu.cn/CN/Default.aspx">Cooperative Medianet Innovation Center</a> at Shanghai Jiao Tong University, focusing on cutting-edge research at the intersection of <span class="highlight">computer vision</span>, <span class="highlight">machine learning</span>, and <span class="highlight">generative intelligent media</span>. We aim to advance the frontiers of multi-modal media (2D/3D/4D) across generation, restoration and enhancement, reconstruction and compression, and quality assessment. Our mission is to build intelligent systems capable of understanding, modeling, and manipulating complex human-centric visual content, enabling the high-quality and efficient creation of next-generation intelligent media.
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
            If you're passionate about intelligent media and generative AI, please send your <strong>CV and transcript</strong> to: <em><span class="highlight">mediax@sjtu.edu.cn</span></em>
          </p>

          <a href="mailto:mediax@sjtu.edu.cn" target="_blank">
          <i class="fas fa-envelope"></i> 联系我们
          </a>


          <a href="https://github.com/MediaX-SJTU" target="_blank">
              <i class="fab fa-github"></i> GitHub
          </a>


          <a href="https://notes.sjtu.edu.cn/s/9NKUMusdX" target="_blank">
              <i class="fab fa-weixin"></i> 微信
          </a>
        </body>

    design:
        columns: '1'


  - block: contact
    content:

      text: |-

        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>News</title>
            <style>
                body {
                }
                .news-item {
                    margin: 10px 0;
                }
            </style>
        </head>
        <body>
            <h1>🔥 News</h1>
            <div class="news-item">[2025/5]   One paper is accepted to ICML 2025</div>
            <div class="news-item">[2025/3]   Two paper is accepted to ICME 2025</div>
            <div class="news-item">[2025/2]   Two paper is accepted to CVPR 2025</div>
            <div class="news-item">[2025/2]   NTIRE 2025 XGC Quality Assessment Challenge Organizer</div>
            <div class="news-item">[2025/1]   One paper is accepted to JSAC 2025</div>
            <div class="news-item">[2024/12]  One paper is accepted to AAAI 2025</div>
            <div class="news-item">[2024/7]   One paper is accepted to TCSVT 2024</div>
            <div class="news-item">[2024/7]   One paper is accepted to ACM MM 2024</div>
            <div class="news-item">[2024/6]   One paper is accepted to ICIP 2024</div>
            <div class="news-item">[2024/3]   One paper is accepted to ICME 2024</div>
            <div class="news-item">[2024/2]   One paper is accepted to CVPR 2024</div>
            <div class="news-item">[2023/12]  One paper is accepted to AAAI 2024</div>
            <div class="news-item">[2023/6]   One paper is accepted to ICCP 2023</div>
            <div class="news-item">[2023/3]   One paper is accepted to CVPR 2023</div>
        </body>
        </html>

    design:
        columns: '1'

  - block: contact
    content:

      text: |-

        <!DOCTYPE html>
        <html lang="zh-CN"> <!-- 改为中文语言，更符合内容定位 -->
        <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge"> <!-- 优化IE渲染 -->
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>[CVPR Oral] Q-Eval-100K: 文本到视觉内容的视觉质量与对齐度评估</title> <!-- 补充网页标题（可根据需求调整中文/英文） -->
            <style>
                /* 全局重置 */
                * {
                    margin: 0;
                    padding: 0;
                    box-sizing: border-box;
                    font-family: '微软雅黑', 'Arial', sans-serif; /* 增加中文字体，提升可读性 */
                }

                /* 整体容器：左右两栏（自适应换行） */
                .container {
                    display: flex;
                    max-width: 1200px;
                    margin: 30px auto;
                    padding: 0 20px;
                    gap: 40px; /* 左右间距 */
                    align-items: flex-start; /* 顶部对齐 */
                    flex-wrap: wrap; /* 小屏幕下换行 */
                }

                /* 左侧图片容器（响应式） */
                .left-container {
                    width: 400px; /* 桌面端固定宽度 */
                    max-width: 100%; /* 小屏幕下自适应 */
                    border: 1px solid #e0e0e0; /* 轻微边框，提升层次感 */
                    border-radius: 8px; /* 圆角 */
                    overflow: hidden; /* 防止图片超出边框 */
                    margin-bottom: 20px; /* 换行后底部间距 */
                }

                /* 左侧图片（保持比例） */
                .left-image {
                    width: 100%;
                    height: auto;
                    display: block; /* 去除图片底部间隙 */
                }

                /* 右侧文字容器（自适应剩余宽度） */
                .right-container {
                    flex: 1; /* 占据剩余空间 */
                    min-width: 300px; /* 小屏幕下最小宽度，避免过窄 */
                    padding-top: 10px; /* 与左侧顶部对齐 */
                }

                /* 论文标题（突出显示） */
                .paper-title {
                    font-size: 1.4rem; /* 使用rem单位，更稳定 */
                    font-weight: bold;
                    color: #2c3e50;
                    margin-bottom: 15px;
                    line-height: 1.4;
                }

                /* CVPR Oral 标签样式（增强视觉识别） */
                .oral-tag {
                    background-color: #e74c3c; /* 红色背景（CVPR常用色） */
                    color: white;
                    padding: 3px 8px;
                    border-radius: 5px;
                    font-size: 0.8em;
                    font-weight: normal;
                    margin-right: 10px;
                    vertical-align: middle; /* 垂直居中 */
                }

                /* 作者列表（学术格式） */
                .authors {
                    font-size: 0.95em;
                    color: #34495e;
                    margin-bottom: 12px;
                    line-height: 1.5;
                }

                /* 共同一作上标 */
                .authors sup {
                    font-size: 0.7em;
                    margin-left: 2px;
                }

                /* 通讯作者（下划线突出） */
                .corresponding-author {
                    text-decoration: underline;
                    font-weight: 500;
                }

                /* 会议信息（灰色小字） */
                .conference {
                    font-size: 0.9em;
                    color: #7f8c8d;
                    margin-bottom: 20px;
                }

                /* 链接样式（蓝色， hover 下划线） */
                .links a {
                    color: #3498db;
                    text-decoration: none;
                    margin-right: 25px;
                    font-size: 0.95em;
                }

                .links a:hover {
                    text-decoration: underline;
                }
            </style>
        </head>
        <body>
            <main> <!-- 语义化标签：页面主要内容 -->
                <div class="container">
                    <!-- 左侧图片 -->
                    <div class="left-container">
                        <img src="images/4DGC.png" alt="Q-Eval-100K 视觉标注示例" class="left-image"> <!-- 优化alt文本（更具体） -->
                    </div>

                    <!-- 右侧论文信息 -->
                    <div class="right-container">
                        <h1 class="paper-title">
                            <span class="oral-tag">CVPR Oral</span> <!-- 突出显示会议标识 -->
                            Q-Eval-100K: Evaluating Visual Quality and Alignment Level for Text-to-Vision Content
                        </h1>
                        <p class="authors">
                            Zicheng Zhang<sup>*</sup>, Tengchuan Kou<sup>*</sup>, Shushi Wang, Chunyi Li, Wei Sun, Wei Wang, Xiaoyu Li, Zongyu Wang, Xuezhi Cao, Xiongkuo Min, 
                            <span class="corresponding-author">Xiaohong Liu<sup>*</sup></span>, Guangtao Zhai
                        </p>
                        <p class="conference">IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025.</p>
                        <div class="links">
                            <a href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">[Paper]</a> <!-- 安全链接 -->
                            <a href="https://github.com/" target="_blank" rel="noopener noreferrer">[Code]</a> <!-- 安全链接 -->
                        </div>
                    </div>
                </div>
            </main>
        </body>
        </html>

        
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