Learn You an _Elm_
=====================================
_Based on [Learn You a Haskell for a Great Good](http://learnyouahaskell.com/chapters)._

_by Miran Lipovača._

Adapted for Elm by: 

* Joey Eremondi
* Alex Neslusan

Contents
----

{% for post in site.pages %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}

Done
----

* Add disclaimer to all chapters that they are un-adapted for Elm
* Intro updated for Elm

TODO
----

* Adapt code-snippets to Elm
* Remove all references to laziness
* Remove all reference to typeclasses
* Replace "Input and Output" with "Signals and Tasks"
* Change Monad/Applicative/Functor terminology
* Fix image references so can be viewed easily online
* Describe `String` vs `List Char`
* Descrive Records as an extension of tuples

License
-------

This book is licensed under an [Attribution-NonCommercial-ShareAlike 3.0
Unported (CC BY-NC-SA 3.0)](http://creativecommons.org/licenses/by-nc-sa/3.0/)
license.
