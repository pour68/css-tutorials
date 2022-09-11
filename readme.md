# CSS

![css Tutorials](https://github.com/pour68/css-tutorials/blob/master/images/CSS-Header.jpg "css Tutorials")

## History

- Founder: w3c (Wium Lie and Bert Bos)
- Birthdate: 17 December 1996
- versions: css1 - css2 - css2.1 - css3 - css4
- Goals: style web pages
- Mime-type: text/css

![authors](https://github.com/pour68/css-tutorials/blob/master/images/authors.jpg "authors")

---

## CSS definition

Cascading stylesheet

---

## CSS Analogy

- Interface of building
- Interface of human-body

---

## CSS file extension

.css

---

## Selectors

- Global
- Element
- Class
- Id
- Attribute

---

## Syntax

selector {
    property: value;
}

---

## CSS reference methods

- inline
- internal
- external

---

## override CSS property

!important

``` The !important rule in CSS is used to add more importance to a property/value than normal. ```

---

## Comments

- ``` /*comment*/ ```

---

## Color

- name
- hex
- rgb - rgba
- hsl - hsla

![color-wheel](https://github.com/pour68/css-tutorials/blob/master/images/color-wheel-bg.jpg "color-wheel")

### Color theory

- Monochromatic
Uses one hue with different saturation and brightness
- Analogous
Uses colors that are next to each other on the wheel
- Complimentary
Uses color that are opposite sides of the color wheel
- Triadic
Uses three colors that are evenly spaced

### Color theory tricks

- Harmony: color should work well together using the principles of color theory.
- Scalable additive: should have multiple shades of grey and law saturated colors, could have a systematic pattern which can be added to as the needs of design system grows.
- Tint your colors with your brands: Tint your grays and black with a hint of your brand color.
- Accessible: A color contrast, visual presentation of text must 4:5:1 contrast ratio in every UI components.

### Practical color

- Choose your base color: A primary or dominant color of your UI, usually your brand color.
- Choose swatches near your base color: This color will support hover, active and focus states for the base color in actionable elements such as button, links and form elements.
- Choose your darkest color and greys: These swatches are most often used an accents, backgrounds, or to give visual weight to a UI element in both dark and light interfaces.

---

## Opacity

opacity: 0-1

---

## Units

- absolute (px cm inch)
- relative (% vh vw em rem)

---

## Box-Model

### width - min-width - max-width

width: auto | size | %

- width: is used to set width of an element.
- min-width: is used to set the minimum width of an element.
- max-width: is used to set the maximum width of an element.

### height - min-height - max-height

height: auto | size | %

- height: property is used to set height of an element.
- min-height: is used to set the minimum height of an element.
- max-height: is used to set the maximum height of an element.

### Padding

Padding is used to create space around an element's content, inside of any defined borders.

- padding-top
- padding-right
- padding-bottom
- padding-left
- padding: top right bottom left | top right/left bottom | top/bottom right/left | top/right/bottom/left

---

### Margin

Margins are used to create space around elements, outside of any defined borders.

- margin-top
- margin-right
- margin-bottom
- margin-left
- margin: top right bottom left | top right/left bottom | top/bottom right/left | top/right/bottom/left

``` margin collapse does not happen on left and right margins, Only top and bottom margins. ```

---

### Border

The CSS border properties allow you to specify the style, width, and color of an element's border.

- border-width
- border-style
- border-color
- border: width style color
- border-direction
- border-dirrection-width
- border-dirrection-style
- border-dirrection-color

``` direction: top|right|bottom|left ```

#### Border functionality

- border: Sets all the border properties in one declaration
- border-color: Sets the color of the four borders
- border-style: Sets the style of the four borders
- border-width: Sets the width of the four borders
- border-direction: Sets all the direction border properties in one declaration
- border-direction-width: Sets the width of the direction border
- border-direction-style: Sets the style of the direction border
- border-bottom-color: Sets the color of the direction border

---

### Outline

An outline is a line drawn outside the element's border.

- outline-width: thin|medium|thick|size
- outline-style: dotted|dashed|solid|double|groove|ridge|inset|outset|outlinenone|hidden
- outline-color: color
- outline-offset: size
- outline: width style color

#### Outline functionality

- outline-width: Sets the width of an outline
- outline-style: Sets the style of an outline
- outline-color: Sets the color of an outline
- outline-offset: Specifies the space between an outline and the edge or border of an element
- outline: A shorthand property for setting outline-width, outline-style, and outline-color in one declaration

``` None of the other outline properties will have ANY effect unless the outline-style property is set! ```

---

## Rounded corners

border-radius: top-left top-right bottom-right bottom-left
border-vdirection-hdirection-radius: size

### Rounded corners functionality

- border-radius: A shorthand property for setting all the four border-*-*-radius properties
- border-vdirection-hdirection-radius: Defines the shape of the border of the vdirection-hdirection corner

---

## Box-sizing

Defines how the width and height of an element are calculated: should they include padding and borders, or not.

- box-sizing: border-box

---

## Background

- background-color: color
- background-image: url(address)
- background-size: contain | cover | auto | width height
- background-position: top | left | right | center | posX posY
- background-attachment: local | scroll | fixed
- background-repeat: no-repeat | repeat-x | repeat-y | round | space
- background-clip: content-box | padding-box | border-box
- background-origin: content-box | padding-box | border-box
- background: color image repeat attachment position
- background-blend-mode: normal|multiply|screen|overlay|darken|lighten|color-dodge|saturation|color|luminosity

### Background functionality

- background-color: Sets the background color of an element
- background-image: Sets the background image for an element
- background-position: Sets the starting position of a background image
- background-repeat: Sets how a background image will be repeated
- background-attachment: Sets whether a background image is fixed or scrolls with the rest of the page
- background-size: Specifies the size of the background image(s)
- background-origin: Specifies where the background image(s) is/are positioned
- background-clip: Specifies the painting area of the background

### Multiple background image

``` #background-container { background-image: url(img_flwr.gif), url(paper.gif); background-position: right bottom, left top; background-repeat: no-repeat, repeat; } ```

---

## Text

- color
- text-align: left | center | right | justify
- text-align-last: left | center | right | justify
- direction: ltr | rtl
- unicode-bidi: embed | bidi-override | isolated | isolated-override | plaintext;
- vertical-align: baseline | sub | super | text-top | text-bottom
- text-decoration: dashed | dotted | double | line-through | overline | underline | wavy | none
- text-transform: uppercase | lowercase | capitalize
- text-spacing
  - text-indent
  - letter-spacing
  - line-height
  - word-spacing
  - white-space: normal(D) | nowrap | pre | pre-line | pre-wrap
- text-shadow: h-shadow v-shadow blur color
- writing-mode: horizontal-tb|vertical-rl|vertical-lr

---

## Fonts

- font-family
  - generic font families: serif - sans-serif - monospace - cursive - fantasy
  - web safe fonts
    - fallback
    - Arial (sans-serif) - Verdana (sans-serif) - Tahoma (sans-serif) - Trebuchet MS (sans-serif) - Times New Roman (serif) - Georgia (serif) - Garamond (serif) - Courier New (monospace) - Brush Script MT (cursive)
- font-style: normal | italic | oblique
- font-size: 16px | 1rem | 1em | 10vw
- font-weight: lighter | normal | bold | bolder | 100-900
- font-variant: normal | small-caps
- font-variant-caps: normal|small-caps|all-small-caps|petite-caps|all-petite-caps|unicase|titling-caps
- font: font-style font-variant font-weight font-size/line-height font-family
- google fonts and font effects

- [type scale](https://type-scale.com/)
- [Google fonts](https://fonts.google.com/)
- [font pair](https://www.pagecloud.com/blog/best-google-fonts-pairings)

---

## Font theory

- Choose a place to find your fonts
- Product audience and branding
  - Research your users - understanding their taste and aesthetic
  - Research your competitors - decide if you want to fit in or stand out
  - Align product market brand
- Font scalability
- Loading time

---

## Css directives

@import "address";
@charset "UTF-8";

---

## Icons

- [Font awesome icons](https://fontawesome.com/icons)
- [Bootstrap icons](https://icons.getbootstrap.com/)
- [Material icons](https://www.w3schools.com/icons/google_icons_intro.asp)
- [Box icons](boxicons.com)
- [Remix icon](remixicon.com/)
- [Ion icon](ionic.io/)

---

## Pseudo class

:hover - :focus - :first-child - :last-child - :nth-child(even|odd|formula) - :nth-of-type(n)  - ...

q:lang(no) {
  quotes: "~" "~";
}

---

## Links

:link - :visited - :hover - :active
cursor: default | crosshair | e-resize | help | move | n-resize | ne-resize | nw-resize | pointer | progress | s-resize | se-resize | sw-resize | text | w-resize | wait

---

## Pseudo element

::before - ::after - ::first-letter - ::first-line - ::selection

---

## List

- list-style-type: disk | circle | square | none | armenian | lower-alpha | lower-green | lower-latin| lower-roman | upper-alpha | upper-latin | upper-roman | georgian | symbols()
- list-style-image: url(address)
- list-style-position: inside | outside (D)

- The list-style-position property specifies the position of the list-item markers (bullet points).

---

## Table

- border-collapse : separate (D) | collapse
- border-spacing: h-space v-space
- caption-side: top (D) | bottom
- empty-cells: show | hide
- table-layout: auto | fixed

- border-spacing: Specifies the distance between the borders of adjacent cells
- table-layout: Sets the layout algorithm to be used for a table

---

## Overflow

- overflow-x
- overflow-y
- overflow: hidden | scroll | visible

---

## Display

display: inline - inline-block - block - flex - grid - table

---

## Visibility

visibility: visible (D) | hidden

---

## Position

position: static | relative | absolute | fixed | sticky

---

## Z-index

---

## Clip path

clip-path

[Clip path tool](https://bennettfeely.com/clippy/)

---

## Float

float: none | left | right | inline-start | inline-end;
clear: left | right | both

---

## Image Spirits

[Sprite generator](https://www.toptal.com/developers/css/sprite-generator/)

---

## Filter

filter: none | blur(px) | brightness(%) | contrast(%) | drop-shadow(h-shadow v-shadow blur spread color) | grayscale(%) | hue-rotate(deg) | invert(%) | opacity(%) | saturate(%) | sepia(%) | url();

---

## Forms

resize: none
accent-color

---

## Specificity

- general selector
- id
- class
- attribute
  - The [attribute="value"] selector is used to select elements with a specified attribute and value.
  - [attribute~="value"]: selector is used to select elements with an attribute value containing a specified word.(just space-separated word)
  - The [attribute|="value"] selector is used to select elements with the specified attribute, whose value can be exactly the specified value, or the specified value followed by a hyphen (-).
  - The [attribute^="value"] selector is used to select elements with the specified attribute, whose value starts with the specified value.
  - The [attribute$="value"] selector is used to select elements whose attribute value ends with a specified value.
  - The [attribute*="value"] selector is used to select elements whose attribute value contains a specified value.

---

## Math functions

- calc()
- min() - max()

---

## Shadows

box-shadow: h-shadow v-shadow blur padding color;

---

## Object-fit

object-fit: fill (D) | contain | cover | none | scale-down

- object-fit: Specifies how an img or video should be resized to fit its container

---

## Object-position

object-position: 50% 50%; center of image till end

- object-position: Specifies how an img or video should be positioned with x/y coordinates inside its "own content box"

---

## Columns

- column-count: number
- column-fill: auto | balance
- column-gap: 1rem
- column-rule: width style color
- column-rule-width: 1px
- column-rule-style: solid
- column-rule-color: skyblue
- column-width
- column-span: all | none
- column: column-width column-count

- column-span: Specifies how many columns an element should span across

---

## CSS 2D and 3D transforms

- transform: rotate(clockwise - non-clockwise)
- transform: scale(x,y) - scaleX(x) - scaleY(y)
- transform: translate(x,y) - translateX(x) - translateY(y)
- transform: skew(x-angle,y-angle) - skewX(x-angle) - skewY(y-angle)
- transform: matrix(scaleX(), skewY(), skewX(), scaleY(), translateX(), translateY())

- transform: rotate3d(x,y,z,angle) - rotateX(angle) - rotateY(angle) - rotateZ(angle)
- transform: translate3d(x,y,z) - translateZ()
- transform: scale3d(x,y,z) - scaleX(x) - scaleY(y) - scaleZ(z)
- perspective(n)
- transform-origin: x-axis y-axis z-axis
- transform-style: preserve-3d
- perspective
- perspective-origin
- backface-visibility

- transform-origin: Allows you to change the position on transformed elements
- perspective-origin: Specifies the bottom position of 3D elements
- backface-visibility: Defines whether or not an element should be visible when not facing the screen

---

## Transition

- transition-delay
- transition-duration
- transition-property
- transition-timing-function: linear | ease | ease-in - ease-out - ease-in-out - cubic-bezier(n,n,n,n)
- transition: property duration timing-function delay

---

## Animations

animation-name: name
animation-duration: 12s
animation-delay: 1s
animation-direction: reverse | alternate | alternate-reverse
animation-iteration-count: -1 | count
animation-fill-mode: forwards | backward | both | none
animation-timing-function: linear | ease | ease-in - ease-out - ease-in-out | step-start | step-start | steps(int,start|end)
animation-play-state: paused | running
animation: name duration timing-function delay iteration-count direction fill-mode play-state

@keyframes animation-name {
  from {}
  to   {}
}

---

## Variable

:root {
    --white-color: #fff;
}

selector {
    color: var(--white-color);
}

---

## Backdrop-filter

- blur(px)
- brightness(%)
- contrast(%)
- drop-shadow(h-shadow v-shadow blur color)
- grayscale(%)
- hue-rotate(deg)
- invert(%)
- opacity(%)
- sepia(%)
- saturate(%)

---

## FlexBox

- justify-content: flex-start|flex-end|center|space-between|space-around|space-evenly
- align-items: stretch|center|flex-start|flex-end|baseline
- flex-direction
- flex-wrap
- flex-flow: direction wrap;

- order
- flex-basis
- flex-grow
- flex-shrink
- flex: grow shrink basis
- align-self
- justify-self

---

## Grid

- grid-row-gap - grid-column-gap - grid-gap
- grid-template-columns - grid-template-rows
- grid-auto-columns - grid-auto-rows
- grid-template-areas: "name name name" "name2 name1 name1" ...
- justify-content: flex-start|flex-end|center|space-between|space-around|space-evenly
- align-items: stretch|center|flex-start|flex-end|baseline

- grid-area: name
- grid-column - grid-row
- grid-column-start - grid-column-end - grid-row-start - grid-row-end
- align-self
- justify-self

---

## Media

@media (max-width: 768px) {}
@media (min-width: 768px) {}

---

## Gradients

### Linear gradients

- background-image: linear-gradient(direction, color-stop1, color-stop2, ...)
  - background-image: linear-gradient(red, blue)
  - background-image: linear-gradient(to right, red, blue)
  - background-image: linear-gradient(to right bottom, red, blue)
- background-image: linear-gradient(angle, color-stop1, color-stop2, ...)
  - background-image: linear-gradient(180deg, red, yellow);
- background-image: repeating-linear-gradient(color-stop1, color-stop2, ...)
  - background-image: repeating-linear-gradient(red, yellow 10%, green 20%);

### Radial gradients

- background-image: radial-gradient(shape size at position, start-color, ..., last-color)
  - background-image: radial-gradient(red, yellow, green)
  - background-image: radial-gradient(red 5%, yellow 15%, green 60%)
  - background-image: radial-gradient(circle, red, yellow, green)
  - background-image: radial-gradient(closest-side at 60% 55%, red, yellow, black)
- background-image: repeating-radial-gradient(start-color, ..., last-color)
  - background-image: repeating-radial-gradient(red, yellow 10%, green 15%)

- size-parameter for gradient: closest-side | farthest-side | closest-corner | farthest-corner

### Conic gradients

- background-image: conic-gradient([from angle] [at position,] color [degree], color [degree], ...)
  - background-image: conic-gradient(red, yellow, green)
  - background-image: conic-gradient(red 0deg, red 90deg, yellow 90deg, yellow 180deg, green 180deg, green 270deg, blue 270deg)
  - background-image: conic-gradient(at 60% 45%, red, yellow, green);
  - background-image: repeating-conic-gradient(red 10%, yellow 20%);
  - background-image: repeating-conic-gradient(red 0deg 10deg, yellow 10deg 20deg, blue 20deg 30deg);

---

## Image Reflection

-webkit-box-reflect: below | above | left | right

---

## Masking

- mask-image: url() | linear-gradient()
- mask-mode: luminance | alpha
- mask-origin: content-box | border-box
- mask-position: left right top center bottom | direction direction | posX posY | % %
- mask-repeat: no-repeat | repeat
- mask-size: %

---

## Border image

- border-image-source: url(address);
- border-image-slice: number | % | fill
- border-image-width: number | % | auto
- border-image-outset: length| number
- border-image-repeat: stretch | repeat | round | space
- border-image: source slice width outset repeat|initial|inherit

---

## Counters

ol {
  counter-reset: section;
  list-style-type: none;
}

li::before {
  content: counters(section,".") " ";
  counter-increment: section;
}

---

## Combinators

- parent child: The descendant selector matches all elements that are descendants of a specified element.
- parent > child: The child selector selects all elements that are the children of a specified element.
- element + element: The adjacent sibling selector is used to select an element that is directly after another specific element.
- element ~ element: The general sibling selector selects all elements that are next siblings of a specified element.

---

## User select

``` -webkit-user-select: none; /*Safari*/ ```
``` -ms-user-select: none; /*IE 10 and IE 11*/ ```
``` user-select: none; /*Standard syntax*/ ```

---

## Pointer events

- pointer-events: none| auto

- Set whether or not an element should react to pointer events

---

## CSS validation

- [CSS validator](https://jigsaw.w3.org/css-validator/)
