# gridpaper
Simple but powerful browser based grid generator.

The web page is simply have a text box, and a canvas. In order to add grid
lines, you'll be able to write in the text box using a simple notation with
commas, spaces, and linebreaks that will indicate the parameters for the grid.
The grid will be rendered each time the contents of the text box change,
set on an interval of 5 seconds or so.

The first line is for the canvas size. All proceeding lines contain one grid
descriptor per line. 

Grid line descriptors come in the form of triplets, i.e. 1, 5, 10, with
the first value being the width of the lines, the second being horizontal
spacing, and the third being vertical spacing.

Grid block descriptors have two values, one for horizontal size, and one for
vertical. This creates a grid similar to a background transparency grid.

[512x512, with 16x16, and 64x64 grids](https://ndevver.github.io/gridpaper/?gray%20white%0A512,%20512%0A#d8d8d8%0A1,%2016,%2016%0A#aaaaaa%0A1,%2064,%2064%0A)