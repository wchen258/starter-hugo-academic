---
title: "Shared Resource Contention in Low-end MCUs: A Reality Check and the Quest for Timeliness"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Oliveira
- admin
- Sandro Pinto
- Renato Mancuso
  
# Author notes (optional)
#author_notes:
#- "Equal contribution"

date: "2024-05-09T00:00:00Z"
#doi: "https://doi.org/10.1145/3576914.3587513"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

#Publication name and optional abbreviated publication name.
publication: In Proceedings of the 36th Euromicro Conference on Real-Time Systems (ECRTS) July 2024, Lille, France
#publication_short: In RAGE2023

abstract: Microcontrollers (MCUs) are steadily embracing multi-core technology to meet growing performance demands. This trend marks a shift from their traditionally simple, deterministic designs to more complex and inherently less predictable architectures. While shared resource contention is well-studied in mid to high-end embedded systems, the emergence of multi-core architectures in MCUs introduces unique challenges and characteristics that existing research has not fully explored. In this paper, we conduct an in-depth investigation of both mainstream and next-generation MCU-based platforms, aiming to identify the sources of contention on systems typically lacking these problems. We empirically demonstrate substantial contention effects across different MCU architectures (i.e., from single- to multi-core configurations), highlighting significant application slowdowns. Notably, we observe that slowdowns can reach several orders of magnitude, with the most extreme cases showing up to a 3800x (times, not percent) increase in execution time. To address these issues, we propose and evaluate uTPArtc, a novel mechanism designed for Timely Progress Assessment (TPA) and TPA-based runtime control specifically tailored to MCUs. uTPArtc is an MCU-specialized TPA-based mechanism that leverages hardware facilities widely available in commercial off-the-shelf MCUs (i.e., hardware breakpoints and cycle counters) to successfully monitor applications' progress, detect, and mitigate timing violations. Our results demonstrate that uTPArtc effectively manages performance degradation due to interference, requiring only minimal modifications to the build pipeline and no changes 

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://n.neurology.org/content/98/15/e1534'
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
