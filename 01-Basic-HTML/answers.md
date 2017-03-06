### Basic HTML

* What tags are required for a basic valid HTML page?

  * html, head, title, body, doctype

* What does DOCTYPE do?

  * It's not an HTML element like all the others, but an instruction to the web browser about what version of HTML is being used.

  * \<!DOCTYPE html> instructs the browser we'll be using HTML5 (the current version) instead of any previous versions.

  * This should be the very first tag.

* What is the function of the head element?

  * This holds any metadata (data that contains information about other data) about a web page. Usually this refers to any links to external CSS or JavaScript a website will be using. Other information such as the webpage's language or character set or the description a website should have in a Google search result.

  * We don't put any content inside these the head element that we want to show up on the website.

* What does \<meta charset="utf-8"> mean?

  * **Technically** this is considered an optional tag. The meta tag is for defining any metadata about a website which isn't better suited for another informational tag. For example, the "link" tag goes in the head and describes what CSS a web page should use.

  * The `charset="utf-8"` part describes the character set our webpage will be using.

  * A character set is basically the system of writing our webpage will use. If we had a website that was entirely in Chinese, we may load a different character set. "utf-8" is the most widely used and most comprehensive.

  * Most modern browsers will correctly interpret the correct character set to use, but it's still good to be explicit if you can.

* What is the function of the body element?

  * This is meant for all of the content that goes into a webpage that we want to show up on the screen when the page is loaded.

* What is the function of the html element?

  * This is the overall container that will hold everything we want to appear on a webpage when it is loaded.

* What is the function of the title element?

  * It describes the title we want to appear at the top of the browser tab.


