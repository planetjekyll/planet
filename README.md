# Planet Jekyll

Feed list/configuration for [Planet Jekyll](http://planetjekyll.herokuapp.com)


Note: All feeds including the feed lists (that is, [jekyll.ini](jekyll.ini)
and friends)
get auto-updated (fetched) once a day (that is, every 24 hours).


## Add Your Feed - How To

Step 1: Add your feed to the feed list (that is, [jekyll.ini](jekyll.ini) or
friends).


Example:

~~~
[jekyllnews]
  title  = Official Jekyll News
  link   = http://jekyllrb.com/news
  feed   = http://jekyllrb.com/feed.xml
~~~

or

~~~
[parkermoore]
  title    = Parker Moore
  link     = https://byparker.com
  feed     = https://byparker.com/blog/atom.xml
  github   = parkr
~~~

Step 2: There's no Step 2 ;-)

That's it. Wait for the next auto-update (max. 24 hours). Welcome on Planet Jekyll.


## Powered by Pluto

Planet Jekyll is powered by the [pluto gem](https://github.com/feedreader).

