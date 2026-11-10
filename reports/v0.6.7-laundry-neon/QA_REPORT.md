# NIGHT LOOP v0.6.7-laundry-neon

Source: 46bca47afdb9d0a2897a6d275f9252e2bffd868d
EXE SHA256: 9EB3124A818EF528C6F951FD24D028CB0DF991B3552B0842A3673E1931C6E0EE
Test ZIP SHA256: 37313D06F620554454354AA58BA6B74766D06E2E2D35E4AA8600164C3AA62E86

Laundry sign now uses reusable BacklitTextSign: shared glyph mask, internally illuminated acrylic face/rim/halo shader, three native PointLight2D spill sources, and an emission-only viewport feeding the dedicated wet-pavement sign reflection. One independent laundry/sign intensity controls off/dimming/on; shared world time/save override retained. Main game and art review reuse the component. No new bitmap/font/external library. Previous size, room and story/save behavior retained.

Validation: 36 regression groups plus final sign/review checks, native F11/bounds/preference, isolated exported-EXE-pack native optics and bare EXE startup, embedded resource/portable ZIP/hash audit. With room lights OFF: sign off emission0, dim0.0865822574830474, on0.211031964809011; wet-floor on/off RGB delta0.0283261627373419; dry-floor delta0; wall delta from native PointLights alone0.0627261913777329. All optical outputs turn off together; interior/machine state stays independent.

This is stylized pixel optical rendering, not physical ray tracing. Laundry overall art remains provisional for later revision. Existing commercial provenance/clearance status retained. APK deferred; mobile hardware/Steam depot not run. Full source/art/EXE local; public GitHub QA text/hashes only.
