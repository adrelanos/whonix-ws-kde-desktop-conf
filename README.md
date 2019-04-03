# KDE Desktop Settings for Whonix-Workstation #

Enables KDE folderview (allows desktop shortcuts) and sets Whonix-Workstation
specific wallpaper.

For better usability.

This package only takes effect for newly created user accounts. Not for
existing user accounts. This package is most useful to help Linux distribution
maintainers setting divergent defaults.
## How to install `whonix-ws-kde-desktop-conf` using apt-get ##

1\. Add [Whonix's Signing Key](https://www.whonix.org/wiki/Whonix_Signing_Key).

```
sudo apt-key --keyring /etc/apt/trusted.gpg.d/whonix.gpg adv --keyserver hkp://ipv4.pool.sks-keyservers.net:80 --recv-keys 916B8D99C38EAF5E8ADC7A2A8D66066A2EEACCDA
```

3\. Add Whonix's APT repository.

```
echo "deb http://deb.whonix.org buster main" | sudo tee /etc/apt/sources.list.d/whonix.list
```

4\. Update your package lists.

```
sudo apt-get update
```

5\. Install `whonix-ws-kde-desktop-conf`.

```
sudo apt-get install whonix-ws-kde-desktop-conf
```

## How to Build deb Package ##

Replace `apparmor-profile-torbrowser` with the actual name of this package with `whonix-ws-kde-desktop-conf` and see [instructions](https://www.whonix.org/wiki/Dev/Build_Documentation/apparmor-profile-torbrowser).

## Contact ##

* [Free Forum Support](https://forums.whonix.org)
* [Professional Support](https://www.whonix.org/wiki/Professional_Support)

## Payments ##

`whonix-ws-kde-desktop-conf` requires [payments](https://www.whonix.org/wiki/Payments) to stay alive!
