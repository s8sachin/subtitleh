<img src="internals/img/erb-banner.png" width="100%" />

<br>

<p>
  Subtitleh is built using <a href="https://electron-react-boilerplate.js.org/">Electron React Boilerplate</a>. That includes <a href="https://electron.atom.io/">Electron</a>, <a href="https://facebook.github.io/react/">React</a>, <a href="https://github.com/reactjs/redux">Redux</a>, <a href="https://github.com/reactjs/react-router">React Router</a>, <a href="https://webpack.github.io/docs/">Webpack</a> and <a href="https://github.com/gaearon/react-hot-loader">React Hot Loader</a> .
</p>

<br>
<hr />
<br />

## Install

First, clone the repo via git and install dependencies:

```bash
yarn
```

## Run Development

Start the app in the `dev` environment. This starts the renderer process in [**hot-module-replacement**](https://webpack.js.org/guides/hmr-react/) mode and starts a webpack dev server that sends hot updates to the renderer process:

```bash
yarn dev
```

## Packaging for Production

To package apps for the local platform:

```bash
yarn package
```

## Debugging on Production

To package apps for the local platform:

```bash
yarn cross-env DEBUG_PROD=true yarn build yarn cross-env DEBUG_PROD=true yarn start
```

<!-- ## Donations

**Donations will ensure the following:**

- 🔨 Long term maintenance of the project
- 🛣 Progress on the [roadmap](https://electron-react-boilerplate.js.org/docs/roadmap)
- 🐛 Quick responses to bug reports and help requests -->

## Maintainers

- [Sachin Srinivasan](https://github.com/amilajack)

## License

MIT © [Sachin Srinivasan](https://github.com/s8sachin)
