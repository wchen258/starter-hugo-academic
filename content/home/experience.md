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
        Modern multi-core computing platforms consist of various powerful units for better performance. However, it is well-known in the community that the commplicated interaction among those components influences the execution time of applications in a unpredicted manner. The unpredictability could be disastrous for many safety-crtical systems, such as missiles, airbags, robotic arms, etc. Our vision is to develop an operating systems that are self-aware of the unpredictability and able to correct itself in a timely manner.  
        * Heterogeneous Platform Development: Our of all the hardwares such as CPU, GPU, RAM, Wifi modules, etc, Field-programmable gate array (FPGA) is a special one. To make an analogy, FPGA is Lego to hardware, in a sense that, FPGA can be programmed to achieve any hardware logic, making them powerful in prototyping new design. Our lab use platforms from AMD Xilinx, who produces FPGA that tightly coupled to other computing hardwares to unleash more potential on what could be done.
        * Deploying
        
  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
