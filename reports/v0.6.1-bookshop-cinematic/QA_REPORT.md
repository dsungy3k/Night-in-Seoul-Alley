# NIGHT LOOP v0.6.1-bookshop-cinematic QA

Actual production game, no simulation launcher required. Bookshop retains the compact flat-roof/ivy/wide-left-window/right-door/sign/book-display identity from v0.5.0-art-preview cell 2 and is regenerated using the approved cafe art as style reference. Uniform scale 0.225, grounded at Y210; door aperture 86.4 world pixels versus cafe 80.34. Story, dialogue, observation triggers and save schema retained.

One continuous layered room (bookshelves back / actor / transparent foreground) is sampled by separate window and doorway captures. Door frame, glass/leaf, roof, sign board and localized sign text are separately controlled. Six native PointLight2D channels use the shared clock/weather policy and persisted overrides. Shared wet cafe pavement receives actual bookshop window/door textures plus independent exterior-light values; no painted door interior is used. Bookshop sidewalk depth extends to Y250. Original completed versions are preserved.

Source commit: 002d55fcd0331ca2de840ccfd504974d2a73af06
EXE SHA256: 81768AECF8C046EA746D9ED9A74E741C0773EC88304C9BB1852C7E8A8A0E1773
Test ZIP SHA256: 50DFD1A290E7C931119B19777DC2642C84A12827856E04E8C79C1743BDAB1505

30 automated verification groups passed, including routed 3-day playthrough, six independent light channels, room continuity, live reflection bindings, door movement, saved light overrides and walking depth. Native captures verify window/door/pavement on-off RGB changes, left-versus-right lamp changes, door leaf movement, daytime/weather and cafe comparison. Windows F11 transitions, portable EXE startup, embedded-pack audit, extracted ZIP hashes and startup passed.

AI art generated/edited using built-in image_gen. Four prompts, originals, source hashes and inherited rights status are stored locally. No unknown external sprites/fonts/libraries. Remaining: user visual acceptance, individual small book/ivy/exterior-prop cutouts, other shops, final day/background artwork, mobile device performance, Steam depot and commercial clearance. APK deferred. Manual native full playthrough not run.

Publication scope: QA text and hashes only; no source, art or executables uploaded.
