You will need to get a copy of batik, the apache SVG tool, from
http://xmlgraphics.apache.org/batik/ and unpack it in the lib
subdirectory.  The makeOTF script is set to use batik-1.7, so you may
need to edit it to call the version you have.

You also need sfnt2woff from http://people.mozilla.org/~jkew/woff/ in
order to make the woff versions of the fonts.
