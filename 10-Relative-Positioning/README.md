# Relative Positioning

* When an element is positioned relatively, it's behaves the same way as an statically positioned element in that it can affect other elements on the page. e.g. adding `margin-top` to box-1 pushes down box-2.

* Absolute elements can be positioned using `top`, `left`, `bottom`, `right` properties.

  * When this happens, relatively positioned elements are nudged `relative` to where they would have otherwise been.

  * The space they would have occupied normally is still respected by the rest of the page.

* Primarily, relatively positioned elements are used to act as containers for absolute elements.

* Absolute elements by default are relative to the viewport. We can make them instead relative to another container.

