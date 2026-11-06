# Simply IPTV — Google Play graphics

Upload the three PNG files individually in Play Console → Store presence → Main store listing → Graphics.

| File | Play Console field | Dimensions | Encoding | File size |
| --- | --- | --- | --- | --- |
| `simply-iptv-logo-512.png` | App icon | 512 × 512 | 32-bit RGBA PNG | 233,528 bytes |
| `simply-iptv-tv-banner-1280x720.png` | Android TV banner | 1280 × 720 | 24-bit RGB PNG, no alpha | 715,380 bytes |
| `simply-iptv-feature-graphic-1024x500.png` | Feature graphic | 1024 × 500 | 24-bit RGB PNG, no alpha | 482,717 bytes |

The app icon is below Google's 1,024 KB maximum. It has a full square background; Google Play applies the display mask. The TV banner is a store-listing upload, separate from the lower-resolution launcher banner bundled in the APK.

Suggested alt text:

- **App icon:** Simply IPTV wordmark in white and cyan, enclosed by a cyan rounded rectangle on midnight navy.
- **TV banner:** Simply IPTV in white and cyan within a cyan outlined panel on midnight navy.
- **Feature graphic:** Simply IPTV beside cyan outlined cards representing broadcasting, playback, and favourites.

`masters/` contains the unmodified high-resolution generated artwork. `PROMPTS.md` records the exact generation prompts. The three upload exports were resized with high-quality bicubic resampling, with a subpixel central crop on the landscape artwork to achieve exact aspect ratios without stretching. The approved logo/banner have also been adopted for launcher icons, splash/setup artwork, TV/Watch Next fallback banners, and the README banner. Regenerate those app assets using `scripts/Export-BrandAssets.ps1` from the repository root.

Created with the built-in image-generation tool using the project's existing banner and splash logo as references. Branding follows the project's navy, white, and cyan palette. The feature graphic is abstract promotional artwork, not an app screenshot.

Requirements checked against [Google Play preview asset requirements](https://support.google.com/googleplay/android-developer/answer/9866151?hl=en). This package covers graphics only; actual app screenshots and other listing fields are separate requirements.
