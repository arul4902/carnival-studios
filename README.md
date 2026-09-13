# Carnival Studios

Four-page static brand website: Home, Portfolio, Contact and Privacy, plus a 404 page. Client-facing content and contact links are configured. Publication has not been requested.

## Editing

- Edit the page content in `build.py`, then run `python3 build.py` to regenerate HTML.
- Shared visual styles: `dist/style.css`.
- Interactions and contact configuration: `dist/app.js`.
- Gallery records are in the `photos` array in `dist/app.js`. The homepage image selections are in `build.py`.
- Images live in `dist/assets`. Current images were retrieved from the studio’s own website and portfolio; see ASSET-SOURCES.md. Captions and alt text reflect the photographs. Confirm reuse permission with the studio before publishing a separate public copy.
- `CONFIG.whatsappNumber` is set to `919852248522`, matching the studio's published telephone and WhatsApp contact at https://about.me/carnivalstudios and https://carnivalstudios.in/. Phone, direct WhatsApp, contextual enquiry and Instagram links are configured. Confirm any future contact changes with the owner.
- Instagram links point to https://www.instagram.com/carnivalstudios/.
- No booking confirmation, payment, analytics, persistent storage or form-submission backend is included. Drafts are temporary browser memory; copy fallback is available.
- All pages are noindex. Confirm content permissions and domain configuration before separately authorized publication. The privacy page describes the implemented browser-only draft and third-party contact flow; it does not claim legal certification.

## Scope and checks

Responsive styles cover mobile, tablet and desktop. Gallery filters and a native modal image viewer support keyboard interaction. Contact fields include validation and service prefills. Internal routes, asset paths, HTML structure and JavaScript syntax were checked. Browser-based visual or end-to-end testing was not run.

Use any static web server rooted at `dist` to review the source website. A separate self-contained HTML preview is exported for convenient offline review.
