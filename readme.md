# ONE MONTH

## LANDING PAGE

The one-month landing page drives to either of the three one-month courses - rails, html, and growth hacking.

### DEPENDENCIES

* FONTS - Markpro Black for headlines and Trade Gothic LT Pro Regular for body copy
* JAVASCRIPT - No dependencies as of yet, though jQuery is included
* CSS - SVG support is currently required for logos, though a PNG fallback could be implemented. Media Queries are also required for responsive layout, and CSS animation support supports the rollover animation on the buttons. Background-size cover allows the background images to resize properly.

### CSS

A base.css file has been included to handle any reset styles as well as reusable styles. Landing.css handles the page specific styling. No preprocessor was used. Twitter bootstrap grid class names have been included for the 3 courses, though the site is not utilizing the bootstrap at the moment.

### JAVASCRIPT

jQuery has been included for convenience here, though you may consider removing it if it is not necessary. In addition, a call to main.js is also being made on window load, though that file is empty. It has been included as an example of the preferred structure of classes within the site, using the javascript module pattern.

### RESPONSIVENESS

The site utilizes two breakpoints. It has a max width of 974px, which you may consider revising to a more standard 960 if you implement the bootstrap grid (you can do this easily by just changing the width of #container in the landing.css file). The breakpoints currently occur between 560 and 960 for tablet, and less than 560 for mobile. These can easily be adjusted in landing.css as well, though keeping in roughly the same range is recommended.
