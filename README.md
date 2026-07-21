# SoBold Site Reporter — release channel

Public, signature-verified release channel for the **SoBold Site Reporter**
WordPress plugin. The plugin's self-updater fetches `manifest.json` from this
repo and only installs a package whose Ed25519 signature verifies against the
public key baked into the plugin.

- `manifest.json` — latest release manifest (version, download URL, sha256, signature)
- Release zips are attached as **GitHub Release assets** (`releases/`).

**No source code lives here** — the dashboard + plugin source is in a private
repo. These are distribution artifacts only, and contain no secrets. See the
plugin's `UPDATES.md` for the release process.