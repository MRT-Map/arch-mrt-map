# arch-mrt-map

To receive packages from this repository, add this to your `/etc/pacman.conf`:
```toml
[arch-mrt-map]
Server = https://mrt-map.github.io/arch-mrt-map/x86_64
SigLevel = Optional TrustAll
```

then run `sudo pacman -Sy`
