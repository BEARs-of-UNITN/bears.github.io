---
title: 'Home'
date: 2023-10-24
type: landing

sections:
  - block: hero
    content:
      title: BEARs Lab
      text: AI for medicine, neurological disorders, and personalized disease progression modeling.
      primary_action:
        text: Our Research
        url: "#research"
        icon: magnifying-glass
      secondary_action:
        text: Publications
        url: "#publications"
      announcement:
        text: "Research at the intersection of AI and medicine."
        link:
          text: "Contact us"
          url: "#contact"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "navy"
        image:
          filename: bg-triangles.svg
          filters:
            brightness: 0.35
          size: cover
          position: center
          parallax: false

  - block: markdown
    id: about
    content:
      title: About
      text: |
        We are a research lab working on artificial intelligence for healthcare, with a focus on neurological disorders, multimodal generative modeling, and personalized medicine.

        Our goal is to develop computational methods that model disease progression from irregular longitudinal data and support clinically meaningful predictions.
    design:
      columns: "1"

  - block: features
    id: research
    content:
      title: Research Areas
      text: Our main directions of work
      items:
        - name: Multimodal AI
          icon: cpu-chip
          description: Integrating imaging, clinical, molecular, and longitudinal data for robust disease modeling.
        - name: Disease Progression Modeling
          icon: chart-bar
          description: Building generative and predictive models of disease trajectories over time.
        - name: Neurological Disorders
          icon: heart
          description: Applying machine learning to clinically relevant questions in neuroscience and neurology.
        - name: Personalized Medicine
          icon: sparkles
          description: Designing models that support individualized prognosis and treatment understanding.
        - name: Longitudinal Data
          icon: calendar-days
          description: Handling irregularly sampled, incomplete, and heterogeneous temporal medical data.
        - name: Clinical AI
          icon: academic-cap
          description: Developing trustworthy methods that connect methodological innovation with medical impact.

  - block: markdown
    id: people
    content:
      title: People
      text: |
        Meet the team behind our research.

        Team member profiles can be added in the `content/authors/` folder.
    design:
      columns: "1"

  - block: markdown
    id: publications
    content:
      title: Publications
      text: |
        Our recent publications and preprints are listed here.

        Publication entries can be managed in the `content/publication/` folder.
    design:
      columns: "1"

  - block: markdown
    id: opportunities
    content:
      title: Open Positions
      text: |
        We welcome inquiries from motivated students and collaborators interested in AI for medicine, generative modeling, and computational neuroscience.

        Please get in touch if you are interested in PhD opportunities, research visits, or collaborations.
    design:
      columns: "1"

  - block: cta-card
    id: contact
    content:
      title: Contact
      text: |
        Get in touch to discuss collaborations, student opportunities, or ongoing projects.

        Email: your.email@unitn.it
      button:
        text: Email Us
        url: "mailto:your.email@unitn.it"
    design:
      card:
        css_class: "bg-primary-300"
        css_style: ""
---
