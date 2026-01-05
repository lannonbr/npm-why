# Notice: Updated fork

This is a fork of npm-why updating the packages as the old version has not been updated and pushed to npm in 3 years.

To use run `npx lannonbr-npm-why <package_name>`. The rest of the docs by Amio still are valid

# npm-why [![npm-version][npm-badge]][npm-link]

Identifies why a package has been installed.

![npm-why-screenshot][screenshot]

## Install & Usage

```bash
npm install -g npm-why
```

```bash
Usage

  $ npm-why <package-name>

Examples

  $ npm-why babel-core
```

or without installation:

```bash
$ npx npm-why babel-core
```

## Related

- [yarn-why][yarn-why-link] - Identifies why a package has been installed (by yarn.lock).
- [nls][nls-link] - Missing inspector for npm packages.

## License

ISC @ Amio

[screenshot]: ./screenshot.png
[amio-link]: https://github.com/amio
[npm-badge]: https://flat.badgen.net/npm/v/npm-why
[npm-link]: https://www.npmjs.com/package/npm-why
[nls-link]: https://github.com/amio/nls
[yarn-why-link]: https://github.com/amio/yarn-why
