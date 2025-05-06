# Detectron

This Project implements a road-sign detection using Detectron2, a powerful object detection library. This model is baed on a Faster R-CNN with Resnet-50-FPN as backbone,
trained on a custom Dataset of COCO format. The formal goal is to accuratelt detect road signs in images, with optimization to reduce duplicate detections using Non-Max Suppression

Number of Classes :- 4 (Crosswalk,Speed-Limit,STOP,Traffic-light)

NMS Value = 0.1
