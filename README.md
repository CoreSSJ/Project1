# Dev & Ops
<pre><div align="right"><a href="https://coressj.github.io/Project1" target="_top">Home</a> <a href="https://coressj.github.io/Project1/page2" target="_top">Categories</a> <a href="https://coressj.github.io/Project1/page3" target="_top">About us</a> </div></pre>

[![.github/workflows/ci.yaml](https://github.com/pages-themes/cayman/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/cayman/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-cayman.svg)](https://badge.fury.io/rb/jekyll-theme-cayman)



*We are the Dev and Ops team that is going to blow this project out of this world*


![Thumbnail of Devops](Devops.jpg)

## Usage

To use the Cayman theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: pages-themes/cayman@v0.2.0
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

Cayman will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" (unquoted) to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```


### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` once before the test script will work.
