git-wiki: because who needs cool names when you use git?
========================================================

[Original wiki][1]  

Mods in This Fork
-----------------
__Page Links__: Removed all the weird wiki syntax and the previous {{}}
styling. Instead rely on markdown...because markdown will suffice. If
linking to internal pages use '/pageName' instead of the whole URL.

__Page and Title Names__: The page title and name was
tied to the name of the markdown file. This was changed
to break up CamelCasing. However, if you write "USABrief" then
the title and the H1 tag will read "U S A Brief". Just make
sure to have a lowercase character between each uppercase
char. This adds to readability and still allows the file
names to be grep-able with git ls | grep.

__Kramdown__: Original used Rdiscount which is a good markdown renderer
but nothing compared to Kramdown. Check out the project on github or on
their homepage to figure out syntax and odities.

Licence
-------
               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                       Version 2, December 2004

    Copyright (C) 2008 Simon Rozet <simon@rozet.name>
    Everyone is permitted to copy and distribute verbatim or modified
    copies of this license document, and changing it is allowed as long
    as the name is changed.

               DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
      TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

     0. You just DO WHAT THE FUCK YOU WANT TO.
    
[1]: https://github.com/sr/git-wiki
