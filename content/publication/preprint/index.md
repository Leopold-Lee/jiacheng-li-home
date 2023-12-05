---
title: "Towards a Better Understanding of the Official Android API Lists"
authors:
- Sinan Wang
- Qi Zhang
- admin
- Yida Tao
- Yepang Liu
date: "2023-12-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Preparing submitting to *IEEE Transactions on Software Engineering"
publication_short: "to be subbmitted"

abstract: Android apps are built upon the Android APIs that abstract the system’s functionalities. These APIs are officially documented in several text files, which we call Android API Lists (AALs) in our study. Previous research on Android APIs has been dependent on specific, yet varied, AALs. As pointed out by a recent study, using different AALs can produce significantly varying research outcomes. It highlights the need for a comprehensive investigation of the AALs. To this end, we conducted the first systematic study about four official AALs. We first analyzed their characteristics and evolution. Then, we compared their documented APIs to reveal their differences. To understand the impact of such differences, we further studied the API existence on nine real devices, including stock Android and vendor-customized Android devices. Finally, we analyzed API usage in 17,759 real-world Android apps, including open-source apps, commercial apps, and malware, to measure the threat of utilizing different AALs for Android research. Our study uncovered the instability of official AALs and the inconsistency between them. We also observed usages of vendor-customized APIs from normal apps, which currently gain little attention from the research community. Based on our findings, we draw several implications for future work. We believe our study can serve as a valuable resource for practitioners and researchers, offering them a deeper understanding of Android APIs and API lists.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Android
  - API Compatibility
  - Android API List 
  
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
