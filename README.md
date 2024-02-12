# Wikistreets raw web front-end

Front-end using raw HTML, CSS, and Javascript. No front-end framework, except jQuery. To be replaced with a new version using a framework.

This front-end is currently bundled with the back-end into the monorepo version, which is the currently live version. The monorepo is being split into separate front- and back- end repositories to improve the workflow of future development. This repository holds only the front-end code for historic reasons.

### Start up the webpack bundler

This repo uses `webpack` to bundle the front-end code. The built static code fiels are placed into the `public` directory.

Client-side scripts in the `src/` folder are automatically minified and bundled on save using [webpack](https://webpack.js.org/). Automatically re-bundle any changes by setting the following watcher:

```
npx webpack --watch
```
