<h1 align="center">
<br />
wine-platform-runtime
</h1>

<h1 align="center">
<a  href="https://snapcraft.io/wine-platform-runtime">
<img alt="Get it from the Snap Store" src="https://snapcraft.io/static/images/badges/en/snap-store-black.svg" /> </a>
</h1>

<h1 align="left">
<a  href="https://snapcraft.io/wine-platform-runtime">
<img alt="wine-platform-runtime" src="https://snapcraft.io/wine-platform-runtime/badge.svg" /> </a>
</h1>

This snap provides WINE runtime base via content interface to be used by other snaps that are depended on WINE so snap developers that create WINE snaps can leverage this base snap to connect their WINE snaps.

Features:

Snap provides WINE runtime libraries that can be used by these snaps.

- wine-platform-3-stable
- wine-platform-4-(stable|devel|staging)
- wine-platform-5-(stable|devel|staging)

Currently powering the following snaps that are using this snap:

- anifx
- anituner
- cncra
- cncra2yr
- cnctsun
- fooba2000
- irfanview
- leagueoflegends
- liveforspeed
- multicommander
- notepad-plus-plus
- notepad3
- pspad
- resourcehacker
- utorrent
- winsnap
- other snaps that are created by other devs

Note: This snap does not provides any ability to run WIN applications from itself but it only shares libraries and other pkg releases PATHS that are available via content interface.

Support me: https://bit.ly/2XkT2bl