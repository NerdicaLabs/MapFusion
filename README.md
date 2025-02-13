## === MapFusion ===
Author: nerdicalabs  
Contributors: charlienerdica, Frank  
Tags: maps, markers, integration  
Requires at least: 5.8  
Tested up to: 6.7.1  
Requires PHP: 7.4  
Stable tag: 1.5.0  
License: GPLv3 or later  
License URI: https://www.gnu.org/licenses/gpl-3.0.html  

Powerful mapping integration for WP Go Maps Pro.

## == Description ==
MapFusion enhances WP Go Maps Pro with advanced map and marker integrations.
MapFusion is a WordPress plugin that bridges the gap between Make and WP Go Maps Pro, providing tools for managing maps, markers, and layers. The PRO version unlocks additional features such as license validation, advanced integrations, and automatic updates.

## == Features ==
* Add, edit, delete maps and markers.
* Modular REST API for external integrations.
* Admin interface with API key management.
* License validation for PRO features.
* Automatic updates via Appsero.

## == Installation ==
1. Download the plugin files.
2. Upload to `/wp-content/plugins/`.
3. Activate in the WordPress admin panel.

## == Usage ==
* Access MapFusion settings via the WordPress admin menu.
* Use the REST API to integrate with external applications like Make.
* Generate and manage your API key in the admin settings.
* Activate PRO features by validating your license in the settings page.
* A dedicated Make module for MapFusion is available for seamless integration.

## == Frequently Asked Questions ==

**❓ What is MapFusion?**
MapFusion is a WordPress plugin that seamlessly integrates **Make** with **WP Go Maps**, allowing you to manage maps and markers via a powerful REST API.

**❓ How do I install MapFusion?**
1. Download and install MapFusion from the **WordPress Plugin Repository**  
2. Activate it through the **Plugins** menu in WordPress.  
3. Copy your API key and start integrating!  

You can also download MapFusion from **[mapfusion.site](https://www.mapfusion.site)** or **[GitHub](https://github.com/NerdicaLabs/MapFusion)**.  

**❓ Do I need Make to use this plugin?**
No, MapFusion **can be used without Make**, but it is primarily designed to integrate seamlessly with **Make** for automating map and marker management.  
Support for other automation platforms may be added in the future.

**❓ What data can I send to MapFusion?**
You can use the following actions with MapFusion:  

- Add Maps/Markers  
- Get Map/Marker Details  
- Edit Map/Marker  
- Export Maps and Markers  
- Import Maps and Markers  

**❓ Is MapFusion free?** 
The core version of MapFusion is **free**, but features such as edit, duplicate, and export/import are available in the **PRO version**.  

👉 Get PRO at [https://www.mapfusion.site/pro/](https://www.mapfusion.site/pro/)

**❓ How do I get my API key?** 
Your API key is automatically generated upon installation.  
Simply go to **API Key Management** in your WordPress Admin Panel and copy it!  

**❓ Will MapFusion work with other mapping plugins?**
Currently, MapFusion is built specifically for **WP Go Maps**. Compatibility with other mapping plugins may be considered in future updates.

**❓ How can I request a feature?**
We love feedback! Submit feature requests via GitHub or contact us directly at **[contact@mapfusion.site](mailto:contact@mapfusion.site)**.  

**❓ Where can I donate to support development?**
Thank you for your support! ❤️ You can donate via PayPal:  
[👉 Donate here](https://www.paypal.com/ncp/payment/9YFMPH2CLTP78)

## == Upgrade Notice ==
See `CHANGELOG.md` for updates and new features.

## == Requirements ==
* WordPress 5.8 or higher.
* WP Go Maps Pro plugin installed and activated.

## == Support ==
For issues and feature requests, contact us via [support@mapfusion.site](mailto:support@mapfusion.site).

## == 📢 Donate & Support ==
If you appreciate MapFusion and want to support its development, consider making a donation. Every contribution helps us improve and add new features! 💖

[👉 Donate via PayPal](https://www.paypal.com/ncp/payment/9YFMPH2CLTP78)

## == Privacy Policy ==
MapFusion PRO collects some telemetry data upon the user's confirmation. This helps us troubleshoot problems faster and improve the product.

Data collection does not occur by default. The data collection only begins when a user allows it through the admin notice. We collect this data to ensure a great user experience.

Integrating MapFusion PRO DOES NOT IMMEDIATELY start gathering data without confirmation from the user in any case.

Learn more about how we collect and use this data in our [Privacy Policy](https://www.mapfusion.site/privacy-policy/).

# Changelog

## [1.5.0] - 2025-02-13
### Added
- Pagination support to improve performance and user experience.
- Custom license management system for handling PRO licenses.

### Fixed
- Several API-related bugs, improving stability and functionality.

## [1.2.0] - 2025-01-15
### Added
- New "Make API Key Management" section for entering and resetting Make API keys.
- Zone settings for Make connection.
- Import, Export, and Clear functionalities for database settings.
- Debugging system with granular logging levels (`Error`, `Info`, `Warning`, `Critical`, `Initializing`, `API`).
- Test connection functionality for verifying Make API integration.
- Dynamic localization of scripts with WordPress options.

### Updated
- Separated and modularized JavaScript files for better maintainability.
- Organized and categorized AJAX handlers for clarity and maintainability.
- Improved user interface with enhanced responsiveness and accessibility.

### Fixed
- Resolved redundant class loading in fallback mechanism.
- Enhanced security and error handling for AJAX actions and Privacy Policy Notice dismissal.
- Corrected dependency handling for WP Go Maps Pro integration.
- Debug logging now properly respects global plugin settings.

### Removed
- Deprecated and unused JavaScript functions consolidated or replaced.

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

# Roadmap

MapFusion is committed to expanding its capabilities. Here are some planned features:

---

## Version 2.0.0 (In Development)
### PRO Features
- **Layer Management:** Add, edit, and organize layers for maps.
- **Category Management:** Comprehensive tools for managing categories.
- **Batch Marker Updates:** Simultaneously update multiple markers for streamlined workflows.

### Accessibility Features
- **`aria-live` for Dynamic Content**: Implement `aria-live="polite"` for sections with dynamically changing content, such as tables, to notify screen readers of updates.
- **`aria-label` and `aria-describedby`**: Use `aria-label` for buttons and other interactive elements that need descriptive labels, and `aria-describedby` for elements that require additional information.
- **Focus Management with `tabindex`**: Ensure logical focus navigation using `tabindex`, ensuring users with keyboard-only navigation can tab through the page in a logical sequence.
- **Skip Links**: While the page is minimal, consider adding **skip links** for quick navigation for keyboard and screen reader users in the future.
- **Semantic HTML**: Use correct HTML elements like `<ul>`, `<ol>`, and `<table>` to create a more structured and accessible content layout.
- **Color and Contrast Improvements**: Plan for better color contrast and larger text for those with visual impairments.

---

## Future Plans
- Improved integration with third-party mapping APIs.
- Multi-site compatibility for enterprise users.
- Advanced analytics for map and marker performance.
- User role-based access control for PRO features.

---
