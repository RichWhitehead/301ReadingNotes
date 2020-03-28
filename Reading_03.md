# Read: 03 - Flexbox and Templating

# Javascript Templating
  * Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.

  * Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object. Dont' get mustache confused as a templating engine it's a specification for templating language.

  # Flexbox

    * Background 

      - The main idea behind the flex layout is to give the container the ability to alter its items' width/height (and order) to best fill the available space (mostly to accommodate to all kind of display devices and screen sizes). A flex container expands items to fill available free space or shrinks them to prevent overflow.

      - Most importantly, the flexbox layout is direction-agnostic as opposed to the regular layouts. While those work well for pages, they lack flexibility to support large or complex applications. 

      - Basic terminology includes 
          - Display: This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

          - Flex-direction: This establishes the main-axis, thus defining the direction flex items are placed in the flex container. Flexbox is (aside from optional wrapping) a single-direction layout concept. Think of flex items as primarily laying out either in horizontal rows or vertical columns.

          - Flex-wrap: By default, flex items will all try to fit onto one line. You can change that and allow the items to wrap as needed with this property.

          - Flex-flow: This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container's main and cross axes. The default value is row nowrap.

          - Justify-content: This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size. It also exerts some control over the alignment of items when they overflow the line.

          - Align-items: This defines the default behavior for how flex items are laid out along the cross axis on the current line. Think of it as the justify-content version for the cross axis (perpendicular to the main-axis).

          - Align-content: This aligns a flex container's lines within when there is extra space in the cross-axis, similar to how justify-content aligns individual items within the main-axis.

          - Order: By default, flex items are laid out in the source order. However, the order property controls the order in which they appear in the flex container.

          - flex-grow: This defines the ability for a flex item to grow if necessary. It accepts a unitless value that serves as a proportion. It dictates what amount of the available space inside the flex container the item should take up.

          - If all items have flex-grow set to 1, the remaining space in the container will be distributed equally to all children. If one of the children has a value of 2, the remaining space would take up twice as much space as the others (or it will try to, at least).

          - Flex-shrink: This defines the ability for a flex item to shrink if necessary.

          - Flex-basis: This defines the default size of an element before the remaining space is distributed. It can be a length (e.g. 20%, 5rem, etc.) or a keyword. The auto keyword means "look at my width or height property" (which was temporarily done by the main-size keyword until deprecated). The content keyword means "size it based on the item's content" - this keyword isn't well supported yet, so it's hard to test and harder to know what its brethren max-content, min-content, and fit-content do.

          - Flex: This is the shorthand for flex-grow, flex-shrink and flex-basis combined. The second and third parameters (flex-shrink and flex-basis) are optional. The default is 0 1 auto, but if you set it with a single number value, it's like <number> 1 0.

          - Flex-start: This allows the default alignment (or the one specified by align-items) to be overridden for individual flex items.

# For more details visit https://css-tricks.com/snippets/css/a-guide-to-flexbox/





 





