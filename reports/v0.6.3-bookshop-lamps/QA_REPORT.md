# NIGHT LOOP v0.6.3-bookshop-lamps QA

Actual production game audit: native lights and live reflections already responded, but pendant halos were above the visible undersides, leaving the black bulb aperture visually unlit. Added a separate code-authored emitter surface and aligned native light/halo anchors. Right indoor desk lamp remains partly occluded by the lower wooden door leaf; opening the door reveals the full lamp. Desk energy scale reduced to0.65 and its anchor aligned. External wall lantern independently responds and was retained.

Approved bookshop original7-file lock, approved midground/walls and latest weather sky retained. No new bitmap, font or third-party library.

Source commit: e5e908666a88a0e61280a49afe7abcc3db3a270d
EXE SHA256: 1A87B1019FE41F336AEF53CCFB16561284980F225826B4644DFD45805B0B7F7A
Test ZIP SHA256: 6E2DC3E4993140D536C51A4C7CEA3B500AE693893EC894482B490FEEE081D75D

32 automated groups passed. Native pendant underside sample luma gain3.430/3.622; all-OFF sample before/after RGB delta0; desk shade luma ratio0.914; desk-only/external-lantern-only/floor reflection responses passed. Dim/master-off state propagation and approved source locks passed. Window-mode, embedded-pack audit, extracted ZIP hashes/startup and native standalone EXE startup passed.

Mobile device, Steam depot, manual native full playthrough and commercial clearance remain pending. APK deferred. Public scope: QA text and hashes only; no source/art/executable upload.
