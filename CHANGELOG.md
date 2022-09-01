# v0.3.0
## New
- Added the ability to choose colours through `colour_splash.colours` and `colour_splash.styles` (e.g. where `"red"` would previously been used, `colour_splash.colours.red`). The previous method is still available
- Changed build tool from hatchling to setuptools
- Updated README with new features
- Added Changelog listing to the PyPI distribution page

## Fixed
- Changed imports of needed modules so only the parts of the modules required are imported
- Updated pyproject.toml to better represent the project (and to fix some issues reflected when running `pip show colour-splash`)

# v0.2.0
## New
- Added the ability to start/stop colours and styles throughout a document to give greater control over the styling
- Updated README with new features
- Added Source listing to the PyPI distribution page

## Fixed
- The license on the PyPI distribution page no longer prints the full license

# v0.1.0
Initial Release