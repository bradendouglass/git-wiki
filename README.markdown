git-wiki: because who needs cool names when you use git?
========================================================

[Original wiki][1]  

Mods in This Fork
-----------------
Page Links: linking, like in many wikis, is performed by
using CamelCase words. This makes life tricky since many
modules and classes in Ruby are CamelCase. CamelCase linking 
has been disabled. To link to separate pages, surround the link
with double squirrely brackets {{link}}.

Page and Title Names: The page title and name was
tied to the name of the markdown file. This was changed
to break up CamelCasing. However, if you write "USABrief" then
the title and the H1 tag will read "U S A Brief". Just make
sure to have a lowercase character between each uppercase
char. This adds to readability and still allows the file
names to be grep-able with git ls | grep.

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
