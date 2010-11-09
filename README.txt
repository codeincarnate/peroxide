Peroxide is a theme engine allowing templates to be created using HAML
and stylesheets to be written using sass and scss.

Templates and styles for large sites can become quite long and complex.  The goal of this
project is to make more advanced tools available to developers so that the code for themes
is shorter, easier to understand and more maintainable.

Peroxide automatically compiles and caches templates as PHP. Sass and scss files are also
automatically complied, cached and their resultant output css is automatically added to a page.

Peroxide uses the phamlp library to parse HAML and Sass.  This can be found at
http://code.google.com/p/phamlp/