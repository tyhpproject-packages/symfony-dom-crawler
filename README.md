<!-- tyhp-readme:start -->
# tyhpdef/symfony-dom-crawler

Tyhp type definitions for `symfony/dom-crawler` `7.4.17`.

```bash
composer require --dev tyhpdef/symfony-dom-crawler:7.4.17
```

This is a metapackage. Composer also installs `tyhpdef/symfony-dom-crawler-impl` (type files).
Require **this** name, not `tyhpdef/symfony-dom-crawler-impl`.

See https://tyhplang.com.

## Maintain `symfony/dom-crawler`? Ship the types yourself

If you are a Packagist maintainer of `symfony/dom-crawler`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-dom-crawler-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/dom-crawler` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-dom-crawler": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/dom-crawler` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/dom-crawler` with a real constraint,
   `"replace": { "tyhpdef/symfony-dom-crawler": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/dom-crawler` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-dom-crawler` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
