# NeoLongSur Distribution

Public, machine-consumed distribution storage for the private NeoLongSur
Minecraft server. Release objects are independently compressed, encrypted, and
authenticated; manifests are signed with Ed25519.

The mutable entry point is `channel/stable.json`. Release manifests and objects
are immutable after their matching Git tag is published.

This repository contains no signing private key and no plaintext synchronization
key.
