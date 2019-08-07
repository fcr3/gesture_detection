# Gesture Detection

## Introduction
Model is based off of a pre-trained SSD Inception V2 model provided by Tensorflow's Object Detection API. The exported frozen graph was fed through OpenVINO's Model Optimizer in order to create FP32 and FP16 precision models optimized for inference on Intel hardware.

## Filesystem
- `model_optimized_fp16` contains the FP16 precision model
- `model_optimized_fp32` contains the FP32 precision model
- `tensorflow_model` contains the original exported frozen graph

## Note
This repository does not contain the .bin or .pb files. If you would like to download these files, click the link here.
