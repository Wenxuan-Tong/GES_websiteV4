---
# 使用网站标题作为主页标题
title:
date: 2025-03-14
type: landing

sections:
  - block: hero
    content:
      title: |
        **华北电力大学重力储能研究团队**<br>
        **NCEPU-Gravity Energy Storage Team**
      image:
        filename: image.png
      text: |
        <br>
        华北电力大学重力储能研究团队隶属于新能源电力系统国家重点实验室，致力于开发创新的储能解决方案，为全球能源转型提供中国智慧。
    design:
      columns: '2'
      css_class: text-center
  
  # - block: collection
  #   content:
  #     title: 最新动态
  #     count: 3
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  - block: markdown
    content:
      title: 研究方向
      text: |
        ### 电站级运行控制与配置优化
        开发重力储能系统的优化控制策略，提升系统运行效率和可靠性。

        ### 复合储能系统设计
        研究重力储能与其他储能形式的协同运行机制，实现多能互补。

        ### 重力储能潜力与综合效益评估
        分析不同地理环境下的重力储能应用潜力，评估其经济和环境效益。

        ### 智能化技术应用
        将人工智能技术应用于重力储能系统的设计、运行和维护。
    design:
      columns: '2'
      background:
        image: 
          filename: background.jpg
          filters:
            brightness: 0.7
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: collection
    content:
      title: 最新成果
      text: ""
      count: 3
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: '2'

  - block: markdown
    content:
      title: 加入我们
      text: |
        我们始终欢迎优秀的人才加入团队，共同探索重力储能技术的创新发展。
        
        {{% cta cta_link="./contact/" cta_text="了解更多 →" %}}
    design:
      columns: '1'
---
