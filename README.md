# Vcoin (Bcoin ported to Vertcoin)

__NOTE__: The latest release of vcoin contains a non-backward compatible change
to the rest API. Please read the [changelog]'s "migrating" section for more
details.

---

**Vcoin** is an alternative implementation of the vertcoin protocol, written in
node.js.

Although still in a beta state, vcoin is well tested and aware of all known
consensus rules. It is currently used in production as the consensus backend
and wallet system for [purse.io][purse].

## Uses

- Full Node
- SPV Node
- Wallet Backend (bip44 derivation)
- Mining Backend (getblocktemplate support)
- Layer 2 Backend (lightning)
- General Purpose Bitcoin Library

Try it in the browser: http://bcoin.io/browser.html

## Install

```
$ git clone https://github.com/vertcoin-project/vcoin.git
$ cd vcoin
$ npm install
$ ./bin/vcoin
```

See the [Beginner's Guide][guide] for more in-depth installation instructions.

## Documentation

- API Docs: http://bcoin.io/docs/
- REST Docs: http://bcoin.io/api-docs/index.html
- Docs: [docs/](docs/README.md)

## Support

Join us on [freenode][freenode] in the [#bcoin][irc] channel.

## Disclaimer

Vcoin does not guarantee you against theft or lost funds due to bugs, mishaps,
or your own incompetence. You and you alone are responsible for securing your
money.

## Contribution and License Agreement

If you contribute code to this project, you are implicitly allowing your code
to be distributed under the MIT license. You are also implicitly verifying that
all code is your original work. `</legalese>`

## License

- Copyright (c) 2014-2015, Fedor Indutny (MIT License).
- Copyright (c) 2014-2017, Christopher Jeffrey (MIT License).

See LICENSE for more info.

[purse]: https://purse.io
[guide]: https://github.com/vertcoin-project/vcoin/blob/master/docs/Beginner's-Guide.md
[freenode]: https://freenode.net/
[irc]: irc://irc.freenode.net/bcoin
[changelog]: https://github.com/vertcoin-project/vcoin/blob/master/CHANGELOG.md
