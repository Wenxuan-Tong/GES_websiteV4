---
title: 学术成果
type: publication

# 文献引用设置
bibliography: publications.bib
citation_style: apa

# 视图类型（必需）
view: citation

# 可选的页眉图片
header:
  caption: ""
  image: ""

# 可选项：添加自定义 CSS 样式
styles:
  - custom.css

# 文章分组和排序设置
sections:
  - block: collection
    content:
      title: 论文列表
      text: |
        点击文章标题可跳转至出版页面。
      filters:
        folders:
          - publication
        exclude_featured: false
      sort_by: date
      sort_ascending: false
    design:
      view: citation
      columns: '1'

  - block: collection
    content:
      title: 代表性论文
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: '2'
---