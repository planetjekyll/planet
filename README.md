# Planet Jekyll

Feed list/configuration for [Planet Jekyll](http://planetjekyll.herokuapp.com)
and [Planet Jekyll (Dev Edition)](http://planetjekyll.herokuapp.com/jekylldev)

Note: All feeds including the feed lists (that is, [jekyll.ini](jekyll.ini)
and [jekyll-dev.ini](jekyll-dev.ini))
get auto-updated (fetched) once a day (that is, every 24 hours).


## Add Your Feed - How To

Step 1: Add your feed to the feed list (that is, [jekyll.ini](jekyll.ini) or
[jekyll-dev.ini](jekyll-dev.ini)).


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
  title    = Parker Moore (Blog - By Parker.)
  link     = https://byparker.com
  feed     = https://byparker.com/blog/atom.xml
  github   = parkr
~~~

Step 2: There's no Step 2 ;-)

That's it. Wait for the next auto-update (max. 24 hours). Welcome on Planet Jekyll.


## Powered by Pluto

Planet Jekyll is powered by the [pluto gem](https://github.com/feedreader).

