# Little Buttons

A native Windows playground for Caroline and a Stream Deck XL: friendly toys, favorite YouTube songs, and Ghost Patrol.

## Update an existing installation (including 1.4.0)

1. [Download the one-time updater](https://github.com/curtner04/little-buttons-downloads/releases/latest/download/LittleButtons-Update.zip).
2. Extract the ZIP and close Little Buttons and any song window normally.
3. Run **Update Little Buttons.cmd**, then click **Download & update**. The helper finds the existing installation; Choose folder is available for custom locations.

This downloads the latest signed app and keeps saved settings, added songs, pictures and Stream Deck controls. It refuses to interrupt running play. No keyboard, GitHub sign-in or administrator access is needed for a normal per-user installation.

Afterward, leave automatic updates enabled. While the app is open, updates check hourly after at least 15 quiet minutes, with no video or parent dialog open and play unpaused. Downloads come directly from GitHub; the main home PC and its network share can be off. Parent controls shows the last check/result and any failure.

## Downloads

[Latest compiled packages and release notes](https://github.com/curtner04/little-buttons-downloads/releases/latest). The app ZIP must be extracted as a complete folder. Windows 10/11 x64, .NET Framework 4.8 and Elgato Stream Deck 6.6+ are required; YouTube songs also need internet and WebView2. Initial Stream Deck setup is separate from app updates.

This is a downloads-only repository. Application source is private. Saved configuration, personal song libraries, credentials, generation models and signing keys are not stored here. The app checks publisher signatures and package hashes before applying updates. The signed app feed is `little-buttons/latest.json`; installer metadata uses a separate path.