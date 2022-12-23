# Website

https://nmiddendorff.github.io/middweb-catalog/

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

This app is deployed using Github Actions and Github Pages. When a PR is merged into the `main` branch, the deployment workflow will build the app and dump the artifacts into the `gh-pages` branch.