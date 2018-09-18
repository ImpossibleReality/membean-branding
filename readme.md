# Membean Branding Guidelines

This site uses the [Foundation 6 sites](https://foundation.zurb.com/sites.html) template. Please [check the documentation](https://foundation.zurb.com/sites/docs/) for information about available styles, scripts, etc.

## Installation

To make changes to this site, your computer needs:

- [NodeJS](https://nodejs.org/en/) (Version 6 only, Tested with 6.11.4)
- [Git](https://git-scm.com/)

### Setup

First, clone this repository to your local computer:

```bash
git clone git@github.com:membean/branding.git
```

Then, you'll want to install all the dependencies:

```bash
cd branding
yarn
```

Finally, run `foundation watch`. The site will be viewable locally at this URL:

```
http://localhost:8000
```

Make whatever changes you need to make, and then push the changes to this repository to update the live Github pages site:

```bash
yarn run build
git add .
git commit -m 'Your commit message...'
git push
```

---

Some of the available features of a Foundation Sites 6 project are:

## Panini Helpers

We've added a Panini helpers for per-page or per-layout styles.

[SEE EXAMPLE](http://notebooks.zurb.com/posts/10139362?t=f9b74287fe3ac074)

---

## Mixins

We've added a few handy mixins for maintainable repeated code and faster development:

### Avatar

### Container Border

### Flex Mixins

---

## Additional Project Dependencies

The following dependencies are at your disposal:

### SVG Injector

Inject an SVG by using an `img` tag with the `.inject-me` class like so:

`<img src="{{root}}assets/img/think.svg" class="inject-me" alt="think icon">`
