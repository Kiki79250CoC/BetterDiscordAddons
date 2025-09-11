# Windows 10/11-ish Titlebar - Changelog
<sup>*Times are expressed in CET/CEST (UTC+1/+2) time.*</sup>

### 1.0.215 <sup>(11 September 2025)</sup>
- Fixed the inbox button because Discord decided to be annoying.
- Reverted the position adjustment from 1.0.200.

### 1.0.210 <sup>(11 June 2025)</sup>
- Updated theme to reflect change on Discord's structure (sorry if it took time, only restarted my clients today for applying Windows updates).

### 1.0.205 <sup>(12 May 2025)</sup>
- Optimized code to reduce CSS node footprint
- Modified icon mask to use newer CSS implementations on newer versions of the client.
  - Old -webkit- prefixed implementation is kept for compatibility with older clients.
- Other internal changes

### 1.0.200 <sup>(09 May 2025)</sup>
- Added close button active state color
- Improved loader infos to display on the card only if the theme itself is activated by the Stub Loader, and not via @import
- Adjusted position of the title bar to always appear on top of everything
- Adjusted title bar icon scale to always be 1
- Updated readme to include example of third-party themes that are compatible

### 1.0.196 <sup>(08 May 2025)</sup>
- Fixed regression of the inbox button's active state when opened

### 1.0.195 <sup>(08 May 2025)</sup>
- Optimized method used to affect buttons
  - This should cover all buttons now
- Optimized SVG icons
- Slightly reorganized code

### 1.0.190 <sup>(02 May 2025)</sup>
- Initial release

-----

Copyright © 2025 AstragonQC<br><sup>All rights reserved.</sup>