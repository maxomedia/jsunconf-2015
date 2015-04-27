Module bundling with Webpack
===
Speaker: Joscha Feth  
GitHub: https://github.com/joscha  
Date of the talk: 2015-04-26

Webpack (https://github.com/webpack/webpack) is a module loader for generally everything a webpage would need: HTML, CSS, JS, Images and even custom stuff. Joscha used it over at Jimdo (http://de.jimdo.com/) to bundle their 14k+ files of javascript.

A few interesting things webpack can do:
- Resolve AMD/CommonJS dependencies
- Compile LESS/SASS/Stylus
- Encodes images in Base64
- Wrap legacy code using globals in closures and export their interface
- Write common dependencies to a shared file
- Add bower_components to rooth path, so bower modules can be required the npm way
- Ships with a dev server which provides a middleware interface and incremental builds