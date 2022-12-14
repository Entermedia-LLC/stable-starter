# stable-starter [![Build Status](https://travis-ci.com/bmarshall511/stable-starter.svg?branch=master)](https://travis-ci.com/bmarshall511/stable-starter)

> Get a jump start building Drupal 8 and 9 themes using Stable Starter, a sub-theme of [Stable](https://www.drupal.org/docs/8/core/themes/stable-theme).

## Installation

### Install via Composer (recommended)

In the Drupal project root, run:

```
composer create-project bmarshall511/stable_starter themes/custom/stable-starter dev-master
```

### Manual Install

1. Download the theme.
2. Upload the _stable-starter_ folder to the desired themes folder in your Drupal installation.
3. Download [gulp-starter](https://github.com/bmarshall511/gulp-starter).
4. Upload the _gulp-starter_ folder the the _stable-starter_ theme folder and rename it to `assets`.
5. Install the required node modules in the assets folder by running `npm install` inside the `assets` directory.
6. Download [scss](https://github.com/Entermedia-LLC/scss) & upload it to the `assets/src` directory.
7. Enable and make it the active, default theme.

## Development

For information on developing and compiling resources within the _assets_ folder, see the [gulp-starter README.md](https://github.com/bmarshall511/gulp-starter/blob/master/README.md).

### Theme Libraries

- `stable_starter/stable_starter` - Includes the global, base [non-critical](https://web.dev/defer-non-critical-css/) CSS styles.

## Deployment Checklist

- [ ] Update the _favicon.ico_.
- [ ] Update the _logo.svg_.
- [ ] Update the _screenshot.png_.
- [ ] Compile _assets_ for production by running `npm run build`.
