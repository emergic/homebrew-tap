# Emergic Homebrew tap

```sh
brew install --cask emergic/tap/emergic
```

Emergic is office AI answered by your office's own idle Macs and PCs: chat, documents, meetings, follow-ups and mail. Releases: [emergic/emergic-releases](https://github.com/emergic/emergic-releases). Apple Silicon, macOS 13 or later. The app is signed but not yet notarised, so the cask clears the download quarantine.

Emergic updates itself from the office server, as the admin's update policy says, so `brew upgrade` leaves it alone (`brew upgrade --greedy` still updates it).

Moving from the old tap: a Mac that installed from `naklitechie/tap` moves here on its next `brew update`; recent Homebrew first asks once for `brew trust emergic/tap`. The `otium` cask, Emergic's earlier name, maps to `emergic`.
