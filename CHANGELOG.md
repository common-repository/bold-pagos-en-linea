# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.0.3] - 2024-10-28
### Changed:
- Improves payment confirmation only if payment has not been recorded on the order and double reduction of product inventory.
- Change name payment method.

## [3.0.2] - 2024-10-22
### Fix:
- Fix error double confirmation payment and double reduce inventory products.

## [3.0.1] - 2024-10-15
### Fix:
- Fix error in alert when try activation method payment in WooCommerce without keys of Bold.

### Changed
- Minor text adjustments.

## [3.0.0] - 2024-10-11
### Added:
- Added status of refund (VOIDED) by webhook and manual update.
- Added UI design in payment method in legacy checkout WooCommerce.
- Validate compatibility with multisite.

### Changed
- Improvement in process of uninstall.
- Improvements in styles of alerts for user experience.

### Fix:
- Improvement in process of update status order by webhook.
- Fix origin_url without WooCommerce.

### Security
Complete improvement of our code, drastically improving the structure, bugs and new functionalities.

## [2.8.0] - 2024-09-26
### Added:
- Add optional URL payment abandon, redirect to this URL if return to store without complete transaction.
- Optimization of texts for compatibilities with translators of WordPress.

### Fix:
- Update form save configurations with problems if URL of admin is changed.

## [2.7.2] - 2024-09-17
### Added:
- New WordPress Design for Cart Description.

## [2.7.1] - 2024-09-02
### Fix:
- Add event for activate button save payment method in panel payments of woocomerce.

### Added:
- Add version to assets css and js evit cache in change versions.

## [2.7.0] - 2024-08-28
### Added:
- Validation of the configured webhook before the key configuration can be saved
- Uninstallation process is added to delete saved data and avoid caching.