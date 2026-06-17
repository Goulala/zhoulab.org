# Zhou Lab Jekyll Site

This is a separate Jekyll/GitHub Pages version of the redesigned Zhou Lab website.

Deploy this folder to the `Goulala/zhoulab.org` GitHub repository, so the site can live at:

`https://goulala.github.io/zhoulab.org/`

That keeps the existing `goulala.github.io` website untouched.

If you connect the custom domain `zhoulab.org`, change `baseurl` in `_config.yml` to an empty string:

```yml
baseurl: ""
```

Local preview:

```bash
bundle install
bundle exec jekyll serve
```
