# color-palettes

A collection of manually compiled color palettes, packaged as a Processing library.

## Installation
Clone this repository into the Processing libraries directory `/Processing/libraries/`.

## Usage
```processing
import processing.palettes.*;

Palettes p;

def setup():
  size(1000, 1000);

def draw():
  Palettes p = new Palettes(this);
  println(p.paletteNames);
  p.loadPalette("flag");
```

## Overview
<p align="center"><img src="resources/overview.png" alt="overview" width="700"/></p>

## Resources
Useful documentation and similar projects for implementing a custom Processing library.

- [Processing Library Template](https://github.com/processing/processing-library-template)
- [Processing Library Basics](https://github.com/processing/processing/wiki/Library-Basics)
- [federico-pepe/nice-color-palettes](https://github.com/federico-pepe/nice-color-palettes)
- [iMikie/Create_Processing_Library](https://github.com/iMikie/Create_Processing_Library)
