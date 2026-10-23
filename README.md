# AURA QUEST — updates

This **public repository** hosts Android update downloads only. Game code and spoilers stay in the private `RrIina/aura-quest` repository.

## Update procedure
1. Build a release APK from the private source using a stable signing keystore.
2. Confirm application ID `com.rowan.auraquest`, and increase Android versionCode and versionName.
3. Upload the signed APK in a GitHub Release with a tag such as `v0.5.0`.
4. The Android app checks `https://api.github.com/repos/RrIina/aura-quest-upgrade/releases/latest` and offers a link to the new release.
5. Android requires the user to confirm installation. All releases must use the same signing certificate for in-place upgrades.

There is **no installable release yet**. Do not upload signing keys or API tokens to this repository. Avoid posting any game spoilers here.

[Releases](https://github.com/RrIina/aura-quest-upgrade/releases)
