# Structure of Web Pages and HTML

## Summaries from Jon Duckett's book, "HTML & CSS":

## Chapter 1 - Structure:
HTML (hypertext markup language) is a formatting language that is used to describe the *structure* of a web page. It consists of content (what a user sees) between opening and closing *tags*, and these tags are what tell a web browser how to display the content. An opening tag, its closing tag, and the content between the two is known as an *element*. Tags frequently describe different elements in a web page, such as `<header>`, `<body>`, and `<footer>`, which organize and encompass other tags (like `<p>` for paragraph, and `<a>` for hyperlink).

## Chapter 8 - Extra Markup:
In addition to the more common structural tags in HTML, there are others that are useful to know:
* Comments can be placed in HTML code using the tag `<!--A COMMENT ON CODE-->`. Comments are are not seen by the user, but can be used to clarify points that may be confusing for other developers or yourself in the future.
* id and class attributes (example: `<div id="identifier" class="class">`) allow particular elements to be grouped and/or delineated. This is especially useful for CSS selectors, say where you want to apply a change to a subset of the `<div>`s on a page.
* The `<iframe>` tag allows windows to be inserted into a web page, for things like applets and access to information on another web page.
* Some characters, such as `<`, `>`, and & are reserved by HTML, and need to be *escaped* to be used for content.

## Chapter 17 - HTML5 Layout
HTML 5 is a new version of HTML that offers additional clarity around web page structure through new tags. It also eliminates the need to close certain tags, such as the `<p>` and `<li>` tags. HTML5 can create issues with older browsers that don't support the newer version, as with the new tags and lack fo closing tags, the browser can have no way to accurately assess the structure.

## Chapter 18 - Process & Design
In designing a website, there are important factors to consider before setting down a single line of code. These include:
* Who you'd like to visit your site
* What they are trying to accomplish
* What functionality/areas you'd like to direct them towards
* What the colors, fonts, and general design of your site conveys to a user. Is this a fun site? A serious site?
When planning a site, it is usually best to both map out and wireframe the site.
* Mapping out a site is determing the structural tree of the site: which pages will be connected to the others. How many layers down will a user need to find a given piece of information?
* Wireframing is the practice of doing a rough sketch of every page in a site's map. Here you can figure out the basic layout, where the links to move around in the structural tree are, and how you want the flow of information to be for your users as they move around your site.