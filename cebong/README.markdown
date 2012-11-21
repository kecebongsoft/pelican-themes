pelican-cebong-theme
===============

This theme is focused on simplicity and solarized-looks, its structure was derived from the pelican's *notmyidea* theme, and I altered some stuff to look more like [my old tumblr blog](http://kecebongsoft.tumblr.com), which is pretty much solarized-like.

This theme is used for [my pelican blog](http://kecebongsoft.com). 

You can add a tagline below the title using `SITETAGLINE`, and add
additional footer information with `FOOTERTEXT`

This theme uses a different way of showing list of posts, at homepage,
you will only see one latest post, and there will be a link to list of
post in a custom template, called stories.html. In order for pelican to
render this custom template, you have to register the template file in
your config, like so:

```python
        from pelican.settings import _DEFAULT_CONFIG
        DIRECT_TEMPLATES = list(_DEFAULT_CONFIG['DIRECT_TEMPLATES']) + ['stories',]
```

