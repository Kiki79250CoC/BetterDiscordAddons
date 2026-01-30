# Windows 10/11-ish Titlebar - Changelog
<sup>*Times are expressed in CET/CEST (UTC+1/+2) time.*</sup><br><sup>*[< Back to README](./)*</sup>

⚠️ *If you haven't restarted Discord since 22 January 2026, support for the old-newish classes will be removed on the 15 February, 2026.*

### 1.3.390 <sup><sub>*(30 January 2026)*</sub></sup>
- Fixed Help and Inbox buttons appearance.
- Fixed size of the Discord logo on the DM page.
- Added support for Back/Forward buttons.
- Seriously optimized CSS rules to reduce further processing time.

### 1.2.315 <sup><sub>*(24 January 2026)*</sub></sup>
- Updated theme to reflect the backpedalling of the class naming convention change because Discord devs are fucking incompetent dumpsters.
- Added support for Discord Web Client.
- Improved some internal localization-related stuff.

### 1.2.295 <sup><sub>*(22 December 2025)*</sub></sup>
- Replaced the attribute selectors for "platform-win" and "appMount" with a proper class name in an attempt to diminish the CSS process time.
- Improved logic to avoid conflict with overlapping elements from other themes like ClearVision v7.
  - Original tests were done on the version *1.0.9034* of the Discord client that did not support CSS nesting, something used by a fair amount of themes nowadays.
- Added French localization for theme stub loader version tooltip on the BD's Theme Settings page.

### 1.1.260 <sup><sub>*(18 December 2025)*</sub></sup>
- Updated theme to reflect change on Discord's internal class naming convention ("Class__xxx" → "xxx-class").

### 1.0.220 <sup><sub>*(16 October 2025)*</sub></sup>
- Fixed the Inbox button's icon when there is a badge over it.
- Removed old Inbox code that was marked as "old" in 1.0.215.

### 1.0.215 <sup><sub>*(11 September 2025)*</sub></sup>
- Fixed the inbox button because Discord decided to be annoying.
- Reverted the position adjustment from 1.0.200.

### 1.0.210 <sup><sub>*(11 June 2025)*</sub></sup>
- Updated theme to reflect change on Discord's structure (sorry if it took time, only restarted my clients today for applying Windows updates).

### 1.0.205 <sup><sub>*(12 May 2025)*</sub></sup>
- Optimized code to reduce CSS node footprint.
- Modified icon mask to use newer CSS implementations on newer versions of the client.
  - Old -webkit- prefixed implementation is kept for compatibility with older clients.
- Other internal changes.

### 1.0.200 <sup><sub>*(09 May 2025)*</sub></sup>
- Added close button active state color.
- Improved loader infos to display on the card only if the theme itself is activated by the Stub Loader, and not via `@import`.
- Adjusted position of the title bar to always appear on top of everything.
- Adjusted title bar icon scale to always be 1.
- Updated readme to include example of third-party themes that are compatible.

### 1.0.196 <sup><sub>*(08 May 2025)*</sub></sup>
- Fixed regression of the inbox button's active state when opened.

### 1.0.195 <sup><sub>*(08 May 2025)*</sub></sup>
- Optimized method used to affect buttons.
  - This should cover all buttons now.
- Optimized SVG icons.
- Slightly reorganized code.

### 1.0.190 <sup><sub>*(02 May 2025)*</sub></sup>
- Initial release.

-----

Copyright © 2025-2026 AstragonQC<br><sup>All rights reserved.</sup>