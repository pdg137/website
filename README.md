Website - Template to make a based static-website
=======

This repository is a template for making a
[Jekyll](https://jekyllrb.com/)-based static website.  It is
compatible with [GitHub Pages](https://pages.github.com/), though you
should adjust `.ruby-version` for compatibility with whatever GitHub
is currently using.

Software installation
---------------------

I recommend installing [chruby](https://github.com/postmodern/chruby)
and following their [ruby installation
instructions](https://github.com/postmodern/chruby/wiki/Ruby).

To autoload ruby when you `cd` into this folder, add this to `~/.bashrc`:

```bash
if [ -d /usr/local/share/chruby ]; then
   source /usr/local/share/chruby/chruby.sh
   source /usr/local/share/chruby/auto.sh
fi
```

Install bundler:

```bash
gem install bundle
```

Preview
-------
Preview the website with `bundle && bundle exec jekyll server`.

Or share it with others using `bundle && bundle exec jekyll server --host 0.0.0.0`.
