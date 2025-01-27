4.0.2 / 2023-12-23
------------------
- switch to noble and scure crypto libraries
- update package to typescript / esm 

3.1.1 / 2020-05-31
------------------
- add safe-buffer as explicit dependency

3.1.0 / 2020-04-09
------------------
- Add async methods

3.0.0 / 2019-09-12
------------------
- Fixed backwards incompatible bug with passphrase NFC normalization

2.0.3 / 2019-05-22
------------------
- made compatible for Electron v4

2.0.2 / 2017-12-14
------------------
- use safe-buffer
- upgrade scryptsy

2.0.1 / 2017-04-20
------------------
- upgrade bs58check
- index: rm unused address parameter

2.0.0 / 2016-12-20
------------------
- removed class instantiation. Removed `coinstring` dep.

1.4.0 / 2015-11-03
------------------
- added `progressCallback`. See: https://github.com/bitcoinjs/bip38/pull/16

1.3.0 / 2015-06-04
------------------
- use `createHash` and `aes` directly. https://github.com/cryptocoinjs/bip38
- JavaScript Standard Style

1.2.0 / 2015-01-05
------------------
- removed dependency upon `aes` package since Browserify now supports aes [Daniel Cousens](https://github.com/cryptocoinjs/bip38/pull/6)
- removed `crypto-browserify` devDep and removed `browser` field from `package.json`; no longer necessary
- added method `verify()` [Daniel Cousens](https://github.com/cryptocoinjs/bip38/pull/7)

1.1.1 / 2014-09-19
------------------
- bugfix: enforce zero padding [Daniel Cousens](https://github.com/cryptocoinjs/bip38/commit/e73598d0fc1d1b3c04c132c34053e96bec6bd201)
- add MIT license to package.json

1.1.0 / 2014-07-11
------------------
- added methods `encryptRaw` and `decryptRaw` [Daniel Cousens](https://github.com/cryptocoinjs/bip38/pull/4)

1.0.0 / 2014-06-10
------------------
- upgraded `"scryptsy": "~0.2.0"` to `"scryptsy": "^1.0.0"`
- upgraded  `"bigi": "~0.2.0"` to `"bigi": "^1.2.0"`
- removed `ecurve-names` dep
- upgraded `"ecurve": "~0.3.0"` to `"ecurve": "^0.8.0"`
- removed semicolons per http://cryptocoinjs.com/about/contributing/#semicolons
- removed `crypto-hashing` dep
- removed `bs58` dep, added `coinstring` dep
- removed `terst` for `assert`
- added TravisCI
- added Coveralls
- added testling
- removed static level methods, must call `new`

0.1.0 / 2014-03-05
------------------
- added support to decrypt ECMultiplied keys, #1
- made constructor work without `new`
- upgraded deps `ecurve`, `ecurve-names`, and `scryptsy`

0.0.1 / 2014-02-28
------------------
- initial release
