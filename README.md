This is a mirror of http://carnage-melon.tom7.org/embed/ for archival purposes. It has worked really well for me in conjunction with [the crimson font](http://sourceforge.net/projects/crimsontext/).

# embed

According to [Microsoft's TrueType Specifications](http://www.microsoft.com/typography/tt/tt.htm), which will change the embedding level of a TrueType font. Alot of fonts [like these by Tom Murphy](http://fonts.tom7.com/) had their embedding set in a very restricting manner. Microsoft's [font properties](http://www.microsoft.com/typography/property/fpedit.htm)  editor does not let you lower this setting (though you can make the license more restrictive).

This program will quickly and automatically set the font to 'installable embedding allowed', the least restrictive setting. You can use Microsoft's editor to make it a more restrictive value, or change it in the source code, if you really require a different embedding level.

To run it, simply give it the name of the ttf file on the command line:

    embed font.ttf

No error messages signifies success.

## Files

`embed.c` [ 2k ] - Source code in C, if you want to play around with it or compile for a non-windows platform.

Both the program and source are in the public domain. Enjoy.

NOTE: Changing the embedding value does not give you license to distribute the fonts. You should only change this setting if you are the font creator, or something like that. Use at your own risk.

Be Back at Tom 7's CMU Page.
Be Productive.

## Links

[Original Author Homepage](http://carnage-melon.tom7.org/index.html)

[Be Productive](http://carnage-melon.tom7.org/mana/be.html)
