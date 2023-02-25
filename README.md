Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2023 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.

---
* 1.html, 2.html, 3.html consists of html obtained from Project Gutenberg (https://www.gutenberg.org/)
 * Modifications were made to 1.html, 2.html, 3.html in order to link to an external style sheet
* gutenberg.css was used to style 1.html, 2.html, and 3.html
* The following novels were used:
   * Heart of Darkness by Joseph Conrad
   * The Great Gatsby by F. Scott Fitzgerald
   * Pride and Prejudice by Jane Austen

gutenberg.css, good.html, bad.html © 2023 by Elena Xu is licensed under CC BY-SA 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/


Screenshots (good.png, bad.png, gutenberg1.png, gutenberg2.png, gutenberg3.png) were created by me, on Ubuntu 20.04 VM.

Part I: Modifications made
=================
* In order to make the HTML documents look "old", some changes were made. In my gutenberg.css file...
  * The body was changed to give it a an old, yellowish background
  * The font of the paragraphs were changed to Garamond (serif) as the first font choice
  * Headers (e.g. Chapter #), were bolded
  * Image captions (if they exist) were usually italicized
  * White backgrounds (if they exist) were removed from images
  * Anchor tags were changed such that they would blend in, rather than appear as blue
  
External Sources Used:
=================
## Part I Credits:
* https://cssgradient.io/
  * Helped me create the linear gradient used in Part I
  
* user1822264's idea on how to get rid of the white background in images, licensed under Creative Commons-Attribution-ShareAlike 4.0 (CC-BY-SA 4.0), found on Stack Overflow (https://stackoverflow.com/)
  * Title of question: Make white background of image transparent in css
  * Year: 2015
  * Link to site where implementation was found: https://stackoverflow.com/questions/12662759/make-white-background-of-image-transparent-in-css
  * Link to author (in this case, the person who asked the question): https://stackoverflow.com/users/1556487/nick
  * Link to author (in this case, the person who answered the question): https://stackoverflow.com/users/1822264/user1822264
  * Link to license: https://creativecommons.org/licenses/by-sa/4.0/

## Part 2 Credits:
* Some Bootstrap components was used in ugly.html and good.html
  * Bootstrap is released under the MIT license and is copyright 2023.
  * Bootstrap components used: Navbar, Cards (by copying and pasting the html for them)
    * https://getbootstrap.com/docs/5.3/components/navbar/#supported-content
    * https://getbootstrap.com/docs/5.3/components/card/#example

## Other Credits:
* Some external images were used, and the source of those images can be found in the img tag (src = "...")
