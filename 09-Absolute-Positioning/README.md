# Absolute positioning

* When an element is positioned absolutely, it's taken out of the flow of the page. Similar to floats. Absolute elements also don't interact with other absolute elements.

* Absolute elements are primarily positioned using `top`, `left`, `bottom`, `right` properties

* Absolute positioning works almost like a grid system. We declaritively say where the element should appear on the page.

  * `<side>` refers to the distance from the specified `<side>` should appear. e.g `top: 40px` says the specified element should be 40px from the top of the viewport.

* Absolutely positioned elements are by default, positioned relatively to the viewport dimensions.

* z-index can be used to specify the order elements should appear when stacked up on top on eachother.

* One vertical `<side>` and one horizontal `<side>` should be used for positioning purposes. Otherwise top left will be preferred.

## Challenge

* Position each box at a different corner of the screen.

