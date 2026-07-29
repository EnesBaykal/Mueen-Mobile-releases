# Mueen Mobile — Releases

This repository hosts release APKs and the in-app update feed (`version.json`)
for **Mueen Mobile**. It does not contain application source code.

The app checks `version.json` periodically and, if a newer `latestVersion`
is found, downloads `downloadUrl` and hands it to Android's package installer.
