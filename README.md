# Murmur releases

Update feed for [Murmur](https://github.com/erwins-enkel/murmur), the on-device dictation and
meeting-notes app for macOS. Murmur checks `appcast.xml` (Sparkle) daily; the notarized
builds are attached to this repo's releases.

Published by `scripts/release.sh --publish` in the app repo. Updates are signed (EdDSA); the
public key is in the app's `Info.plist`.
