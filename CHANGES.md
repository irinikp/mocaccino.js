# Changes

## 5.0.0

- 💥 [`2a6c8c9`](https://github.com/mantoni/mocaccino.js/commit/2a6c8c922765bb3ca01abd541ac40f24049bfcf2)
  Update mocha to v8, adjust assertions (Frederik Ring)
- 🍏 [`a90d13a`](https://github.com/mantoni/mocaccino.js/commit/a90d13a98b9db38be7bb625459a8ce7c88d1a764)
  Port browser tests to use puppeteer (Frederik Ring)
- 🐛 [`4382056`](https://github.com/mantoni/mocaccino.js/commit/4382056553ec27774483e8cac3d884e8dae31f9a)
  Ensure brout is required before mocha (Frederik Ring)
- 🐛 [`3fa740a`](https://github.com/mantoni/mocaccino.js/commit/3fa740a258b02bdfb2e0783fec4520a059a445da)
  Pass in custom reporters in setup to work around dynamic require limitation (Frederik Ring)
- 🛡 [`05ee03e`](https://github.com/mantoni/mocaccino.js/commit/05ee03ecd40ac9117c2aa490da8938610ebd542c)
  npm audit
- 🛡 [`7f1ae36`](https://github.com/mantoni/mocaccino.js/commit/7f1ae368f9732a270b95b20a788d3c82093980a1)
  Bump lodash from 4.17.19 to 4.17.21 (dependabot[bot])
- 🛡 [`637cb13`](https://github.com/mantoni/mocaccino.js/commit/637cb13990bbdabee46b4ee9d3ae2b8ae23d6235)
  Bump elliptic from 6.4.1 to 6.5.4 (dependabot[bot])
- 🛡 [`9a81451`](https://github.com/mantoni/mocaccino.js/commit/9a81451b806bcf3dc445b2927c8edd73f7ddc029)
  Bump js-yaml from 3.12.0 to 3.14.0 (dependabot[bot])
- 🛡 [`2fce39a`](https://github.com/mantoni/mocaccino.js/commit/2fce39a82b3690ae1f20e5814c8925b0097a16f4)
  Bump lodash from 4.17.11 to 4.17.19 (dependabot[bot])
- 📚 [`c29813f`](https://github.com/mantoni/mocaccino.js/commit/c29813fb727b86832324b3592c855e9039b89ec8)
  Remove phantomic references from README and update engine requirements (Frederik Ring)
- ✨ [`953e4ee`](https://github.com/mantoni/mocaccino.js/commit/953e4ee032af83c5b4e04b215cea557c8cc27316)
  Upgrade Studio Changes

_Released by [Maximilian Antoni](https://github.com/mantoni) on 2021-05-23._

## 4.1.2

- [`f46487a`](https://github.com/mantoni/mocaccino.js/commit/f46487a16d1da04bcad60d111ea98b900e2b62e4)
  Do not assume `process.nextTick` exists

_Released by [Maximilian Antoni](https://github.com/mantoni) on 2019-10-09._

## 4.1.1

- [`fc0eb96`](https://github.com/mantoni/mocaccino.js/commit/fc0eb96deeaeb57d0f7c515177a1bfa418fcd837)
  Fix problems with absolute custom mocha path (#25) (Christopher Hiller)

_Released by [Maximilian Antoni](https://github.com/mantoni) on 2019-03-12._

## 4.1.0

Adds the `mochaPath` option to specify a custom path to resolve mocha.

- [`aea12b7`](https://github.com/mantoni/mocaccino.js/commit/aea12b70e0540a44bc624999997c7f13282fdd1e)
  Add support for custom path to mocha module (Christopher Hiller) (#24)
- [`40e28dc`](https://github.com/mantoni/mocaccino.js/commit/40e28dce56e89faed33398294cf3d00afce21d88)
  Add contributor

_Released by [Maximilian Antoni](https://github.com/mantoni) on 2019-02-28._

## 4.0.0

- [`1b3d32a`](https://github.com/mantoni/mocaccino.js/commit/1b3d32ade806842fb10d94985612e58be76e8d0d)
  Show build status on master branch in README
- [`575abdc`](https://github.com/mantoni/mocaccino.js/commit/575abdc58975954d2f59fd72a156351c3e63c375)
  Run builds in Node 6, 8 and 10
- [`8cfa0ba`](https://github.com/mantoni/mocaccino.js/commit/8cfa0ba7d60ca906a67da3fb0bf3c12edf197afe)
  Replace jslint with eslint
- [`da0d287`](https://github.com/mantoni/mocaccino.js/commit/da0d287602278aa59b8b6034939ceb819a0d99ee)
  Update all transient dependencies
- [`ca8e25c`](https://github.com/mantoni/mocaccino.js/commit/ca8e25c3fa0b222117b765c7d45d8242e4badc71)
  Update resolve and through2
- [`3f3317d`](https://github.com/mantoni/mocaccino.js/commit/3f3317d5ea20c58e19ae032c954aa8c8b98d93f2)
  Upgrade Mocha to v5
- [`3bea39e`](https://github.com/mantoni/mocaccino.js/commit/3bea39eb5f2b278dcaa76f4ac6d04cf46fc20e34)
  Upgrade supports-color to v5
- [`db00c21`](https://github.com/mantoni/mocaccino.js/commit/db00c21b5a494c9e5ec41806469ccc1a6fa5f426)
  Upgrade Browserify to v16
- [`84dd99a`](https://github.com/mantoni/mocaccino.js/commit/84dd99ad718954f614f0327bb772ed377b7b9891)
  Update @studio/changes for `--commits` and `--footer` support

_Released by [Maximilian Antoni](https://github.com/mantoni) on 2018-11-19._

## 3.0.0

- Update to Mocha 4 (Carl-Erik Kopseng)

## 2.0.0

- Upgrade Mocha to `^3.2` (Morgan Roderick)
- Order dependencies by using `npm` command (Morgan Roderick)

    This will make future changesets made with `npm install` read much better,
    as `npm` commands always sorts dependencies lexicographically.

- Run tests in newer node versions, and remove 0.10, 0.12 (#21) (Morgan
  Roderick)
- Use `@studio/changes` instead of make

## 1.9.0

- Add support for `reporterOptions` in API (Tomer Lahav)
- Update Mocha link (Morton Fox)

## 1.8.2

Revert "Nail Mocha to `~2.3.4` to workaround issues with `2.4.x`" since the
underlying issue was reverted in Mocha.

## 1.8.1

Nail Mocha to `~2.3.4` to workaround issues with `2.4.x`.
Follow <https://github.com/mantoni/mochify.js/issues/129> for updates.

## 1.8.0

Streams 3: bump dependencies so that `through2@2` is used everywhere.

These dependencies have been updated:

- `through2: ^2.0.0`
- `resolve: ^1.1.6`
- `brout: ^1.1.0`
- `supports-color: ^3.1.2`

Test are now using `browserify@13`.

## 1.7.0

Brad Buchanan fixed the `grep` behavior to align better with Mocha. See
[pull request #16](https://github.com/mantoni/mocaccino.js/pull/16).

> Adds the ability to pass the Mocha fgrep option through, so that any users
> who were depending on the incorrect behavior of `--grep` before can easily
> switch over to `fgrep` (which is what they want).

- Treat `grep` option as a regular expression. (Brad Buchanan)
- Add `fgrep` option. (Brad Buchanan)

## 1.6.1

- Bump Mocha version to use at least 2.3.0 (Matheus Kautzmann)

## 1.6.0

- Add support for third party reporters (Matheus Kautzmann)
- Move mocha from `devDependencies` to `dependencies`

## 1.5.2

- Update through2 to `^1.1`

## 1.5.1

- Improve documentation
- Add node 0.12 to travis config

## 1.5.0

- Add options `--colors` and `--no-colors` to explicitly enable or disable colors
- Fix setting colors

## 1.4.0

- Use same color feature detection as introduced in Mocha 2.2

## 1.3.0

- Allow to override the window width

## 1.2.0

- Add support for grep invert option (Daniel Davidson)

## 1.1.0

- Add support for mocha `grep` option (Daniel Davidson)

## 1.0.7

- Set window width and dot symbol for node as well

## 1.0.6

- Bump through2, resolve and phantomic
- Fix coverage for browsers

## 1.0.5

- Fix for calling `b.bundle()` multiple times

## 1.0.4

- Listen to Browserify 'reset' events

## 1.0.3

- Fix brout resolution for Windows

## 1.0.2

- Fix issue with multiple push calls to through2

## 1.0.1

- Fix brout resolving

## 1.0.0

- Require Browserify 5

## 0.8.0

- Added `timeout` and `t` options so one can test async scripts that last longer than `2000ms`

## 0.7.0

- Added `ui` and `U` options so one can select BDD/TDD/QUnit (Mikela Clemmons)

## 0.6.4

- Use `process.nextTick` to yield instead of `setTimeout`

## 0.6.3

- Support `require('mocha')`

## 0.6.2

- Lame cygwin thing with `getWindowSize`

## 0.6.1

- Pass on terminal window width
- Use ascii dot symbol for compatibility

## 0.6.0

- Bump [brout][] and verify [phantomic][] can be used with `--brout`
- Fix path to setup file on windows

## 0.5.0

- Yield every 250 milliseconds by default to allow pending I/O to happen
- Add `--yields` / `-y` option to configure yield interval

## 0.4.2

- Allow to use Mocaccino output in a browser with [coverify][]

## 0.4.1

- Fix `describe.only` and `it.only` (Andrey Popp)

## 0.4.0

- Include Mocha via Browserify (Andrey Popp)
- Remove `Function.prototype.bind` shim since Phantomic 0.5 always includes
  es5-shim (Andrey Popp)

## 0.3.1

Don't screw up [coverify][] output

## 0.3.0

Rewrote Mocaccino as Browserify plugin

## 0.2.1

Resolve Mocha properly

## 0.2.0

Support most Mocha reporters when used with `brout`

- Removed mocaccino-reporter
- Using "tap" as the default reporter because it works with standard
  `console.log` statements
- Adding in browser shims for `Array.forEach` and `Function.bind`
- Using `process.exit(code)` on finish if available

## 0.1.0

Initial release

[coverify]: https://github.com/substack/coverify
[brout]: https://github.com/mantoni/brout.js
[phantomic]: https://github.com/mantoni/phantomic
