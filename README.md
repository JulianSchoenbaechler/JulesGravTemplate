# Jules Theme

**Jules** is the portfolio theme for [https://julian-s.ch/](https://julian-s.ch/).

### Supported Page Templates

* Default view template `default.md`
* Error view template `error.md`
* Blog view template `blog.md`
* Blog item view template `item.md`

# Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `jules`.

You should now have all the theme files under

    /your/site/grav/user/themes/jules

## Default Options

Quark comes with a few default options that can be set site-wide.  These options are:

```yaml
enabled: true                 # Enable the theme
production-mode: true         # In production mode, only minified CSS is used. When disabled, nested CSS with sourcemaps are enabled
blog-page: '/blog'            # The route to the blog listing page, useful for a blog style layout with sidebar
```

To make modifications, you can copy the `user/themes/jules/jules.yaml` file to `user/config/themes/` folder and modify, or you can use the admin plugin.

> NOTE: Do not modify the `user/themes/jules/jules.yaml` file directly or your changes will be lost with any updates

# License
This GRAV theme is licensed under the [MIT License](https://github.com/JulianSchoenbaechler/JulesGravTemplate/blob/master/LICENSE).
