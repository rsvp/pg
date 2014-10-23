## What is this pg repository?

Github provides web hosting of static 
[Project Pages](https://help.github.com/articles/creating-project-pages-manually/) 
which we utilize to serve introductory pages for various projects. 

It uses the *--orphan branch* hack to render files, 
for example, as `http://username.github.io/foo/bar.html` 
where bar.html lives in an orphan branch which must be 
strictly named "gh-pages". 

For those unfamiliar with such an *ad hoc* arrangement, 
this could cause merge confusion if an orthogonal master 
branch also co-exists. 
One might also easily believe that `foo` is an directory under 
the personal page repo `username.github.io`, 
but in fact it must be a separate repo unto itself (like this pg).

Thus for clarity we created an entirely distinct repo, 
not containing development code, whose 
**sole purpose is serving project documents**. 

So think of *pg* as an abbreviation for *"page"* or *"project guide."*

## Other links

import Adriano as [rsvp](http://rsvp.github.com)

Actual source code repositories mentioned under pg 
may reside [here](http://github.com/rsvp), e.g. 
the *fecon235* projects.
 
- - - -

(2014-10-22 Convert README.md to index.html) 

    