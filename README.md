# Nostr Browser

Native Nostr browser with local signing, WApps and Flight Deck,
released at 22:00 Australia/Perth. Installs alongside stable WMAPP using
`com.wingmanbefree.wingman_app.nightly` and the visible name **Nostr Browser**.

Each release includes the signed ARM64 APK, committed WMAPP and Flight Deck
source archives and a build proof containing source commits, asset SHA-256 hashes,
Android version and signing certificate. Android APK signing and Nostr publisher
signing are separate. Rick's Nostr publisher signs exclusively through the local
Autopilot capability broker; no Nostr private keys enter this repository or CI.

This repository is the public release catalog and publisher ownership proof.
Release automation lives in the WMAPP source repository (`tools/nightly_zapstore.py`).
Nightly builds are previews and use separate application storage from stable.
