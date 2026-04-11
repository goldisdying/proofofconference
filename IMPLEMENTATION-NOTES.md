# Proof of Conference implementation notes

This package includes a first-pass site improvement update focused on preserving current functionality while improving structure and resilience.

## What changed

- Homepage layout widened and reorganized into clearer hero, featured events, filters, and results sections.
- Added quick-filter chips and a featured upcoming conferences section.
- Kept existing JS-driven directory behavior, including favorites, calendar actions, sorting, speaker search, newsletter form, and popup.
- Changed conference/ad/speaker data loading to prefer local CSV files first, with GitHub raw URLs as fallback.
- Reduced popup aggressiveness by increasing delay, increasing re-show interval, and waiting for deeper engagement.
- Added accessible labels to clear-filter buttons and a skip link.
- Replaced the redirect-only subscribe page with a real landing page and working email form.
- Added canonical/OG/Twitter metadata to key utility pages.

## What was intentionally preserved

- Existing conference cards and calendar views
- Favorites via localStorage
- Add-to-calendar functionality
- Kit/ConvertKit newsletter forms
- Blog and conference pages
- Translation controls

## Suggested next step

Run this build in a staging environment and spot-check:
- homepage filtering and sorting
- favorites add/remove
- calendar export links
- newsletter form submission
- popup close/submit behavior
- top navigation and mobile layout
