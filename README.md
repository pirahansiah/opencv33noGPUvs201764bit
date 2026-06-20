# OpenCV 3.3 — Visual Studio 2017 (No GPU, 64-bit)

[![OpenCV](https://img.shields.io/badge/OpenCV-3.3-blue.svg)](https://opencv.org)
[![Visual Studio](https://img.shields.io/badge/Visual%20Studio-2017-purple.svg)](https://visualstudio.microsoft.com)
[![Platform](https://img.shields.io/badge/Platform-Windows%2064--bit-lightgrey.svg)](https://www.microsoft.com/windows)
[![GPU](https://img.shields.io/badge/GPU-None%20(CPU%20Only)-orange.svg)](#)
[![YouTube](https://img.shields.io/badge/YouTube-Tutorials-red.svg)](https://www.youtube.com/tiziran)

Prebuilt OpenCV 3.3 libraries for Visual Studio 2017 on Windows 64-bit. CPU-only build (no GPU/CUDA dependency) — ideal for systems without NVIDIA GPUs or for lightweight deployments.

> **Project by Dr. Farshid Pirahansiah** — [www.tiziran.com](https://www.tiziran.com) | [YouTube](https://www.youtube.com/tiziran)

## Contents

- OpenCV 3.3 prebuilt libraries (CPU-only, no CUDA)
- Visual Studio 2017 project configuration
- Multi-part archive: `opencv33.z01` through `opencv33.z04` + `opencv33.zip`

## Quick Start

1. Download all archive parts (`opencv33.zip` + `opencv33.z01`–`.z04`)
2. Extract the combined archive using 7-Zip or WinRAR
3. Open Visual Studio 2017 and configure include/library paths
4. Build and run

## What's New in OpenCV 3.3

- **DNN module improvements** — Faster inference, expanded layer support
- **Improved T-API** — Transparent OpenCL acceleration for compatible operations
- **New tracking API** — MIL, KCF, and MedianFlow trackers
- **aruco module enhancements** — Better board detection and pose estimation
- **Quality assessment API** — PSNR, SSIM, and modified Haar wavelet metrics

## CPU-Only vs GPU Comparison

| Aspect | CPU (This Build) | GPU (CUDA) |
|--------|-----------------|------------|
| Setup complexity | Low | High (requires CUDA + cuDNN) |
| Inference speed | Moderate | 5-20x faster |
| Memory | Shared system RAM | Dedicated VRAM |
| Deployment | Any machine | NVIDIA GPU required |
| Best for | Prototyping, embedded | Production, real-time |

## Modern Upgrade Path (2025-2026)

For new projects, consider:

| Tool | Notes |
|------|-------|
| [OpenCV 4.10+](https://github.com/opencv/opencv) | Latest CPU + GPU optimized builds |
| [OpenCV 5.x](https://github.com/pirahansiah/opencv5vs2022) | Next-gen with improved performance |
| [ONNX Runtime CPU](https://onnxruntime.ai) | Cross-platform CPU inference |
| [OpenVINO](https://docs.openvino.ai) | Intel-optimized CPU inference (2-4x speedup) |

## Related Projects

- [OpenCV 3.2 (VS2013)](https://github.com/pirahansiah/opencv32vs2013win64)
- [OpenCV 4 (VS2017)](https://github.com/pirahansiah/opencv4)
- [OpenCV 5 (VS2022)](https://github.com/pirahansiah/opencv5vs2022)
- [OpenCV Python Workshop](https://github.com/pirahansiah/opencv_python)

## Resources

- [OpenCV 3.3 Release Notes](https://docs.opencv.org/3.3/release_notes.html)
- [OpenCV Official Documentation](https://docs.opencv.org/3.3/)
- [YouTube Channel](https://www.youtube.com/tiziran)

## License

See repository for license details.
