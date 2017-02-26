# Static Floats

* By default, every statically positioned element, "flows" with the page. Top to bottom. Left to right.

* Floating is one way to take an element out of the normal flow of the page. Imagine the "flow" of the page is like a river current. It's pulling all of the elements in this direction, top to bottom, left to right.

* When we float an element, imagine that now we're causing it to "float" independently of the current or "flow" of the page.

* Floats are particularly useful for aligning elements to the right of the page. Floating left is less useful (we're going to learn a better way)

* Floating causes a few things to happen.

  * Elements only take up as much width as they need to fit their content.

  * These elements are ignored by their parent container.

* We can have the parent container **not** ignore by floated content by clearing it.

## Challenge

* Create a navigation bar. Give it 3 - 5 links. Float it left. Clear the floats.
