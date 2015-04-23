# website-optimization
Udacity Front-End Web Developement Project 4 submission

This website was largely pre-built by Udacity, but I optimized it for a >60 page fps and a >90 Google Developers PageSpeed Insights score.

Optimizations:
- Changed order of css to take advantage of DOM tree construction steps
- Applied async where appropriate
- Minified the css
- Reduced unnecesarily large image file sizes
- Reduced the number of background pizzas created to the minimum number my Macbook screen will display at any given spacetime
- Commented out unnecessary console.log's
- Got rid of repeating code in changePizzaSizes()
- Got rid of repeating code in and improved updatePositions()


Build Steps:
- Build via index.html