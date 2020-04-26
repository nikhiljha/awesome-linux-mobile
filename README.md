# 🐧📱 Awesome Linux Mobile [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An awesome list of Linux Mobile related [apps](#apps), [OS images](#distributions), and [devices](#devices).
Curated to only list beta (or better) projects with a *reasonable amount* of functionality.

## Contents

- [Devices](#devices) - Devices that support Linux.
- [Apps](#apps) - Apps that work well in mobile form factors.
- [Distributions](#distributions) - Distros for your phone.

## Devices

These are devices that have excellent Linux support, either natively or by community support.

### Native

These devices have manufacturers that actively support running Linux on their devices.

- [Pine64 PinePhone](https://www.pine64.org/pinephone/) | [<img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/PostmarketOS_logo.svg" width=15 height=15> postmarketOS](https://wiki.postmarketos.org/wiki/PINE64_PinePhone_(pine64-pinephone)) | [<img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Ubuntu_and_Ubuntu_Server_Icon.png" width=15 height=15> Ubuntu Touch](https://devices.ubuntu-touch.io/device/pinephone/) | [📱 Other Distributions](https://wiki.pine64.org/index.php/PinePhone_Software_Release) | [🐧 Any* Desktop Distribution](https://xnux.eu/howtos/install-arch-linux-arm.html)
- [Purism Librem 5](https://puri.sm/products/librem-5/) | [<img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/PostmarketOS_logo.svg" width=15 height=15> postmarketOS](https://wiki.postmarketos.org/wiki/PINE64_PinePhone_(pine64-pinephone)) | [<img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Ubuntu_and_Ubuntu_Server_Icon.png" width=15 height=15> Ubuntu Touch](https://devices.ubuntu-touch.io/device/pinephone/) | [🐧 PureOS (Debian-Based)](https://puri.sm/products/librem-5/pureos-mobile/)

### Community Support

These devices have a strong Linux community and are well-supported by more than one Linux on Phone project OR are *really* well supported by just one project (all modem functionality, cameras, WiFi and Bluetooth at minimum). <!-- TODO: Make a badge for PostmarketOS and Ubuntu Touch and others to display next to these phone names. -->

- Nexus 5 | [<img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/PostmarketOS_logo.svg" width=15 height=15> postmarketOS](https://wiki.postmarketos.org/wiki/Google_Nexus_5_(lg-hammerhead)) | [<img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Ubuntu_and_Ubuntu_Server_Icon.png" width=15 height=15> Ubuntu Touch](https://devices.ubuntu-touch.io/device/hammerhead/)
- OnePlus One | [<img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Ubuntu_and_Ubuntu_Server_Icon.png" width=15 height=15> Ubuntu Touch](https://devices.ubuntu-touch.io/device/bacon/)
- A few others, too! Contributions to this list [are welcome](#contribute).

### Other Devices

A surprising number of Android phones (and, possibly the iPhone 7 soon) can boot Linux, but may have significant issues with the basic functionality you would expect from a phone. If you own one of these devices and can contribute to the effort to making them ready for use, you may want to give them a shot. Fixing a feature on one phone often fixes it for many phones, since devices released in the same year usually have similar components.

- [Can My Phone Run Linux?](https://many.tuxphones.com/) - An excellent site by [Tuxphones](https://tuxphones.com/) that allows you to **search** for devices that boot Linux.
- <img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/PostmarketOS_logo.svg" width=15 height=15> [PostmarketOS Device List](https://wiki.postmarketos.org/wiki/Devices) - A list of devices that can boot into postmarketOS, along with the features they currently support. This page also documents some failed attempts at porting, which might be useful for future successful attempts.
- <img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Ubuntu_and_Ubuntu_Server_Icon.png" width=15 height=15> [Ubuntu Touch Device List](https://devices.ubuntu-touch.io/) - A list of devices that can boot into Ubuntu Touch, with some kind of metric showing the "maturity" of each device.
- <img src="https://nixos.org/logo/nixos-logo-only-hires.png" width=15 height=15> [NixOS Device List](https://mobile.nixos.org/devices/index.html) - A list of devices that can boot into NixOS, no information pertaining to feature support is available.

## Apps

These apps work well on Linux phones, and are in a beta stage or better. Once this list grows large enough, it should be split into categories, perhaps following the Google Play Store.

- [Authenticator](https://gitlab.gnome.org/World/Authenticator) (<img src="https://upload.wikimedia.org/wikipedia/commons/7/71/GTK_logo.svg" width=15 height=15> GTK) - an app for two factor authentication/OTP, features a qr-code scanner and file backups
- [Foliate](https://johnfactotum.github.io/foliate/) (<img src="https://upload.wikimedia.org/wikipedia/commons/7/71/GTK_logo.svg" width=15 height=15> GTK) - a simple and modern ebook viewer, supporting .epub, .mobi, .azw, and .azw3 files
- [Fractal](https://gitlab.gnome.org/GNOME/fractal/) (<img src="https://upload.wikimedia.org/wikipedia/commons/7/71/GTK_logo.svg" width=15 height=15> GTK) - a matrix.org chat client, works decently well on mobile
- [Feeds](https://gabmus.gitlab.io/gnome-feeds/) (<img src="https://upload.wikimedia.org/wikipedia/commons/7/71/GTK_logo.svg" width=15 height=15> GTK) - an RSS feed reader for GNOME, works well in GNOME-based desktop environments
- [VVAVE](https://vvave.kde.org/) (<img src="https://upload.wikimedia.org/wikipedia/commons/8/8d/KDE_logo.svg" width=15 height=15> Kirigami) - a convergent music player that is often shipped with the KDE Plasma Mobile desktop environment
- More? See the lists below for a non-curated listing of apps.

These are some other lists with Linux Phone apps.
- [Librem's List](https://source.puri.sm/Librem5/community-wiki/-/wikis/List-of-Apps-in-Development) - Mostly GTK+ apps that integrate well with their `phosh` mobile desktop shell.
- [Framasoft's List](https://mglapps.frama.io/) - Practically *every* app for mobile GNU/Linux, or apps that could possibly be modified to work on mobile, organized into a table.

## Distributions

These are mobile-specific distributions, or regular distributions that support mobile phones.

- <img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/PostmarketOS_logo.svg" width=15 height=15> [PostmarketOS](https://postmarketos.org/) - Based on Alpine Linux, PostmarketOS is a good lightweight pick that still supports a multitude of mobile interfaces.
- <img src="https://upload.wikimedia.org/wikipedia/commons/1/16/Ubuntu_and_Ubuntu_Server_Icon.png" width=15 height=15> [Ubuntu Touch](https://ubuntu-touch.io/) - A community supported continuation of Canonical's project of the same name, Ubuntu Touch runs the unique Unity-based Lomiri interface and has a decently populated app store.
- <img src="https://nixos.org/logo/nixos-logo-only-hires.png" width=15 height=15> [Mobile NixOS](https://mobile.nixos.org/) - Currently supporting around [10 devices](https://mobile.nixos.org/devices/index.html), and featuring the same desktop Nix package manager in all it's declarative/reproducible goodness.
- <img src="https://maemo-leste.github.io/images/logo.png" width=15 height=15> [Maemo Leste](https://maemo-leste.github.io/) - Currently supports a few older devices (notably, the N900 and the PinePhone).
- And more! You can find a pretty good list at the [PinePhone Software Release](https://wiki.pine64.org/index.php/PinePhone_Software_Release) page, since nearly every (if not every) Linux-on-phone distribution runs on the PinePhone.

## Contribute

Contributions are welcome & encouraged! Be sure to read the [contribution guidelines](CONTRIBUTING.md) first.
