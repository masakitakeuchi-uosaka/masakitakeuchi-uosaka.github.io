---
layout: page
title: Projection Mapping under Environmental Lighting
description: IEEE TVCG 2024, IEEE VR 2024
img: assets/img/teaser_2024TVCG_room_only.png
importance: 1
category: work
related_publications: false
---

Projection mapping (PM) is a technique that enhances the appearance of real-world surfaces using projected images, enabling multiple people to view augmentations simultaneously, thereby facilitating communication and collaboration. However, PM typically requires a dark environment to achieve high-quality projections, limiting its practicality. In this paper, we overcome this limitation by replacing conventional room lighting with heterogeneous projectors. These projectors replicate environmental lighting by selectively illuminating the scene, excluding the projection target. Our contributions include a distributed projector optimization framework designed to effectively replicate environmental lighting and the incorporation of a large-aperture projector, in addition to standard projectors, to reduce high-luminance emitted rays and hard shadows-undesirable factors for collaborative tasks in PM. We conducted a series of quantitative and qualitative experiments, including user studies, to validate our approach. Our findings demonstrate t hat our projector-based lighting system significantly enhancesthe contrast and realism of PM results even under e nvironmental lighting compared to typical lights. Furthermore, our method facilitates a substantial shift in the perceived color mode from the undesirable aperture-color mode, where observers perceive the projected object as self-luminous, to the surface-color mode in PM.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/teaser_2024TVCG.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The proposed projection mapping system mitigates the reduction in contrast under environmental lighting. The left image provides an overall view of the texture projection in a well-lit room using the proposed technique. The crack pattern texture is projected onto the white statue located at the center of the desk. The images on the right show enlarged views of the statue without (left) and with (right) the texture projection. These images were captured in three different lighting conditions: a dark room, where projection mapping is typically conducted; under typical room lighting with LED lights; and under the proposed environmental lighting using projectors. The results demonstrate that our technique reproduces typical room lighting using multiple projectors and enhances the contrast of the projected result on the target surface.
</div>
