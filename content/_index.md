---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-27
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: publications
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
        - project
        
    design:
      # Choose a listing view
      view: showcase

  - block: collection
    id: awards
    content:
      title: Awards
      subtitle: ''
      text: Recent fellowships and awards.
      filters:
        folders:
        - awards
    design:
      # Choose a listing view
      view: compact
---
