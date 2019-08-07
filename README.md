# Gesture Detection

## Introduction
Model is based off of a pre-trained SSD Inception V2 model provided by Tensorflow's Object Detection API. The exported frozen graph was fed through OpenVINO's Model Optimizer in order to create FP32 and FP16 precision models optimized for inference on Intel hardware.

## Filesystem
- `model_optimized_fp16` contains the FP16 precision model
- `model_optimized_fp32` contains the FP32 precision model
- `tensorflow_model` contains the original exported frozen graph
- `ssd_v2_support_inception_custom.json` is the config file used for the model optimizer

## Note
This repository does not contain the .bin or .pb files. If you would like to download these files, click the link [here](https://drive.google.com/open?id=1Dr9y1WA5do_TulqFgVrImRJe6rRsd6AX).
