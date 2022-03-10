Changes
=======

v1.2.0
------

### New features

- Added `pylint-executable` input, allowing the `pylint` executable
  to be overridden from the default.

v1.1.0
------

### New features

- Added `pylint-ignore-paths` input, passed to `pylint` via the
  `--ignore-paths` command-line argument.

### Bug fixes

- Usage errors thrown by the `pylint` invocation will now fail the
  action.

v1.0.0
------

- Initial release.
