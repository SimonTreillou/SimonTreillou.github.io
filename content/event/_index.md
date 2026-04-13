---
title: Talks
cms_exclude: true
type: landing

design:
  spacing: "4rem"

sections:
  - block: collection
    content:
      title: 🗓️ Upcoming talks
      count: 0
      filters:
        folders:
          - event
        exclude_past: true
    design:
      view: card

  - block: collection
    content:
      title: Featured past talks
      count: 0
      filters:
        folders:
          - event
        exclude_future: true
    design:
      view: citation
---
