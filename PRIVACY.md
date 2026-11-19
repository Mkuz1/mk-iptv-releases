# MK IPTV – Privacy Policy

_Last updated: 19 November 2026_

MK IPTV is a video player for IPTV services that use the Xtream Codes API, for Android phones, tablets, Google TV and iPhone/iPad. It does not provide any TV channels, movies or series. You connect it to a service you already subscribe to.

## What the app stores on your device

- **Playlist details you enter**: server address, username and password. On Android the password is encrypted with a key held in the Android Keystore; on iPhone it is kept in the Keychain.
- **Profiles, favourites, watch progress and settings.**
- **A cached copy of your provider's channel/movie/series list**, so the app opens quickly.
- **Downloaded videos**, in the app's private storage.

This data is excluded from Android cloud backup and device-to-device transfer.

## What is sent over the network

- **To the IPTV provider you configured**: your username and password, plus requests for channel lists, programme guides, artwork and video streams. This is required for the app to work. That provider's own privacy policy applies to it.
- **When you cast (Google Cast) or use AirPlay**: the stream address of what you are watching is sent to the TV or device you choose on your network.
- **Only if you turn on account sync**: the data described in the next section.

## Account sync (optional)

Sync is off until you choose **Sign in with Google**, **Sign in with Apple**, or **link devices with a code**. If you never do, nothing in this section applies.

When sync is on, the app stores a copy of the following in Google Firebase (Cloud Firestore and Firebase Authentication), in a cloud project operated by the developer:

- **Your sync account**: a Firebase user ID and, if you sign in with Google or Apple, the email address those services provide (Apple may give a private relay address).
- **Your playlists**: name, server address, username and playlist options. The password is end-to-end encrypted on your device before upload (with a key that only your linked devices hold), so neither Google nor the developer can read it.
- **Profiles, favourites, watch progress** (titles, artwork links and positions), dismissed items and app settings.
- **The device model** of each linked device (for example "Google Pixel 8") and a public encryption key for it, so you can see which devices are linked and they can share the encryption key.

This data is used only to keep your library the same on your own devices. It is not sold, not shared with third parties, not used for advertising or analytics, and not combined with other data. It is encrypted in transit and at rest by Google, and Firestore security rules allow only the devices you have linked to your account to read or change it. Google acts as the developer's data processor ([Firebase privacy information](https://firebase.google.com/support/privacy)).

## What we (the developer) receive

Without sync: **nothing**. MK IPTV has no analytics, no advertising and no tracking.

With sync on: the data listed above is held in the developer's Firebase project only to provide sync. We do not look at it or use it for any other purpose.

If the app crashes, it can offer to let you **share an error report**. It is only sent if you choose to share it, through the app you pick, and passwords and stream addresses are removed from it first.

## Children

MK IPTV is not directed at children, and the content shown comes from your own IPTV provider.

## Deleting your data

- **On your device**: remove a playlist or profile in Settings, or uninstall the app.
- **Synced data**: in the app's Sync settings, choose **Delete synced data**. This deletes the cloud copy for all linked devices and your sync account. Data on the device itself stays until you remove it. You can also email us to ask for deletion.

## Contact

Questions about this policy or the app: email **mohamad@koussa.org**
