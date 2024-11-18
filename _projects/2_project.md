---
layout: page
title: Gaze-Based Authentication
description: evaluating gaze-based authentication techniques for nuclear operator training in virtual reality
img: assets/img/publication_preview/gazebased.png
importance: 1
category: UF
related_publications: 9757593
---


Behavior-based authentication methods are actively being developed for XR. In particular, gaze-based methods promise continuous au-thentication of remote users. However, gaze behavior depends on the task being performed. Identification rate is typically highest when comparing data from the same task. In this study, we compared authentication performance using VR gaze data during random dot viewing, 360-degree image viewing, and a nuclear training simulation. We found that within-task authentication performed best for image viewing (72%). The implication for practitioners is to integrate image viewing into a VR workflow to collect gaze data that is viable for authentication.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/publication_preview/gazebased.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/5Q-Yhv7c0dw" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

I got started on this project in my first year at UF as a part of my <a href="https://cur.aa.ufl.edu/about-ursp/">University Research Scholars Program</a> Course-based Undergraduate Research experience. We learned about development in Unity for VR and brainstormed on how a VR-based training scenario might be implemented. I continued my involvement through an NSF Research Experience for Undergraduates (REU) the following Summer.

My specific role in this project was to work with our collaborators from nuclear engineering at UF to implement a VR-based nuclear training simulation. I also implemented random dot viewing and image viewing activities, which tracked users' eye movements throughout to complete our experimental design. I adapted a radial basis function network classifier to take in gaze data from these various tasks and attempt to authenticate users. I went on to lead the production of a short paper and poster for publication at IEEE VR 2022. 

For more information about this project, please see our <a href="https://www.youtube.com/watch?v=5Q-Yhv7c0dw">teaser video</a>, poster, <a href="https://github.com/klarubbio/fall21_headset_demo">GitHub repository</a>, and <a href="https://ieeexplore.ieee.org/document/9757593">IEEE page</a>.





<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/ieee_gaze_poster.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

K. LaRubbio, J. Wright, B. David-John, A. Enqvist and E. Jain, "Who do you look like? - Gaze-based authentication for workers in VR," 2022 IEEE Conference on Virtual Reality and 3D User Interfaces Abstracts and Workshops (VRW), Christchurch, New Zealand, 2022, pp. 744-745, doi: 10.1109/VRW55335.2022.00223.


