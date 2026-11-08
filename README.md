# Craton for macOS

Downloads and updates for the Craton desktop app.

Each [release](../../releases) is one version of Craton:

- `Craton-<version>-arm64.dmg`: the app for Macs with Apple silicon. Signed with Craton's Developer ID and notarised by
  Apple, so it opens without a warning.
- `Craton-<version>-arm64-mac.zip` and `latest-mac.yml`: what the app itself downloads to update.

Craton installs an update only when it is signed by the same Developer ID as the copy you're running. Releases are
published from Craton's own build; this repository holds nothing else.