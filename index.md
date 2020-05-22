---
layout: default
title: Home
nav_order: 1
description: "Repos"
---


# Imported
- [ ] Github repos
    - [ ] Segmentation [https://github.com/RU-RobotInteractionLab/segmentation](https://github.com/RU-RobotInteractionLab/segmentation)
    - [ ] perception, panda configs and new config for vacuum cup
        - [ ] [https://github.com/RU-RobotInteractionLab/perception](https://github.com/RU-RobotInteractionLab/perception)
    - [ ] robotic stuff [https://github.com/RU-RobotInteractionLab/robot-lab](https://github.com/RU-RobotInteractionLab/robot-lab)
    - [ ] dataset utilities [https://github.com/RU-RobotInteractionLab/dataset\_tools](https://github.com/RU-RobotInteractionLab/dataset_tools)
        - [ ] Parser for LAbelbox
        - [ ] Parser for COCO annotator(óklarað)
        - [ ] Parser for NDDS to port directly to SD maskrcnn with depth images
            - [ ] Flokkar instances og setur í mask, sem inniheldur hvert instance með value 1-255, 0 er background
    - [ ] NDDS [https://github.com/RU-RobotInteractionLab/Dataset-synthesizer](https://github.com/RU-RobotInteractionLab/Dataset-synthesizer)
        - [ ] Sett upp á /mnt/bigdata/ndds1_12....
        - [ ] Setja upp bash alias fyrir UE4
    - [ ] coco annotator /mnt/bigdata/coco-annotator
        - [ ] [https://github.com/RU-RobotInteractionLab/LabelingTool](https://github.com/RU-RobotInteractionLab/LabelingTool)
    - [ ] maskrcnn [https://github.com/RU-RobotInteractionLab/maskrcnn](https://github.com/RU-RobotInteractionLab/maskrcnn)
        - [ ] er á eymar13 i maskrcnn\_conda foldernum
    - [ ] detectron
    - [ ] yolov3 [https://github.com/RU-RobotInteractionLab/yolov3-tf2](https://github.com/RU-RobotInteractionLab/yolov3-tf2)
    - [ ] sd maskrcnn
        - [ ] [https://github.com/RU-RobotInteractionLab/sdmaskrcnn](https://github.com/RU-RobotInteractionLab/sdmaskrcnn)
        - [ ] Virkar med NDDS og dataset\_tools scripts.


<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

