# The Queens College Campus Maps (1940 – 1980) Assignment
This assignment is designed to get you to produce a multi-page web site over an 11-week period using much of what you learn about HTML, CSS, and Sketch.

## Description
You will implement the web page design for the Sketch comp found in the file [`sketch/queens-college-campus-maps.sketch`](sketch/queens-college-campus-maps.sketch). A responsive version is not required, but extra credit, discussed towards the end of this document, will be assigned to those who implement it.

## Before You Start
**<u>*Before doing anything at all to this repo, make sure to checkout your personalized branch first.*</u>**

Read this document over *carefully* to understand the rules of the project, how to submit it, and when. Then follow up by looking over all the files in this scaffold in order to better understand its structure. (The scaffold is discussed below.) If you decide to work in a different folder before submitting this project, copy this entire repo, rename the copy, then copy back to this repo your project files. See below for a list of files expected in your submission.

## Font Files
This design uses Font Awesome 5 and IBM Plex Sans. You’ll need desktop and web versions: The former in order to view the Sketch file; the latter to implement the web page.

For the desktop, download IBM Plex Sans from  [https://ibm.github.io/type/](https://ibm.github.io/type/) and the free version of Font Awesome 5 from [https://fontawesome.com/how-to-use/use-on-desktop](https://fontawesome.com/how-to-use/use-on-desktop). Otherwise, when you launch `queens-college-campus-maps.sketch`, Sketch will generate a “missing fonts” error in the upper right hand corner of the window.

For the web, Font Awesome 5 is already included via a `link` element in `index.html`. IBM Plex Sans is included in this repo’s `fonts` folder.

**Note: Do not change any file names, and do not add any more fonts.**

## CSS Files
There are two style sheets in the `css` folder: Eric Meyer’s reset CSS (`reset.css`) and `style.css`. Both are included in the style sheet stack in `index.html`. **You’ll do all of your CSS-related work in `style.css` — do not touch `reset.css`, and do not add any more CSS files to the `css` folder**.

## Image Files
All the images you’ll need for this project are in the `img` folder. However, all the PNG files are empty. You’ll need to *replace* each of the `.png` files with an exported equivalent from `sketch/queens-college-campus-maps.sketch`.

**Note: Do not change any file names. Do not add or remove any more images to the `img` folder. Only replace the `.png` files.**

## HTML Files
A suite of empty HTML files exist in the root of this repo. Those are the only files you may edit, and each must represent its respective map page.

The file `index.html` contains some starter syntax, including a location in which to add your name.

## Grid
You will need [this Chrome extension](https://github.com/code-warrior/the-modular-grid) in order to implement the web pages accurately.

## Rules
* Implement the web page equivalent of the file `queens-college-campus-maps.sketch` in the `sketch` folder.
* The map icon and the navigation along the left must remain fixed; the heading and main section containing the map and legend must scroll.
* Hovering over any navigation item must generate a right-pointing arrow whose color is the same as the element over which the mouse is hovering.
* Clicking on any navigation item opens that item’s corresponding map page. For example, hovering over `1940` in the navigation opens the page `campus-map--1940.html`.
* Clicking any image should open its high resolution version, which has a `.jpg` extension, in a new window.
* The higher resolution image of each map should be rendered as the map on high resolution devices.

## Due
This assignment is due by 11:59 PM on Sunday, 6 May 2018 for both sections of the spring 2018 ARTS 214 class. ***No* late work will be accepted. Your window for submission is between 8:00 AM – 11:59 PM on Sunday, 6 May 2018. *Do not submit outside of this window.***

## Submission
1. Log into GitHub.
2. Fork this repo.
3. Clone your fork.
4. Checkout your personal branch.
5. Generate all the commits required for your project.
6. Issue a pull request back to the source repo. Make sure the `base` and `compare` branches are yours. See [these videos](http://code-warrior.github.io/tutorials/git/github/) and read [Submitting Assignments Using GitHub Desktop](https://code-warrior.github.io/tutorials/submitting-assignments-using-github-desktop/).

Only the following files should appear as “changed” in your pull request.
1. `index.html`
2. `css/style.css`
3. `img/1940.png`
4. `img/1956.png`
5. `img/1959.png`
6. `img/1960.png`
7. `img/1962.png`
8. `img/1970.png`
9. `img/1980.png`
10. `campus-map--1940.html`
11. `campus-map--1956.html`
12. `campus-map--1959.html`
13. `campus-map--1960.html`
14. `campus-map--1962.html`
15. `campus-map--1970.html`
16. `campus-map--1980.html`

A project is considered “submitted” if the rules for modifying and not modifying files have been observed. All others will be rejected. If a rejected submission isn’t re-submitted by the deadline, then the project’s grade is `0`.

## Extra Credit
Extra credit of a third of a grade for your final course grade will be given to projects that fully respond to viewport sizes down to `320px` without a horizontal scrollbar.
