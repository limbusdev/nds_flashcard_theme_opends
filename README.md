# openDS Flashcard Theme

![](src/supercard_dstwo/plugin_menu/PNG/up_bk.png)

openDS is an open source flashcard theme / skin for cartridges that enable playing homebrew on the NDS, 2DS and 3DS.

# Supported Devices

|SuperCard DSONE|SuperCard DSTWO|DSTWO Plugin-Menu|Wood / R4i 3DS Gold Plus|YSMenu|
|-|-|-|-|-|
|![](screenshots/screenshot_dsone.png)|![](screenshots/screenshot_dstwo.png)|![](screenshots/screenshot_dstwo_plugin.png)|![](screenshots/screenshot_wood.jpg)|![](screenshots/screenshot_ysmenu.png)|
|[Download](https://github.com/gembutterfly/nds_flashcard_theme_opends/raw/master/downloads/openDS_for_supercard_dsone.zip)|[Download](https://github.com/gembutterfly/nds_flashcard_theme_opends/raw/master/downloads/openDS_for_supercard_dstwo.zip)|[Download](https://github.com/gembutterfly/nds_flashcard_theme_opends/raw/master/downloads/openDS_for_r4i_wood.zip)|[Download](https://github.com/gembutterfly/nds_flashcard_theme_opends/raw/master/downloads/openDS_for_ysmenu.zip)|

# Important Notice

I do not support or approve video game piracy in any form. If you want to play a game, buy it, to reward the developers of it and to make sure more great games are developed in future.

Video game piracy leads to **stupid, short, advertisement infested** games.

Buy games and use flashcards to play homebrew or copies you made yourself from your own games. Do not use my work with stolen games!

# Disclaimer

SuperCard, Nintendo, DSTWO, NintendoDS and all other used trademarks belong to their respective owners. I claim no rights on them. Please contact them prior using their property.

# Copyright

openDS themes for NDS flashcards are licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).

# Used Software

Graphics made with [GIMP](https://www.gimp.org/) and [Inkscape](https://www.inkscape.org/).

# How to make your own graphics

## For SuperCards and Wood

Note down the dimensions of the graphic, you want to design. Design it with GIMP or Inkscape. Export it to PNG. Open it with GIMP and export it to a 16 Bit Windows-Bitmap with:

***File** > **Export** > **Windows-Bitmap** > **Advanced Options** > **16 Bit** > **X1 R5 G5 B5***

This leads to far better quality then the 16 bit conversions of the various skin editors.

## For YSMenu

***File** > **Export** > **Windows-Bitmap** > **Advanced Options** > **24 Bit** > **R8 G8 B8** > **Compatibility Options** > **Don't write Color Space Information***

The color values in YSMenu are a little bit strange. The Format is

|-|B|G|R|
|-|-|-|-|
|1 Bit|5 Bit|5 Bit|5 Bit|

Examples:

|Color|-|B|G|R|
|-|-|-|-|-|
|White|1|11111|11111|11111|
|Black|1|00000|00000|00000|
|Blue|1|11111|00000|00000|
|Green|1|00000|11111|00000|
|Red|1|00000|00000|11111|

Finally convert it to a Hex number with 4 positions.


