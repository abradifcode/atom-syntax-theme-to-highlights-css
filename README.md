# atom-syntax-theme-to-highlights-css

[![Build Status](https://travis-ci.org/MoOx/atom-syntax-theme-to-highlights-css.svg?branch=master)](https://travis-ci.org/MoOx/atom-syntax-theme-to-highlights-css)

[![Repo on GitHub](https://img.shields.io/badge/repo-GitHub-3D76C2.svg)](https://github.com/MoOx/atom-syntax-theme-to-highlights-css)
[![Repo on GitLab](https://img.shields.io/badge/repo-GitLab-6C488A.svg)](https://gitlab.com/MoOx/atom-syntax-theme-to-highlights-css)
[![Repo on BitBucket](https://img.shields.io/badge/repo-BitBucket-1F5081.svg)](https://bitbucket.org/MoOx/atom-syntax-theme-to-highlights-css)

This CLI tool allows you to transform an [Atom theme](https://www.atom.io/themes) to CSS ready to be used by code highlighted with [atom/highlights](https://github.com/atom/highlights).

Atom themes are [less](http://lesscss.org) files so a compilation is required when you want to use those directly.

This simple command clone, compile and adjust CSS for you.

![Preview](preview.gif)

## Install

⚠️ No need to install this package globally as you will probably not use it often.
_You can rely on [npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) which is provided by default in latest version of npm._

Bu in case you want to...

```console
npm install -g atom-syntax-theme-to-highlights-css
```

## Usage

To output the CSS

```console
npx atom-syntax-theme-to-highlights-css https://github.com/simurai/duotone-dark-sea-syntax
```

To copy directly into your clipboard

```console
npx atom-syntax-theme-to-highlights-css --clipboard https://github.com/simurai/duotone-dark-sea-syntax
```

Note: an alias is also available if you have installed the package globally: `atomst2hlcss`

## Related

* [remark-highlights](https://github.com/MoOx/remark-highlights)
