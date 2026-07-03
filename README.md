# DataZen launch package

Deploy the complete contents of this folder to the web root.

Required files:
- index.html
- datazen-promo-updated.html
- datazen-promo-animation.html
- assets/

This package contains only production files. Large page artwork and the live-preview video are external, cacheable assets rather than embedded data payloads.

The promo section uses `assets/datazen-promo.mp4`, a 1600×900, 38-second H.264 video rendered from `datazen-promo-animation.html`. It is muted, loops, and begins when the section scrolls into view.
