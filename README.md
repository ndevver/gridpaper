# gridpaper
Simple but powerful browser based grid generator.

The web page will simply have a text box, and a canvas. In order to add grid
lines, you'll be able to write in kthe text box using a simple notation with
commas, spaces, and linebreaks that will indicate the parameters for the grid.
The grid will be rendered each time the contents of the text box change,
set on an interval of 5 seconds or so.

The first line is for the canvas size. All proceeding lines contain one grid
descriptor per line. A line with only numbers will default to a black one pixel
thick grid line. This is because it will be easier to change the numbers to get
line spacing and placement, then copy and pasting can overide that with colored
lines with other variables being set.

The first line is invisible and starts at 0, and the first visible line starts
at 'a', and 'b'. So a simple grid can be made with two numbers, 'a', and 'b',
or 'abcd', for vertical, and horizontal. The number of values on a line will
determine which format is being used.

Grid line descriptors will come in the form of triplets, i.e. 1, 5, 10, with
the first value being the width of the lines, the second bei:withng horizontal
spacing, and the third being vertical spacing.

Added grid background color, and page background color.
Added URL bookmarking of grid parameters.

TODO: Add transparency style dual color grid with filled squares.
This shouldn't be very hard to accomplish by just adding another route
that checks for 4 arguments on a grid line instead of 3.