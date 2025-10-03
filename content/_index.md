---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
       # Tward Research Group
       ### Precision radiation oncology for prostate and genitourinary cancers
      image:
        filename: welcome.jpg
      text: |
        
We are a clinician–scientist team advancing how prostate and genitourinary (GU) cancers are detected, risk-stratified, and treated. Led by **Jonathan D. Tward, MD, PhD, FASTRO**—Professor of Radiation Oncology at the University of Utah and Huntsman Cancer Institute—our lab bridges AI, image-guided radiotherapy, and prospective clinical trials to deliver care that is both **more effective and less toxic**.

## What we work on
- **AI-enhanced risk stratification.** We helped pioneer **multimodal deep-learning models** that integrate digital pathology with clinical features to outperform conventional systems and define actionable thresholds within phase III NRG Oncology trials.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
