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
            <strong>MediaX</strong> is a research group under the <a href="https://cmic.sjtu.edu.cn/CN/Default.aspx">Cooperative Medianet Innovation Center</a> at Shanghai Jiao Tong University, focusing on cutting-edge research at the intersection of computer vision, <span class="highlight">computer vision</span>, <span class="highlight">machine learning</span>, and <span class="highlight">generative intelligent media</span>. We aim to advance the frontiers of multi-modal media (2D/3D/4D) across generation, restoration and enhancement, reconstruction and compression, and quality assessment. Our mission is to build intelligent systems capable of understanding, modeling, and manipulating complex human-centric visual content, enabling the high-quality and efficient creation of next-generation intelligent media.
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
            <div class="news-item">[2025/6]   Six papers are accepted by ICCV 2025</div>
            <div class="news-item">[2025/2]   Eight papers are accepted by CVPR 2025 (Two orals! 3.3% of the accepted papers, and two spotlights! 13.5% of the accepted papers)</div>
            <div class="news-item">[2025/1]   One paper is accepted by ICLR 2025</div>
            <div class="news-item">[2024/12]   One paper is accepted by AAAI 2025</div>
            <div class="news-item">[2024/9]   Four papers are accepted by NeurIPS 2024</div>
            <div class="news-item">[2024/7]   Five papers are accepted by ACM MM 2024 (Three orals! One oral paper was selected as Best Paper Nominees!)</div>
            <div class="news-item">[2024/7]   Three papers are accepted by ECCV 2024 (One oral)</div>
            <div class="news-item">[2024/4]   One paper is accepted by IJCAI 2024</div>
            <div class="news-item">[2024/2]   Two papers are accepted by CVPR 2024</div>
            <div class="news-item">[2023/7]   Three papers are accepted by ACM MM 2023 (Two orals!)</div>
            <div class="news-item">[2023/7]   One paper is accepted by ICCV 2023</div>
            <div class="news-item">[2023/3]   One paper is accepted by CVPR 2023</div>
            <div class="news-item">[2022/9]   One paper is accepted by NeurIPS 2022</div>
            <div class="news-item">[2022/3]   One paper is accepted by CVPR 2022</div>
        </body>
        </html>

    design:
        columns: '1'

  - block: contact
    content:

      text: |-

        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <style>
                /* 全局重置 */
                * {
                    margin: 0;
                    padding: 0;
                    box-sizing: border-box;
                    font-family: 'Arial', sans-serif;
                }

                /* 整体容器：左右两栏（左侧图片+右侧文字） */
                .container {
                    display: flex;
                    max-width: 1200px;
                    margin: 30px auto;
                    padding: 0 20px;
                    gap: 40px; /* 左右间距 */
                    align-items: flex-start; /* 顶部对齐（避免图片高度影响右侧布局） */
                }

                /* ------------------- 左侧图片容器（仅图片） ------------------- */
                .left-container {
                    width: 400px; /* 固定宽度（可根据图片比例调整） */
                    border: 1px solid #e0e0e0; /* 轻微边框（可选，提升层次感） */
                    border-radius: 8px; /* 圆角（可选） */
                    overflow: hidden; /* 防止图片超出边框（若有圆角） */
                }

                /* 左侧图片（占满容器，保持比例） */
                .left-image {
                    width: 100%; /* 占满左侧容器宽度 */
                    height: auto; /* 高度自动调整，避免变形 */
                    display: block; /* 去除图片底部间隙 */
                }

                /* ------------------- 右侧文字容器（论文信息） ------------------- */
                .right-container {
                    flex: 1; /* 占据剩余宽度，自适应 */
                    padding-top: 10px; /* 与左侧容器顶部对齐（可选） */
                }

                /* 论文标题（突出显示） */
                .paper-title {
                    font-size: 1.3em;
                    font-weight: bold;
                    color: #2c3e50;
                    margin-bottom: 15px;
                    line-height: 1.3;
                }

                /* 作者列表（带黑点标记） */
                .authors {
                    list-style-type: disc;
                    margin-left: 25px;
                    padding-left: 0;
                    font-size: 0.95em;
                    color: #34495e;
                    margin-bottom: 10px;
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

                /* 论文/代码链接（蓝色） */
                .links a {
                    color: #3498db;
                    text-decoration: none;
                    margin-right: 20px;
                    font-size: 0.95em;
                }

                .links a:hover {
                    text-decoration: underline; /* Hover下划线 */
                }

            </style>
        </head>
        <body>
            <div class="container">
                <!-- 左侧：仅单张图片（无额外元素） -->
                <div class="left-container">
                    <img src="images/4DGC.png" alt="Visual Annotation Example" class="left-image"> <!-- 替换为实际图片路径 -->
                </div>

                <!-- 右侧：论文文字内容（保持不变） -->
                <div class="right-container">
                    <h2 class="paper-title">[CVPR Oral] Q-Eval-100K: Evaluating Visual Quality and Alignment Level for Text-to-Vision Content</h2>
                    <ul class="authors">
                        <li>Zicheng Zhang*, Tengchuan Kou*, Shushi Wang, Chunyi Li, Wei Sun, Wei Wang, Xiaoyu Li, Zongyu Wang, Xuezhi Cao, Xiongkuo Min, <span class="corresponding-author">Xiaohong Liu*</span>, Guangtao Zhai</li>
                    </ul>
                    <p class="conference">IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025.</p>
                    <div class="links">
                        <a href="https://arxiv.org/" target="_blank">[Paper]</a> <!-- 替换为实际论文链接 -->
                        <a href="https://github.com/" target="_blank">[Code]</a> <!-- 替换为实际代码链接 -->
                    </div>
                </div>
            </div>
        </body>
        </html>

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