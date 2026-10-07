# Molly iOS WORK IN PROGRESS 🚧 

[![Test](https://github.com/mollyim/mollyim-android/workflows/Test/badge.svg)](https://github.com/mollyim/mollyim-android/actions)
[![Reproducible build](https://github.com/mollyim/mollyim-android/actions/workflows/reprocheck.yml/badge.svg)](https://github.com/mollyim/mollyim-android/actions/workflows/reprocheck.yml)
[![Translation status](https://hosted.weblate.org/widgets/molly-instant-messenger/-/svg-badge.svg)](https://hosted.weblate.org/engage/molly-instant-messenger/?utm_source=widget)
[![Financial contributors](https://opencollective.com/mollyim/tiers/badge.svg)](https://opencollective.com/mollyim#category-CONTRIBUTE)
[![Cloudsmith](https://img.shields.io/badge/OSS%20hosting%20by-cloudsmith-blue?logo=cloudsmith&style=flat-square)](https://cloudsmith.com)

Molly is a hardened version of [Signal](https://github.com/signalapp/Signal-Android) for iOS, the fast simple yet secure messaging app by [Signal Foundation](https://signal.org).

Also available on [Android](https://github.com/mollyim/mollyim-android). 

## Introduction

Back in 2018, Signal allowed the user to set a passphrase to secure the local message database. But this option was removed with the introduction of file-based encryption on Android. Molly brings it back again with additional security features.

Molly connects to Signal's servers, so you can chat with your Signal contacts seamlessly. Before signing up, please remember to review the [Signal Terms & Privacy Policy](https://signal.org/legal/).

We update Molly every two weeks to include the latest Signal features and fixes. The exceptions are security patches, which are applied as soon as they are available.

## Download

You will be able to install the app from the [Apple App Store](https://molly.im/fdroid/):

[<img src="./AppStore.svg"
    alt="Get it on the App Store"
    height="80">](https://molly.im/fdroid/)

## Features

Molly has unique features compared to Signal:

- **Data encryption at rest** - Protect your app database with [passphrase encryption](https://github.com/mollyim/mollyim-android/wiki/Data-Encryption-At-Rest)
- **Secure RAM wiper** - Securely shred sensitive data from device memory
- **Automatic lock** - Lock the app automatically under user-defined conditions
- **Block unknown contacts** - Block messages and calls from unknown senders for security and anti-spam
- **Custom backup scheduling** - Set daily or weekly interval and the number of backups to retain
- **SOCKS proxy and Tor support** - Tunnel app network traffic via proxy and Orbot
- **Debug logs are optional** - iOS logging can be disabled

Additionally, you will find all the features of Signal, along with some minor tweaks and improvements.

## Compatibility with Signal

Molly and Signal apps can be installed on the same device. If you need a second number for messaging, you can register Molly with a different number while keeping Signal active. Any phone number capable of receiving SMS or calls can be used during registration.

If you wish to use the same phone number for both Molly and Signal, you must register Molly as a linked device. Registering the same number independently on both apps will result in only the most recently registered app staying active, while the other will go offline.

For Signal users looking to switch to Molly without changing the phone number, please refer to the [Migrating From Signal](https://github.com/mollyim/mollyim-android/wiki/Migrating-From-Signal) guide on the wiki.

## Backups

Backups are fully compatible. Signal [backups](https://support.signal.org/hc/en-us/articles/360007059752-Backup-and-Restore-Messages) can be restored in Molly, and the other way around, simply by choosing the backup folder and file. However, to import a backup from Signal, you must use a matching or newer version of Molly.

## Feedback

- [Submit bugs and feature requests](https://github.com/mollyim/mollyim-android/issues) on GitHub
- Join us at [#mollyim:matrix.org](https://matrix.to/#/#mollyim:matrix.org) on Matrix (via space: [#mollyim-space:matrix.org](https://matrix.to/#/#mollyim-space:matrix.org))
- For news, tips, and tricks, follow [@mollyim](https://fosstodon.org/@mollyim) on Mastodon

## Changelog

See the [Changelog](https://github.com/mollyim/mollyim-android/wiki/Changelog) to view recent changes.

## License

Licensed under the GNU Affero General Public License, version 3 only
([`AGPL-3.0-only`](LICENSE)).

See [LEGAL.md](LEGAL.md) for legal and copyright information.

## Acknowledgements

Molly is an independent project built on code published by Signal. We are
deeply grateful to the Signal contributors for the work we build on.

Thanks to the following organizations for supporting the **Molly** project.

<div align="center">
<table>
<tr>
  <td>
    <a href="https://nlnet.nl/" target="_blank">
      <img src="https://nlnet.nl/logo/banner.svg" alt="NLnet logo" height="56" />
    </a>
  </td>
  <td>
    <a href="https://bahnhof.cloud/en/" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/de/c/c0/Bahnhof_AB_logo.svg" alt="Bahnhof logo" height="56" />
    </a>
  </td>
  <td>
    <a href="https://cloudsmith.com/blog/cloudsmith-loves-opensource/" target="_blank">
      <img src="https://raw.githubusercontent.com/opswithranjan/CloudsmithLogo/main/CloudsmithLogoCropped.jpeg" alt="Cloudsmith logo" height="32" />
    </a>
  </td>
  <td>
    <a href="https://www.jetbrains.com/community/opensource/" target="_blank">
      <img src="https://resources.jetbrains.com/storage/products/company/brand/logos/jetbrains.svg" alt="JetBrains logo" height="32" />
    </a>
  </td>
</tr>
</table>
</div>
