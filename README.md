# Murmures-d-anges.github.io
website with zola https://www.getzola.org/

It uses Hub Pages to  publish any generated files provided there is an index.html file in the root of a branch called gh-pages, main or master.
That branch name can also be manually changed in the settings of a repository.
To serve a site at <username>.github.io or <organization>.github.io,
you must name the repository <username>.github.io or <organization>.github.io (otherwise GitHub will append the repository name to the URL, e.g.: <username>.github.io/<repositoryname>.

We  use any continuous integration (CI) server to build and deploy our site with Github Actions
It use git submodule to include the theme, e.g.:
```
git submodule add https://github.com/getzola/after-dark.git themes/after-dark
```
