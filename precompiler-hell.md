Precompiler Hell
===

Speaker: Peter Müller  
GitHub: https://github.com/Munter  
Date of the talk: 2015-04-25

Precompiling assets should be simple, not easy. E=mc2 is easy for Einstein, but it's not simple for non-physicists. Therefore, a precompiler should include amongst others the following features:
- Sourcemaps (there is hardly a reason why not)
- CSS autoprefixing (who does not want that?)
- Autoreloading (becorse we can)
- No complicated setup of a task runner (like gulp, grunt, broccoli, ...)

Beginners should be able to start like the pros of today started when HTML/CSS/JS were born. Create a file, start to code and open it in a browser. But its not 1990 and LESS/SASS/JADE/COFFESCRIPT/TYPESCRIPT are cool and we want starters to use them, so we got to provide an simple way to get them going.

Peter started to develop a precompiler with minimal setup requirement. One of the goals was to keep file pahts out of the configuration file. Take a look at https://github.com/Munter/fusile if you are interested in the details. To date, it's still in alpha phase, but the major issues are adressed and some minor ones can be fixed. Currently it only runs on mac, but plans for a windows and linux port exist.
