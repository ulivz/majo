# majo

<a href="https://www.pixiv.net/member_illust.php?mode=medium&illust_id=62542828">
<img src="https://ooo.0o0.ooo/2017/04/27/59016709425c9.jpg" width="300" />
</a>

*Art by [でんでんCOMIC1・こ24b](https://www.pixiv.net/member.php?id=12192)*

[![NPM version](https://img.shields.io/npm/v/majo.svg?style=flat)](https://npmjs.com/package/majo) [![NPM downloads](https://img.shields.io/npm/dm/majo.svg?style=flat)](https://npmjs.com/package/majo) [![CircleCI](https://circleci.com/gh/egoist/majo/tree/master.svg?style=shield&circle-token=560404744e167900959a512d617a05ec5240616f)](https://circleci.com/gh/egoist/majo/tree/master)  [![donate](https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&style=flat)](https://github.com/egoist/donate)

## Install

```bash
yarn add majo
```

## Usage

```js
const majo = require('majo')

const stream = majo()

// Given that you have js/app.js js/index.js
stream
  .source('js/**')
  .dest('dist')
  .then(() => {
    // Now you got dist/js/app.js dist/js/index.js
  })
```

## Support

[API docs](/docs/api.md)<br>
[Middleware](/docs/middleware.md)

## Used By

- [SAO](https://github.com/egoist/sao): ⚔️ Futuristic scaffolding tool. 

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## Author

**majo** © [egoist](https://github.com/egoist), Released under the [MIT](./LICENSE) License.<br>
Authored and maintained by egoist with help from contributors ([list](https://github.com/egoist/majo/contributors)).

> [egoistian.com](https://egoistian.com) · GitHub [@egoist](https://github.com/egoist) · Twitter [@rem_rin_rin](https://twitter.com/rem_rin_rin)
