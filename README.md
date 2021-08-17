Flex layout

It is type of a layout. It focuses mainly on layout arrangements.
It doesn't support div properties like, float, clear, etc.
It is a container having items that we want to arrange in certain way.

In order to enable flex layout for current container set display property to flex.
After that you can set other required properties to make flexbox working.

Terminologies:
1. Flex container: It is the box that will contain the items.
2. Flex items: These are the contents of flex container.

Container properties:
1. display - enable flexbox layout for particular element

2. flex-direction - set vertical or horizontal axis - i.e. how the elements will flow vertically or horizontally
2.1 flex-direction: row | row-reverse | column | column-reverse;

/*
flex-direction: column;
flex-direction: column-reverse;
flex-direction: row;
flex-direction: row-reverse;
*/

3. flex-wrap - by default flex items will remain on same line. You can change that by setting this property.
3.1 flex-wrap: nowrap | wrap | wrap-reverse;
3.2 nowrap - default - all items on same line
3.3 wrap - items will get wrapped onto multiple lines from top to bottom
3.4 wrap-reverse - items will get wrapped onto multiple lines from bottom to top

4. justify-content - flex-start | flex-end | center | space-between | space-around
4.1 flex-start - items are packed towards the start of flex-direction
4.2 flex-end - items gets packed towards end of flex-direction
4.3 center - items will get centered
4.4 space-between - items will get evenly distributed - first item will be at start position and last will be at last
4.5 space-around - items will get evenly distributed - and there will be equal space around them.

5. align-items: stretch | flex-start | flex-end | center | baseline *
5.1 stretch - stretch to fill the container
5.1 flex-start - items will get placed at start of the cross axis
5.2 flex-end - items will get placed at the end of the cross axis
5.3 center - items will get centered on cross axis
5.4 baseline - items will get arranged corresponding to their baselines

6. align-content: flex-start | flex-end | center | space-between | space-around *


Flex items properties
1. order - set order of particular item - default is 0
5. align-self: auto | flex-start | flex-end | center | baseline;*
2. flex-grow - *
3. flex-shrink - *
4. flex-basis - *