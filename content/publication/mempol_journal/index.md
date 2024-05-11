---
title: "MemPol: Polling-Based Microsecond-Scale Per-Core Memory Bandwidth Regulation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Alexander Zuepke
- Andrea Bastoni
- admin
- Marco Caccamo
- Renato Mancuso
  
# Author notes (optional)
#author_notes:
#- "Equal contribution"

date: "2024-05-09T00:00:00Z"
#doi: "https://doi.org/10.1212/WNL.0000000000200120"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Real-Time Systems
#publication_short: In RTAS(2023)

abstract: In today's multiprocessor systems-on-a-chip (MPSoC),the shared memory subsystemis a known source of temporal interference.The problem causes logically independent coresto affect each other's performance,leading to pessimistic worst-case execution time (WCET) analysis. Memory regulation via throttling is one of the most practical techniques to mitigate interference.Traditional regulation schemes rely on a combinationof timer and performance counter interrupts to be delivered andprocessed on the same cores running real-time workload.Unfortunately, to prevent excessive overhead, regulationcan only be enforced at a millisecond-scale granularity. In this work, we presenta novel regulation mechanism from outside the cores that monitors performance countersfor the application core's activity in main memoryat a microsecond scale. The approach is fully transparentto the applications on the cores,and can be implemented using widely available on-chipdebug facilities. The presented mechanism also allows more complex compositionof metrics to enact load-aware regulation. For instance, it allowsredistributing unused bandwidth between coreswhile keeping the overall memory bandwidthof all cores below a given threshold. We implement our approach on a host of embedded platforms andconduct an in-depth evaluationon the Xilinx Zynq UltraScale+ ZCU102, NXP i.MX8M and NXP S32G2 platformsusing the San Diego Vision Benchmark Suite.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: 'https://n.neurology.org/content/98/15/e1534'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" 
---
