# OpenCV 3.3 — Development Roadmap

## 12-Month Vision

Transition OpenCV 3.3 from an active distribution to a well-documented legacy reference, with comprehensive migration tooling and performance baselines for comparison with modern OpenCV versions.

### Q1: Documentation & Migration
- Create detailed migration guide from OpenCV 3.3 → 4.10+ (API changes, breaking changes)
- Document T-API → Vulkan backend migration path
- Add automated build verification scripts for VS2017
- Create side-by-side code comparison examples (3.3 vs 4.x)
- Update README with clear end-of-life timeline

### Q2: Performance & Testing
- Create comprehensive benchmark suite comparing 3.3 CPU vs modern backends
- Add automated regression testing for core CV operations
- Document quality assessment metrics (PSNR, SSIM) as baseline references
- Create Docker image for reproducible 3.3 builds
- Add CI pipeline for build verification on Windows 10/11

### Q3: Migration Tooling
- Build automated API translation tool (3.3 → 4.x code migration)
- Create ONNX Runtime migration examples for DNN module
- Document OpenVINO as Intel-optimized inference replacement
- Add TensorRT migration guide for NVIDIA GPU targets
- Create hardware recommendation matrix for upgrade decisions

### Q4: Archive & Legacy
- Mark repository as archived with successor repository links
- Create final release with all documentation consolidated
- Write "OpenCV 3.x Era" retrospective document
- Ensure YouTube tutorial links remain accessible
- Add permanent redirect to modern OpenCV repositories

## Technical Debt

| Item | Priority | Impact | Effort |
|------|----------|--------|--------|
| Multi-part archive distribution | Medium | User friction | Medium |
| No automated build pipeline | High | Reproducibility | Medium |
| VS2017-only support | Medium | Outdated toolchain | Low |
| No test suite | High | Regression risk | Medium |
| T-API deprecation risk | Medium | Future compatibility | Low |
| No CI/CD | Medium | Manual validation | Medium |
| Missing Docker support | Low | Environment consistency | Low |
| No package manager integration | Low | Adoption friction | Low |

## Future Features

| Feature | Description | Priority |
|---------|-------------|----------|
| Migration Guide | 3.3 → 4.x/5.x comprehensive code migration | High |
| Benchmark Suite | CPU vs GPU vs T-API performance comparison | High |
| Docker Image | Reproducible build environment | Medium |
| CI Pipeline | Automated build and test on Windows | Medium |
| API Translation Tool | Automated 3.3 → 4.x code migration | Medium |
| ONNX Runtime Examples | DNN module replacement | Medium |
| Archive Release | Final release with EOL documentation | Medium |
| Quality Metrics Guide | PSNR/SSIM baseline documentation | Low |
| Legacy Support | Extended maintenance for enterprise | Low |
