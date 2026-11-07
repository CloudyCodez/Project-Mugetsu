# BSR Sandbox

An on-device damage-testing server for BLEACH: Soul Resonance.

## Setup

1. Install the BSR Sandbox hub APK from Releases.
2. Open **Client setup**, then **Prepare client**.
3. Keep the app open while the client is prepared. Android will ask you to approve installation.
4. Choose **Start and play** and approve Android's VPN connection request.
5. Open **Battle Modes → Training → Free Practice** and choose your team.

Preparation resumes interrupted parts and verifies SHA-256 checksums. The public release must include all 15 client parts and `release.json` before first-time setup is available.

## Sandbox account

Cloud-QA is saved locally inside the Sandbox hub.

- 39 supported characters, including the Full Hollow Ichigo prototype.
- 134 highest-available-rarity stamp families, including native set pieces.
- 55 weapon cards.
- Unlimited development materials, summon currency and stamina.
- Normal upgrade and equipment controls for testing different builds.
- Main-story checkpoint through Chapter 2-14.

The prototype skins for Rangiku, Grimmjow and Orihime are excluded from automatic grants.

## Requirements and current validation

Android 8 or later with ARM64 support and enough storage for the prepared client and temporary setup files. MuMu and BlueStacks require an Android instance capable of running this ARM64 client.

The local login, account grants and native training entry have automated protocol coverage. Physical Samsung-device testing reached training and passed the client combat-stat checks. Fresh installation of the complete public package, MuMu and BlueStacks still need end-to-end testing.

Some character and combat systems remain under restoration. Full Hollow Ichigo uses recovered prototype assets and behavior.

## Stop and saves

**Stop** closes the local server, sockets and VPN route. The prepared client supports a signed hub request to close its local session. Account progress stays in the hub. Uninstalling the hub can remove its local account.

## Credits

made with <3 - cloud

Thanks to REA for the tools and resources used during analysis and verification.

Community testing project. Not affiliated with the game's publishers or developers.
