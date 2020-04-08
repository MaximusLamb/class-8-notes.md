# Layout
## Positioning Schemes
### Normal Flow
### position: static;
* Every block-level element appears on a new line, causing each item to apear lower down the page than the previous one.
### Relative Positioning
### position: relative;
* This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.
### Absolute Postitioning
### position: absolute;
* This positions the element in relation to its containing element. Absolutely positioned elements move as users scroll up and down the page.
### Fixed Positioning
### position: fixed;
* This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with this positioning do not move when the user scrolls up or down the page.
### Floating Elements
### float: left or right;
* Floating an element allows you to take that element out of normal flow and position it to the far left or right of a contained box.
## When you move any element from normal flow, boxes can overlap.  The **z-index** property allows you to control which box appears on top.
* **z-index** is how you control which elements sit on top of which other elements. The higher the number the higher its positioning.
## Clearing Floats
* The clear property allows you to say that no element should touch the left or right hand sides of a box.
### clear: left;
### clear: right;
### clear: both;
### clear: none;
* **clear: none** means elements can touch either side.
## Creating multi-column layouts with floats
* Many web pages use multiple columns in their design.  This is achieved by using a ```<div>``` element to represent each column.
### width
* Sets the width of the column.
### float
* This positions the columns next to each other.
### margin
* This creates a gap between the columns.
## Fixed Width Layouts
* Fixed width layout designs do not change size as the user increases or deceases the size of their browser window.  Measurements tend to be given in **pixels**.
## Liquid Layouts
* Liquid layout designs stretch and contract as the user increases or decreases the size of the browser window.  They tend to use **percentages**.