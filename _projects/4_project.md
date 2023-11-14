---
layout: page
title: Gaze Gesture Recognition
description: leveraging gesture recognition to classify gaze scan paths
img: assets/img/hcira.png
importance: 1
category: UF
related_publications:
---

This work is the finals project from a special topics course I took at the University of Florida called Human-Centered Input Recognition Algorithms. The course provided an overview of the <a href="https://depts.washington.edu/acelab/proj/dollar/impact.html">$-family recognizers</a> and broadly prompted us to extend some facet of the $1 recognizer for the final project. This recognizer is an instance-based nearest-neighbor classifier used to distinguish between user inputs. I am expanding this project as my senior capstone at UF to attempt to classify natural user gaze gestures on the basis of scan path shape.

<a href="/assets/pdf/hcira.pdf">Final Presentation Link</a>

<a href="https://github.com/klarubbio/EyeTrack_HCIRA">GitHub Repository</a>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/hcira.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   These are the gaze paths recorded for the 16 unistroke gestures that are tested with normal evaluations of the $1 recognizer that use pen or touch-based inputs. They are undoubtedly less distinct than touch-based input paths, yet still exhibit recognizable shapes. 
</div>

Rather than extending the recognizer's capabilities itself, this project evaluates its capacity to understand user gestures through a new modality: eye gaze. Gaze is ideal for unistroke gestures, as it is a continuous stream of data (excluding blinks or other moments when the eyes are not visible). This falls within the category of collecting a new dataset. The same sixteen unistroke gestures were performed for each participants, though it is expected that the data collection medium will render significant differences from the original experiment with mouse input. 





