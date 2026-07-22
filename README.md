# NeurealRoblox wally-index

Package index for the private NeuLibs Wally registry (`registry.neureal.dev`).
Access to **this repo** is what gates package discovery — if you can read this,
you can install.

## Installing NeuLibs packages

No API key, no `wally login`. One-time: install [rokit](https://github.com/rojo-rbx/rokit),
then `rokit add UpliftGames/wally` and `rokit add rojo-rbx/rojo`.

In your project's `wally.toml`:

```toml
[package]
name = "yourscope/your-game"
version = "0.1.0"
registry = "https://github.com/NeurealRoblox/wally-index"
realm = "shared"

[dependencies]
UICore = "neurealroblox/ui-core@0.1.2"
UIStyled = "neurealroblox/ui-styled@0.3.10"
```

Then:

```sh
wally install
```

Server-realm packages (`leaderboards`, `achievements`, matchmaking) go under
`[server-dependencies]`. Full guide incl. Rojo mapping + troubleshooting:
[NeuLibs docs/consuming.md](https://github.com/NeurealRoblox/NeuLibs/blob/main/docs/consuming.md).

Publishing is restricted (write API key held by the admin) — see
[NeuLibs docs/publishing.md](https://github.com/NeurealRoblox/NeuLibs/blob/main/docs/publishing.md).
