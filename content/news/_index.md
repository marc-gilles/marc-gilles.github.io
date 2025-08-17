---
title: News
summary:
type: landing
# Choose how many pages you would like to display (0 = all pages)
count: 0

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
      # spacing
      padding: ['0', '0', '0', '0']
    # Choose how many pages you would like to display (0 = all pages)
    count: 0
    
---
