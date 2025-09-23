---
title: News
summary:
type: landing
# Choose how many pages you would like to display (0 = all pages)
count: 8 # does not seem to work

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
      count: 8 # how many posts are displayed (0 = all)
    design:
      view: compact # style of posts (others are: citation, article-grid, compact, card)
      # flip_alt_rows: true # for the Showcase view, flip alternate rows
      columns: 1
    
    
---
