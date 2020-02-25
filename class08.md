# CSS layouts 
_express the ways to position the elements in the webpage and there is defferant ways to position the elements such as:_
1. **Noraml flow** : _Every block-level element appears on a new line causing each item to appear lower downthe page than the previous one._
2. **Relative position** : _in relative positon the element moves from normal flow to shifting it to the top,right,bottom,or left of where it would have been placed._
3. **absulute position** : _which means that the element has the absulute position dose not affect the position of any surrounding elements_
4. Fixed Positioning his is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element.**Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the use scrolls up or down the page.**
5. Floating elements :_Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box._ **The floated element becomes a block-level element around which other content can flow.**

+ _When you move any element from normal flow, boxes can overlap. The z-index property allows you to control which box appearson top._

#### Clearing floats
_clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:_
+ Left: the left-hand side of the box
should not touch any other
elements appearing in the same
containing element
+ Right : The right-hand side of the
box will not touch elements
appearing in the same containing
element. 
+ Both :Neither the left nor right-hand
sides of the box will touch
elements appearing in the same
containing element.
+ None : Elements can touch either side.

**Many web pages use multiple columns in their design. This is achieved by using a < div > element to represent each column. The following three CSS properties are used to position the columns next to each other**
_this is the following css rule that we used to handle the divs_
1. **height:** _specify the height of the box_
2. **Width:** _specify the width of the box_
3. **margins:**_specify and create a gap between coloumn_


### Fixed width layout
_designs do not change size as the user increases or decreases the size of their browser window. **Measurements tend to be given in pixels.**_

### Liquid layout designs
_stretch and contract as the user increases or decreases the size of their browser window. **They tend to use percentages.**_
### A Fixed Width Layout
_To create a fixed width layout,the width of the main boxes on a page will usually be specified in pixels (and sometimes their height, too)._
### Layout grids 
Composition in any visual art (such as design, painting, or photography)
is the placement or arrangement of visual elements — how they are
organized on a page. Many designers use a grid structure to help them
position items on a page, and the same is true for web designers.