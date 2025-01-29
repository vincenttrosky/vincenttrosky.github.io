---
title: "Design and Control of a Mini Bipedal Robot"
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

summary: This project aims to propose a framework for computing a library of stable gaits for general biped robots.

tags:
- Nonsmooth Robotics Lab
- Mechanical Design
- CAD
- Manufacturing
- Control Systems

featured: true

links:
# - name: Custom Link
#   url: 'http://example.org'
# url2: 'preprint.pdf'
url_pdf: 'project/paul/design_review.pdf'
url_code: ''
url_dataset: ''
url_poster: 'IROS2023_Poster_Template.pdf'
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
    <img src="featured.jpg" style="width: 100%; display: block;">
    <figcaption style="text-align: center;"></figcaption>
</figure>



## Summary

See the <a href="design_review.pdf">PDF</a> and <a href="IROS2023_Poster_Template.pdf">Poster</a> links at the top of the page for more info! 

Testing
control algorithms for bipedal robots on physical hardware can
become a time-consuming and expensive process. The robot
presented in this project offers a modular, open-source platform
for bipedal control algorithm testing for roughly $200. The
manufacturing process requires simple 3D-printing, turning,
and drilling operations. The final prototype can stand passively
and will soon be tested using a planar support mechanism on
a treadmill to constrain the robot to the saggital plane and
identify compatible control approaches.


## Status (In Progress...)

Currently, the robot is being fitted with current sensors to enable elementary feedback control. PID controllers will be the first controllers applied to achieve limit-cycle walking. 
