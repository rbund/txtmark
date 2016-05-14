__This is a fork of__  

# Txtmark - Java markdown processor
Copyright (C) 2011-2015 René Jeschke <rene_jeschke@yahoo.de>  
See LICENSE.txt for licensing information.

_For more detailed information please have a look onto the [original page](https://github.com/rjeschke/txtmark)_

***
## Important!
Development on this repository is __canceled__ in favor of the [Commonmark](https://github.com/atlassian/commonmark-java) implementation. I will keep the repository some time for documentation but it might be dropped in future without any further notice.


__Some explanation on that__: Markdown as such isn't clearly specified. Unfortunately even with a test suite provided, the specification leaves space for various possible interpretations. René probably saw that too and stated, that txtmark isn't Markdown. Now [Commonmark](commonmark.org) fills the gap and Atlassian did a great job in implementing it in Java. Their implementation fulfill the requirements I have and as a result, no further development on txtmark is needed from my side.

__Historical:__

***

__René did a great job creating this library and I feel as I'm able to add some improvements to it. I will try to stick to his philosophy and keep all additions simple and performant.__

### What I really like about TxtMark

* It's fast.
* It's kept simple but efficient.
* It's easy to integrate into existing or new projects.
* I really like the coding style.
* more to come! :)
 
### What I think where some improvements might be helpful

* During my source review _(not yet finished)_ I found some bugs which should be fixed.
* Some more modularity for easier extensions.
* I'd like to see some parsing additions but without introducing "performance killer" like regular expressions.

All changes done by me will also apply to the Apache License, Version 2.0.

***

## Changes made so far ##

1. __Bugfix__ for issue #34: _Numeric list after unnumbered lists continues unnumbered list_
2. __Bugfix__ for issue #48: _StringIndexOutOfBoundsException_ - This also solved a not yet documented issue for indented XML remarks.
3. __Implementation__ of issue #7 (actually a feature request): _auto link links_



Best,
Rüdiger Bund
