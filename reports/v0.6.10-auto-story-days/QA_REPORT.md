# NIGHT LOOP v0.6.10-auto-story-days QA

Source commit: 6472d71671036e8ccff59b6dd9387ef0b2706cb2
EXE SHA256: CCF903E188743984E007B724E2EA9786912C028BAA4CAB0209427A8D357743E2
Test ZIP SHA256: AC5D3092E5015F6955A2005CF33E65BCE91DE885C103032A493BDD74C93E6357

Fixed completed-save camera restore and walking. Old v0.6.8 embedded pack reproduced camera misalignment and zero keyboard/joystick displacement; fixed production and isolated exported-pack checks show camera aligned, player visible, movement33.25/35 world pixels and unchanged narrative snapshot. Existing user save was not reset or overwritten.

Ordinary game at speed1:1.2 game minutes per real second,1200 seconds/full24-hour story day. Environment continues during menus, background focus and post-ending exploration. User explicitly selected automatic story dates: transactional GameSession.end_day advances1/2/3 and archives once. Dialogues/choices defer rollover until closed. No automatic new run, invented observations or simulator UI. Existing manual day ending and speed/skip APIs retained. Existing weather presets retained; no new automatic weather schedule.

40 regression PASS groups: input-routed three-day playthrough, completed-run movement/shop visits, full-day clock, automatic world events/dates, dialogue deferral, write-failure rollback/retry, final archive/reload. Native and isolated exported-PCK render checks passed for daily light/weather/surface samples and automatic story day2/day3/archive. Native Windows F11/preferences, embedded resource audit, EXE-only startup, extracted ZIP hashes/startup passed. Clock tests inject1200 elapsed seconds; a real20-minute wall-clock soak was not run.

No new image/font/dependency. Previous complete version folders preserved; v0.6.9 is the intermediate clock/fix snapshot before user selected automatic story dates. APK deferred; physical mobile, Steam depot and final commercial rights review pending. Publishing scope: QA text/hashes only; game source/art/binaries remain local.
