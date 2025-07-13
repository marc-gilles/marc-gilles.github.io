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
      title: news
      filters:
        folders:
          - news
    design:
      view: article-grid
      columns: 3
---
