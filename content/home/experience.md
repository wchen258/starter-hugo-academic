---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Fellow
    company: Boston University Cyber Physical Lab
    company_url: 'http://cpslab.bu.edu'
    company_logo: org-gc
    location: Massachusetts
    date_start: '2020-09-02'
    date_end: ''
    description: |2-
        Multiple Processor System-on-Chip (MPSoC) has become ubiquitous. Albeit powerful, the complex interaction between various components pose a threat to tasks that require strict timeliness behaviors (a.k.a hard real-time tasks). The timeliness has to be met to prevent distrastrous consequences. For example, the deployment of the safety air bag on cars has to be just in time. Too late or too early would invalid such systems. In fact, hard real-time tasks exist for many industries, automotive, avionic, home appliances, medical, telecommunication, aerospace and military applications. Our vision is to develop a system capable of being self-aware of the time progress of running applications, so that regulation strategies can be effective applied dynamically, to truly unleash the power of modern computing platforms. 
    Keywords: Real-Time Operating System (RTOS); MPSoC; Internet of Things (IoT)
        
  - title: Research Assistant & Peer Mentor
    company: Boston University Bio-Imaging & Information Lab
    company_url: 'https://sites.bu.edu/bil/'
    company_logo: org-x
    location: Massachusetts
    date_start: '2020-01-010'
    date_end: '2022-09-01'
    description: Magnetic Resonance Imaging (MRI) generates a huge volume of data reflecting brain structure. I worked closely with the research group, and developed various machine learning frameworks to analyze the data. I also mentored other undergraduates who take an interest in both machine learning and brain imaging. 
    keywords: Machine Learning; Deep Learning; Computer Vision; Data Science; Optimization; MRI; Brain Imaging

design:
  columns: '2'
---
