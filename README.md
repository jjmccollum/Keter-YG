# Keter-YG
Yoram Gnat's Keter-YG Hebrew typeface with minor typographical features added

## About This Project

This project is a fork of https://github.com/ibleaman/Keter-YG. As the changes made in this fork are motivated by a very specific use case, they are limited to the upright, medium-weight style of the font. This fork differs from the original project in that it uses a more recent version (.103yg) of the Keter YG Medium font and incorporates the following changes:
- Improved positioning of vowel points, especially for _yod_, _lamed_, and _qof_.
- Improved positioning of _holam_.
- Added support for furtive _patah_ positioning to the `calt` (contextual alternates) feature set.
- Added support for the merging of _holam_ with _shin_ dot or _sin_ dot, followed by shifting of the position of the _shin_ dot or _sin_ dot. This is currently placed in the `calt` feature set, but it may be moved to a different set (perhaps `dlig`, discretionary ligatures) later, as it more aesthetic and less functional than the furtive _patah_ feature described above.
- Added support for the merging of _shin_ and _sin_ dots when a _sin_ is followed by a _shin_. Like the previous feature, this is currently placed in the `calt` feature set, but it may be moved in the future.
