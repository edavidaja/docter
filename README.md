# docter

Docter is a project documentation theme based on  [CFPB's DOCter](https://github.com/cfpb/docter). 18F Guides also made significant use of these themes, and some inspiration is drawn from those as well.

## installation

this theme requires Hugo Extended.

from the root of your hugo site, run:

```
cd themes
git clone https://gitlab.com/edavidaja/docter.git
```

## getting started

### pages

The sidebar will be built automatically from the content in `page`. You can use `weight` in the content front matter to adjust the order of the items.

### posts

You can create blog posts in `post`. The most recent five by date will be displayed on the home page.

## brand color

You can set the color for the website using the `brand_color` option in `config.toml`.
