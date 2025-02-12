# ImageOptimize Thumbor Image Transform Changelog

## 1.3.3 - 2022.03.29

### Changed

* Tighten the `composer.json` `require` constraints to limit it to the Craft 3 version of ImageOptimize

## 1.3.2 - 2022.02.24

### Changed

* Loosen the `composer.json` `require` constraints

## 1.3.1 - 2021.04.23
### Added
* Added a setting to control the amount an image needs to be scaled down for automatic sharpening to be applied (https://github.com/nystudio107/craft-imageoptimize/issues/263)

## 1.3.0 - 2019.07.05
### Changed
* Updated to work with the ImageOptimize 1.6.0 `ImageTransformInterface`

## 1.2.1 - 2019.03.11
### Changed
* Fixed un-parsed [environmental variables](https://docs.craftcms.com/v3/config/environments.html#control-panel-settings) for secrets

## 1.2.0 - 2019.03.04
### Added
* Added support for `stretch` filter

### Changed
* Fixed SVGs by deferring to Craft

## 1.1.2 - 2019.02.07
### Changed
* Fixed an issue where `.env` vars were not actually parsed

## 1.1.1 - 2019.02.07
### Changed
* If you're using Craft 3.1, ImageOptimize will use Craft [environmental variables](https://docs.craftcms.com/v3/config/environments.html#control-panel-settings) for secrets

## 1.0.0 - 2018.12.28
### Added
- Initial release
