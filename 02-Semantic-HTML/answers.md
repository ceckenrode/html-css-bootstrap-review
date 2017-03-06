### Semantic HTML

* What does semantic HTML mean? Why do we want to use it?

  * Semantic HTML is the use of HTML markup to reinforce the semantics, or meaning, of the information in web pages and web applications rather than merely to define its presentation or look. Semantic HTML is processed by traditional web browsers as well as by many other user agents.

  * Using semantic HTML makes websites more accessible. Web accessibility refers to the "inclusive practice of removing barriers that prevent interaction with, or access to websites, by people with disabilities. When sites are correctly designed, developed and edited, all users have equal access to information and functionality."

    * Users will disabilities may use special software or to consume content on a website.

  * Having a more accessible website helps with SEO (Search Engine Optimization), which has to do with how a website ranks in search results.

  * Having a semantic accessible website can help with how a websites content appears on different types of devices, such a phones or tablets.

- - -

* What is the header element? How is it different from the head element?

  * The header element represents a container for introductory content or a set of navigational links.
  
  * Navigational links don't **need** to be put in the header but often are.
  
  * If navigational links are in the header they should be internal URLs (link to other pages within the same website)

- - -

* What is a nav element?

  * It's a container for navigation links

- - -

* What is the ul element? How is it different than an ol element?

  * The ul element represents an unordered list. li elements represent the list items.

  * A ul is different from ol elements in that ol elements are numbered.

  * If we are displaying a **list** of content, we should use some kind of list element.

  * The bullet points can be removed with CSS and made to look more nav-like.

- - -

* What is the difference between h1 and h3?

  * h1 and h3 are both **heading** tags (not to be confused with head or header).

  * Presentationally, heading tags are sized largest to smallest from h1-h6.

  * Heading tags are also numbered from importance from h1-h6. h1 tags are generally used to describe or title the web page. h2 tags might be used for some kind of supporting content. Everything else might be used to title an article or section of content.

  * This matters when it comes to SEO as it helps search engine's better understand what a website is about.

- - -

* What are article and section? Why not just use div?

  * A div is a general purpose container element. It has no semantic meaning.

  * A section represents a section of content. In our case here, that's our blog articles. Sections should be titled with some kind of heading element.

  * An article "represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable".

  * Usually smaller than a section.

- - -

* What is a footer? Why isn't it at the bottom of the page?

  * A footer "element represents a footer for its nearest sectioning content or sectioning root element. A footer typically contains information about the author of the section, copyright data or links to related documents."

  * By this definition (taken from MDN), we can **technically** have multiple footers per web page. Any section of a web page can have a footer. Though this is tricky to do in a semantic way. For the most part, we'll just use one at the bottom of the web page.

  * It doesn't appear at the very bottom of a web page automatically because we need to use CSS to tell it to appear at the bottom. Since we can have multiple footers on a page (maybe each blog post has a footer of some sort), we need to be specific about where we want it to be placed.

- - -

* I can make a table without thead, tbody, and tfoot. Why do I want to use them?

  * It's true that we can build an HTML5 table without these elements. But they give our table semantic meaning. Using them makes portions of a table represent more than it's presentation, which helps us with SEO and accessibility.
