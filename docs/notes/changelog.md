# Change Log


### Notable Changes:

* 2019-11-11: `detectron2.data.detection_utils.read_image` transposes images with exif information.
* 2019-10-10: initial release.

### Config Version Change Log

* v1: Rename `RPN_HEAD.NAME` to `RPN.HEAD_NAME`.
* v2: A batch of rename of many configurations before release.

### Known Bugs in Historical Versions:
* Dec 19 - Dec 26: Using aspect ratio grouping causes a drop in accuracy.
*  - Nov 9: Test time augmentation does not predict the last category.
