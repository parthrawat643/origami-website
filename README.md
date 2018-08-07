
# Origami

This is the source code for the Origami website as well as a place to open up issues on Origami as a whole. Please visit [origami.ft.com] if you're looking for the documentation.

**:warning: WORK IN PROGRESS :warning:**<br/>
This is currently a work in progress, and we're porting across content from the live site piece by piece. The content here is subject to change without notice and you shouldn't consider this the canonical Origami documentation yet.


## Editing this site

This is a rough guide to editing this site, and where the content lives.

### Static pages

Single static pages live in the [`pages` folder](pages). These each have `permalink` frontmatter set to indicate where the rendered page will live on the site. We store them in this folder to avoid cluttering up the root path of the repo.

### Technical documentation pages

The actual documentation for Origami lives in the [`_documentation` folder](_documentation). This should contain an easier-to-digest version of the Origami specification as well as in depth guides on how to use Origami (excluding step by step tutorials).

### Specification pages

The formal Origami specification lives in the [`_specification` folder](_specification).

### Tutorial pages

Step by step tutorials on how to use Origami live in the [`_tutorials` folder](_tutorials).


## Running locally

You'll need [Ruby], [Bundler] and [Node.js] installed for this.

  1. Install dependencies: `make install`
  2. Build and serve the site: `make serve`
  3. Visit <http://localhost:4000/>



[bundler]: http://bundler.io/
[jekyll]: http://jekyllrb.com/
[node.js]: https://nodejs.org/
[origami.ft.com]: http://origami.ft.com/
[ruby]: https://www.ruby-lang.org/en/