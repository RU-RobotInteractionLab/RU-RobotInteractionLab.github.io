---
layout: default
title: Home
nav_order: 1
description: "Repos"
---


# Github repos
*   LCCP and supervoxel [Segmentation](https://github.com/RU-RobotInteractionLab/segmentation)
*   Perception, panda configs and new config for vacuum cup
    *   [Perception](https://github.com/RU-RobotInteractionLab/perception)
*   Lab and panda [robot-lab](https://github.com/RU-RobotInteractionLab/robot-lab)
*   Dataset parsers and extraction [dataset tools](https://github.com/RU-RobotInteractionLab/dataset_tools)
    *   Parser for LAbelbox
    *   Parser for COCO annotator(óklarað)
    *   Parser for NDDS to port directly to SD maskrcnn with depth images
    *   Flokkar instances og setur í mask, sem inniheldur hvert instance með value 1-255, 0 er background
*   NDDS [Dataset-synthesizer](https://github.com/RU-RobotInteractionLab/Dataset-synthesizer)
    *   Sett upp á /mnt/bigdata/ndds\_122....
    *   Setja upp bash alias fyrir UE4
*   Labeling tool a /mnt/bigdata/coco-annotator
    *   [LabelingTool](https://github.com/RU-RobotInteractionLab/LabelingTool)
*   maskrcnn [maskrcnn](https://github.com/RU-RobotInteractionLab/maskrcnn)
    *   er á eymar13 i maskrcnn\_conda foldernum
*   YOLOV3 [yolov3-tf2](https://github.com/RU-RobotInteractionLab/yolov3-tf2)
*   SD-Mask-RCNN
    *   [sdmaskrcnn](https://github.com/RU-RobotInteractionLab/sdmaskrcnn)
    *   Virkar med NDDS og dataset\_tools scripts.

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

