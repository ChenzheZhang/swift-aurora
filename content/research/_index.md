---
# Leave the homepage title empty to use the site title
title: 'Research'
summary: 'Ongoing research, manuscripts in revision, and selected projects.'
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '1rem'

sections:
  - block: tag-cloud
    content:
      title: Research Areas
      taxonomy: tags
      count: 20
      font_size_min: 0.8
      font_size_max: 1.0
      filters:
        folders:
          - publications
    design:
      spacing:
        padding: ['2rem', '0', '2rem', '0']
  - block: paper-list
    content:
      title: Ongoing Research
      filters:
        folders:
          - publications
        publication_type: ongoing-research
    design:
      spacing:
        padding: ['2rem', '0', '2rem', '0']

  - block: paper-list
    content:
      title: Selected Research Projects
      filters:
        folders:
          - publications
        publication_type: completed-project
    design:
      spacing:
        padding: ['2rem', '0', '2rem', '0']
---
