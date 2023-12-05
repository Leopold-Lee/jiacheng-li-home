---
title: 'Towards a Better Understanding of the Official Android API Lists'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Sinan Wang
- Qi Zhang
- admin
- Yida Tao
- Yepang Liu

date: '2023-09-21T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 23rd IEEE International Conference on Software Quality, Reliability, and Security*
publication_short: In *QRS 2023*

abstract: AndroidX is an official Android library that enables backward compatibility for Android APIs used by various apps. It is the successor of the Android Support library since Android 9.0. Since then, many apps that originally relied on Android Support needed to be adapted to use AndroidX. However, for app developers, such a migration task can be challenging and error-prone. Yet, there is no systematic study on the migration status of real-world Android apps or the issues that may arise during the migration to AndroidX. To fill this knowledge gap, we conducted the first comprehensive study concerning the adoption and adaptation of the AndroidX library. In this study, we inspected 171 Stack Overflow posts about AndroidX and identified common categories of issues that can occur when adapting apps to use AndroidX, as well as the causes. We also examined the trend of these issues in recent five years to assess their impact over time. Then, we investigated the utilization status of both Android Support and AndroidX libraries in 15,334 top commercial apps and 2,470 open-source apps. Finally, we developed an algorithm that utilizes cosine similarity to identify Java class mappings between Android Support and AndroidX. The algorithm allows us to recover an additional mapping of 579 Java class pairs, which can supplement the official class mapping.

# Summary. An optional shortened abstract.
summary: ''

tags: 
  - Android
  - AndroidX
  - Support Library
  - Class Migration

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/huangkr03/AndroidX-Empirical-Research'
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---
