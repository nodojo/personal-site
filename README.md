# personal-site

Welcome to my personal site!
To create this site, I used the static site generator
[jekyll](https://jekyllrb.com/) along with an incredible theme named
[Jalpc](https://github.com/jarrekk/Jalpc). The site is hosted using
[GitHub Pages](https://pages.github.com/) and can be found at
[nodojo.github.io/](https://nodojo.github.io/) or
[jamieleviner.com](https://www.jamieleviner.com/).

## Develop and Deploy

***Note: All commands should be run from the root directory (personal-site) unless specified otherwise.***

During local development, the site can be served using the command that follows.
It should be noted that this command will first run a build, so it is
unnecessary to run the command `jekyll build` before it.

```bash
jekyll serve
```

To automatically refresh the browser with every change, run the command:

```bash
jekyll serve --livereload
```

To build the project so that it is ready for deployment, run:

```bash
jekyll build
```

### Come back to this

#### original

This will create (or modify) a `_site/ directory`, containing everything from `assets/`, and then the `index.md` and all `pages/*.md` files, converted to html. (So there’ll be `_site/index.html` and the various `_site/pages/*.html.`)

#### simplification (wip)

Building creates or modifies the contents of the `_site/` directory.
When the process completes, the directory will contain converted html
files to represent everything from `assets/`, the `index.md`, and all
files that have names following the `pages/*.md` pattern.
