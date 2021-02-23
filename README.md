# Learning [Browsersync](https://www.browsersync.io)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

https://www.browsersync.io

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
