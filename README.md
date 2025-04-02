# TensorFlow Lite Object Detection Android - YOLOv11

The repository is in conjunction with the YOLO-Detection repository. The TF Lite file sits within the assets of this app. When the application is running, scroll on the menu to select the correct model. I have broken them down into chunks, clumps of several hundred classes, which is the only way YOLO will detect. Too many classes cause a data insufficiency problem. As it stands currently, I cannot get multiple .tf lite models working through an overlap method in the Android application. Below is an example of the YOLO model solution which sits within this model as a TF Lite file, only a single model.

![val_batch0_labels](https://github.com/user-attachments/assets/b0cd27e6-b08c-46fa-884b-1eb9949c0c90)

### Overview

This application was adapted using code from:
- [TensorFlow Lite Object Detection Android Demo](https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/android), and
- [Ultralytics Flutter demo app](https://github.com/ultralytics/yolo-flutter-app)

### Licences
Original TensorFlow Lite Object Detection Android Demo has [Apache License 2.0](LICENSE-Apache2.0.txt), while Ultralytics has [GNU GENERAL PUBLIC LICENSE](LICENSE).
So in case of using this code you must complain both licences.



### Application

This is a camera app that continuously detects the objects (bounding boxes and
classes) in the frames seen by your device's back camera, with the option to use
a quantized
[MobileNet SSD](https://tfhub.dev/tensorflow/lite-model/ssd_mobilenet_v1/1/metadata/2),
[EfficientDet Lite 0](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite0/detection/metadata/1),
[EfficientDet Lite1](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite1/detection/metadata/1),
[EfficientDet Lite2](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite2/detection/metadata/1),
and [Ultralytics Yolo](https://docs.ultralytics.com/tasks/detect/#models)
model trained on the [COCO dataset](http://cocodataset.org/).




## Build the demo using Android Studio





