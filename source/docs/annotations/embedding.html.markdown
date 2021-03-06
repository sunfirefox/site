---
title: Embedding a complete tutorial IDE in a page
class_name: docs
full_width: true
---

If you have a web page (a blog post, for example) with a good amount of available width, you can very easily embed the complete Codio IDE within it using an `<iframe>`.

Below is some sample HTML showing the Impress project in the fmay account being loaded with the impress.js file opened by default. Just load the IDE as you want it to display to an anonymous person and then copy and paste the URL into the src attribute.

    <iframe src="https://codio.com/fmay/Impress/tree/Impress/js/impress.js" width="100%" height="500" frameborder="0" marginheight="20" marginwidth="35" scrolling="auto"></iframe>

To make sure the embedded IDE is loaded at the right place, there are a number of options.
	
##Open in Tour
You can open the IDE with your project running in Tour mode by specifying the url as described in the [Auto-starting from a URL](/docs/annotations/auto-start) page.


