# Changelog — `toxi`

Per-crate history extracted from the monolith changelog
([meshackbahati/toxi](https://github.com/meshackbahati/toxi/blob/main/CHANGELOG.md)),
which remains the full documentation hub.

## 3.2.0

- **toxi** (`3.2.0`): `http3` feature (`toxi-core/http3`). QUIC/HTTP3 server support is no longer pulled into every build. `full` still includes it.

## 3.2.0

- **toxi** (`3.2.0`): `toxi-core` is now depended on with `default-features = false`. Minimal feature sets no longer compile quinn, h3 and aws-lc-sys. If you used `Server::listen_h3` without `full` or `http3`, add the feature.
