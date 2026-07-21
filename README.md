# wally-index

Neureal's private [Wally](https://wally.run) package index. Metadata only — package
zips live in the backend's GCS bucket, served by the Rust `wally-registry-backend`
at the `api` URL below.

Consumer games point their `wally.toml` at this repo:

```toml
[package]
registry = "https://github.com/NeurealRoblox/wally-index"
```

Then `wally login` (read key) → `wally install`. See the NeuLibs repo's
`docs/registry-setup.md` for how this is deployed and `docs/publishing.md` for releases.
