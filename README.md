# Crimson Pro S

A slightly modified version of [Crimson
Pro](https://github.com/Fonthausen/Crimson).

Crimson Pro S differs from Crimson Pro in a few stylistic details: sharper
terminals, straight-legged capital R, slightly resized punctuation, somewhat lighter-leaning
weight distribution.

It's no better or worse than the original Crimson Pro by [@Fonthausen](https://github.com/Fonthausen), just a little different.

<img src="https://raw.githubusercontent.com/skosch/CrimsonProS/master/specimen/comparison.png" width="1011">
<img src="https://raw.githubusercontent.com/skosch/CrimsonProS/master/specimen/waterfall.png" width="1011">

## Building the weight instances

Clone this directory, install [fontmake](https://github.com/googlei18n/fontmake)
(I recommend using a virtualenv), and run

```
fontmake -m CrimsonProS_Roman.designspace -o otf -a -i
```
and

```
fontmake -m CrimsonProS_Italic.designspace -o otf -a -i
```
