# eleventy-dot-js-blog

A starter project showing how to build a blog with the [Eleventy](https://11ty.dev/) static site generator using [JavaScript templates (`*.11ty.js`)](https://11ty.dev/languages/javascript/).

[![Netlify Status](https://api.netlify.com/api/v1/badges/cd87e631-aeaa-45fe-9c99-800ef96b53b1/deploy-status)](https://app.netlify.com/sites/eleventy-dot-js-blog/deploys)

## Demo

* [Netlify](https://eleventy-dot-js-blog.netlify.com/)

## Summary

The [layouts](https://gitlab.com/reubenlillie/eleventy-dot-js-blog/-/tree/master/_includes/layouts) are written entirely in vanilla JavaScript (files with the [`*.11ty.js`](https://www.11ty.dev/docs/languages/javascript/) extension). Eleventy processes those templates and creates prerendered copies of the site HTML.

## Features

* π― Lighthouse scores for 
  * π¨ Performance 
  * βΏ Accessibility
  * βοΈ  Best practices
  * π Search Engine Optimization
* πΈ Lightweight front end
  * πΈ Semantic HTML
  * π¨ Progressively-enhanced, modular CSS
  * π¦ Vanilla [JavaScript templates](https://11ty.dev/languages/javascript/)
* ποΈ Customizable design and data options
* π¬ [Choose](https://gitlab.com/reubenlillie/eleventy-dot-js-blog/-/blob/master/_includes/shortcodes/favicon.js) between emoji favicons and the Real Favicon Generator
* π‘ Dark/light mode based on userβs system preferences
* π£ Multilingual support (instructions in [`./content/README.md`](https://gitlab.com/reubenlillie/eleventy-dot-js-blog/-/blob/master/content/README.md) and [`./_data/README.md`](https://gitlab.com/reubenlillie/eleventy-dot-js-blog/-/blob/master/_data/README.md))
* π Smart pagination
* ποΈ Extensive inline documentation

## Project Roadmap

Hereβs a list of new features being considered. [Submit a feature request](https://gitlab.com/reubenlillie/eleventy-dot-js-blog/-/issues/new) to add to this list!

* ποΈ Dark/light mode toggle #14
* π·οΈ Tag archives for blog (coming with [Computed Data](https://www.11ty.dev/docs/data-computed/) in Eleventy v0.11.0) #7
* π Date archives for blog #16
* π Contact form (using [Netlify Forms](https://docs.netlify.com/forms/setup/)) #17
* π‘ [RSS feed](https://www.11ty.dev/docs/plugins/rss/) for blog posts #3
* πΊοΈ Sitemap #54
* π [Search](https://www.hawksworx.com/blog/adding-search-to-a-jamstack-site/) #18
* π Documentation site #19
* π£ [Webmentions](https://mxb.dev/blog/using-webmentions-on-static-sites/) #20
* π¬ [Comments](https://jamstack-comments.netlify.com/) #21
* π Integrate with [Netlify CMS](https://www.netlifycms.org/) #22
* βοΈ  Service worker to cache content for offline access #23
* ποΈ Apply logo/branding assets #24
* ποΈ [Syntax highlighting](https://www.11ty.dev/docs/plugins/syntaxhighlight/) for code blocks #25
* βοΈ  Author information posts (options for mulitple authors and guest submissions) #26

## Getting started

Run a local copy of this site on your computer.

Install [Node.js](https://nodejs.org/) on your machine (see [11ty documentation for version requirements](https://www.11ty.dev/docs/getting-started/)).

Then enter the following commands into your terminal:

### 1. Clone this repository and all its dependencies

```cli
git clone git@gitlab.com:reubenlillie/eleventy-dot-js-blog.git my-blog-directory-name
```

### 2. Go to the working directory

```cli
cd my-blog-directory-name
```
Specifically take a look at the file named [`.eleventy.js`](https://gitlab.com/reubenlillie/eleventy-dot-js-blog/-/blob/master/.eleventy.js) to see if you want to [configure any Eleventy options differently](https://www.11ty.dev/docs/config/).

### 3. Install the project dependencies with [NPM](https://www.npmjs.com/)

```cli
npm install
```

### 4. Edit the `.js` files in the [`_data`](https://gitlab.com/reubenlillie/eleventy-dot-js-blog/-/blob/master/_data/site.js) directory with your site information

### 5. Run Eleventy

```cli
npx eleventy
```

Or build and host locally for local development

```cli
npx eleventy --serve
```

Or build automatically when a template changes

```cli
npx eleventy --watch
```

Or in debug mode

```cli
DEBUG=* npx eleventy
```

## Publish your own copy

The command `npm run build` will generate a copy of the site files in a `_site` directory, which you can deploy with any hosting service.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://gitlab.com/reubenlillie/eleventy-dot-js-blog)

&copy; 2020 by [Reuben L. Lillie](https://twitter.com/reubenlillie)
