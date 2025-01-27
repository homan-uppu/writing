Greats is an animating, moving grid of portraits of some of the greatest people to walk the earth.  
  
the list of greats is attached:  
  
each great in the list has a corresponding portrait image located in /greats/<last_name>.png.

The grid is a set of rows, each row with images.
Create GridItem component that is just the portrait image with a label at the bottom right of the image.
The size of GridItem depends on the screen width: 4 images should take up the entire width of the screen (minus 48px).

use framer motion to make the rows move to the right.

because 4 images span the screen, have 6 images per row so that there's room move them to the right.

loop the animation. make the animation quite slow.

for the state, just set the greats i provided above in the state, not just as an array of names, but rather, array of { name, src, displayName}, and the displayName is just the last name. in cases where there's a middle name, the displayName is the middle + last name (e.g. Da Vinci).

