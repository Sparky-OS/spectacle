<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/sparky-stereo-os/sparkyos-swirl-light-128.png">
  <img src=".github/sparky-stereo-os/sparkyos-swirl-dark-128.png" alt="SparkyOS" width="128" height="128">
</picture>

## Sparky Stereo OS

This is the stereo version of Spectacle by Sparky Stereo OS, forked from [KDE/spectacle](https://github.com/KDE/spectacle).
It saves stereo screenshots as JPS and as MPO (CIPA DC-007 Multi-Picture Format) pictures.

Where it comes from:

- [Spectacle](https://invent.kde.org/plasma/spectacle) is made by the KDE community. Its authors are Boudhayan Gupta, David Redondo and Noah Davis.
- [Debian](https://www.debian.org/) is the base of the system.
- [SparkyLinux](https://sparkylinux.org/), by Paweł "pavroo" Pijanowski, builds on Debian.
- [Sparky Stereo OS](https://github.com/Sparky-OS/sparky-stereo-os) is the stereo 3D edition of SparkyLinux: SparkyOS, powered by Debian.

The `stereo3d` branch holds the version the distribution builds.
KDE develops Spectacle on invent.kde.org.
The canonical version of this work is there too, on the [`stereo3d`](https://invent.kde.org/danielcamposramos/spectacle/-/tree/stereo3d) branch.
The licences are unchanged; see [LICENSES](LICENSES).

Sparky Stereo OS, Daniel Ramos's edition of SparkyLinux (by Paweł "pavroo" Pijanowski).

---

# <img src="logo.png" width="48"/> Spectacle - The KDE Screenshot Utility

Spectacle is a screenshot taking utility for the KDE desktop. Spectacle
can also be used in non-KDE X11 desktop environments.

![Screenshot of Spectacle](https://cdn.kde.org/screenshots/spectacle/spectacle.png)

## Get help
You can get help in :
* Forum: https://discuss.kde.org/tag/spectacle
* Matrix: https://matrix.to/#/#kde:kde.org
* IRC: irc://irc.libera.chat/kde
## Contributing

Spectacle is developed under the KDE umbrella and uses KDE infrastructure
for development.

Please see the file [`CONTRIBUTING`](./CONTRIBUTING.md) for details on coding style and how
to contribute patches. Please note that pull requests on GitHub aren't
supported. The recommended way of contributing patches is via KDE's
instance of GitLab at https://invent.kde.org/plasma/spectacle.

When building Spectacle yourself (including when using kde-builder), you may
find that Spectacle is not authorized to take screenshots or recordings with
your system's installed KWin. To work around this, you can either also build
KWin from source, or use the `KWIN_SCREENSHOT_NO_PERMISSION_CHECKS=1`/\
`KWIN_WAYLAND_NO_PERMISSION_CHECKS=1` environment variables in your session.

## Release Schedule

Spectacle is released by KDE's release service and has three
major releases every year. They are numbered YY.MM, where YY is the two-
digit year and MM is the two-digit month. Major releases are made in April,
August and December every year. The Spectacle version follows the KDE
release service version.

## Reporting Bugs

Please report bugs at KDE's Bugzilla, available at https://bugs.kde.org/.

For discussions, the `#kde-devel` IRC channel and the kde-devel mailing list
are good places to post.
