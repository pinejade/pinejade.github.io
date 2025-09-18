---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Yuzhe Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        <p>
          <span style="font-size: 28px;">
          🧠<b>Yuzhe Lab</b>专注于脑损伤力学研究，探索如何在冲击中更好地监测和保护大脑。
          </span>
        <br>
          <span style="font-size: 20px;">
          🔬The <b>Yuzhe Lab</b> explores the mechanics of brain injury and designs better ways to monitor, model, and protect the brain to advance human health.
          </span>
        </p>

  - block: markdown
    content:
      title: "我们的研究方向"
      text: |
        自伽利略首次提出材料强度极限的概念以来，人类已花费数百年发展材料损伤理论。然而，至今仍有一个关键问题尚未解答：**力学是如何导致脑损伤（受伤）的？** 这一知识空白是不可接受的。

        💡 为了解决这一问题，Yuzhe Lab 重点关注四个方向：  
        - 揭示脑损伤的力学机制  
        - 构建精确的脑损伤模型  
        - 开发高精度脑损伤监测设备  
        - 设计先进的脑损伤防护装备  

        🚀 加入我们，一起推动科学与技术的前沿！

  - block: markdown
    content:
      title: What We Are Working On
      text: |
        Since Galileo first proposed the idea of material strength limitations, humanity has spent centuries developing theories of material damage. Yet to this day, one critical question remains unanswered: **How does mechanics lead to brain damage (injury)?** This gap in knowledge is unacceptable.  

        💡 To address it, The Yuzhe Lab focuses on four key directions:  
        - Uncovering the mechanical mechanisms of brain injury  
        - Building accurate brain injury models  
        - Developing high-precision brain injury monitoring devices  
        - Designing advanced protective equipment against brain injury  

        🚀 Join us as we push the boundaries of science and technology!

  - block: collection
    content:
      title: 课题组新闻 | Latest News
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
      title: 最新文章 | Latest Preprints
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
