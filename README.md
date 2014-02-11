floodfill.js
============

this code give the basics for how to take a 2d array, pass a point of origin, then return the total number
of spaces that meet a certain parameter (e.g. # of contiguous cells with a value of -1 starting from origin)

this will modify whatever array is passed, so it needs to not have data you expect to keep.

the resultant data can be used to see if there is a path between the origin and any other cell.
  This assumed that -1 denoted an "open space" so checking to see if a location's value now == valUse
  means it was part of the touching open-space.
