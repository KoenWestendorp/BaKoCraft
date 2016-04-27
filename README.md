# BaKoCraft
A Jekyll based website for the BaKoCraft minecraft server.

## User Manual ;-)
### Syntax for articles
The YML meta data in posts should be like this:
``` yml
layout: [post , img-post]
category: [news , img-gallery , kit-pvp , ...]
published: [true , false]
title: [ THE TITLE OF THE POST (keep it a bit short ;-) )]
image: /img/[ IMAGENAME ].[ EXTENTION] or [ LINK TO A WEB IMAGE WITH AN URL ]
```

And the title of the article should always be written like this
``` txt
# {{ page.title }}
```
