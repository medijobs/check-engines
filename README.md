<div align="center">
  <img src="https://gist.githubusercontent.com/0-vortex/acffcb296295f5d6e10865528ed5c7f2/raw/3666f45755d249534f83d5658ac892c6bc0b4963/medirecruit.svg" width="400">
</div>

# @medijobs/check-engines

> Never break your dependency tree with [**npm-install-checks**](https://www.npmjs.com/package/npm-install-checks) running on [**npx**](https://www.npmjs.com/package/npx).

[![Commits](https://img.shields.io/github/commit-activity/w/medijobs/check-engines?style=flat)](https://github.com/medijobs/check-engines/pulse)
[![Issues](https://img.shields.io/github/issues/medijobs/check-engines.svg?style=flat)](https://github.com/medijobs/check-engines/issues)
[![Releases](https://img.shields.io/github/v/release/medijobs/check-engines.svg?style=flat)](https://github.com/medijobs/check-engines/releases)

</div>

## 📦 Install

This package is binary and doesn't require installation however you can add it to your repository as a `devDependency`:

```shell
npm install --save-dev @medijobs/check-engines
```

## 🚀 Usage

All you have to do is run the script next to your `package.json`:

```shell
npx @medijobs/check-engines
```

## 🔧 Configuration

The most common use case for this package is to let it run on `install` and `start` generic `npm` scripts:

```json
{
  "scripts": {
    "preinstall": "npx @medijobs/check-engines",
    "prestart": "npx @medijobs/check-engines"
  }
}
```

Or with less copy paste:

```json
{
  "scripts": {
    "engines": "npx @medijobs/check-engines",
    "preinstall": "npm run engines",
    "prestart": "npm run engines"
  }
}
```

## 🤝 Contributing

If you decide to fix a bug, make sure to use the conventional commit available at:

```shell
npm run push
```

## ⚖️ LICENSE

MIT © [TED (Teodor-Eugen Dutulescu) Vortex](./LICENSE)
