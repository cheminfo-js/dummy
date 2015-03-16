# dummy

  [![NPM version][npm-image]][npm-url]
  [![build status][travis-image]][travis-url]
  [![David deps][david-image]][david-url]
  [![npm download][download-image]][download-url]

Dummy project - used as a starting point for new libraries

## Init project

* Download [latest zip](https://github.com/cheminfo-js/dummy/archive/master.zip)
* Extract __entire__ folder (including .gitignore, .npmignore and .travis.myl files) to a new location
* Edit :
 * package.json
 * bower.json
 * README.md (links at the end)
* `git init`
* `git add --all`
* Create a [new repository](https://github.com/organizations/cheminfo-js/repositories/new) on GitHub. (__DO NOT INITIALIZE IT__)
* Push the initial code to GitHub

## Configure release hooks

* [Travis CI](https://travis-ci.org/profile)
* [lactame](http://direct.lactame.com/release/)

## First release

* Build using the lactame interface
* On your computer:
 * git pull
 * `npm publish`
 * `npm author add cheminfo-bot dummy`
 * if you want it on Bower : `bower register project-name git://github.com/cheminfo-js/dummy`

## Next releases

* Build using the lactame interface
* Publish on NPM using the same interface (NPM button)
* nothing needed for Bower

## License

  [MIT](./LICENSE)

[npm-image]: https://img.shields.io/npm/v/cheminfo-dummy.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/cheminfo-dummy
[travis-image]: https://img.shields.io/travis/cheminfo-js/dummy/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/cheminfo-js/dummy
[david-image]: https://img.shields.io/david/cheminfo-js/dummy.svg?style=flat-square
[david-url]: https://david-dm.org/cheminfo-js/dummy
[download-image]: https://img.shields.io/npm/dm/cheminfo-dummy.svg?style=flat-square
[download-url]: https://www.npmjs.com/package/cheminfo-dummy
