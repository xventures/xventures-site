# Setting up

XVentures site uses Hugo static site generator, [download Hugo](http://gohugo.io/) binary and put it into PATH.

    # This repository
    $ git clone https://github.com/xventures/xventures-site.git
    # Publish destination
    $ cd xventures-site
    $ git clone https://github.com/xventures/xventures.github.io.git


Add a new page using

    $ hugo new page-name

Start a local server to test, then publish content.

    # Start local server for the site.
    $ hugo server
    # Just publish
    $ hugo

Push it to github: note that you need to push two repositories separately: xventures-site and xventures.github.io, this is intended.
