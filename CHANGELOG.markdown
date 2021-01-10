next [yyyy.mm.dd]
-----------------
* The build-type has been changed from `Custom` to `Simple`.
  To achieve this, the `doctests` test suite has been removed in favor of using
  [`cabal-docspec`](https://github.com/phadej/cabal-extras/tree/master/cabal-docspec)
  to run the doctests.

0.3 [2019.05.10]
----------------
* `jerks` now has a `MonadFail` constraint instead of just `Monad`.

0.2.5
-----
* Add `Semigroup` instance for `Jacket`.

0.2.4
-----
* Support `doctest-0.12`

0.2.3
-----
* Revamp `Setup.hs` to use `cabal-doctest`. This makes it build
  with `Cabal-2.0`, and makes the `doctest`s work with `cabal new-build` and
  sandboxes.

0.2.2
-----
* Fix compilation of tests with `stack`

0.2.1
-----
* Migrate zipper benchmarks from `lens`

0.1
---
* Repository initialized
