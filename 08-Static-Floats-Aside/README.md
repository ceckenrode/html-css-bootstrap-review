# Static Floats Aside

* As we've just seen, we can use floats to make block level elements live on the same line.

* We can also use floats to create web layouts.

* In this example, we will use floats to create a web layout where we have an aside on the left, and a content section on the right.

* Both the aside and the content section should be floated left.

* Both the aside and the section should sit inside of a container which clears the floats.

## Some takeaways

* We can use the `border-box` CSS property in order to more predictably position elements. `border-box` factors an elements border, `padding`, and `width` into the `width`, rather than add them together.

 * Floated block elements can't have their height set to 100% of their non floated container. This is because floated elements are out of the flow of the page, and thus don't know anything about their parent's or other elements.

 * By using floats, we're essentially creating a grid system using CSS. This is the method of creating grids that Bootstrap uses.

  * There are 3 other methods of creating grids in CSS:

    * Tables. No need to clear any elements. Can have height set. No way to push elements to next line if they don't fit. Elements can't be aligned/floated to the right the same way they can with floats.

    * Inline-blocks. Can set height, not need to clear anything. Elements can't be aligned/floated to the right the same way they can with floats. There is a problem where some space gets put between each element. Read more [here](https://css-tricks.com/fighting-the-space-between-inline-block-elements/)

    * Flexbox. Lots of ways to set height width of elements, can do vertical centering. Offers the most control. Disadvantages include: The syntax is unintuitive, a deep understanding takes a long time, not very good browser support.

* To be clear, floating is not a display type, or a position type. It's, just, well, floating.

* To see tables being used instead of floats, use the table-style.css instead of float-style.css in the index.html file.


## Wrap up - The Rules

* Elements can be floated left or right.

* Floating an element takes it out of the flow of the page.

* Block elements can sit on the same line if they are floated.

* Floated elements are ignored by their parent containers unless they are cleared.

  * Floats can be cleared in the following ways:

    * Add `overflow: auto` to the parent container. This tells the parent to handle any content "overflow" by stretching to fit the extra content.

    * Add a div at the bottom of the parent container, after any floated elements. Give this div a property of `clear: both`.

    * Use a pseudo-element, (`::after`) on the parent container to create block level pseudo element to clear the floats.
