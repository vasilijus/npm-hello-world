# npm-hello-world
Simple NPM package demo

This is a simple npm package that demonstrates the [GitHub Package Registry](https://github.com/features/package-registry).

## Installation

Before installing, make sure to authenticate with GitHub Package Registry or using a `.npmrc` file. See "[Configuring npm for use with GitHub Package Registry](https://help.github.com/en/articles/configuring-npm-for-use-with-github-package-registry#authenticating-to-github-package-registry)."

```
$ npm install @vasilijus/npm-hello-world`
```

Or add this package to your `package.json` file:

```
"dependencies": {
    "@vasilijus/npm-hello-world": "1.0.0"
}
```

## Usage

```
const myPackage = require('@vasilijus/npm-hello-world');
myPackage.helloWorld();
```



