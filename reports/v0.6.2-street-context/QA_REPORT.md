# NIGHT LOOP v0.6.2-street-context QA

Production game review build. User-approved v0.6.1 bookshop exterior/assets, interior, scale data and visual code are locked: 7 source files unchanged, image byte hashes and normalized text comparison passed. Prior completed versions preserved.

Root causes: cafe baked context and local separate background overlapped; bookshop wall patches used nonuniform scale; cafe and bookshop walls used different material grading; existing full-map panorama was enlarged at 1.414 versus cafe art scale 0.287; fixed skies/local tint interfered with the latest weather sky.

Existing full-map skyline is reused as a distant geometry-masked layer at cafe pixel scale. New image_gen transparent midground neighborhood is a separately replaceable layer pending visual acceptance. Uniform cafe-source boundary walls use the exact cafe facade shader and shared environment frame. One sky owns the latest clear/cloud/rain palette, shared with legacy DaylightBand through SkyPalette include. No baked sky/day-image crossfade overlays it. Cafe context is masked without replacing its source art. Background windows have separate time/manual channels; manual background overrides are not persisted yet.

Source commit: ea94b1613082f49a9c17e3cc8d413409fa4779ae
EXE SHA256: BC4E61645207EE540FFC13449F7FC3C0B890D6602A04B4888DBD376CE9C567B6
Test ZIP SHA256: E46621A94150D0D1202340F83BCC9A750395B80E1C356268DC699869FD6FB39D

31 automated groups passed, including routed 3-day input playthrough, environment/save regression, shared context/weather and bookshop locks. Native same-source wall-patch luma ratio bookshop/cafe changed from 2.822 to 0.998 (small matched samples, not whole-screen brightness). Protected bookshop room/door RGB difference is 0; sign mean summed RGB difference 0.003775. Latest sky native clear/rain brightness ratio is 1.992. Windows F11, embedded-pack audit, portable startup, extracted ZIP hashes/startup and actual standalone EXE native rendering passed.

Pending: new midground art/height/placement visual approval, other front-shop art, mobile device performance, Steam depot and commercial clearance. Existing bookshop art approval does not constitute rights clearance. One new generated midground has prompt, source/output hashes and retained original bytes documented locally. No unknown external media/library introduced. APK deferred; manual native full playthrough not run.

Publication scope: QA text and hashes only. No source, artwork or executable uploaded.
