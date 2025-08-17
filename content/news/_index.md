---
title: News
summary:
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: news
    content:
      title: News
      filters:
        folders:
          - news
    design:
      view: showcase
      columns: 1
      padding: ['20px', '0', '20px', '0']
---
