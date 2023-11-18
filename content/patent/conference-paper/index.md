---
title: 'Face-changing malicious Android app Detection'
title: Face-changing malicious Android app Detection

authors:
  - admin
  - Kerui Huang
  - Sinan Wang
  - Yepang Liu

summary: An example of using the in-built project page.
tags:
  - Deep Learning
  
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
---

abstract: AndroidX is an official Android library that enables backward compatibility for Android APIs used by various apps. It is the successor of the Android Support library since Android 9.0. Since then, many apps that originally relied on Android Support needed to be adapted to use AndroidX. However, for app developers, such a migration task can be challenging and error-prone. Yet, there is no systematic study on the migration status of real-world Android apps or the issues that may arise during the migration to AndroidX. To fill this knowledge gap, we conducted the first comprehensive study concerning the adoption and adaptation of the AndroidX library. In this study, we inspected 171 Stack Overflow posts about AndroidX and identified common categories of issues that can occur when adapting apps to use AndroidX, as well as the causes. We also examined the trend of these issues in recent five years to assess their impact over time. Then, we investigated the utilization status of both Android Support and AndroidX libraries in 15,334 top commercial apps and 2,470 open-source apps. Finally, we developed an algorithm that utilizes cosine similarity to identify Java class mappings between Android Support and AndroidX. The algorithm allows us to recover an additional mapping of 579 Java class pairs, which can supplement the official class mapping.