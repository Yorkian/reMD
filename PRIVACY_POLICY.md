# Privacy Policy

**reMD - Markdown Renderer Chrome Extension**

*Last Updated: January 2025*

---

## Overview

reMD ("the Extension") is a browser extension that detects and renders Markdown content displayed as plain text on web pages. We are committed to protecting your privacy and being transparent about our data practices.

> **Summary:** reMD does not collect, store, transmit, or share any personal data or browsing information. All processing happens locally in your browser.

---

## Data Collection

reMD does **not** collect any data. Specifically, we do not collect:

- Personal information (name, email, address, etc.)
- Browsing history or visited URLs
- Page content or text from websites you visit
- Authentication or login information
- IP addresses or location data
- Device identifiers or fingerprints
- Usage statistics or analytics

---

## Data Storage

The only data stored by reMD is your preference setting:

- **Auto Scan Setting:** A single boolean value (true/false) indicating whether you want the extension to automatically scan pages for Markdown content on load.

This preference is stored locally in your browser using Chrome's storage.sync API. It may sync across your Chrome browsers if you are signed in to Chrome, but it is never accessible to us or any third party.

---

## Data Processing

When you use reMD:

- The extension scans the current webpage's text content to detect Markdown patterns.
- All processing occurs entirely within your browser—no data is sent to external servers.
- Detected Markdown is rendered into formatted HTML and displayed locally.
- No webpage content is stored, cached, or transmitted anywhere.

---

## Third-Party Services

reMD does not use any third-party services, analytics tools, or external APIs. The extension operates completely offline after installation and does not make any network requests.

---

## Permissions Explained

reMD requires the following browser permissions:

| Permission | Purpose |
|------------|---------|
| **activeTab** | To access the current page's content for Markdown detection when you activate the extension. |
| **storage** | To save your Auto Scan preference setting locally. |
| **Host permissions (all URLs)** | To allow the extension to work on any website where you may encounter plain-text Markdown. |

These permissions are used solely for the extension's core functionality and not for data collection purposes.

---

## Remote Code

reMD does not load or execute any remote code. All code, including third-party libraries, is bundled within the extension package and reviewed as part of the Chrome Web Store submission process.

---

## Children's Privacy

reMD does not knowingly collect any information from anyone, including children under the age of 13. Since no data is collected, there are no special provisions needed for children's privacy.

---

## Changes to This Policy

If we make changes to this privacy policy, we will update the "Last Updated" date at the top of this page. We encourage you to review this policy periodically.

---

## Contact Us

If you have any questions or concerns about this privacy policy or the reMD extension, please contact us:

- **GitHub:** [https://github.com/Yorkian/reMD](https://github.com/Yorkian/reMD)
- **Issues:** [https://github.com/Yorkian/reMD/issues](https://github.com/Yorkian/reMD/issues)

---

*© 2025 reMD. All rights reserved.*
