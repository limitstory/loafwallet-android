[![Pyeongtaekwallet](/images/header-android.png)](https://play.google.com/store/apps/details?id=com.loafwallet&hl=en_US)
======================
[![Release](https://img.shields.io/github/v/release/pyeongtaekcoin-foundation/loafwallet-android?style=plastic)](https://img.shields.io/github/v/release/pyeongtaekcoin-foundation/loafwallet-android) 
[![MIT License](https://img.shields.io/github/license/pyeongtaekcoin-foundation/loafwallet-android?style=plastic)](https://img.shields.io/github/license/pyeongtaekcoin-foundation/loafwallet-android?style=plastic)

## Easy and secure
Pyeongtaekwallet is the best way to get started with Pyeongtaekcoin. Our simple, streamlined design is easy for beginners, yet powerful enough for experienced users. This is a free app produced by the Pyeongtaekcoin Foundation.
 
## Donations
The Pyeongtaekwallet Team is a group of global volunteers & part of the Pyeongtaekcoin Foundation that work hard to promote the use of Pyeongtaekcoin. Pyeongtaekwallet takes alot of time and resources to improve and test features but we need your help.  Please consider donating to one of our addresses:
|                                   Hardware Campaign                                   	|                              General Pyeongtaekcoin Foundation                              	|
|:-------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------:	|
| [QR Code](https://blockchair.com/pyeongtaekcoin/address/MJ4W7NZya4SzE7R6xpEVdamGCimaQYPiWu) 	| [QR Code](https://blockchair.com/pyeongtaekcoin/address/MVZj7gBRwcVpa9AAWdJm8A3HqTst112eJe) 	|

## Completely decentralized

Unlike other iOS Pyeongtaekcoin wallets, **Pyeongtaekwallet** is a standalone Pyeongtaekcoin client. It connects directly to the Pyeongtaekcoin network using [SPV](https://en.bitcoin.it/wiki/Thin_Client_Security#Header-Only_Clients) mode, and doesn't rely on servers that can be hacked or disabled. Even if Pyeongtaekwallet is removed from the App Store, the app will continue to function, allowing users to access their valuable Pyeongtaekcoin at any time.

## Cutting-edge security

**Pyeongtaekwallet** utilizes AES hardware encryption, app sandboxing, and the latest iOS security features to protect users from malware, browser security holes, and even physical theft. Private keys are stored only in the secure enclave of the user's phone, inaccessible to anyone other than the user.

## Designed with new users in mind

Simplicity and ease-of-use is **Pyeongtaekwallet**'s core design principle. A simple recovery phrase (which we call a paper key) is all that is needed to restore the user's wallet if they ever lose or replace their device. **Pyeongtaekwallet** is [deterministic](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki), which means the user's balance and transaction history can be recovered just from the paper key.

## Features:

- ["simplified payment verification"](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) for fast mobile performance
- no server to get hacked or go down
- single backup phrase that works forever
- private keys never leave your device
- import [password protected](https://github.com/bitcoin/bips/blob/master/bip-0038.mediawiki) paper wallets
- ["payment protocol"](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) payee identity certification


## Localization

**Pyeongtaekwallet** is available in the following languages:

- Chinese (Simplified and traditional)
- Danish
- Dutch
- English
- French
- German
- Indonesian
- Italian
- Japanese
- Korean
- Portuguese
- Russian
- Spanish
- Swedish

---
## Pyeongtaekwallet Development:
[![GitHub issues](https://img.shields.io/github/issues/pyeongtaekcoin-foundation/loafwallet-android?style=plastic)](https://github.com/pyeongtaekcoin-foundation/loafwallet-android/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/pyeongtaekcoin-foundation/loafwallet-android?color=00ff00&style=plastic)](https://github.com/pyeongtaekcoin-foundation/loafwallet-android/pulls)

### Building & Developing Pyeongtaekwallet for Android: 

1. Download and install Java 7 or up
2. Download and install the latest Android studio
3. Download NDK r15c from the [NDK Archives](https://developer.android.com/ndk/downloads/older_releases.html)
4. Clone this repo & init submodules
```bash
$ git clone https://github.com/pyeongtaekcoin-foundation/loafwallet-android
$ git submodule init
$ git submodule update
```
5. Open the project with Android Studio, navigate to `File > Project Structure > SDK Location`
6. Change `Android NDK Location` with the path to NDK r15c that you downloaded earlier
7. Go to SDK Manager and download all the SDK Platforms and SDK Tools
9. Build -> Rebuild Project

### Pyeongtaekwallet Team:
* [Development Code of Conduct](https://github.com/pyeongtaekcoin-foundation/litewallet/blob/master/DEVELOPMENT.md)
---
**Pyeongtaekcoin** source code is available at https://github.com/pyeongtaekcoin-project/pyeongtaekcoin

