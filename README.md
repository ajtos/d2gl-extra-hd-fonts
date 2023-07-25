# d2gl-extra-hd-fonts
Additional fonts for D2GL's HD Text mode.

![Fontin font screenshot](/screenshots/fontin.png)

[Fontin font](https://www.fontsquirrel.com/fonts/fontin) best known from **Path of Exile** was converted using sdf atlas type. Otherwise there are too many glyph errors. Due to that there are some limitation - you might turn off overshadow for drop items, otherwise it looks weird.

![Antiqua SSK](/screenshots/antiquassk.png)

[Antiqua SSK](https://eng.m.fontke.com/font/10000725/) was font used by **Sacred 2**.

## Usage

Check official D2GL [documentation here](https://github.com/bayaraa/d2gl/wiki/HD-Text)

TL;DR version. Copy `data` into Diablo II base directory, edit `data/assets/atlases/default.txt` depending on what font you want to use, then launch game with `-direct`.
I only provided unchanged `default.txt`, here is entry that was used for taking screenshot as an example:

`14 | AntqSSK | 12.000 | 1.040 | 0.050 | 1.100 | 0.500 | 0.070 | -0.200 | 0.050`
