# blaise-sdk

Core AI SDK for the Blaise Raman spectrometer platform — part of the [Blaise OSE](https://github.com/Blaise-OSE).

Blaise combines a double-layer disordered metasurface optical architecture with Vision
Transformer (ViT) and Deep Neural Network (DNN) models to deliver laboratory-grade Raman
molecular fingerprinting from a USB-C device under 30 grams — at under $800 per unit and
under $0.50 per test.

## Status

🚧 This repository currently contains documentation only. SDK access is provided directly
to accepted teams as part of the [Blaise xTECH Challenge](https://support.forwardedge.ai/en/?q=XTECH),
a five-phase global competition opening **August 1, 2026** with a $1,000,000 prize pool.

## What the SDK provides

- Spectral preprocessing pipelines
- Vision Transformer (ViT) and Deep Neural Network (DNN) model architectures for
  contaminant / substance classification
- Device interface libraries for connecting to the Blaise spectrometer over USB-C

## Versioning and releases

The SDK follows semantic versioning:

- **Major releases** ship at the opening of each xTECH Challenge phase, introducing new
  model architectures, preprocessing capabilities, or device interface changes.
- **Minor releases** address performance improvements and bug fixes on a monthly cadence.
- All releases are tagged, signed, and accompanied by release notes documenting changes,
  migration paths, and benchmarking results against the community reference dataset.

## Contributing

Changes follow a feature-branch workflow requiring two peer reviews and a passing
automated test suite before merge, with a minimum 72-hour staging validation period
before production promotion. A change freeze applies during the 14 days preceding each
xTECH Challenge phase transition.

## Related repositories

- [blaise-spectral-library](https://github.com/Blaise-OSE/blaise-spectral-library) — community Raman spectral data (HDF5, CC-BY 4.0)
- [blaise-applications](https://github.com/Blaise-OSE/blaise-applications) — published competitor applications
- [blaise-docs](https://github.com/Blaise-OSE/blaise-docs) — technical documentation and integration guides

## License

Apache License 2.0 — see [LICENSE](LICENSE).
