# LAW-XI-2017
The 11th Linguistic Annotation Workshop

This is the `master` branch; it contains sources for building the website.
The [website](https://sigann.github.io/LAW-XI-2017) itself lives on the `gh-pages` branch.
To deploy changes:

    $ git checkout master
    ...make, commit, and push changes...
    $ python2 build.py deploy
    $ git checkout gh-pages
    $ mv deploy/* .
    $ rmdir deploy
    $ git commit -a -m "deploy changes"
    $ git push
