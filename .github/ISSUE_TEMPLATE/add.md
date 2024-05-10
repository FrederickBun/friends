name: 添加友链
description: 请先阅读自述文件后按照issues模板填写即可添加
title: "[ADD-FRIENDS] "
labels: ["friends:add"]
assignees: ["FrederickAsYou"]
body:
  - type: checkboxes
    id: pre-check
    attributes:
      label: 交换友链检查清单
      description: 请确保确认后，再提交 Issue
      options:
        - label: "已经阅读 `README.md`"
        - label: "您的站点类型为 `博客`"
        - label: "[网站域名符合规定](https://github.com/FrederickAsYou/friends/tree/main?tab=readme-ov-file#%E4%BA%A4%E6%8D%A2%E5%89%8D%E8%AF%B7%E9%98%85%E8%AF%BB)"
        - label: "网站内容符合国家规定"
  - type: textarea
    id: reproduce-steps
    attributes:
      label: "站点名称"
      placeholder: "站点名称请勿携带“博客”等字样且长度不宜太长"
  - type: textarea
    id: reproduce-steps
    attributes:
      label: "站点logo"
      placeholder: "建议使用头像用作logo"
  - type: textarea
    id: reproduce-steps
    attributes:
      label: "站点URL"
      placeholder: "URL须符合域名规定"
  - type: textarea
    id: reproduce-steps
    attributes:
      label: "站点介绍及人生格言"
      placeholder: "请包涵正能量内容"
