# NeuLibs release changelog

Newest first; one entry per publish wave. Auto-appended by the repo's
`scripts/publish` (release train). Machine-readable mirror: `releases.json`.

<!-- waves -->
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
