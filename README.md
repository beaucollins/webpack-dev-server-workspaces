# Example of `webpack-dev-server` and npm workspaces

```
npm install
npx -w packages/web webpack serve
```

The dependency is installed but `serve` reports otherwise.

```
npm ls -w packages/web webpack-dev-server
webpack-dev-server-workspaces@1.0.0 ./webpack-dev-server-workspaces
└─┬ web@1.0.0 -> ./packages/web
  └── webpack-dev-server@4.3.0
```

```
npx -w packages/web webpack serve
CLI for webpack must be installed.
  webpack-cli (https://github.com/webpack/webpack-cli)

We will use "npm" to install the CLI via "npm install -D webpack-cli".
Do you want to install 'webpack-cli' (yes/no):

```
