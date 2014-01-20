SkeleType
=========

A module for character rendering engines that takes glyphs for 
characters in some fonts but not others and attempts to redraw 
them in a font with which they have not been included, based on 
the "style" of the target font. For example, on Windows, the 
Han characters are included with MS Mincho but not with more 
common fonts such as Arial. The program would use the Han 
character glyphs from MS Mincho to generate glyphs with 
Arial-specific design elements.

The process can be simplified by creating a "base font" with 
only the basic shapes of character glyphs and no embellishments. 
Characters to be rendered are derived from the base font with 
aesthetic elements specific to the target font.

### Categories
* Pattern recognition
* System utilities
