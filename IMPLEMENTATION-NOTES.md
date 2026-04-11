# Implementation Notes (v2)

Updated after QA feedback:

- Fixed homepage quick chips:
  - Removed confusing `Europe spotlight` behavior and replaced it with a real `Europe` quick filter.
  - Kept `USA` as a normal quick filter.
  - Added active-state styling for quick chips.
  - Added result summary text so chip clicks visibly change the page.
  - Quick chips now reset conflicting filters before applying their own filter.
- Restored translator behavior:
  - Switched Google Translate script to explicit `https://`.
  - Added more reliable cookie handling for `googtrans`.
  - Added retry logic so language changes still work if the Google translate dropdown loads a moment later.
- Preserved existing directory functionality:
  - filters
  - favorites
  - calendar/cards toggle
  - newsletter section
  - speaker filtering
  - ads and inserted cards
