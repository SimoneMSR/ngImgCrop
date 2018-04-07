# ngImgCrop

NOTE: this is a fork of <a href ="https://github.com/alexk111/ngImgCrop">alexk111/ngImgCrop</a>, inspired by a pen by <a href="https://codepen.io/HugeHugh/pen/NRgmWm">Hugh Anderson</a>
Angular(1) directive for cropping identity photographs. The forked directive add these attributes to the `<img-crop>` element:

- tollerance-ratio : set a tolerance on the image ratio (width / height) (in percent, es. 10)
- can-rotate: enable image rotation
- min-resolution: prevent image cropping if the image does not satisfied the minimum requested resolution (DPI)

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

## Usage

Follow <a href ="https://github.com/alexk111/ngImgCrop#usage">these instructions</a> and then consider that:
- you can add rotation by setting the `can-rotate` attributo of the `<img-crop>` element to `true`
- you can set the miminum resolution by setting the `min-resolution` attribute
- you can set the resolution tollerance by setting the 'tollerance-ratio' attribute
