---
title: Teaching
summary: My courses
type: landing

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

design:
  # Section spacing
  spacing: '5rem'

sections:
  - block: collection
    id: teaching
    content:
      title: Teaching
      text: Here's a list of courses that I have taught over the years. Course icons were created using Birdtrack Notation via ChatGPT-4.1.
      filters:
        folders:
          - teaching
    design:
      view: card # article-grid
      fill_image: false
      columns: '3'
---

