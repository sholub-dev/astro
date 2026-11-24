---
'@astrojs/rss': patch
---

Fixes `customData` values being converted to numbers, so `<itunes:episode>007</itunes:episode>` or `<itunes:duration>1.10</itunes:duration>` are no longer written as `7` and `1.1`
