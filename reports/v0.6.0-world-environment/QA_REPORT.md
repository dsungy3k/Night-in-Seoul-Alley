# NIGHT LOOP v0.6.0-world-environment QA

Production game default entry now owns shared clock, weather, lighting, wetness, shaders and per-building reflection bindings. No simulation launcher is required. Clock appears below the date card; each story date starts randomly at 18:45–19:15. Clock color rules: morning sky blue, day orange, rainy day/night navy. Speed and event skip APIs are available; checkpoints preserve clock, weather, wetness and light overrides. Full 3072-wide street uses approved cafe neutral pavement.

Source commit: a13437d5a8f7cb9c3ae5f4c2abb0bca3fa6a63c2
EXE SHA256: 365344116BAF6638CECD81D45E57D3004C28A4E94D9F83E1F4D4F71BC29964AF
Test ZIP SHA256: 8313DE73DB148EAEF51C0810E3234DE90E8317DE56DDE15DCA2F06E5ED78B808

29 automated verification groups passed, including routed 3-day input playthrough, save/reload compatibility and failed-save rollback. Native production captures cover four badge modes, dates 1–3, bookshop reflection binding and full-street pavement. Native Windows F11 transitions and saved window preference passed. Embedded pack audit, portable EXE startup, extracted ZIP hashes and startup passed.

Remaining: other shop artwork/interiors and independent external/door light layers, final background/day artwork, mobile device performance. APK deferred; Steam depot and manual native full playthrough not run. Existing commercial rights review status retained; no new external media. Prior complete version folders preserved.

Publication scope: QA text and hashes only; no game source, art or executables uploaded.
