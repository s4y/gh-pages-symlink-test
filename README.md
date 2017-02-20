# GitHub Pages symlink test

#### QUESTION:

Do symbolic links work with [GitHub Pages](http://pages.github.com/)?

#### ANSWER:

YES! but only in non-jekyll mode.

The key is to place a empty file `.nojekyll` in root folder of `gh-pages`.

(That will disable the jekyll support of your github pages site.)

#### TEST

1. This:

<http://s4y.github.io/gh-pages-symlink-test/link.txt>

... is an exact copy of this:

<http://s4y.github.io/gh-pages-symlink-test/target.txt>

2. This

<http://s4y.github.io/gh-pages-symlink-test/docs/current/>

... goes to:

<http://s4y.github.io/gh-pages-symlink-test/docs/hello/>

[Any questions](https://github.com/s4y/gh-pages-symlink-test/issues)?
