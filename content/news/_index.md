---
title: News
summary:
type: landing
# Choose how many pages you would like to display (0 = all pages)
count: 0 # does not seem to work

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
      count: 0 # how many posts (0 = all); does not seem to work
    design:
      view: showcase
      columns: 1
      # spacing
      padding: ['0', '0', '0', '0']
    
    
---
