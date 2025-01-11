## === MapFusion ===  
Plugin Name: MapFusion  
Plugin URI: https://www.mapfusion.site/  
Description: MapFusion provides powerful map and marker integration for WordPress, allowing you to easily visualize and manage your data.  
Author: Charlie the Nerdica  
Author URI: https://www.charlienerdica.tech/  
Contributors: Charlie the Nerdica, Frank  
Tags: maps, markers, integration  
Requires at least: 5.8  
Tested up to: 6.7.1  
Requires PHP: 7.4  
Stable tag: 1.1.0  
License: GPLv2 or later  
License URI: https://www.gnu.org/licenses/gpl-2.0.html  

## Description
MapFusion is a WordPress plugin that bridges the gap between Make and WP Go Maps Pro, providing powerful tools for managing maps, markers, and advanced integrations. The PRO version unlocks additional features such as license validation, advanced integrations, multi-site compatibility, and automatic updates.

## Features
- Add, edit, and delete maps and markers.
- Modular REST API for external integrations.
- Admin interface with API key management.
- License validation for PRO features.
- Automatic updates via Appsero.
- Seamless integration with Make.

## Installation
1. Download the plugin files.
2. Upload to `/wp-content/plugins/`.
3. Activate the plugin in the WordPress admin panel.

## Usage
- Access MapFusion settings via the WordPress admin menu.
- Use the REST API to integrate with external applications like Make.
- Generate and manage your API key in the admin settings.
- Activate PRO features by validating your license on the settings page.
- Leverage advanced PRO features such as bulk marker updates and category management.

## Privacy Policy
MapFusion PRO uses [Appsero](https://appsero.com) SDK to collect some telemetry data upon user's confirmation. This helps us to troubleshoot problems faster & make product improvements.

Appsero SDK **does not gather any data by default.** The SDK only starts gathering basic telemetry data **when a user allows it via the admin notice.** We collect the data to ensure a great user experience for all our users.

Integrating Appsero SDK **DOES NOT IMMEDIATELY** start gathering data, **without confirmation from users in any case.**

Learn more about how [Appsero collects and uses this data](https://appsero.com/privacy-policy/).

## Changelog
See `CHANGELOG.md` for details on updates, new features, and fixes.

## Requirements
- WordPress 5.8 or higher.
- WP Go Maps Pro plugin installed and activated.
- PHP version 7.4 or higher.

## Support
For issues and feature requests, contact us via [support@mapfusion.site](mailto:support@mapfusion.site) or visit our [support page](https://mapfusion.site/support).

---

# Changelog

## [1.1.0] - 2025-01-08
### Added
- Modularized REST API into separate files for better organization.
- Added dynamic API class loading.
- Introduced PRO features, including license validation and Appsero integration for automatic updates.
- Added a dashboard accessible via the website for PRO users.
- Beta Testing Program: Early access to upcoming PRO features for selected users.

### Fixed
- Improved nonce validation for enhanced security.
- Fixed dependency check for WP Go Maps Pro.
- Enhanced error handling during plugin activation.
- Ensured proper handling for failed script enqueue.
- Miscellaneous bugfixes.

## [1.0.0] - 2024-12-25
### Added
- Initial release of MapFusion.
- REST API for adding, editing, and deleting maps and markers.
- Admin interface for managing maps and markers.
- API key generation and validation.

---

# Roadmap

MapFusion is committed to expanding its capabilities. Here are some planned features:

## Version 1.2.0
- Bugfixes and performance improvements.
- Enhanced debug tools for easier troubleshooting.
- Internationalization support for broader accessibility.

## Version 2.0.0 (In Development)
### PRO Features
- **Layer Management:** Add, edit, and organize layers for maps.
- **Category Management:** Comprehensive tools for managing categories.
- **Batch Marker Updates:** Simultaneously update multiple markers for streamlined workflows.

## Future Plans
- Improved integration with third-party mapping APIs.
- Multi-site compatibility for enterprise users.
- Advanced analytics for map and marker performance.
- User role-based access control for PRO features.
