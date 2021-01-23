# hugo-theme-weui

[![hugo-theme-weui](https://img.shields.io/badge/Hugo%20Theme-%40weui-blue)](https://themes.gohugo.io/hugo-theme-weui/)
[![Hugo](https://img.shields.io/badge/Hugo-%5E0.76-orange)](https://gohugo.io/)
![GitHub](https://img.shields.io/github/license/wayjam/hugo-theme-weui)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/wayjam/hugo-theme-weui)
![Netlify](https://img.shields.io/netlify/ac8ca626-646f-45a5-86d4-a182877ebb1f)

A simple hugo theme which is built with [weui](https://github.com/Tencent/weui). You can preview this theme at a [Live Demo](https://hugo-weui-demo.netlify.app/).

## Installation

Run this command from the root of your Hugo directory (Git needs to be installed):

```
$ git clone https://github.com/wayjam/hugo-theme-weui.git
```

Or, if your Hugo site is already in git, you can include this repository as a `git submodule`. This makes it easier to update this theme (_and for some deployment options i.e. Netlify_).

```
$ git submodule add https://github.com/siegerts/hugo-theme-weui.git themes/hugo-theme-weui
```

Alternatively, if you are not familiar with git, you can download the theme as a .zip file, unzip the theme contents, and then move the unzipped source into your themes directory.

For more information, read the official [documentation](https://gohugo.io/themes/installing-and-using-themes) of Hugo.

## Run example site

From the root of `themes/hugo-theme-weui/exampleSite`:

```
hugo server --themesDir ../..
```

## Configuration

Check out the sample `config.toml`file located in the [`exampleSite`](https://github.com/wayjam/hugo-theme-weui/tree/master/exampleSite) directory. Copy the `config.toml` to the root directory of your Hugo site, then edit as desired.

## Syntax highlighting

Syntax highlighting is provided by [highlight.js](https://highlightjs.org/). The color theme can be changed by modifying the highlight.js stylesheet in `layouts/partials/head_includes.html`.

## License

The code is available under the [MIT license](https://github.com/wayjam/hugo-theme-weui/blob/master/LICENSE).
