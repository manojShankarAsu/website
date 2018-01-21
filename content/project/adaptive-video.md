+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Adaptive Video Streaming over HTTP"

# Project summary to display on homepage.
summary = "Developed a Adaptive video streaming system over HTTP employing dynamic on the fly bitrate analysis"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Java","video_processing"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

* Implemented an adaptive client-server video streaming system in which the client analyses the bit rates on the fly and sends a feedback to the server which in turn changes the frame rate and quality of the video to maintain smooth video playback.
* Developed a mathematical model to judge the bandwidth conditions from the incoming bit-rates and incorporated it in an intelligent algorithm at the client to analyse the incoming video stream.
* Implemented the algorithm in Java employing multi-threading concepts achieving avg PSNR of 36.267 and SSIM of 0.9683.