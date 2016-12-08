<h1>'\'#LJ Code 201 - Day7'</h1>
<p>
1. Block Level html elements start on a new line and are the building blocks
of a layout. examples include <h>, <p> <ul>, <li>

2. Inline Element flow between surrounding test controlling the space each box
takes up by setting the width of boxes. examples include <img> <b> <i>

3. Containing Elements hold or contain other block level elements.  examples
we might have a div that contains a header, the div would be called the containing element

Positioning Schemes
4. Normal Flow: block level elements appear vertically down the page on a new line below one another.. the default position is position:static.  You don't need to indicate this.

5.  Relative Positioning: Moves an element from its normal position shifting it to the top, right, bottom or left of where it would have been placed, not impacting surrounding elements. position:relative requires that you then use top, left, bottom, right to indicate how far to move the element from where it would have been in normal flow..

6. Absolute Positioning:  positions the element in relation to its containing
element.  It doesn't impact surrounding elements.  These elements move as users scroll up and down the page. position:absolute This makes the other elements on the page act as if the absolute positioned element isn't there.  requires that you us the top, left, width etc to prevent text from overlapping.

  a. Fixed positioning: is a form of absolute positioning and positions the element in relation to the browser window as opposed to the containing element.  These elements do not impact surrounding elements and they DO NOT move when the user scrolls up or down the page.  position: fixed this will cause the element to stay in the exact same place if the user scrolls up or down.

7.  Floating elements: allows you to take the element out of normal flow and position it to the far left or right of the containing box.  This element becomes a block-level element around which other content can flow.
  WHEN YOU REMOVE AN ELEMENT FROM NORMAL FLOW, BOXES CAN OVERLAP, THE Z-INDEX PROPERTY ALLOW YOU TO CONTROL WHICH BOX APPEARS ON TOP.  Use the WIDTH element to indicate how wide the floated element should be.
      a. Placing elements side by side (use the width property)
      b. Clearing floats - the clear property allows you to say no element within the same containing element should touch the lf or rt hand sides of the box.  The clear property is a .clear in css see page 372.
      c. for parents of floated element problems/solutions see pages 373 & 374
      d. creating multi-column layouts with floats - use the <div> element to represent each colmn.  Then use the width, float and margin to set the width, position the columns nexst to each other and create a gap between them.

  8. Overlapping Elements can occur when using relative, fixed or absolute positioning.  Use z-index with a number (z-index: 10;)  This controls which element sits on top.  An element with a higher z-index will sit on top of one with a lower z-index.


</p>
