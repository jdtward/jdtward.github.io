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
        <br>
        
        We are a clinician–scientist led team advancing how prostate and genitourinary (GU) cancers are detected, risk-stratified, and treated. Led by **Jonathan D. Tward, MD, PhD, FASTRO**—Professor of Radiation Oncology at the University of Utah and Huntsman Cancer Institute—our lab bridges AI, image-guided radiotherapy, and prospective clinical trials to deliver care that is both **more effective and less toxic**.
## What we work on
- **AI-enhanced risk stratification.** We helped pioneer **multimodal deep-learning models** that integrate digital pathology with clinical features to outperform conventional systems and define actionable thresholds within phase III NRG Oncology trials.
- **Metastasis-directed therapies & radiopharmaceuticals.** We design and lead trials combining **SABR** with agents like **radium-223** to control oligometastatic disease while preserving quality of life and delaying systemic therapy.
- **Brachytherapy & treatment quality.** From perirectal spacers and customized bolus to HDR/LDR technique optimization, we focus on interventions that **maximize tumor control and minimize side effects.**
- **Guideline leadership & implementation.** Dr. Tward serves on **NCCN guideline panels** (prostate, bladder, penile) and resource-stratification efforts that shape standards of care globally.

## Why it matters
Prostate cancer is heterogeneous; two patients with the same stage can face very different trajectories. Our research delivers:
- **Sharper prognostication** using AI on routine histology to better match intensity of care to individual risk.
- **Therapies that preserve quality of life,** such as SABR plus alpha-emitting radiopharmaceuticals that aim to control bone-only oligometastatic disease while postponing long-term androgen deprivation.
- **Practical pathways** that align cutting-edge evidence with day-to-day clinical decisions through NCCN leadership.

## Selected highlights
- **Multimodal AI risk groups** validated across five NRG phase III trials; published in *JCO Precision Oncology* (2024).
- **RadSABR & RAVENS studies:** evaluating **radium-223 + SABR** versus SABR alone in oligometastatic prostate cancer; results and trial details reported in 2025 across peer-reviewed and conference outlets.
- **Endowed leadership & GU center:** Dr. Tward is a tenured professor and leads GU cancer initiatives at HCI, reflecting sustained impact in research, clinical innovation, and mentorship.

## Our approach
1. **Ask better questions.** Use population data, prospective trials, and digital pathology to identify who benefits from which therapy.
2. **Engineer better care.** Translate insights into improved radiation planning, brachytherapy techniques, and workflow standards.
3. **Share and scale.** Drive consensus through guideline work and open collaboration with urology, medical oncology, pathology, imaging, and data science.

## For patients
We partner with Huntsman Cancer Institute to offer consultations, clinical trials, and second opinions for prostate and GU cancers—prioritizing outcomes **and** life quality.

**Interested in participating in a study?** Ask about active trials evaluating SABR, radiopharmaceuticals, and biomarker-guided therapy selection (e.g., RAVENS: NCT04037358).

## For collaborators
We welcome collaborations in:
- **AI/ML & digital pathology**
- **Radiopharmaceuticals and SABR**
- **Brachytherapy devices and QA**
- **Outcomes, PROs, & health services research**

**Contact:** University of Utah / Huntsman Cancer Institute — Tward Research Group.

  
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
