# Object-Detection-System-with-yolov7
This repository contains code and models for an object detection system designed to identify and classify insect pests in images of rice plants. The system is built using the YOLOv7 (You Only Look Once version 7) model, which is one of the latest and most advanced object detection algorithms.


# step by step to run this deploying

# go to conda prompt and your environment
1. ---conda prompt > 
1.python export.py --weights best.pt --grid --end2end --simplify --topk-all 100 --iou-thres 0.50 --conf-thres 0.25 --img-size 640 640 --max-wh 640


# go to command prompt and your environment
command prompt
1. install node.js
2. install yarn
--onnx : salah satu eksisten yolo untuk melakukan deploy di web
-- cd deploy
3. > git clone github https://github.com/Hyuto/yolov7-onnxruntime-web.git
4. > cd yolov7-onnxruntime-web
5. >yarn install
6. >yarn start
