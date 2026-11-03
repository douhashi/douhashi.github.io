---
title: Perari Privacy Policy
lang: en
---

# Perari Privacy Policy

[日本語](../)

Last updated: November 3, 2026

This privacy policy explains how the Android app "Perari" (the "App") handles your information. The App is developed and provided by douhashi, an individual developer.

## Summary

The App does not send, collect, or share your information with the developer or any third party. All information the App handles is stored on your device and is used only to communicate with network devices you specify (such as a NAS).

The App contains no advertising, analytics, crash-report uploading, or any other tracking.

## Information the App handles on your device

### Folders and files on your device

The App reads only the folders you choose in the Android folder picker. When you download books from the network, it writes only to the folder you choose as the destination. It does not access any other files.

### Connection information

The name, address, user name, and password of your connections (such as a NAS) are encrypted with a key held in the Android Keystore and stored on your device. This information is used only to communicate with the connections you specify and is never sent to the developer or any third party. It is also excluded from device backups and from data transfer to a new device.

### Reading progress and settings

Your reading position, the page direction of each book, your bookshelf locations, and settings such as the theme are stored only on your device.

### Covers, pages, and book cache

To display books quickly, the App temporarily stores cover thumbnails, loaded pages, and books in formats that are saved to the device before reading (such as RAR) on your device. These are never sent off your device.

### App lock

If you use the app lock, your password is stored on your device only as a hash made with a key held in the Android Keystore; the password itself is not stored. Biometric authentication is performed by Android, and the App never receives biometric data such as fingerprints or face data.

### Diagnostic logs

To help investigate problems, the App keeps an activity log and a crash record on your device, within a size limit. When writing logs, the App masks connection addresses, user names, passwords, and IP addresses. Logs leave your device only when you export them from the settings screen and choose where to share them yourself. They are never sent automatically.

## Network use

The App communicates over the network only in the following cases:

- SMB communication with the connections you register (such as a NAS)
- Discovery of devices on the same local network (mDNS) when you use the connection search feature

The App does not communicate with any server operated by the developer or by third parties.

## How permissions are used

| Permission | Purpose |
|---|---|
| Internet, network state | Communicating with your connections, and checking whether you are on a metered connection |
| Wi-Fi multicast | Finding connections on the same network |
| Notifications | Showing download progress and completion |
| Foreground service | Continuing downloads after you leave the App |

## Deleting your information

All information stored by the App is on your device. Uninstalling the App, or clearing its data in Android settings, deletes all of it. You can also remove connections and bookshelf locations individually within the App. Downloaded books remain in the folder you chose; delete them yourself if you no longer need them.

## Children's privacy

The App is not directed at children and does not knowingly collect information from children. In any case, the App does not send any user information to the developer.

## Changes to this policy

This policy may be updated, for example when the App's features change. Any updates will be posted on this page with a new "Last updated" date.

## Contact

If you have any questions about this policy, please contact:

- Developer: douhashi
- Email: [perari.support@gmail.com](mailto:perari.support@gmail.com)
