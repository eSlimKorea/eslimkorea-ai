# eslimkorea-ai

![image](https://github.com/user-attachments/assets/6e026b54-bd4a-4be3-8ac0-4d7aa63f6348)



# Introduction

eSlimKorea is conducting advanced testing with Tenstorrent’s NPU to explore and validate its potential in accelerating AI/ML models. Our goal is to test various AI models on this emerging technology and compare its performance with traditional GPUs, aiming to identify advantages and areas for optimization with frameworks like PyTorch and TensorFlow.



## Quick Links
- [PyBuda Docs](#docs)
- [Model Demos](https://github.com/tenstorrent/tt-buda-demos)
- [TT-Buda Installation](#build)

## Introduction
The PyBuda interface enables developers to leverage Tenstorrent's TT-Buda stack from within Python, making it easy to import and run models from major frameworks like PyTorch, TensorFlow, ONNX, and TFLite on Tenstorrent hardware.

## Model Demos
For model demos and example scripts, refer to the separate repository:
- [TT-Buda Model Demos](https://github.com/tenstorrent/tt-buda-demos)

## Docs
For detailed documentation on PyBuda and TT-Buda, refer to the [official documentation](#docs).

## Build
Instructions for installing and building the TT-Buda stack can be found [here](#build).

## Environment Setup
To ensure PyBuda works correctly with TT-Buda, set the `LD_LIBRARY_PATH` environment variable to the following path:
```bash
export LD_LIBRARY_PATH=/path/to/third_party/budabackend/build/lib
