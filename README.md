Certain packages do not adhere to semantic versioning, or ["SemVer"](http://semver.org).  If your code depends upon such a package, using a "fuzzy" SemVer version requirement can lead to problems when breaking changes are released within non-"major" versions.

For this reason, the **following packages are recommended to be installed with the`--save-exact` option**, which means any upgrades to new versions must be performed manually.

Example:

```sh
$ npm install --save --save-exact underscore
```

# List of known npm packages which do not adhere to SemVer

***Please send PRs for other packages you discover!***

> Note: This is **not** a list of projects which have "violated" SemVer on occasion; these are packages that historically do not use the versioning scheme and/or its guidelines.

- [underscore](https://www.npmjs.org/package/underscore)
- [coffee-script](https://www.npmjs.org/package/coffee-script)

