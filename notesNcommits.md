<!-- 

Notes and Commits documentation moved from original home on style.css

Documentation for trying to fix footer display on mobile

Issue #1: On mobile the footer is pushed off the page the aprox height of the navbar OR the browser / phone control bar at bottom of screen.

Issue 1
    Oct 1 / Paul / Added float-right to line 92 of index.html

Commit 2
    "Issue 1 - Oct 1 / Paul / Removed float-right line 92 of index.html Removed d-flex class from line 28 of index.html since the parent container is already set to d-flex"

Commit 3
    "Issue 1 - Paul - Found https://developers.google.com/web/updates/2016/12/url-bar-resizing and https://dev.to/peiche/100vh-behavior-on-chrome-2hm8 added @supports on body line 34-40 of style.css"

Commit 4
    "Reverting previous commit"

Commit 5
    "Issue 1 - Paul - Adding min-height: -webkit-fill-available; to line 33 of style.css based on https://stackoverflow.com/a/55003985/11665872"

Commit 6
    "Issue 1 - Paul - Removing change from last commit, adding a fix with JS from https://css-tricks.com/the-trick-to-viewport-units-on-mobile/ and commented out the min-height 100vh"

Commit 7
    "Commenting out last commit and moving over to new repo as I will submit assignment like this"

Commit 8
    "Issue 1 Resolved - Implementing JS fix proved to work from https://github.com/PaulB-H/Portfolio---Fixing-100vh-on-mobile, ensured each html page has correct link to new JS file, previously attempted this fix but I did not give GitHub enough time to update the page before checking it on my phone - Need better way to live-test pages on phone"

Commit 9
    "Removing mt-4 from Portfolio header, added style padding top 10px inline to keep spacing consistant with other pages, will work towards proper global styling between pages"

Commit 10
    "added stylepaddingtop 0px to contact page to match portfolio"

Commit 11
    "Adding favicon and link in headers of all pages, set goal for next fix above .portPic in style.css"

NOTE:
    Consider adding more support for favicons
    See:
    https://stackoverflow.com/a/30839701/11665872
    and 
    https://scotch.io/tutorials/all-favicons-for-all-devices-and-sizes
    for info

commit 12
    "moved notes and commit comments from styles.css to notesNcommits.md, deleted unused images"