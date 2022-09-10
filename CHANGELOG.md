# v0.4.0
## New
- Enabled coloured outputs by default for Windows terminals which support it (e.g. PowerShell, Windows Terminal)
- New setting `colour_splash.settings.no_colours` to manually disable coloured outputs. This overrides `colour_splash.settings.force_colours`
- Colours can now be selected through RGB codes using `colour_splash.rgb()`
- Added docstrings to classes and functions

## Fixed
- Colours are now enabled on Windows if using the Windows Terminal (which supports ANSI colours)
- Fixed issue where help screen would error out when outputting styles
- Incorrect colour and style names now raise a ValueError rather than a TypeError
- Fixed issue where parameters for `colour_start` and `colour_end` could only be strings
- Renamed the style parameter to decoration to resolve clash between functions and variables with the same name

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