Instructions for getting the workshop set up:
• Start by forking the repo at https://github.com/cb-nw-3/m1-1-htmlcss--html.

This should take you to an identical-looking page, except it's your own copy. In the top-left of the page, you should see yourusername / m1-1-htmlcss--html

• Click the green "Clone or download" button, and copy the URL provided.

• Open the Terminal application (Terminal.app on MacOS, Git Bash on Windows)

• create a new directory to house all your projects. You can call it work or projects or anything you'd like :sourire: create the directory with mkdir work (where work is whatever name you wnat)

• cd into that new directory (eg. cd work)

• Type git clone, and then paste the URL so that it reads git clone https://blablabla.git

• The code is now on your machine! Open it in VS Code using code m1-1-htmlcss--html

• Read the README, and get started with the workshop! (modifié)

---

To view images in the README:

• Have the README file open in VS Code

• Type command + shift + P on Mac, or control + shift + P. This opens the command palette

• Start typing "Markdown". The first option should be Markdown: Open preview to the side

• this will open a formatted preview of this document, including the images!

You'll need to do this to solve the exercises :visage_légèrement_souriant:

This trick will work in any Markdown file (that ends in .md), not just the README (modifié)

---

A "semantic" tag is one that has meaning in terms of the element's role. So, for example, a `<header>` tag is semantic because it communicates that the element is at the very top of the page.

If you see `<header><h1>My website</h1></header>`, it tells you a lot more about the meaning than `<div><div>My website</div></div>`

A bit more specifically, many "semantic tags" were released with HTML 5, and include "landmark" type tags, like `<article>, <section>, <footer>, <nav>`. They refer to specific parts of the page. But I'd say tags like `<p>` and `<h1>` are semantic as well. Pretty much everything except div and span is semantic

Block-level = section, inline = items? Kind of?
Yeah, kind of! I would say that the distinction is that inline elements are happy to be within a paragraph, whereas block items are meant to be sections on a page. (modifié)
