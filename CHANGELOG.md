# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2021-01-06

- Migrated from lv-distribution to lv-distribution-build
- Simplified functional globals by removing private command
- Added ability to set download location
- Broke the API when introducing the fg_download_location.vi, deprecated get_installer_locations and all vis associated wih add_installer_location.
- Moved the lv-post-installer-interface into the lv-post-installer project (and included it in the vip artifact)

## [0.9.0] - 2020-05-20

- Initial release
