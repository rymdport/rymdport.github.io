# Rymdport

Rymdport (formerly wormhole-gui) is a cross-platform application that lets you easily and safely share files, folders, and text between devices.
The data is sent securely with end-to-end encryption using the same protocol as [magic-wormhole](https://github.com/magic-wormhole/magic-wormhole). This means that Rymdport can talk not only to itself, but also to other wormhole clients.

The transfers are implemented using [wormhole-william](https://github.com/psanford/wormhole-william), a native [Go](https://go.dev/) implementation of magic-wormhole. As a result, Rymdport compiles into a native binary with no runtime dependencies while also outperforming the reference implementation of magic-wormhole.

<p align="center">
  <a href='https://github.com/Jacalz/rymdport'>
    <img href='https://github.com/Jacalz/rymdport' src="https://github.com/Jacalz/rymdport/blob/main/internal/assets/screenshot1.png?raw=true" />
  </a>
</p>

## Downloads

Please visit the [release page](https://github.com/Jacalz/rymdport/releases) to download the latest release.
Pre-built binaries are available for FreeBSD, Linux, macOS (`x86-64` and `arm64`) and Windows (`x86-64`).

For Linux users, Rymdport is also avaliable as a Flatpak on [Flathub](https://flathub.org/apps/details/io.github.jacalz.rymdport):

<a href='https://flathub.org/apps/details/io.github.jacalz.rymdport'><img width='200' alt='Download on Flathub' src='https://flathub.org/assets/badges/flathub-badge-en.png'/></a>

The following distributions also have binary packages available through their respective package managers:

[![Packaging status](https://repology.org/badge/vertical-allrepos/rymdport.svg)](https://repology.org/project/rymdport/versions)
## Our Sponsors

We are grateful for the support received by the following organizations:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://tutanota.com/resources/images/press/tutanota-red-gray-font-logo.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://tutanota.com/resources/images/press/tutanota-red-black-font-logo.svg">
  <a href='https://tutanota.com/'>
    <img alt="Sponsored by Tutanota" width='300' src="https://tutanota.com/resources/images/press/tutanota-red-gray-font-logo.svg">
  </a>
</picture>
<br />
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://i0.wp.com/fynelabs.com/wp-content/uploads/2022/01/logo_light.png">
  <source media="(prefers-color-scheme: light)" srcset="https://i0.wp.com/fynelabs.com/wp-content/uploads/2022/01/logo_dark.png">
  
  <a href='https://fynelabs.com/'>
    <img alt="Sponsored by Fyne Labs" width='200' src="https://i0.wp.com/fynelabs.com/wp-content/uploads/2022/01/logo_light.png">
  </a>
</picture>
