# About Blank

A minimalist [Hugo](https://gohugo.io/) theme.

## Requirements

* Hugo extended (with Sass/SCSS support)

## Installation

```
cd <your Hugo project>
git submodule add https://github.com/schu/about-blank themes/about-blank
cd themes/about-blank
npm install
```

In your `config.toml` set

```
theme = "about-blank"
```

## Configuration parameters

Configuration parameters with their defaults.

```
# Hugo config.toml

[params]
  # Whether the top navigation should be disabled
  disableMenu = false
  # Whether the default list view should show tag pills below items
  showTagPills = false
```
