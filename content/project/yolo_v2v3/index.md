---
title: "Improving YOLO V2"
authors:
- admin
date: "2024-09-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["article"]

# # Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

# abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

summary: This project was an attempt improve the YOLO V2 baseline model.

tags:
- Graduate Projects
- Computer Vision

featured: true

links:
# - name: Custom Link
#   url: http://example.org
# url2: preprint.pdf
url_pdf: 'project/yolo_v2v3/Final Project_ Improving YOLOv2.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  placement: 2
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: 'Center'
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

<figure style="width: 100%; margin: 0;">
    <img src="featured.png" style="width: 100%; display: block;">
    <figcaption style="text-align: center;"></figcaption>
</figure>

## Summary

See the <a href="Final Project_ Improving YOLOv2.pdf">PDF above</a> for the full report!

“You Only Look Once version 2” (YOLOv2) is an object detection algorithm capable of
completing real-time object detection tasks. Developed by Joseph Redmon and Ali Farhadi, YOLOv2 is a deep learning-based algorithm that approaches object
detection as a single regression problem. After dividing an input image into a grid, the algorithm
uses anchor bounding boxes around objects and produces class probabilities for each grid cell.
The algorithm then uses this data and performs feature extraction based on prior training over a
set of image classes using a deep convolutional neural network (CNN).

In this project, I attempted to modify the the Darknet-19 backbone used by YOLOv2. All Max Pooling layers in the backbone were replaced by convolutional layers in an attempt to increase the amount of relevant information being transmitted between layer input and output. My attempt did not outperform the baseline model at the 50 epoch checkpoint, as the mean average precision (mAP) decreased from 70% to 28% and the frames per second (FPS) rate decreased from 71.88 to 62.63. Eventually, I would like to go back and attempt to replace the Darknet-19 backbone with a residual backbone like ResNet or modify the loss function to improve performance.

