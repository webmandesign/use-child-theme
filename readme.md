# WebMan Design Use Child Theme

*This is a fork of **[Use Child Theme](https://github.com/FacetWP/use-child-theme) by FacetWP** modified for use in WebMan Design themes out of the box.*

---

## How It Works

* If a child theme is not active, the user will see a WP notice with an "Activate" link **on the Theme Editor screen**
* When clicked, a child theme is created (if needed) and enabled

---

## Development Setup

This script uses `text_domain` development variable/prefix. Search & replace the `{%= text_domain %}` to match the parent theme text domain.

---

## Changelog

### 1.0

* Initial release (derived from original [Use Child Theme version 0.4](https://github.com/FacetWP/use-child-theme/releases/tag/0.4) with ["Fixing text domain issue" commit](https://github.com/FacetWP/use-child-theme/pull/19) included)
