# Inspect — Privacy Policy

_Effective date: April 17, 2026_

## Overview

Inspect is a browser extension that displays Counter-Strike 2 item prices from Steam, Skinport, and Waxpeer directly on your Steam inventory page. This policy explains what data the extension accesses and how it is handled.

## Data We Access

The extension reads the contents of your Steam Community inventory page (`steamcommunity.com`) to identify CS2 items and their properties (name, wear, tradability, etc.). This data is already publicly visible on your Steam profile and is processed entirely within your browser.

## Data We Store

The extension saves your preferences locally in `chrome.storage.local`:

- Language (English / Russian)
- Preferred marketplace (Steam, Skinport, or Waxpeer)
- Minimum price filter threshold
- Theme preference (light, dark, or system)
- Show/hide cents (kopecks) toggle

This data never leaves your device and is not transmitted to any server.

## Network Requests

The extension makes requests to public APIs to fetch current item prices:

- **Steam Community Market** — item pricing data
- **Skinport API** (`api.skinport.com`) — item pricing data
- **Waxpeer API** (`api.waxpeer.com`) — item pricing data
- **Currency API** (`latest.currency-api.pages.dev`) — USD/RUB exchange rate

These requests contain only item names — no personal identifiers, account credentials, or browsing history are sent.

## Third Parties

We do not share, sell, or transfer any user data to third parties. The API requests listed above are the only external communications made by the extension.

## Remote Code

The extension does not load or execute any remote JavaScript or WebAssembly code. All executable code is included in the extension package. External resources are limited to fonts and CSS stylesheets (`cdn.jsdelivr.net`, `fonts.googleapis.com`).

## Data Removal

Uninstalling the extension removes all locally stored preferences. No data remains on any external server.

## Contact

Questions about this policy can be sent to: `inspect.cs2.extension@gmail.com`
