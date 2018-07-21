## Project "Restaurant Reviews" - Overview

In this project, I incrementally converted a static webpage to a mobile-ready web application. I took a static design that lacked accessibility and converted the design to be responsive on different sized displays and accessible for screen reader use. I also added a service worker to begin the process of creating a seamless offline experience for the users.


## Specification

I was provided with the code for a restaurant reviews website. This code had a lot of issues. It was barely usable on a desktop browser, much less a mobile device. It also didn’t include any standard accessibility features, and it didn't work offline at all. My job was to update the code to resolve these issues while still maintaining the included functionality.


## How you can run this project

To run the project, download or clone the repository in your computer:

`$ git clone https://github.com/dimikara/Restaurant-Reviews-App-Stage-1.git`

and follow the instructions below:

* In the repository folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

* In a terminal (like Git Bash, Cygwin or the Windows terminal), check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000` or `python -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

* With your server running, visit the site: `http://localhost:8000`. You can now see the live site.


## Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, I tried to maintain use of ES6 in the additional JavaScript I wrote. 


## Credits & Tools Used

* Starter code by [**Udacity**](https://github.com/udacity/mws-restaurant-stage-1)
* Maps: [**Leafletjs**](https://leafletjs.com/), an open-source JavaScript library
for mobile-friendly interactive maps, & [**Mapbox**](https://www.mapbox.com/), an open source mapping platform for custom designed maps
* Presentations by [**Mohammed Riaad**](https://www.youtube.com/watch?v=TxXwlOAXUko) and [**Doug Brown**](https://www.youtube.com/watch?v=92dtrNU1GQc)
* [**Lighhouse**](https://developers.google.com/web/tools/lighthouse/), an open-source ([GitHub repository](https://github.com/GoogleChrome/lighthouse)), automated tool for improving the quality of web pages. I used it as an index mainly for Accessibility issues.
___


