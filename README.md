SRL Resource Library
=====================

SRL is a library that provides an API for writing bots in Simba for the game Old School RuneScape.

We use the stable build of Simba 1400: https://github.com/Villavu/Simba/releases/tag/simba1400-release

And we support Jagex's new official OSRS client: https://help.jagex.com/hc/en-gb/articles/17160273294097-Jagex-Launcher-FAQ

API documentation is available [here](https://villavu.github.io/SRL-Development)

## Usage

We only support the New Official Client from the Jagex Launcher. Thus we only support Windows (and macOS should work too but hasn't been tested yet). We use 64-bit Simba even though the Jagex Launcher is a 32-bit application. We do NOT use RemoteInput or abstract the mouse in any way - this is the responsibility of the user's environment.

To use most scripts, your client options must match ours:

![image](https://github.com/KeepBotting/SRL-Development/assets/7429071/7ba0340c-d148-4ac0-849a-ffbad57d8da0)

![image](https://github.com/KeepBotting/SRL-Development/assets/7429071/d6f25a82-82de-4e37-aa4a-d823dfe41246)

![image](https://github.com/KeepBotting/SRL-Development/assets/7429071/69b5adda-c910-41ff-b360-8eb54a47d1b7)


## Features

<img src="docs/images/resizable.png" width="738" height="600">\
*Resizable mode*

<img src="docs/images/mm2ms.png" width="734" height="662">\
*Minimap to mainscreen projection*

<img src="docs/images/walker.png">\
*Detecting position on the world map*

<img src="docs/images/webber.png" width="650" height="650">\
*Web walking system (does not handle obstacles)*
