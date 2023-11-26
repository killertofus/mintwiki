<h1 align="center"> Roblox </h1>
----
>Category: Gaming
---
from the [wiki](https://en.wikipedia.org/wiki/Roblox) Roblox is an online game platform and game creation system developed by Roblox Corporation that allows users to program games and play games created by other users.
---
<ol>
<li> Methods to play

<a href="#section-1"> i. [automated](#automated) </a><br />
<a href="#section-1"> ii. [manual](#manual) </a><br />
</li>



---

<ol>

##  automated
the [installer](https://github.com/killertofus/scripts) works by installing [flatpak](), (which is already installed on mint) [vinegar](https://vinegarhq.org/) and [wineGE](https://github.com/GloriousEggroll/wine-ge-custom)
to run it all you need to do is git clone the installer then cd into it then type ./roblox_flatpak_installer.sh
the let it run

## manual
install vinegar from flatpak
```flatpak install io.gitub.vinegarhq.Vinegar```

move [wineGE](https://github.com/GloriousEggroll/wine-ge-custom/releases) to here `~/.local/share/lutris/runners/wine/`

then make the vinegar folder `mkdir -p ~/.var/app/io.github.vinegarhq.Vinegar/config/vinegar`

then make the file `touch ~/.var/app/io.github.vinegarhq.Vinegar/config/vinegar/config.toml`

then add this `echo -e "[global]\nwineroot = \"$HOME/wine-lutris-GE-Proton8-21-x86_64\"\nchannel = \"zavatarteam2\"" > ~/.var/app/io.github.vinegarhq.Vinegar/config/vinegar/config.toml`

then run it `flatpak run io.github.vinegarhq.Vinegar player`
