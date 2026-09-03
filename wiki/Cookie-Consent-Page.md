# Cookie Consent Page Wiki

## Purpose
This page provides Ionity's cookie consent experience, including a consent banner, a settings modal, and preference handling for necessary, security, analytics, marketing, and preference cookies.

## Main Files
- `/home/runner/work/ionity-assets-ionity-global-jwva/ionity-assets-ionity-global-jwva/assets/cookie-banner.html`  
  HTML markup for the banner and settings modal.
- `/home/runner/work/ionity-assets-ionity-global-jwva/ionity-assets-ionity-global-jwva/assets/js/cookie-manager.js`  
  JavaScript logic for consent state, storage, and cookie behavior.
- `/home/runner/work/ionity-assets-ionity-global-jwva/ionity-assets-ionity-global-jwva/assets/css/style.css`  
  Styling and animations for the banner and modal UI.

## Consent Behavior
- On first visit, the banner appears after a short delay.
- If consent already exists, preferences are loaded and applied automatically.
- Security and necessary cookies remain enabled.
- Users can:
  - Accept all cookies
  - Accept only necessary/security cookies
  - Open settings and save custom preferences

## Stored Consent Data
- Consent is stored under `ionity_cookie_consent`.
- The system stores:
  - `necessary`
  - `security`
  - `analytics`
  - `marketing`
  - `preferences`
- Consent is persisted with both:
  - `localStorage` (when available)
  - browser cookies

## Security Notes
- Security cookies are set with stricter `SameSite=Strict` handling.
- Secure flag is added when served over HTTPS.
- A random token is generated for CSRF-related protection support.

## UI Elements
- Banner container: `#cookie-banner`
- Settings modal: `#cookie-settings-modal`
- Preference toggles:
  - `#cookie-analytics`
  - `#cookie-marketing`
  - `#cookie-preferences`

## Integration Notes
- Ensure the cookie banner HTML is present in the page layout.
- Ensure `cookie-manager.js` is loaded on pages where consent is required.
- Ensure cookie consent styles from `style.css` are included.
- Other scripts can listen for `cookieConsentChanged` to react to user preferences.

## Maintenance Guidelines
- Keep cookie categories in HTML and JavaScript aligned.
- Keep policy/legal text in the banner and modal up to date.
- Validate that consent flows still work after UI or script updates.
