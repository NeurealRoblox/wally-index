# NeuLibs release changelog

Newest first; one entry per publish wave. Auto-appended by the repo's
`scripts/publish` (release train). Machine-readable mirror: `releases.json`.

<!-- waves -->
## 2026-08-11 20:05 UTC

- `neurealroblox/ui-core@0.2.2`
- `neurealroblox/ui-reveal@0.5.1`
- `neurealroblox/ui-styled@0.8.1`
- `neurealroblox/ui-world-stage@0.2.1`
- `neurealroblox/ui-class-select@0.5.1`
- `neurealroblox/ui-modal@0.6.1`
- `neurealroblox/ui-results@0.4.1`
- `neurealroblox/ui-skill-tree@0.9.1`
- `neurealroblox/ui-slots@0.7.1`
- `neurealroblox/ui-loadout@0.5.1`
- `neurealroblox/ui-bundle@0.2.26`

Core.Diagnostics: one switch to silence or route every warning the UI kit prints; adopted by nine packages

## 2026-08-11 19:43 UTC

- `neurealroblox/ui-reveal@0.5.0`
- `neurealroblox/ui-bundle@0.2.25`

ui-reveal 0.5.0: container open duration is a dial, its removal derives from it, and onContainerOpened/keepContainer hand the container to the game

## 2026-08-11 17:02 UTC

- `neurealroblox/neurhythm@0.6.0`
- `neurealroblox/ui-styled@0.8.0`
- `neurealroblox/ui-achievements@0.5.0`
- `neurealroblox/ui-battlepass@0.4.0`
- `neurealroblox/ui-class-select@0.5.0`
- `neurealroblox/ui-daily-rewards@0.4.0`
- `neurealroblox/ui-hud@0.4.0`
- `neurealroblox/ui-leaderboards@0.5.0`
- `neurealroblox/ui-lobby-nav@0.4.0`
- `neurealroblox/ui-menu-window@0.6.0`
- `neurealroblox/ui-modal@0.6.0`
- `neurealroblox/ui-player-stats@0.5.0`
- `neurealroblox/ui-quest-tracker@0.4.0`
- `neurealroblox/ui-results@0.4.0`
- `neurealroblox/ui-settings@0.4.0`
- `neurealroblox/ui-skill-tree@0.9.0`
- `neurealroblox/ui-slots@0.7.0`
- `neurealroblox/ui-store@0.5.0`
- `neurealroblox/ui-loadout@0.5.0`
- `neurealroblox/ui-bundle@0.2.24`

ui-styled 0.8.0: Panel honours a contentBox on unsliced art (rendered suite 800/0); neurhythm 0.6.0: the headroom warning measures the knob it names

## 2026-08-11 16:21 UTC

- `neurealroblox/telemetry@0.6.0`
- `neurealroblox/server-bundle@0.1.14`

## 2026-08-11 00:40 UTC

- `neurealroblox/server-bundle@0.1.13`

## 2026-08-11 00:39 UTC

- `neurealroblox/telemetry@0.5.0`

## 2026-08-09 01:50 UTC

- `neurealroblox/telemetry@0.4.0`
- `neurealroblox/server-bundle@0.1.12`

## 2026-08-09 00:10 UTC

- `neurealroblox/telemetry@0.3.1`
- `neurealroblox/server-bundle@0.1.11`

## 2026-08-08 20:09 UTC

- `neurealroblox/telemetry@0.3.0`
- `neurealroblox/server-bundle@0.1.10`

## 2026-08-08 14:45 UTC

- `neurealroblox/leader-election@0.2.1`
- `neurealroblox/matchmaker@0.2.1`
- `neurealroblox/player-data@0.2.1`
- `neurealroblox/server-bundle@0.1.9`

The review fixes that lived in Roblox-only shells are now pure, Lune-tested modules: lease.luau, session-rules.luau, registration.luau. No behaviour change.

## 2026-08-08 14:38 UTC

- `neurealroblox/telemetry@0.2.1`
- `neurealroblox/server-bundle@0.1.8`

telemetry 0.2.1 republishes without a scratch file that 0.2.0 shipped; the publisher now refuses stray files at a package root.

## 2026-08-08 06:41 UTC

- `neurealroblox/daily-rewards@0.2.0`
- `neurealroblox/leader-election@0.2.0`
- `neurealroblox/matchmaker@0.2.0`
- `neurealroblox/player-data@0.2.0`
- `neurealroblox/telemetry@0.2.0`
- `neurealroblox/server-bundle@0.1.7`

Second-pass review remediation: daily-reward double grant, migration mutating an adapter's live table, leaked adapter sessions and stale dirty flags, simultaneous leaders on renewal failure, matchmaker ghost queues, telemetry backfill double-counting and a lost 413.

## 2026-08-08 00:45 UTC

- `neurealroblox/ui-theme@0.3.0`
- `neurealroblox/ui-tooltip@0.3.0`
- `neurealroblox/ui-topbar-icon@0.3.0`
- `neurealroblox/ui-blur@0.2.0`
- `neurealroblox/ui-gamepad@0.2.0`
- `neurealroblox/ui-killfeed@0.2.0`
- `neurealroblox/ui-notifications@0.2.0`
- `neurealroblox/ui-reveal@0.4.0`
- `neurealroblox/ui-styled@0.7.0`
- `neurealroblox/ui-viewport-character@0.2.0`
- `neurealroblox/ui-world-stage@0.2.0`
- `neurealroblox/ui-achievements@0.4.0`
- `neurealroblox/ui-battlepass@0.3.0`
- `neurealroblox/ui-class-select@0.4.0`
- `neurealroblox/ui-daily-rewards@0.3.0`
- `neurealroblox/ui-hud@0.3.0`
- `neurealroblox/ui-leaderboards@0.4.0`
- `neurealroblox/ui-lobby-nav@0.3.0`
- `neurealroblox/ui-menu-window@0.5.0`
- `neurealroblox/ui-modal@0.5.0`
- `neurealroblox/ui-player-stats@0.4.0`
- `neurealroblox/ui-quest-tracker@0.3.0`
- `neurealroblox/ui-results@0.3.0`
- `neurealroblox/ui-settings@0.3.0`
- `neurealroblox/ui-skill-tree@0.8.0`
- `neurealroblox/ui-slots@0.6.0`
- `neurealroblox/ui-store@0.4.0`
- `neurealroblox/ui-loadout@0.4.0`
- `neurealroblox/ui-bundle@0.2.23`

UITheme.extend now drops panel tokens that described a retargeted image (chromeSlice/closeChrome* siblings), the same rule Variants.mergeInto got. ui-tooltip and ui-topbar-icon join the text contract. BREAKING for themes relying on stale panel geometry.

## 2026-08-07 16:41 UTC

- `neurealroblox/ui-styled@0.6.0`
- `neurealroblox/ui-achievements@0.3.0`
- `neurealroblox/ui-battlepass@0.2.0`
- `neurealroblox/ui-class-select@0.3.0`
- `neurealroblox/ui-daily-rewards@0.2.0`
- `neurealroblox/ui-hud@0.2.0`
- `neurealroblox/ui-leaderboards@0.3.0`
- `neurealroblox/ui-lobby-nav@0.2.0`
- `neurealroblox/ui-menu-window@0.4.0`
- `neurealroblox/ui-modal@0.4.0`
- `neurealroblox/ui-player-stats@0.3.0`
- `neurealroblox/ui-quest-tracker@0.2.0`
- `neurealroblox/ui-results@0.2.0`
- `neurealroblox/ui-settings@0.2.0`
- `neurealroblox/ui-skill-tree@0.7.0`
- `neurealroblox/ui-slots@0.5.0`
- `neurealroblox/ui-store@0.3.0`
- `neurealroblox/ui-loadout@0.3.0`
- `neurealroblox/ui-bundle@0.2.22`

ui-styled: retargeting a variant's image now drops the previous image's geometry (contentBox/imageRect/slice), which was being applied to different art. Also: ui-skill-tree's extent floor is in design px. BREAKING for reskinned variants.

## 2026-08-07 16:13 UTC

- `neurealroblox/ui-responsive@0.2.0`
- `neurealroblox/ui-achievements@0.2.0`
- `neurealroblox/ui-class-select@0.2.0`
- `neurealroblox/ui-hud@0.1.14`
- `neurealroblox/ui-leaderboards@0.2.0`
- `neurealroblox/ui-menu-window@0.3.0`
- `neurealroblox/ui-modal@0.3.0`
- `neurealroblox/ui-player-stats@0.2.0`
- `neurealroblox/ui-quest-tracker@0.1.8`
- `neurealroblox/ui-skill-tree@0.6.0`
- `neurealroblox/ui-slots@0.4.0`
- `neurealroblox/ui-store@0.2.0`
- `neurealroblox/ui-loadout@0.2.0`
- `neurealroblox/ui-bundle@0.2.21`

One canvas: every ui-responsive profile now references 640x360 (the smallest supported device) with a legibility floor that means 11 real px everywhere. BREAKING for menu surfaces authored against 720x405.

## 2026-08-07 04:58 UTC

- `neurealroblox/ui-text-fit@0.3.0`
- `neurealroblox/ui-core@0.2.1`
- `neurealroblox/ui-killfeed@0.1.7`
- `neurealroblox/ui-notifications@0.1.7`
- `neurealroblox/ui-reveal@0.3.4`
- `neurealroblox/ui-styled@0.5.30`
- `neurealroblox/ui-achievements@0.1.16`
- `neurealroblox/ui-class-select@0.1.8`
- `neurealroblox/ui-leaderboards@0.1.16`
- `neurealroblox/ui-player-stats@0.1.3`
- `neurealroblox/ui-skill-tree@0.5.9`
- `neurealroblox/ui-slots@0.3.6`
- `neurealroblox/ui-loadout@0.1.5`
- `neurealroblox/ui-bundle@0.2.20`

on-screen DIP legibility floor + per-label floors for sub-fields

## 2026-08-07 00:55 UTC

- `neurealroblox/ui-text-fit@0.2.3`
- `neurealroblox/ui-core@0.2.0`
- `neurealroblox/ui-reveal@0.3.3`
- `neurealroblox/ui-styled@0.5.29`
- `neurealroblox/ui-viewport-character@0.1.4`
- `neurealroblox/ui-world-stage@0.1.3`
- `neurealroblox/ui-achievements@0.1.15`
- `neurealroblox/ui-battlepass@0.1.10`
- `neurealroblox/ui-class-select@0.1.7`
- `neurealroblox/ui-daily-rewards@0.1.8`
- `neurealroblox/ui-hud@0.1.13`
- `neurealroblox/ui-leaderboards@0.1.15`
- `neurealroblox/ui-lobby-nav@0.1.5`
- `neurealroblox/ui-menu-window@0.2.8`
- `neurealroblox/ui-modal@0.2.5`
- `neurealroblox/ui-player-stats@0.1.2`
- `neurealroblox/ui-quest-tracker@0.1.7`
- `neurealroblox/ui-results@0.1.8`
- `neurealroblox/ui-settings@0.1.6`
- `neurealroblox/ui-skill-tree@0.5.8`
- `neurealroblox/ui-slots@0.3.5`
- `neurealroblox/ui-loadout@0.1.4`
- `neurealroblox/ui-bundle@0.2.18`

ui-core 0.2.0: the overflow contract is ON by default; TextFit.initial; legibility floor 11

## 2026-08-06 23:37 UTC

- `neurealroblox/ui-text-fit@0.2.2`
- `neurealroblox/ui-reveal@0.3.2`
- `neurealroblox/ui-class-select@0.1.6`
- `neurealroblox/ui-player-stats@0.1.1`
- `neurealroblox/ui-skill-tree@0.5.7`
- `neurealroblox/ui-slots@0.3.4`
- `neurealroblox/ui-loadout@0.1.3`
- `neurealroblox/ui-bundle@0.2.16`

TextFit.initial: a monogram is a character, not a byte -- fixes tofu/empty initials for non-ASCII names across 6 packages

## 2026-08-05 16:35 UTC

- `neurealroblox/ui-reveal@0.3.1`
- `neurealroblox/ui-styled@0.5.28`
- `neurealroblox/ui-achievements@0.1.14`
- `neurealroblox/ui-class-select@0.1.5`
- `neurealroblox/ui-leaderboards@0.1.14`
- `neurealroblox/ui-store@0.1.1`
- `neurealroblox/ui-loadout@0.1.2`
- `neurealroblox/ui-bundle@0.2.15`

## 2026-08-05 07:01 UTC

- `neurealroblox/ui-reveal@0.3.0`

The 3D subject now needs no assets at all. Subject3D.model was mandatory, so a game without an egg mesh got a reveal that rendered nothing -- the same mistake the card made before its monogram fallback. It is optional now, with a chest built from two blocks and a stock R15 dummy from a blank HumanoidDescription rather than a web call that can fail. That removed a dependency I had assumed was unavoidable: parts can be animated by arithmetic, so the default container opens with no animation asset, no Animator and no upload, while the marker-driven sequencer stays for games that have an animator. Three things only a screenshot could have caught: two Ball parts read as a SNOWMAN rather than a cracked shell, so chest is the default and egg needs a real mesh; the lid detached and floated above the box because it rotated about its own centre, so hatch now returns a pivot and the lid turns about its back edge; and a head-on camera cannot see a lid hinge backward, so at 70 percent open the box looked shut -- framing is three-quarter and elevated now. The last one also broke two tests that were asserting the old mechanism, and those were rewritten to the property that survives rather than relaxed to fit.

## 2026-08-05 05:47 UTC

- `neurealroblox/ui-reveal@0.2.1`

The reveal card, redesigned against a photograph rather than an assertion. v1 drew a flat grey rectangle and never rendered the item icon at all -- subject.icon was accepted, carried through, and referenced zero times -- and it passed every check it had, because those checks asserted a card existed and arrived on time, which a grey box does perfectly. Nothing in this repo could SEE a ScreenGui (studio-mcp's screen_capture is the 3D viewport only), so this ships the missing half of the loop as well: a plugin mounts the cards into CoreGui in Edit mode and PrintWindow photographs the window's own content, no playtest and no focus needed. Looking caught six things no assertion would: tiers rendering alphabetically, a glow whose layers you could count, cards clipping their own names, burst rays escaping onto neighbours, dead space in the composition, and 'JACKPOTI' -- letterspacing had orphaned the exclamation mark into a capital I on the payoff line of the best tier in the game. The card now reads its tier before any text does: size, glow depth, stroke weight and ornament all ride the rank, the item is the hero with a monogram fallback rather than an empty square, and Common deliberately gets almost no glow because a grey glow is a smudge.

## 2026-08-05 05:04 UTC

- `neurealroblox/ui-director@0.2.0`
- `neurealroblox/ui-reveal@0.2.0`

The dials drive something now. ui-director 0.2.0: post beats RAMP instead of snapping (an instant set reads as a rendering glitch); shake actually moves the camera, with the base CFrame captured ONCE so the offset cannot feed back into itself and walk the camera across the scene; pushIn is an FOV move rather than a translation, so it reads as leaning in from any pose and cannot clip geometry; and dilate is a real seam, because there is no safe global -- slowing the simulation changes the game for every player -- so time is now { set, restore } like the camera and granting true no longer works. That last one is breaking, hence the minor. ui-reveal 0.2.0 wires the tier table to renderers that were reading nothing: the telegraph aura (tier-coloured, during the build, Rare and above only, because an aura that fires every time is not a telegraph), shockwave sized by the dial, rays by rayCount/rayLength/halo, overshoot only above 1.0, and a shine sweep -- all through the existing ui-animation helpers rather than reinvented, and all in the tier's own hue so the colour the build promises is the colour the payoff keeps. Verified in a live DataModel: 18 checks green, including that a legendary builds its aura DURING the build and that a common does not.

## 2026-08-05 04:13 UTC

- `neurealroblox/ui-director@0.1.0`
- `neurealroblox/ui-reveal@0.1.0`
- `neurealroblox/ui-styled@0.5.27`

Reveals become directed scenes. ui-director 0.1.0 is new and is the piece the kit never had: camera, post-processing and time as beats the GAME grants per call and that are always put back. It never pauses the world and never asks whether it is paused -- one scene description plus a grant, so the same title plays the full scene in the lobby and a self-contained overlay mid-combat through one code path, and an empty grant still yields a working scene. The camera is a seam rather than a boolean, and a half-built seam counts as absent. A ledger records the value it found and restores it on completion, skip, error, destruction and a watchdog; shake is trauma rather than a tween, scaling with trauma squared and decaying per second. ui-reveal 0.1.0 is chest and egg openings on one timeline with two presenters. Two laws carry most of the feel and both are nearly free: the first second is IDENTICAL across every tier, so a big pull announces itself by not stopping where a common would have; and cheap outcomes stay cheap in TIME (2.7s for a common against 9.6s for a legendary, against a shipped implementation that ran 4.0s for everything). Plus 350ms of stillness before the break, and rarity telegraphed before identity. Effects declare their layer, so a particle burst that a ViewportFrame cannot draw is refused at config time instead of silently rendering nothing, and animation is marker-driven rather than timed. ui-styled 0.5.27 warns when a variant declares the legacy image shorthand next to a states table -- the states table wins and the shorthand is never read, which cost this repo 21 red assertions written off as a baseline for weeks.

## 2026-08-03 20:52 UTC

- `neurealroblox/neurhythm@0.5.0`
- `neurealroblox/telemetry@0.1.3`
- `neurealroblox/ui-animation@0.3.4`
- `neurealroblox/ui-styled@0.5.26`

Motion presets reach the whole kit, buttons react instead of lerping, roles carry sound, and Neurhythm joins as an adaptive-audio package. ui-animation 0.3.4 routes all 24 juice helpers through the motion signature (a preset is a skin, so partial reach is no reach) and adds loopTween, which gives a loop a signature WITHOUT letting the budget shorten its period -- shortening a loop speeds a spinner up. ui-styled 0.5.26 adds pressMotion, a squash-peak-settle reaction composed with the hover state on ONE UIScale, plus a sound-cue vocabulary that fires OUTSIDE the motion gate (reduced motion is a vestibular accommodation, not a request for silence). neurhythm 0.5.0 is new: intensity-driven stem mixing, and stem balance is now supplied as MEASURED loudness rather than a hand-computed scalar. telemetry 0.1.3 is a typecheck fix only.

## 2026-08-03 18:08 UTC

- `neurealroblox/telemetry@0.1.2`

Removes infrastructure specifics from the published README and documents the integrator/administrator permission split.

## 2026-08-03 17:58 UTC

- `neurealroblox/telemetry@0.1.1`

priceFor seam and price_source on purchase rows: a receipt with no amount no longer silently zeroes revenue.

## 2026-08-03 06:13 UTC

- `neurealroblox/server-bundle@0.1.5`

Adds neurealroblox/telemetry to the server bundle.

## 2026-08-03 06:12 UTC

- `neurealroblox/telemetry@0.1.0`

Portable game telemetry: batched egress to a queryable store, teleport-continuous sessions, heartbeat playtime, credential from the Roblox Secrets Store.

## 2026-07-30 18:20 UTC

- `neurealroblox/ui-core@0.1.15`
- `neurealroblox/ui-styled@0.5.25`
- `neurealroblox/ui-bundle@0.2.14`

## 2026-07-30 17:38 UTC

- `neurealroblox/ui-core@0.1.14`
- `neurealroblox/ui-bundle@0.2.13`

## 2026-07-30 17:10 UTC

- `neurealroblox/leaderboards@0.1.3`
- `neurealroblox/regions@0.1.1`
- `neurealroblox/player-data@0.1.1`
- `neurealroblox/ui-animation@0.3.3`
- `neurealroblox/ui-localization@0.1.1`
- `neurealroblox/ui-responsive@0.1.8`
- `neurealroblox/ui-screen-manager@0.1.2`
- `neurealroblox/ui-theme@0.2.1`
- `neurealroblox/cleanup@0.1.1`
- `neurealroblox/ui-blur@0.1.1`
- `neurealroblox/ui-core@0.1.13`
- `neurealroblox/ui-gamepad@0.1.2`
- `neurealroblox/ui-killfeed@0.1.6`
- `neurealroblox/ui-notifications@0.1.6`
- `neurealroblox/ui-styled@0.5.24`
- `neurealroblox/ui-viewport-character@0.1.3`
- `neurealroblox/ui-world-stage@0.1.2`
- `neurealroblox/ui-class-select@0.1.4`
- `neurealroblox/ui-hud@0.1.12`
- `neurealroblox/ui-menu-window@0.2.7`
- `neurealroblox/ui-results@0.1.7`
- `neurealroblox/ui-skill-tree@0.5.6`
- `neurealroblox/ui-slots@0.3.3`
- `neurealroblox/ui-bundle@0.2.12`

## 2026-07-30 07:01 UTC

- `neurealroblox/ui-core@0.1.12`
- `neurealroblox/ui-skill-tree@0.5.4`
- `neurealroblox/ui-bundle@0.2.8`

## 2026-07-30 03:44 UTC

- `neurealroblox/ui-core@0.1.11`
- `neurealroblox/ui-styled@0.5.21`
- `neurealroblox/ui-bundle@0.2.7`

## 2026-07-30 03:23 UTC

- `neurealroblox/ui-core@0.1.10`
- `neurealroblox/ui-styled@0.5.20`
- `neurealroblox/ui-bundle@0.2.6`

## 2026-07-30 02:36 UTC

- `neurealroblox/ui-core@0.1.9`
- `neurealroblox/ui-menu-window@0.2.5`
- `neurealroblox/ui-bundle@0.2.5`

## 2026-07-30 01:57 UTC

- `neurealroblox/ui-core@0.1.8`
- `neurealroblox/ui-styled@0.5.19`
- `neurealroblox/ui-class-select@0.1.3`
- `neurealroblox/ui-menu-window@0.2.4`
- `neurealroblox/ui-modal@0.2.4`
- `neurealroblox/ui-bundle@0.2.4`

## 2026-07-30 00:49 UTC

- `neurealroblox/ui-animation@0.3.1`
- `neurealroblox/ui-tooltip@0.2.0`
- `neurealroblox/ui-core@0.1.7`
- `neurealroblox/ui-styled@0.5.18`
- `neurealroblox/ui-viewport-character@0.1.2`
- `neurealroblox/ui-world-stage@0.1.1`
- `neurealroblox/ui-class-select@0.1.2`
- `neurealroblox/ui-modal@0.2.3`
- `neurealroblox/ui-settings@0.1.5`
- `neurealroblox/ui-skill-tree@0.5.3`
- `neurealroblox/ui-bundle@0.2.3`

## 2026-07-29 23:21 UTC

- `neurealroblox/ui-styled@0.5.17`
- `neurealroblox/ui-viewport-character@0.1.1`
- `neurealroblox/ui-world-stage@0.1.0`
- `neurealroblox/ui-class-select@0.1.1`
- `neurealroblox/ui-hud@0.1.11`
- `neurealroblox/ui-modal@0.2.2`
- `neurealroblox/ui-skill-tree@0.5.2`
- `neurealroblox/ui-slots@0.3.2`
- `neurealroblox/ui-loadout@0.1.1`
- `neurealroblox/ui-bundle@0.2.2`

## 2026-07-29 17:14 UTC

- `neurealroblox/ui-styled@0.5.16`

## 2026-07-29 17:11 UTC

- `neurealroblox/class-select@0.1.0`
- `neurealroblox/ui-core@0.1.6`
- `neurealroblox/ui-viewport-character@0.1.0`
- `neurealroblox/ui-achievements@0.1.13`
- `neurealroblox/ui-battlepass@0.1.9`
- `neurealroblox/ui-class-select@0.1.0`
- `neurealroblox/ui-daily-rewards@0.1.7`
- `neurealroblox/ui-hud@0.1.10`
- `neurealroblox/ui-leaderboards@0.1.13`
- `neurealroblox/ui-lobby-nav@0.1.4`
- `neurealroblox/ui-menu-window@0.2.3`
- `neurealroblox/ui-modal@0.2.1`
- `neurealroblox/ui-player-stats@0.1.0`
- `neurealroblox/ui-quest-tracker@0.1.6`
- `neurealroblox/ui-results@0.1.6`
- `neurealroblox/ui-settings@0.1.4`
- `neurealroblox/ui-skill-tree@0.5.1`
- `neurealroblox/ui-slots@0.3.1`
- `neurealroblox/ui-loadout@0.1.0`
- `neurealroblox/ui-bundle@0.2.1`

## 2026-07-29 04:56 UTC

- `neurealroblox/ui-skill-tree@0.3.0`

## 2026-07-29 04:38 UTC

- `neurealroblox/ui-skill-tree@0.2.0`

## 2026-07-29 04:24 UTC

- `neurealroblox/ui-skill-tree@0.1.6`

## 2026-07-29 04:21 UTC

- `neurealroblox/ui-skill-tree@0.1.5`

## 2026-07-29 04:16 UTC

- `neurealroblox/ui-skill-tree@0.1.4`

## 2026-07-29 02:59 UTC

- `neurealroblox/ui-skill-tree@0.1.3`

## 2026-07-29 02:51 UTC

- `neurealroblox/ui-skill-tree@0.1.2`

## 2026-07-29 02:47 UTC

- `neurealroblox/ui-skill-tree@0.1.1`

## 2026-07-29 02:10 UTC

- `neurealroblox/ui-styled@0.5.14`
- `neurealroblox/ui-leaderboards@0.1.12`
- `neurealroblox/ui-modal@0.2.0`
- `neurealroblox/ui-skill-tree@0.1.0`
- `neurealroblox/ui-slots@0.2.0`
- `neurealroblox/ui-bundle@0.2.0`

## 2026-07-28 15:28 UTC

- `neurealroblox/ui-bundle@0.1.32`

## 2026-07-28 15:27 UTC

- `neurealroblox/ui-slots@0.1.3`

## 2026-07-28 04:36 UTC

- `neurealroblox/ui-bundle@0.1.31`

## 2026-07-28 04:35 UTC

- `neurealroblox/ui-hud@0.1.9`

## 2026-07-28 04:25 UTC

- `neurealroblox/ui-bundle@0.1.30`

## 2026-07-28 04:24 UTC

- `neurealroblox/ui-killfeed@0.1.5`

## 2026-07-28 02:56 UTC

- `neurealroblox/ui-bundle@0.1.29`

## 2026-07-28 02:56 UTC

- `neurealroblox/ui-achievements@0.1.12`

## 2026-07-28 02:36 UTC

- `neurealroblox/ui-killfeed@0.1.4`

## 2026-07-28 01:30 UTC

- `neurealroblox/ui-bundle@0.1.28`

## 2026-07-28 01:29 UTC

- `neurealroblox/ui-notifications@0.1.5`

## 2026-07-27 18:27 UTC

- `neurealroblox/ui-bundle@0.1.27`

## 2026-07-27 18:26 UTC

- `neurealroblox/ui-theme@0.1.9`
- `neurealroblox/ui-core@0.1.5`
- `neurealroblox/ui-styled@0.5.13`
- `neurealroblox/ui-achievements@0.1.11`
- `neurealroblox/ui-leaderboards@0.1.11`

## 2026-07-27 17:35 UTC

- `neurealroblox/ui-bundle@0.1.26`

## 2026-07-27 17:34 UTC

- `neurealroblox/ui-styled@0.5.11`
- `neurealroblox/ui-menu-window@0.2.1`
- `neurealroblox/ui-slots@0.1.2`

## 2026-07-27 07:59 UTC

- `neurealroblox/ui-hud@0.1.8`
- `neurealroblox/ui-bundle@0.1.25`

## 2026-07-27 06:08 UTC

- `neurealroblox/ui-styled@0.5.10`
- `neurealroblox/ui-bundle@0.1.24`

## 2026-07-27 05:49 UTC

- `neurealroblox/ui-styled@0.5.9`
- `neurealroblox/ui-bundle@0.1.23`

## 2026-07-27 02:21 UTC

- `neurealroblox/ui-styled@0.5.8`
- `neurealroblox/ui-bundle@0.1.22`

## 2026-07-27 01:08 UTC

- `neurealroblox/ui-killfeed@0.1.3`
- `neurealroblox/ui-bundle@0.1.21`

## 2026-07-26 23:14 UTC

- `neurealroblox/ui-styled@0.5.7`
- `neurealroblox/ui-menu-window@0.2.0`
- `neurealroblox/ui-store@0.1.0`
- `neurealroblox/ui-bundle@0.1.20`

## 2026-07-26 22:16 UTC

- `neurealroblox/ui-topbar-icon@0.2.2`
- `neurealroblox/ui-styled@0.5.6`
- `neurealroblox/ui-bundle@0.1.19`

## 2026-07-26 08:59 UTC

- `neurealroblox/ui-styled@0.5.5`
- `neurealroblox/ui-bundle@0.1.18`

R2-11: flat background tokens no longer paint behind active chrome art -- fixed in all six components that had it (Button, IconButton, Tag, ProgressBar, ItemTile as well as the reported Card and Panel), so a light skin no longer shows a cream rim around every surface. R2-12: ImageAsset/ChromeSpec gain contentBox (where content may sit, as 0..1 fractions, surfaced as Styled.contentBox) and imageRect (crop a padded canvas through the chrome API instead of dropping to a raw ImageLabel). Also adds Styled.resetSeams, because configure() cannot clear a seam by passing nil. Bundle floors synced to published versions.

## 2026-07-26 08:28 UTC

- `neurealroblox/ui-text-fit@0.2.1`
- `neurealroblox/ui-killfeed@0.1.1`
- `neurealroblox/ui-notifications@0.1.4`
- `neurealroblox/ui-bundle@0.1.17`

Ship the measured advance constants (GetTextBoundsAsync: regular 0.490 / bold 0.501 / upperBold 0.582, carried with a one-sided 3% margin) that the previous wave documented but did not publish. Budgets: notification 23 at rest / 148 max, killfeed 45 per name.

## 2026-07-26 08:26 UTC

- `neurealroblox/ui-killfeed@0.1.0`
- `neurealroblox/ui-bundle@0.1.16`

New ui-killfeed: a rolling elimination feed that is deliberately not a notification variant -- no coalescing (two kills are two events), rows age out silently, newest-first, 13px bottom-right, and lines the local player is in get accented. Both names survive at any length via per-part text allocation. The text-fit advance constants are now MEASURED against GetTextBoundsAsync rather than estimated, so the published character budgets are real: notification 23 at rest / 148 max, killfeed 45 per name.

## 2026-07-26 08:07 UTC

- `neurealroblox/ui-text-fit@0.2.0`
- `neurealroblox/ui-notifications@0.1.3`
- `neurealroblox/ui-bundle@0.1.15`

Notification cards grow to their message instead of truncating at a fixed 220px: widen to 45% of viewport (capped 560px), then wrap to a second line, then shrink 14->12, and only then cut. 140 characters intact against 22 before; minWidth/maxWidth now configurable. TextFit gains per-call shrink depth and segment allocation for composite lines (killfeed-style 'NAME VERB NAME'), where fixed parts survive whole and names share the remainder so both ends stay readable at any length.

## 2026-07-26 07:14 UTC

- `neurealroblox/ui-animation@0.3.0`
- `neurealroblox/ui-text-fit@0.1.0`
- `neurealroblox/ui-notifications@0.1.2`
- `neurealroblox/ui-styled@0.5.4`
- `neurealroblox/ui-achievements@0.1.10`
- `neurealroblox/ui-daily-rewards@0.1.6`
- `neurealroblox/ui-leaderboards@0.1.10`
- `neurealroblox/ui-slots@0.1.1`
- `neurealroblox/ui-bundle@0.1.14`

MotionPack: components ask for a beat by ROLE (entrance/tap/reject/attention/hover/reveal/payoff/impact/suspense/ambient) and a game's pack decides what each means; the motion budget still decides how much. Wired in: claims in daily-rewards and achievements, shaped first-load skeletons in leaderboards and achievements, the suspense beat on the ui-slots stall. New ui-text-fit publishes the text-overflow contract (shrink, then truncate, except numbers which abbreviate) and fixes notification text drawing outside its card.

## 2026-07-26 04:38 UTC

- `neurealroblox/ui-gamepad@0.1.1`
- `neurealroblox/ui-styled@0.5.3`
- `neurealroblox/ui-lobby-nav@0.1.3`
- `neurealroblox/ui-bundle@0.1.12`

Consumer audit round 2: the server can require ui-bundle again (ui-gamepad guarded its module-scope input wiring; the bundle resolves members lazily), and the interactive tint no longer washes over authored state art (ChromeStates reports needsInteractionTint; swept out of lobby-nav tiles and the panel close control too). ui-lobby-nav's fallback glyph no longer sits under every nav icon.

## 2026-07-25 07:34 UTC

- `neurealroblox/ui-animation@0.2.0`
- `neurealroblox/ui-theme@0.1.8`
- `neurealroblox/ui-topbar-icon@0.2.1`
- `neurealroblox/ui-styled@0.5.2`
- `neurealroblox/ui-hud@0.1.7`
- `neurealroblox/ui-bundle@0.1.11`

Motion tier: keyframe timelines + a device-aware motion budget (functional/polish/decorative), the payoff and loading-skeleton families, and a Vide animation adapter. Plus every Round 2 consumer-audit fix: AbilitySlot cooling chrome no longer hides the icon, the icon fallback glyph no longer draws forever, labelled topbar icons size correctly, and the panel close control gained real pressed state and a skin seam.

## 2026-07-25 03:56 UTC

- `neurealroblox/ui-slots@0.1.0`
- `neurealroblox/ui-bundle@0.1.9`

NEW package ui-slots (Neu.Slots): reel and roll reveals — slot machines, crate openings, gacha pulls. Server decides the outcome, the package stages it. Slots.play{} is a one-shot takeover that dims and blocks; Slots.Machine{present='inline'} mounts in place. Shape is orthogonal (axis + reels + rows gives classic/grid/case/column); duration is the velocity lever, with peak speed derived rather than dialled in. Motion: run, LINEAR brake, a stall straddling two symbols, then a slow adjust onto the result — never travels backwards. Close calls come from authored strips (landing picks uniformly among occurrences; there is no API for manufactured near-misses) and anticipation only fires when a win is genuinely still live.

## 2026-07-25 02:53 UTC

- `neurealroblox/ui-responsive@0.1.7`
- `neurealroblox/ui-lobby-nav@0.1.2`
- `neurealroblox/ui-bundle@0.1.8`

Follow-up wave: P1-6 from the revised audit — UIResponsive.attach no longer pins a bad scale on a ScreenGui created with Enabled = false (falls back to the camera viewport, recomputes on Enabled). New Responsive.tierCeiling(vpW, vpH) so profiles track the library's own tier instead of hardcoding a maxScale under it, documented in responsive-contract.md. lobby-nav sizes tiles from the camera viewport, not the safe-area box (caught by a live Studio selftest: 123px where the spec wanted 130px).

## 2026-07-25 02:32 UTC

- `neurealroblox/ui-platform@0.1.1`
- `neurealroblox/ui-theme@0.1.7`
- `neurealroblox/ui-topbar-icon@0.2.0`
- `neurealroblox/ui-styled@0.5.0`
- `neurealroblox/ui-achievements@0.1.9`
- `neurealroblox/ui-battlepass@0.1.8`
- `neurealroblox/ui-daily-rewards@0.1.5`
- `neurealroblox/ui-hud@0.1.6`
- `neurealroblox/ui-leaderboards@0.1.9`
- `neurealroblox/ui-lobby-nav@0.1.1`
- `neurealroblox/ui-menu-window@0.1.2`
- `neurealroblox/ui-quest-tracker@0.1.5`
- `neurealroblox/ui-results@0.1.5`
- `neurealroblox/ui-settings@0.1.3`
- `neurealroblox/ui-bundle@0.1.7`

Consumer-audit wave: every P0/P1 from the Rotten Tomato UI audit. P0 platform.classify is keyboard+mouse-first (a touchscreen PC / Studio play session is no longer a phone); P0 the slice guard clamps per axis (wide-short plates stop being crushed); P0 sliceless art whose frame aspect differs now warns once per asset, plus Surface{lockAspect}. P1 Surface padding no longer shrinks the chrome; Backdrop takes a per-instance image; new closeIcon/closeIconHover/titleInk tokens + Panel{titleColor}; AbilitySlot gained iconTint/iconTransparency/chromeCooling/onReady; TopbarIcon gained left/center/right lanes + laneRect(). WorldBoard derives its canvas from the part's face and takes row colours. ui-bundle stays 0.1.x so a plain wally update picks all of it up.

## 2026-07-24 22:20 UTC

- `neurealroblox/leaderboards@0.1.2`
- `neurealroblox/server-bundle@0.1.4`
- `neurealroblox/ui-leaderboards@0.1.8`
- `neurealroblox/ui-bundle@0.1.6`

In-world leaderboards: server worldPublisher (change-only compacted snapshots, join replay) + client WorldBoard SurfaceGui and PodiumAvatars local rigs. Geometry and transport are injected; pairs across leaderboards 0.1.2 / ui-leaderboards 0.1.8.


## 2026-07-24 21:14 UTC

- `neurealroblox/ui-lobby-nav@0.1.0`
- `neurealroblox/ui-bundle@0.1.5`

NEW package ui-lobby-nav: bottom-center lobby destinations strip (big square
tiles, one-of-N exclusivity via MenuWindow binding, badges, disabled tiles,
state-aware skin chrome `lobbyNav.tile*`). Exported as `Neu.LobbyNav`.

## 2026-07-24 17:02 UTC

- `neurealroblox/ui-achievements@0.1.8`
- `neurealroblox/ui-battlepass@0.1.7`
- `neurealroblox/ui-daily-rewards@0.1.4`
- `neurealroblox/ui-leaderboards@0.1.7`
- `neurealroblox/ui-quest-tracker@0.1.4`
- `neurealroblox/ui-results@0.1.4`
- `neurealroblox/ui-settings@0.1.2`
- `neurealroblox/ui-bundle@0.1.4`

Floor sweep: every panel package's ui-styled floor raised across the 0.3->0.4
boundary so consumer installs resolve ONE copy of styled (stale floors caused
duplicate vendoring = two seam singletons). No API changes.

## 2026-07-24 16:37-16:53 UTC

- `neurealroblox/ui-styled@0.4.0` -> `0.4.2`
- `neurealroblox/ui-core@0.1.4`
- `neurealroblox/ui-theme@0.1.6`
- `neurealroblox/ui-hud@0.1.4` -> `0.1.5`
- `neurealroblox/ui-menu-window@0.1.1`
- `neurealroblox/ui-bundle@0.1.3`

Production-skin round: chrome-states contract (state-aware art with
precedence + focus accessibility), `Styled.Surface` public skinned-surface
primitive, `Styled.configure({ resolveImage })` typed asset registry seam,
`selected` + real gamepad focus on Button/IconButton/Card, `Panel{ variant }`,
HUD skin seams (frame/track/fill chrome + segments), FontFace text support,
`Styled.preload` + warn-once diagnostics, theme snapshot/restore. See
docs/theme-packs.md in NeuLibs.
