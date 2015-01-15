# Jekyll Blog Theme

Blog theme for [Jekyll](http://jekyllrb.com), a static site generator written in Ruby.

Based upon [Jekyll Incorporated Theme](https://github.com/kippt/jekyll-incorporated) by Kippt Inc.

Slightly modified and simplified for my needs. Uses Jekyll's built-in support for Sass (which was introduced in Jekyll 2.0).


## Installation & Usage

```shell
gem install jekyll
git clone https://github.com/1element/jekyll-blog-theme.git .
jekyll serve --watch
```


## Configuration

Edit: ```_config.yml``` (general options) and ```_sass/*.scss``` for stylesheets (theme colors &amp; fonts).

```
jekyll-blog-theme/
+-- _config.yml
+-- _sass/
    +-- _animate.scss
    +-- _article.scss
    +-- _base.scss
    +-- _bootstrap.scss
    +-- _icons.scss
    +-- _nav.scss
    +-- _responsive.scss
    +-- _syntax.scss
```

_Note: when editing _config.yml, you need to restart jekyll to see the changes._


## Copyright and License

Copyright 2013 Kippt Inc. under [The MIT License](LICENSE)
