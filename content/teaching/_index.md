---
title: Teaching
summary: My courses
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

# design:
#   # Section spacing
#   spacing: '5rem'

sections:
  - block: portfolio
    id: teaching
    content:
      title: Teaching
      subtitle: Here is a list of courses that I have taught. Course icons were created using Birdtrack Notation via ChatGPT-4.1.
      text: |2-
        Play around with the filters below to find out the study fields and technical skills covered among courses. The difficulty levels are:
        
          1. Basic
          2. Moderate
          3. Challenging (stay tuned)
          4. Extreme
      filters:
        folders:
          - teaching
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: R coding
          tag: r
        - name: JAGS coding
          tag: jags
        - name: LaTeX
          tag: latex
        - name: Statistics
          tag: stats
        - name: Computational Social Science
          tag: css
        - name: Basic level
          tag: easy
        - name: Moderate level
          tag: moderate
        - name: Challenging level
          tag: challenging
        - name: Extreme level
          tag: extreme
    # design:
    #   view: article-grid
    #   fill_image: false
    #   columns: '3'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
---
