---
layout: page
title: "though it may feel real this is all just a memory"
description: programmatic art with musical data input
img: assets/img/memory.png
importance: 1
category: fun
---

*In collaboration with Molly Trueman and Alexander Moravscik*

Have you ever listened to a live music performance and relived it in your dreams? Over and over, until sounds blend together, until all that you’re left with is a faint memory?

Welcome to that memory.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/memory-performance.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    A live demonstration of how this artwork changes through both live music performance and the produced "memory" version. Live vocals and original song by Molly Trueman and production by Alexander Moravscik.
</div>

The intent of this project is to transform sound into visuals and atmosphere, using music production techniques and creative coding. Our aim is to combine poetry, acoustic guitar performance, digital synthesis, and coding in a way that transforms live music into a complete audiovisual experience.

Live music is processed using Ableton Live, and data is retrieved from the sound using Max MSP. Another connected MIDI device can be directly manipulated to further process the sound and visuals. Data from Max MSP and the connected device is sent to a p5.js sketch that transforms these numbers into visuals. The p5.js sketch, which acts as the visual aspect of this experience, is separated into five different mini sketches which the user can switch between using the arrow keys.

From the sound, we extract five kinds of data:
 1. Estimated fundamental pitch
 2. Peak amplitude
 3. Chromatic note
 4. Deviation in sense
 5. Onsent detection

Each of these data sources are used in differing ways throughout the five mini-sketches, such as colors, size of shapes, and speed of moving objects.

We also adjust the visuals in a corresponding manner to four parameters, knobs on the connected MIDI device:
 1. Auto-pan (speed & amount)
 2. Soft bit reduction & and high-pass filter 
 3. Reverb decay time (inverted)
 4. Resonator (tonic pitch, +7, +12)

These processes also adjust visuals like speed, color, size, and opacity of objects.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/memory-tech-demo.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    The technical demo of how different musical fluctuations can affect the animation via sliders.
</div>