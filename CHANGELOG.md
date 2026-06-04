# Changelog

All notable changes to **JT Visual Blocks** will be documented in this file.

## [0.1.10] - 2026-06-04

### Added
- Added accessibility-focused settings.
- Added optional ARIA label for the module wrapper.
- Added configurable main heading level.
- Added configurable item heading level for cards, articles and FAQ items.
- Added screen-reader text for links that open in a new window.
- Added accessibility-conscious handling for decorative feature icons.

### Improved
- Improved FAQ accordion markup for Bootstrap 5 and assistive technologies.
- Improved frontend output for Joomla 6 default template compatibility.
- Improved accessibility support for visually hidden helper text.

### Notes
- This is the first stable candidate prepared after JED Checker validation.
- No custom CSS or JavaScript is loaded by the module.

## [0.1.9] - 2026-06-04

### Added
- Added JoomTheme link in the module description.
- Added Joomla Directory review link in the module description.
- Added Turkish and English description strings for the new links.

## [0.1.8] - 2026-06-04

### Fixed
- Added update server definition to the manifest.
- Added GPL-compatible license headers to PHP files.
- Removed duplicate language keys from English and Turkish language files.
- Replaced unknown `JREADMORE` language usage with a module-specific language key.

## [0.1.7] - 2026-06-04

### Added
- Added FAQ Accordion block type.
- Added six FAQ question and answer fields.
- Added FAQ layout options: default accordion, flush accordion and card wrapper.
- Added option to open the first FAQ item by default.
- Added option to show item numbers.

## [0.1.6] - 2026-06-04

### Added
- Added advanced Feature Cards settings.
- Added card column selection.
- Added card style selection.
- Added equal-height card option.
- Added full-card link option.
- Added per-card badge, icon, image, alt text, title, text, button text and link fields.

## [0.1.5] - 2026-06-04

### Improved
- Manual badges are no longer shown on category article lists.
- Category article cards use article metadata instead of global manual badges.

## [0.1.4] - 2026-06-04

### Added
- Added article source selection: manual content, single article or category articles.
- Added category article display support.
- Added article count, ordering, layout and column options.
- Added title link, image link and read more visibility options.

## [0.1.3] - 2026-06-04

### Added
- Replaced single badge setting with three manual badges.
- Added individual Bootstrap color selection for each badge.

### Fixed
- Fixed text alignment option labels.

## [0.1.2] - 2026-06-04

### Added
- Added article metadata options: category, author and date/time.
- Added date source and format options.
- Added image link option for article images.

### Fixed
- Fixed uninstall display name by using a literal module name in the manifest.
- Content and Feature Card fields now start empty by default.

## [0.1.1] - 2026-06-04

### Improved
- Improved article selection field.
- Added clearer manual content fallback behavior.

## [0.1.0] - 2026-06-04

### Added
- Initial release.
- Added Hero block.
- Added CTA Box block.
- Added Article Highlight block.
- Added Feature Cards block.
- Added primary, secondary and PayPal button support.
- Added English and Turkish language files.
- Added Joomla 6 module structure using services provider, dispatcher and helper.
- Built with Bootstrap 5 classes and no custom CSS or JavaScript.
