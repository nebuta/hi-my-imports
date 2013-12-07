hi-imports
=================

A template for [hi](https://github.com/fujimura/hi).

Forked from [hi-hspec](https://github.com/fujimura/hi-hspec), added some common imports I use.

example:

```
$ hi -m Foo.Bar -p foo-bar  -r git@github.com:fujimura/hi-hspec.git
$ tree
.
├── LICENSE
├── README.md
├── foo-bar.cabal
├── src
│   └── Foo
│       ├── Bar
│       │   └── Internal.hs
│       └── Bar.hs
└── test
    ├── Foo
    │   └── BarSpec.hs
    └── Spec.hs

5 directories, 7 files
```
