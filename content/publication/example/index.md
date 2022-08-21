---
abstract: |
  With emerging vision-based autonomous driving
  (AD) systems, it becomes increasingly important to have datasets
  to evaluate their correct operation and identify potential security
  flaws. However, when collecting a large amount of data, either
  human experts manually label potentially hundreds of thousands
  of image frames or systems use machine learning algorithms to
  label the data, with the hope that the accuracy is good enough
  for the application. This can become especially problematic when
  tracking the context information, such as the location and velocity
  of surrounding objects, useful to evaluate the correctness and
  improve stability and robustness of the AD systems.

  In this paper, we introduce DRIVETRUTH, a data collection
  framework built on CARLA, an open-source simulator for AD
  research, which constructs datasets with automatically generated
  accurate object labels, bounding boxes of objects and their
  contextual information through accessing simulation state and
  using semantic LiDAR raycasts. By leveraging the actual state of
  the simulation and the agents within it, we guarantee complete
  accuracy in all labels and gathered contextual information.
  Further, the use of the simulator provides easily collecting data
  in diverse environmental conditions and agent behaviors, with
  lighting, weather, and traffic behavior being configurable within
  the simulation. Through this effort, we provide users a means to
  extracting actionable simulated data from CARLA to test and
  explore attacks and defenses for AD systems.a
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
  - Yanmao Man
  - Z. Berkay Celik
  - Ming Li
  - "& Ryan Gerdes"
author_notes: []
publication: International Workshop on Automotive and Autonomous Vehicle
  Security, collocated with NDSS
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *AutoSec*
url_source: ""
url_video: ""
title: "DriveTruth: Automated Autonomous Driving Dataset Generation for Security
  Applications"
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2022-08-21T21:44:23.997Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
