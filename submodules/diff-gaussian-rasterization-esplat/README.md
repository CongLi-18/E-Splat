# E-Splat Semantic Gaussian Rasterizer

This module is the semantic rasterization backend used by E-Splat. It extends the original 3D Gaussian Splatting rasterizer with configurable semantic channels and differentiable rendering of semantic fields.

The number of semantic channels is configured in:

```
cuda_rasterizer/config.h
```

The default E-Splat configuration uses 512 channels for LSeg features. Rebuild the extension after changing this value.

This implementation is based on [3D Gaussian Splatting](https://github.com/graphdeco-inria/diff-gaussian-rasterization/tree/59f5f77e3ddbac3ed9db93ec2cfe99ed6c5d121d). The original copyright and license terms are retained in `LICENSE.md`.
