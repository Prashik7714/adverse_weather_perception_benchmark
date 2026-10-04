# Weather Robustness for Driving Segmentation

How much does a driving segmentation model lose in fog, rain and darkness?

This project tests a pretrained SegFormer model on Cityscapes street scenes
under adverse weather, created in two ways: classical image corruptions and
diffusion-generated weather. The goal is to measure how accuracy (mIoU)
drops as conditions get worse, and which objects fail first.

**Status:** work in progress

## Plan
- [ ] Baseline accuracy on clear-weather images
- [ ] Classical fog, rain and night corruptions
- [ ] Diffusion-generated adverse weather
- [ ] Analysis, comparison with real adverse weather (ACDC), results

Data is not included in this repository. See the Cityscapes and ACDC
websites for access.
