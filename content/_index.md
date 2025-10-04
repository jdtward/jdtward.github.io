---
# Leave the homepage title empty to use the site title
title: Tward Research Group
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
    


sections:
  - block: markdown
    content:
      title: "About This Section"
      subtitle: "More details below"
      text: |
        ## Welcome
        
        This is **markdown content** that you can edit.
        ## What we work on
        - **AI-enhanced risk stratification.** We helped pioneer **multimodal deep-learning models** that integrate digital pathology with clinical features to outperform conventional systems and define actionable thresholds within phase III NRG Oncology trials.
        - **Metastasis-directed therapies & radiopharmaceuticals.** We design and lead trials combining **SABR** with agents like **radium-223** to control oligometastatic disease while preserving quality of life and delaying systemic therapy.
        - **Brachytherapy & treatment quality.** From perirectal spacers and customized bolus to HDR/LDR technique optimization, we focus on interventions that **maximize tumor control and minimize side effects.**
        - **Guideline leadership & implementation.** Dr. Tward serves on **NCCN guideline panels** (prostate, bladder, penile) and resource-stratification efforts that shape standards of care globally.

        
        - Create lists
        - Add links
        - Format text
        
        [Learn more](https://example.com)
    design:
      columns: "1"
      background:
        color: "white"


         
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
