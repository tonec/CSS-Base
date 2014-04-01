
# CSS Bass

This is not framework. It is however a set of css files and a directory structure that I developed whilst working on a project recently. I use it to provide myself with a starting point on new projects to reduce that initial setup time.

The benefits of it's structure include.
- *Adherance to Mobile First methodolody.* Generic and mobile styles are served up first with css for larger screen served using media queries as and when that extra real estate come available.
- *No media query polyfill is needed for old IEs.* Old IEs are served up fixed width styles using the magic of scss and the creative use of conditional comments in the HTML head.
- *The CSS is modular and 'componentized' - if that be a word!* This is in part made possible by SCSS's compiling of @input, which means you can split those files up with impunity and not worry about any extra HTTP requests. This makes is so much easier to keep related styling together amd work within a team whilst minimizing conflicts in your code. 