# Privacy Policy — TabOS

**Last Updated:** November 2026  
**Author:** Created by Sajjad Mohabati

TabOS respects your privacy completely.

## 1. Data Collection & Storage
- **Zero Telemetry / Zero Tracking:** TabOS does **not** collect, transmit, sell, or share any personal data, browsing history, bookmarks, notes, or analytics to any third-party server.
- **100% Local Storage:** All settings, custom wallpapers, notes, sticky notes, focus timer state, and cached icons are stored strictly locally on your device using Chrome's `storage.local` and `IndexedDB`.
- **Chrome Bookmarks Sync:** Bookmark operations read and write directly through Chrome's built-in `chrome.bookmarks` API, managed entirely by your browser.

## 2. Optional Network Requests
TabOS only makes external network requests when you explicitly use an online feature:
- **Search & AI Queries:** Navigating to the search engine or AI assistant you choose.
- **High-Resolution Site Icons:** Fetching website favicons for your bookmarks.
- **Speed Test Tool (On-Demand):** Only when you click "Start Test", measuring latency/throughput against Cloudflare's public speed test endpoints (`speed.cloudflare.com`).
- **Release Update Check:** Periodically checking public release metadata on GitHub (`api.github.com/repos/SajjadMohabati/tab-os-releases/releases/latest`) to notify you when a newer version of TabOS is available.

## 3. Contact
For questions or support regarding TabOS, please open an issue on [SajjadMohabati/tab-os-releases](https://github.com/SajjadMohabati/tab-os-releases).

---
*TabOS — Created by Sajjad Mohabati*
