# v0.5.0 cafe baseline review — 2026-11-10

Local review commit: 46ef8f71f78bc011b03a1c350d4a9e9532f18c7f.

Development runtime scripts/assets/data/scenes/project settings restored to the v0.5.0-art-preview source. Both v0.5.0 and v0.5.1 release folders and EXEs are preserved and their existing recorded hashes still match. v0.5.1 implementation is not the basis for this review.

Read-only disposable Windows render review confirmed:
- Exterior cafe.png is a flattened 1672x941 plate containing structure, upper rooms/windows, exterior fixtures/glow, side walls, midground houses and painted pavement reflections.
- The first-floor room is separately composited from master_v1/cafe_interior_v1.png back/front regions, with an independent NPC. Room lamps and wall glow are painted into those images.
- The door independently opens via a cropped/scaled door region; NPC exterior/interior handoff works.
- Pavement uses cafe.png region (0,752,1672,189). The dominant amber reflections remain after code effects are hidden and after lights_on=false. There is no connected tile-material/PointLight2D/normal-map reflection system.
- Extra light/reflection drawing exists, but its visibility does not remove painted source glow.
- No save or story state changed.

Four user-supplied storefront references (laundry, florist, home, bookshop), each 1672x941, are visually compatible in palette/viewpoint/ground level. They are flattened artwork, not independently layered assets. Their pavements must NOT be used: extend the existing cafe pavement instead. Keep the cafe appearance unchanged. Preserve the supplied building silhouettes; use a shared, separately replaceable boundary-wall system and cafe-based distant/midground background. Exact contour masks, wall joins and pavement seams require further work. Individual window/fixture switching requires matching masks/off-state material; adding nodes alone cannot separate painted light.

Recommendation only: review a one-store connection preview before broader integration. No reference art replacement, regeneration or new game build was performed. Public upload is this report only; supplied artwork/source/saves/binaries remain local. Commercial-rights status of provided inputs was not newly approved.
