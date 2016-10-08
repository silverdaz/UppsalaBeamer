Unofficial Beamer Theme for Uppsala University
----
## Installation

* Download from GitHub
* Copy the files into `[tex-dist]/[beamer]/themes/`
* Run `texhash` (probably as `root`)

----
## Available options
* hideallsubsections, hideothersubsections
* nonumbers,totalnumber
* withnav, mylogo
* grey
* noprogressbar

For the sidebar layout:
* subsectionsattop, sectionpathattop,

### Removed
* sidebarshades

----
## TODO

* Make sure that in plain mode, the sidebar width goes to size 0

* Fix the bloody warnings

* Create a "keyword macro" that blanks some texts in the handout mode
  and shows it in other modes. Useful to make the students take notes.
  (in another package)
* Update the keyword macro to include portion of the text or graphs

* Create good-looking smileys like :) and :(, or find images and
  include them in the uu folder

* Update the notes mode to reflect smarter use.

* Publish my script for slides creation. (Should probably clean it first!)

* Redesign the myslide as makefile to use latexmk -pdf --silent

* Add a small white round dot for each section we come across in the progress bar.

* Create a horizontal progression bar at the top of the slides

----
Author: Frédéric Haziza <daz@it.uu.se>
