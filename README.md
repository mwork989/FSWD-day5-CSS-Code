
W3c Link for all css properties - https://www.w3.org/Style/CSS/all-properties  


All CSS properties very rarely will be used in projects
best and efficient way to learn css is to categorize it based on
its area


1. Layout 
    1. display 
               block : generate a block-level box
               inline : generate an inline-level box we cannot height and width
               inline-block : generate a combination of an inline-level box that flows within text content and a block-level box that respects width and height properties. It's often used for creating inline elements that can have a fixed width or height.
               inline-flex : Inline-flex elements behave similarly to inline elements, but they have a flexible container inside
               inline-table: Inline-table elements behave as inline elements but contain a table. Here's an example:
               none: does not showcase any element in page
    2. position 
    3. top, right, bottom, left 
    4. float 
    5. Flexbox
    6. Grid
    
2. Box Model:
     width
     max-width
     min-width
     height
     max-height
     min height
     margin
     padding
     border
     box-sizing


3. Typography
     font-family
     font-size
     font-weight
     font-style
     


4. Color
       color:

       
5. Text
      letter-spacing 
      word-spacing
      line-height
      text-align
      text-decoration
      text-transform

6. Links
       Pseudo classes 
          a:link, a:visited, a:hover
         
7. Background
         background
         background-color
         background-image
         background-repeat
         background-size
        
8. Lists
          list-style-type
          list-style-image

9. Transitions & Animations
      transition-property
      transition-duration
      @keyframes
      animation

10. Transformations   
          transform





flex-flow:

The flex-flow property is a shorthand property for setting both the flex-direction and flex-wrap properties in one declaration. It allows you to specify how flex items are arranged within a flex container. e.g.  flex-flow: row wrap;

flex-wrap

The flex-wrap property, when used by itself, specifically controls whether flex items should wrap or not within a flex container. e.g.flex-wrap: wrap;


CSS units can be broadly categorized into following

Absolute Units:
---------------------
px (pixels)      - 1px = 1/96th of 1in  -use this measurement when one needs to be precise and consistent across different devices and screens. commonly used 
    1.defining the size of elements e.g. height width of HTML elements
    2.spacing between two elements 

in (inches)      - 1in = 2.54cm = 96px
cm (centimeters) - 1cm = 37.8px = 25.2/64in
mm (millimeters) - 1mm = 1/10th of 1cm
    Thse units are commonly used in print media 


pt (points)      - 1pt = 1/72nd of 1in
pc (picas)       - 	1pc = 1/6th of 1in
 Thse units are commonly used when importance is given typography text and print media will adjsut the setting while printing based on this

Relative Units:
--------------------
em (relative to the font-size of the element) - used based on font 
ex (relative to the x-height of the font)
ch (relative to the width of the "0" character)
rem (relative to the font-size of the root element) - used based on font 
vw (relative to 1% of the viewport width)  - during targetting the small to medium devices
vh (relative to 1% of the viewport height) - during targetting the small to medium devices
vmin (relative to 1% of the viewport's smaller dimension)
vmax (relative to 1% of the viewport's larger dimension)
% (percentage, relative to the parent element or the viewport) - most commonly used
responsiveness 


Viewport-percentage Units: used inn mobile as well medium screen devices dimensioning 
------------------------
vw (viewport width)
vh (viewport height)
vmin (viewport minimum dimension)
vmax (viewport maximum dimension)


Angle Units: used in animation and css transitions
----------------
deg (degrees)
rad (radians)
grad (gradients)
turn (a full turn)

Duration Units:used in animation and css transitions
----------------------
s (seconds)
ms (milliseconds)

Frequency Units: Use for defining audio or video frequencies.
--------------------
Hz (hertz)
kHz (kilohertz)

Resolution Units: defining the resolution of screens and images.
-------------
dpi (dots per inch)
dpcm (dots per centimeter)
dppx (dots per pixel)
