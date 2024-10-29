---
title: "Bioinspired Lightweight Open-Loop Climbing Robot"
authors:
- admin
date: "2020-12-02T00:00:00Z"
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

tags:
- Nonsmooth Robotics Lab

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url2: preprint.pdf
# url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: '#'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: 'Smart'
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

{{< youtube o-Uxel5dEWk>}}

## Summary

The goal of this project was to build a bioinspired robot capable of climbing a 10-ft. wooden pegboard in my Design for Innovation course. The robot was made primarily using 3D printed parts, 1/8" MDF board, and various fasteners. An Arduino Uno was used to apply open-loop control to two continuous servos which drove a rack-and-pinion mechanism. Design constraints included low servo stall torque and clear bioinspiration.

## Bioinspiration

{{< youtube U1UxnXnpDME>}}

The tree pangolin's tree climbing gait cycle informed many of the design decisions on my robot. As seen in the video above, the pangolin contracts and extends its abdomen to alternate between gripping the tree with clawed forelimbs and hindlimbs. Similarly, my robot uses a rack and pinion mechanism to extend its upper half to grab the next peg with two spring-loaded hooks or "claws". The pangolin uses its tail to maintain stability between grips. Similarly, my robot uses its lower rigid body to maintain contact with two pegs at once, effectively maintaining stability while reaching for the next peg. Once the next peg has been hooked, the robot pulls the lower rigid body and hooks up to the next peg.

## Design Evolution

After being compared with numerous other concepts, this design was selected due to its lightweight nature and strong correlation with an existing animal's gait. As seen in the images below, the robot was sketched by hand, drawn and animated in Autodesk Inventor, and fabricated using primarily 3D printed PLA and laser cut 1/8" MDF board.

![targets](]

<div style="text-align: center;">
    <img src="content/project/red_foo/RedFoo Drawing Bioinspired Robot Tree Pangolin.jpg">
</div>

## Results

The robot successfully scaled roughly half of the pegboard on its best climb. Unfortunately, there was at least one slightly loose peg in every column of the pegboard. My design did not account for that possibility, so the hooks did not always engage completely when attempting to mount a loose peg. The video at the top of this page shows an instance of this at the 0.19 sec mark. If I were to have had the chance to iterate on this design, I would have enlarged the mouth of the upper hooks to ensure that they engage with every peg they come into contact with.
