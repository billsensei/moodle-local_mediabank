# Contributing

Thank you for helping with the Media bank. This repository is `local_mediabank`, one of three plugins; the other two are
[moodle-contenttype_mediabank](https://github.com/billsensei/moodle-contenttype_mediabank) (the main plugin, and where the guides live) and
[moodle-filter_mediabank](https://github.com/billsensei/moodle-filter_mediabank).

How to report a problem, set up a test site, run the tests and what a change needs before it is merged are described in the
[contributing guide](https://github.com/billsensei/moodle-contenttype_mediabank/blob/main/CONTRIBUTING.md) and the
[development guide](https://github.com/billsensei/moodle-contenttype_mediabank/blob/main/docs/DEVELOPMENT.md) of the content type. They apply here. This plugin needs
`contenttype_mediabank` installed, so a test site needs both.

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md). By contributing you agree that your work is
released under the [GNU GPL v3 or later](LICENSE).

A change to the code needs a new version number and a new release: see
[RELEASING.md](https://github.com/billsensei/moodle-contenttype_mediabank/blob/main/docs/RELEASING.md). Run `python3 scripts/build_release.py` to build the zip and
`php scripts/validate_plugin_zip.php` to check it.
