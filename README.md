# Restaurant Reviews: Stage 1

"For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users."

## Installation

Clone folder from github:
`git clone https://github.com/KevinTou/mws-restaurant-stage-1`

Make sure you have Python installed:
Python 2: `python -m SimpleHTTPServer 8000`
Python 3: `python3 -m http.server 8000`

Visit the site in your browser at: `http://localhost:8000`

(Side note: I was using Visual Studio Code, and the command I ended up using was `py -3.6 -m http.server 8000`)

## Reference List

- https://developers.google.com/web/fundamentals/primers/service-workers/
Used for creating the service worker and copied some code as a template for the service worker implementation

- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
Used for making the website more responsive