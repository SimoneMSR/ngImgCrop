# ngImgCrop

NOTE: this is a fork of <a href ="https://github.com/alexk111/ngImgCrop">alexk111/ngImgCrop</a>, inspired by a pen by <a href="https://codepen.io/HugeHugh/pen/NRgmWm">Hugh Anderson</a>
Angular(1) module for cropping identity photographs. The photo image must satisfy:

- Size: 35 x 45 mm with a tolerance on the ratio (width / height) of +/- 10%
- Resolution: minimum between 300 and 400 DPI

## Requirements

- npm
- bower

## Build and install directive

```
npm install
bower install
gulp build-unminified
```

will produce `ng-img-crop.css` and `ng-img-crop.js`  in the `compile/unminified` folder. This file loads the directive, include it where needed

```
<script src="ng-img-crop.js"></script>
<link rel="stylesheet" type="text/css" href="ng-img-crop.css">
```
