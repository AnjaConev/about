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
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'

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
---
