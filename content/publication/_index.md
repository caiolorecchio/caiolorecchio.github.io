---
type: landing
design:
  spacing: "3rem"  
sections:
  - block: collection
    id: publications
    content:
      title: "Publications"
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
 #     columns: 2
  - block: collection
    id: projects
    content:
      title: "Ongoing Projects"
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      view: citation
 #     columns: 2
---


