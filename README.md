# Responsive-Portfolio
Responsive-Portfolio

This is the assignment to highlight the use of media queries in our CSS styles sheets without the use of the Bootstrap framework to make each one of our 3 pages (About, Contact, Porfolio) responsive to the 3 sizes set out in the instructions:  640px, 768px, 990px.  The work was done based upon the images provided in the homework instructions.

Per instructions I used the 3 pages built in the Basic Portfolio in Lesson01 and edited all the files to meet the requirements.

Note that there was a issue that was brought up by Michael Hrivnk on September 28 in the Genreal Slack Channel, (https://stackoverflow.com/questions/26888751/chrome-device-mode-emulation-media-queries-not-working), this was a issue as well for me.

Given the lack of time I had to manually write a new media query to overcome those certain classes that did not display properly on the browser.  The extra media query is listed in the css as:

@media (min-width: 770px) and (max-width: 990px) {...}, with the ... being those classes/elements that did not respond.