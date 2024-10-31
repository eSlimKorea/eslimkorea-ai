# eslimkorea-ai

# PyBuda with Tenstorrent Integration

PyBuda is a Python-based interface that allows seamless interaction with the TT-Buda AI/ML compiler stack from Tenstorrent. This setup facilitates the compiling and execution of AI/ML models from various frameworks, such as PyTorch and TensorFlow, directly on Tenstorrent hardware.

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
