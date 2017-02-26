# Simple Footer

* We set the body and html height to 100%.

* We create a container to act as a wrapper, set it's position to relative, set it's `min-height` to 100%. This means it will always be at least the size of the viewport, but will stretch larger if it needs to.

* We add the footer inside the wrapper. Give the footer a position of absolute. Position the footer at the bottom of its container, (the wrapper).

* We add another container inside of the wrapper to hold the content. This container gets a `padding-bottom` value of at least the height of the footer. This prevents the footer content from going inside the footer.

* The issue with this technique is media queries are required to make the footer responsive. This is a common problem with most footers found online.
