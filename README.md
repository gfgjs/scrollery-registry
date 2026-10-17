# Scrollery plugin registry

Official Windows x64 PSD plugin distribution:

- Registry: https://raw.githubusercontent.com/gfgjs/scrollery-registry/main/prod/exotic/v1/index.json
- Plugin 1.0.5 and corresponding source: https://github.com/gfgjs/scrollery-registry/releases/tag/psd-1.0.5-1792257889
- Application source: https://github.com/gfgjs/scrollery

The official registry is a single JSON file. Plugin packages are immutable Release assets with explicit version and sequence numbers. The current worker uses protocol 3. Plugins do not require public/private keys or signature files; the host checks HTTPS, sizes, SHA-256 digests, paths, protocol, expiry and sequence.

The current index expires at 2026-12-17T01:25:04+08:00. Renew the index before expiry, increasing its sequence. Keep the package URL, bytes and package sequence unchanged when only renewing the index.

`exotic/v1/` contains obsolete internal-test artifacts; it is not the official source. Current builds use `prod/exotic/v1/`.
