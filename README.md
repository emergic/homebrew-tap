# Emergic Homebrew tap

```sh
brew install --cask emergic/tap/emergic
```

Emergic is office AI chat served by your office's own idle Macs and Windows PCs. Releases: [emergic/emergic-releases](https://github.com/emergic/emergic-releases). Apple Silicon only; the app is ad-hoc signed and not notarised, so the cask clears the download quarantine.

Emergic updates itself when the office admin approves a release, so `brew upgrade` leaves it alone (`brew upgrade --greedy` still updates it).

Moving from the old tap: a Mac that installed from `naklitechie/tap` moves here on its next `brew update`; recent Homebrew first asks once for `brew trust emergic/tap`. The `otium` cask, Emergic's earlier name, maps to `emergic`.
