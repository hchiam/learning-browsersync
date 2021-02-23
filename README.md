# Learning [Browsersync](https://www.browsersync.io)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

https://www.browsersync.io

Mirror your actions across a bunch of synchronized browsers on the same machine. Example: run the same actions on a bunch of browsers at the same time. Just open them all to the same port (e.g. Browsersync creates http://localhost:3000), and it'll try to replicate your actions on all the browsers at the same time. https://www.sitepoint.com/improve-workflow-browsersync-2-0

```bash
npm install -g browser-sync
```

<!-- (didn't seem to work for yarn)

or

```bash
yarn global add browser-sync
```

-->

Example if you don't have a server running already:

```bash
browser-sync start --server --files "css/*.css"
```

Example if already running a server:

```bash
browser-sync start --proxy "myproject.dev" --files "css/*.css"
```

Another example:

```bash
browser-sync start --proxy "http://localhost:1234/" --files "some-css-folder" "some-js-folder" "index.html" "slides.css" "slides.js"
```

## Recipes:

https://www.browsersync.io/docs/recipes
