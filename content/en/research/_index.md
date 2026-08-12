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
  - block: research-areas
    content:
      title: Research Areas
      intro: >-
        I use applied microeconomics to study how environmental conditions,
        public policy, and information shape behavior and welfare.
      areas:
        - title: Environmental & Energy Economics
          eyebrow: Primary focus
          project_count: 3 projects
          description: >-
            I study pollution, climate, and the energy transition, with work on
            air quality, wind power, and distributed solar.
          topics:
            - Air Pollution
            - Climate & Wind
            - Energy Transition
          featured: true
        - title: Behavioral, Consumer & Health Economics
          eyebrow: Research theme
          project_count: 1 project
          description: >-
            I examine how information and nutrition labeling shape healthy
            consumer choices.
          topics:
            - Consumer Choice
            - Food Policy
            - Health
        - title: Education, Labor & Urban Economics
          eyebrow: Research theme
          project_count: 2 projects
          description: >-
            I evaluate long-run education outcomes and policy effects in labor
            and housing markets.
          topics:
            - Education
            - Labor
            - Housing
        - title: Political Economy & Information
          eyebrow: Research theme
          project_count: 1 project
          description: >-
            I study selective disclosure and how government endorsements affect
            voter beliefs.
          topics:
            - Information Disclosure
            - Political Communication
      methods:
        title: Methods
        intro: Empirical and structural tools used across the research portfolio.
        items:
          - Causal Inference
          - Regression Discontinuity
          - Instrumental Variables
          - Field Experiments
          - Survey Research
          - Dynamic Optimization
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
