---
title: Latest News

# 使用默认 list 视图（左图右文布局）
view: list  

# 排序规则（可选，按日期倒序显示最新新闻）
sort_by: Date
sort_ascending: false  


# 显示字段：必须包含 Image（左侧图片）、Title（右侧标题）、Date（日期）等
fields:  
  - Image    # 左侧图片（关键）
  - title    # 右侧标题（关键）
  - date     # 右侧日期（可选）
#   - Summary  # 右侧摘要（可选，内容较多时显示）

# 内容来源（仅显示 post 文件夹下的新闻，根据实际调整）
# filter:  
#   folders:  
#     - post  
----