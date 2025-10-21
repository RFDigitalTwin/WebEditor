Environment Lighting Setup
==========================

Place your HDR/EXR environment map file in this directory with the name:
- environment.exr

The file will be used for Image-Based Lighting (IBL) for all materials in the scene.

Recommended sources for HDR/EXR files:
- Poly Haven (https://polyhaven.com/hdris) - Free HDR environments
- HDRI Haven - High quality environment maps
- HDR Labs (http://www.hdrlabs.com/sibl/archive.html)

File format requirements:
- Format: EXR (OpenEXR) or HDR
- Resolution: 2K-4K recommended for good quality/performance balance
- Tone mapping: Linear color space

The environment map provides realistic lighting and reflections for all materials
without adding a visible skybox to the scene.