# Footers

* Footers can be tricky because we need the footer to sit at the bottom of the screen whether the page has no content or no content at all.

* We accomplish this by giving the html and body elements a height of 100%.

* Then we use a wrapper to contain our content.

* We also add the footer, outside of and underneath the wrapper.

* Both the footer and the wrapper should be positioned relatively.

* The footer and wrapper should both have min-height properties set with percentages. Both these height's should add up to 100%.

* Inside the wrapper, we should have a container to hold the content. This container needs a `padding-bottom` to keep the content from getting too close or going inside to footer.

* The footer needs an  `overflow: auto;` property to make it responsive on mobile devices.
