# nix-installers
These are my custom nix installers

# Regular Installer

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/nix-installers/main/regular-installer-no-selinux.sh && chmod a+x ./regular-installer-no-selinux.sh && ./regular-installer-no-selinux.sh ; rm ./regular-installer-no-selinux.sh
```

# [Installers for SELinux based systems](https://github.com/dnkmmr69420/nix-with-selinux)

## Regular installer for mutable linux with selinux

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/nix-with-selinux/main/regular-installer.sh && chmod a+x ./regular-installer.sh && ./regular-installer.sh ; rm ./regular-installer.sh
```

## Nix installer for silverblue

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/nix-with-selinux/main/silverblue-installer.sh && chmod a+x ./silverblue-installer.sh && ./silverblue-installer.sh ; rm ./silverblue-installer.sh
```

# Nix app icons

## Multiuser

Type this command

```bash
sudo wget -P /etc/profile.d https://raw.githubusercontent.com/dnkmmr69420/nix-installers/main/nix-app-icons.sh
```

## Singleuser

add this to the end of ~/.bashrc

```bash
XDG_DATA_DIRS="$HOME/.nix-profile/share:/nix/var/nix/profiles/default/share:$XDG_DATA_DIRS"
```

# Nix Uninstallers

## Regular uninstaller for selinux and non selinux systems

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/nix-uninstallers/main/regular-uninstaller.sh && chmod a+x ./regular-uninstaller.sh && ./regular-uninstaller.sh ; rm ./regular-uninstaller.sh
```

## Silverblue uninstaller

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/nix-uninstallers/main/silverblue-nix-uninstaller.sh && chmod a+x ./silverblue-nix-uninstaller.sh && ./silverblue-nix-uninstaller.sh ; rm ./silverblue-nix-uninstaller.sh
```

## [nix uninstallers github repo](https://github.com/dnkmmr69420/nix-uninstallers)
