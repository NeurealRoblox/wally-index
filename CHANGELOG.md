# NeuLibs release changelog

Newest first; one entry per publish wave. Auto-appended by the repo's
`scripts/publish` (release train). Machine-readable mirror: `releases.json`.

<!-- waves -->
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
