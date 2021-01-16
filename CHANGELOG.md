# Change Log

## 0.2.1

### Fixed

* Bundled `datefinder` did not get added to `setup.py`.

## 0.2.0

### Added

* Additional log levels `TRACE`, `CRITICAL`, and `EMERG`.

### Changed

* Scrolling is now based on display lines, not log records.
* Page Up/Down now scrolls an entire page, not 5 records.
* Improved line wrapping.
* Log level matching now ignores case.

### Fixed

* Crash when a file contains a blank line.
* Multiline log records not being coloured correctly.
* Crash if scrolling and scroll bounds have been miscalculated.
* Windows not resizing correctly or redrawing on terminal resize.

## 0.1.1

### Fixed

* Import error of version file. (Fixes [#1](https://github.com/CrazyIvan359/logview/issues/1))
* Name error in `__main__.py`. (Fixes [#2](https://github.com/CrazyIvan359/logview/issues/2))
* TypeError when not using `--dir` option. (Fixes [#3](https://github.com/CrazyIvan359/logview/issues/3))

## 0.1.0

Initial beta release
