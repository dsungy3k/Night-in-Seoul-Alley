# NIGHT LOOP v0.6.13-camera-range QA

Source: 418bbb122bf12861408c935d04ac2f98c10372cf
EXE SHA256: 199288A0A5E1A460DA95C66D1D9AD87287DA9103CF99909F1BC9532FA2F2E985
ZIP SHA256: 673A143DE2600A93F17734261CAA38235B4B73EBB8408DE4D556CAAF62B8CC2F

Ordinary game menu/settings exposes persisted1x..5x reduction (camera_scale1.0..0.2), closer/wider, direct reset and max shortcut. Art, world coordinates, proportions, movement and CanvasLayer UI scale remain unchanged at1x. Bottom-anchored framing keeps existing pavement in frame; existing world-coordinate sky extended toY-4000. At16:9 max view2400x1350 world units. Rain covers actual camera rectangle, native shadow receiver/lookup width follows view(2400 at max).5x is a wide overview with small street content and a large sky area, not new scenery generation.

43 regression PASS groups: settings/reload/failed-write rollback, invalid scale rejection, world/art invariance, reset, full routed3-day gameplay and existing systems. Native source and isolated exported-PCK1x/2x/5x/rain-day/settings passed. Actual Windows F11/preferences, embedded-pack audit, EXE-only startup and extracted ZIP hashes/startup passed.

No new bitmap/font/library. Asset production remains1x. Existing commercial provenance status retained. APK deferred; physical mobile performance/Steam depot not tested. QA text/hashes only public; source/art/binary remain local.
