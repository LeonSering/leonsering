---
title: Axonium
summary: Automatically measuring the length of axons, the nerve fiber connections between neurons in a biological brain.

tags:
  - Minor
date: '2017-07-01T00:00:00Z'
# Optional external URL for project (replaces project detail page).
# external_link: ''

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/LeonSering/axonium
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''
---
Axonium is a tool for automatically measuring the length of [axons](https://en.wikipedia.org/wiki/Axon),
the nerve fiber connections between neurons in a biological brain.

During her studies in the neurology, my girlfriend had to measure the length of a lot of axons.
They used ImageScope to load the TIFF-image and then measure the length (in pixel) by a simple ruler
tool and then enter the value into Excel.

As it was necessary to measures thousands of axons, and each measurement took quite long and was error prune,
I decided to write a small tool, to make this automatically.

<center>{{< figure src="axonium.png" caption="Automatically measure the length of axons with a single mouse click." numbered="true">}}</center>


The basic idea is the following:

1. First isolate the axons by making it monochrome, i.e., each pixel is either false (black background) or true
(colored foreground = axons) based on an adjustable threshold.

2. Then skeletonize the axons with the [medial axis transformation](https://scikit-image.org/docs/stable/api/skimage.morphology.html#skimage.morphology.medial_axis).
Basically, the axon (connected components in the monochrome image) are shrunk to have a width of one pixel.

3. Finally, the longest path within the skeleton is determined by a [breadth-first search (BFS)](https://en.wikipedia.org/wiki/Breadth-first_search).


Since axon images can get wild, I added a couple of tools (a pen to connect interrupted axons and an eraser to
separate two intersecting axons) and the functionality to still measure by hand.

Finally, the length is easily stored and can be exported to an Excel file.
