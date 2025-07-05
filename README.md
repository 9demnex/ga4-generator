# GA4 Event Snippet Generator

A lightweight, self-hosted web tool to quickly generate Google Analytics 4 (GA4) event-tracking snippets for any clickable element on your site. Just choose your selector, fill in the event details, click “Generate,” and copy the ready-to-paste JavaScript snippet.

---

## Features

- **Selector Type**  
  Choose between ID (`#`) or Class (`.`) selectors via the dropdown.

- **Event Parameters**
- – **Element Selector** (e.g. `notification-button`)  
  – **Event Name** (e.g. `notification_click`)  
  – **Event Category** (e.g. `Notification Click`)  
  – **Event Label** (e.g. `Notification Tracker`)  
  – **Optional Numeric Value** (e.g. `1`)  

- **Auto-prefixing**  
  If you forget to include the leading `#` or `.`, the script will add it for you.

- **Dynamic Snippet Output**  
  Generates a self-contained, `DOMContentLoaded`-wrapped snippet that:
  1. Locates all matching elements  
  2. Attaches a `click` handler  
  3. Fires `gtag('event', …)` with your custom parameters  
  4. Logs a console warning if no elements or if `gtag` is unavailable

- **Responsive, Frosted-Glass UI**  
  Modern, dark-mode-friendly styling with blurred background, smooth transitions, and mobile support.

- **Dynamic Footer**  
  Always-up-to-date © year (`©2025 Strops Marketing, Inc. | All rights reserved.`) inserted on page load.

---
