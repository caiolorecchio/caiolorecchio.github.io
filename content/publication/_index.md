---
title: " "
cms_exclude: true

design:
# Default section spacing
  spacing: "6rem"

# View.
view: compact

sections:
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: compact
 #     columns: 2
  - block: collection
    id: projects
    content:
      title: Ongoing Projects
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      view: compact
 #     columns: 2
---


