
# This is the data for my blog

You can see my blog at http://dongminkim.github.io/

It is automatically transformed by [Jekyll](http://github.com/jekyll/jekyll)
into a static site whenever I push this repository to GitHub.

## Branches

`source` branch contains source data, and `master` branch contains built site.
Currently I'm following these steps because `jekyll-archives` is [not supported by GitHub Pages](https://help.github.com/articles/configuring-jekyll-plugins/) and I don't want to use external services like [Travis CI](https://travis-ci.org).

1. Test locally with `source` branch: `jekyll serve`
2. When it is ready to push, `jekyll build`
3. Push contents of `_site` directory into `master` branch

