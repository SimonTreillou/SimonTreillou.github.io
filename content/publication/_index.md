---
title: Publications
cms_exclude: true
type: landing

design:
  spacing: "4rem"

sections:
  - block: collection
    content:
      title: Peer-reviewed publications
      filters:
        folders:
          - publication
        publication_type: "article-journal"
    design:
      view: citation

  - block: collection
    content:
      title: Conference proceedings
      filters:
        folders:
          - publication
        publication_type: "paper-conference"
    design:
      view: citation

  - block: collection
    content:
      title: Thesis
      filters:
        folders:
          - publication
        publication_type: "thesis"
    design:
      view: citation

  - block: collection
    content:
      title: Software
      filters:
        folders:
          - publication
        publication_type: "software"
    design:
      view: citation

  - block: collection
    content:
      title: Under review
      filters:
        folders:
          - publication
        publication_type: "under-review"
    design:
      view: citation
---
