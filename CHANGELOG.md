# Change Log

## (06/10/2016) [1.0.1]

**Fixed bugs:**
- Fix feature while looping by moving feof to after read_image.
- Fix issue #2 use hashed string for log filename and result filename to avoid file names getting too long.

**New features:**
- Add SsimFeatureExtractor and MsSsimFeatureExtractor with intermediate features (luminence, contrast, structure).

## [1.0.2]

**New features:**
- Refactor feature code to expose ssim/ms-ssim, speed up ssim/ms-ssim
