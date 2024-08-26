# SMW Font

A pixel font adapted from Super Mario World

(https://www.youtube.com/watch?v=V7oGZcy2vxo)

## About this font

This is a recreation of the font used in the SNES game *Super Mario World*, as a modern computer font. I changed a few characters so they look nicer, and added a couple of new characters. It was made using [YellowAfterlife](https://yal.cc)'s pixel font converter (https://yal.cc/r/20/pixelfont).

The inspiration for this project is "ILLUSIYELLOW" by ssaamm (?), an earlier and more limited font that set out to do the same thing.

## Variants

### SMW
The regular font. This is suitable for everyday use with large font sizes (where the font pixels are larger than the screen pixels).

### SMW Whole-Pixel Spacing
Same as the SMW font above, but the space between characters is always a whole number of pixels (never half a pixel). This is suitable for cases where the screen pixels are the same size as the font pixels, so the screen doesn't have to render anything small than a pixel.

### SMW Monospace
A monospace (fixed-with) font where every character takes up the same space. Some characters are different so they make better use of space. You could use this as a novelty programming font if you're so inclined.

There are no separate bold or italic variants.

## Usage

Install the .ttf or .otf files found in the Releases section.

## Extending this font with your own characters

You can edit this font yourself, the same way I made it:

1. Go to https://yal.cc/r/20/pixelfont.
2. Click "Pick image" and select the image (either SMW.png or SMW Monospace.png, depending on which font variant you're editing).
3. Click "Menu --> Import settings" and select the settings file (.json).
4. Make changes as you see fit. (If you're planning to make a pull request, see CONTRIBUTING.md.)
5. Click "Save TTF".

Note that the space character will always be blank in the generated font file, but its width depends on what the character looks like in the image (that's why there's a dot in the top left).

Also note that the generated font files (both TTF and OTF) apparently don't support kerning. (And if you select OTF in the "Output" tab, the kerning won't even apply to the preview text.) I've found that when you convert OTF to TTF (and vice versa) using an online converter such as cloudconvert, both OTF and TTF work.

