# Retroactive-Non-Complete-Page-Sizing-Agent
A collection of several lines of JavaScript which can be added to a page retroactively.

Retroactive Non Complete Page-Sizing Agent (RNCPSA) is a collection of several lines of JavaScript that does the following:

-Identifies the size of the user's web browser window. (height and width)

-If the window is less than 1900px in width or 1044px in height, the software is triggered.

-The software uses a feature all IE browsers (IE7 and up) have, the CSS zoom property, to reduce the size of all the web page content to a size that allows all of the content to fit in the user's window.


It requires jQuery. RNCPSA has been tested on IE, Chrome, and Opera, which jQuery versions 1.8 or higher.
