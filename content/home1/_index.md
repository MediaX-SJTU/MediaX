---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: contact
    content:

      text: |-

        <p style="text-align: center;">MediaX thanks national research programs and our industrial partners for their support.</p>
        
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
                    gap: 100px;          /* 图标之间的间距 */
                    padding: 20px;      /* 容器内边距，避免图标贴边 */
                }
                /* 图片样式：统一宽度，保持比例 */
                .logo-container img {
                    width: auto;       /* 图标宽度（可根据需求调整） */
                    height: 120px;       /* 自动保持宽高比，避免变形 */
                }
            </style>
        </head>
        <body>
            <div class="logo-container">
                <a href="https://www.nsfc.gov.cn/" target="_blank">
                    <img src="images/nsfc.png" alt="Apple Logo">
                </a>
                <a href="https://www.bilibili.com/" target="_blank">
                    <img src="images/bilibili.png" alt="SONY Logo">
                </a>
                <a href="http://samc.comac.cc/" target="_blank">
                    <img src="images/comac.jpg" alt="Google Logo">
                </a>
                <a href="https://www.huawei.com/cn/" target="_blank">
                    <img src="images/huawei.jpg" alt="GM Logo">
                </a>
                <a href="https://www.most.gov.cn/index.html" target="_blank">
                    <img src="images/tests.jpg" alt="NVIDIA Logo">
                </a>
                <a href="https://stcsm.sh.gov.cn/" target="_blank">
                    <img src="images/shstcsm.jpg" alt="NVIDIA Logo">
                </a>
                <a href="https://tv.cctv.com/live/" target="_blank">
                    <img src="images/cmg.png" alt="Toyota Research Institute Logo">
                </a>
                <a href="https://www.189.cn/" target="_blank">
                    <img src="images/chinatele.jpg" alt="Verizon Logo">
                </a>
                <a href="https://www.aliyun.com/?spm=5176.28507329.J_4VYgf18xNlTAyFFbOuOQe.d_logo.f8032868b1cDqr" target="_blank">
                    <img src="images/alibaba.png" alt="Meta Logo">
                </a>
                <a href="https://mall.hisense.com/" target="_blank">
                    <img src="images/hisense.jpg" alt="Picsart Logo">
                </a> 
            </div>
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
            <title>News</title>
            <style>
                body {
                    margin: 0;
                    padding: 0;
                }
                .container {
                    display: flex;
                    justify-content: space-between;
                    align-items: flex-start;
                    padding: 20px;
                }
                .title {
                    flex: 0 0 auto;
                    margin-top: 0;
                }
                .news-list {
                    flex: 1 1 auto;
                    margin-left: 120px; /* 标题和新闻列表之间的间距 */
                    margin-top: 30px;
                }
                .news-item {
                    margin: 6px 0;
                }
            </style>
        </head>
        <body>
            <div class="container">
                <div class="title">
                    <h1>🔥 News: </h1>
                </div>
                <div class="news-list">
                    <div class="news-item">[2025/6]   Two paper is accepted to ICCV 2025</div>
                    <div class="news-item">[2025/5]   One paper is accepted to ICML 2025</div>
                    <div class="news-item">[2025/3]   Two paper is accepted to ICME 2025</div>
                    <div class="news-item">[2025/2]   Two paper is accepted to CVPR 2025</div>
                    <div class="news-item">[2025/2]   NTIRE 2025 XGC Quality Assessment Challenge Organizer</div>
                    <div class="news-item">[2025/1]   One paper is accepted to JSAC 2025</div>
                    <div class="news-item">[2024/12]  One paper is accepted to AAAI 2025</div>
                    <div class="news-item">[2024/7]   One paper is accepted to TCSVT 2024</div>
                    <div class="news-item">[2024/7]   One paper is accepted to ACM MM 2024</div>
                    <div class="news-item">[2024/6]   One paper is accepted to ICIP 2024</div>
                </div>
            </div>
        </body>
        </html>
      
    design:
        columns: '1'

---