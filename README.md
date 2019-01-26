In this repository I present interactive games solutions

FLEX CSS:

- justify-content - aligns items within the main axis and
accepts the following values: flex-start, flex-end, center,
space-between, space-around;
- align-items - aligns items with cross axis and accepts 
the following values: flex-start, flex-end, center, baseline,
stretch
- align-content - set how multiple lines are spaced apart from
each other. This may be confusing, but align-content determines
the spacing between lines, while align-items determines how
the whole items are aligned within the container. It takes the
following values: flex-start; flex-end; center; space-between;
space-around; stretch (lines are stretched to fit the container)
- flex-direction - defines the direction items are placed 
in the container, and accepts the following values:
row, row-reverse, column, column-reverse
- order - property to individual items. By default, items have a value
of 0, but we can use this property to set it to a positive or negative integer v$
- align-self - apply to individual item and accepts the same values 
as align-items
- flex-wrap - spread out the items and accepts the following
values: nowrap, wrap, wrap-reverse
- flex-flow - the combination of flex-direction and flex-wrap, e.g.
flex-flow: row wrap.

GRID CSS:
- grid-column-start - specifies a grid item's start position
- grid-column-end
- grid-column - e.g. grid-column: 2/4, grid-column: 2/ span 3 
- grid-row-start
- grid-row-end
- grid-row
- grid-area: grid-row-start / grid-column-start / grid-row-end / grid-column-end
- grid-template-rows
- grid-template-column
- grid-template- the combination of grid0template-columns and grid-template-rows
e.g. grid-template: 50% 50% / 200 px - two rows with 50px each and one column 200 px
/

CSS selectors:
- .classname - select all elements with that class atribute. Elements can only have one ID, but many classes
- A.classname - combine the class selector with other selector
- A, B - comma combinators - combine selectors more than two
- A* - selects all elements inside of A
- A + B - -selects all B elements that directly follow A. Elements following one another are called siblings. They are on the same level, or depth
- A~B - like the (A+B) selector except it gets all of the following elemens instead of none. Selects all B that follow A
- A>B selects all B that are that are a direct children A
- :first-child - selects all first child elements
- :only-child - select any elements that is the only element inside of another one
- :last-child- 
- :nth-child(A) - Nth Child Pseudo-selector, A-number of child
- :nth-last-child(A) - select the children from the bottom of the parent, e.g. :nth-last-child(2) - selects all second to last child
- first-of-type- e.g. span:first-of-type - selects the first span in any elements
- nth-of-type(A) - select a specific element based on its type and order in another element or even or odd. e.g. .example:nth-of-type(odd)
- only-of-type - selects the elements that are the only ones of their type within their parent element
-last-of-type
- empty - selects elements that don't have any pther elements inside of them
- not (X) - select all elements except selector "X"
- [attribute] 
- [attribute="value"]
- [attribute^="value"]
- [attribute$="value"]
- [attribute*="value"]
