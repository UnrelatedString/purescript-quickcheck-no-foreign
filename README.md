# purescript-quickcheck

[![Latest release](http://img.shields.io/github/release/UnrelatedString/purescript-quickcheck-no-foreign.svg)](https://github.com/UnrelatedString/purescript-quickcheck-no-foreign/releases)
[![Build status](https://github.com/UnrelatedString/purescript-quickcheck-no-foreign/workflows/CI/badge.svg?branch=master)](https://github.com/UnrelatedString/purescript-quickcheck-no-foreign/actions?query=workflow%3ACI+branch%3Amaster)
[![Pursuit](https://pursuit.purescript.org/packages/purescript-quickcheck/badge)](https://pursuit.purescript.org/packages/purescript-quickcheck)

An implementation of QuickCheck in PureScript, without FFI calls so as to be more easily used on alternate backends (particularly those which do not offer easy access to the bit representation of their `Number`s). Unlikely to work well if `Number` is not a double, and does not guarantee identical performance to the normal implementation of quickcheck.

## Installation

uhhh probably just stick it in your extrapackages realistically speaking

## Documentation

- [Guide](GUIDE.md)
- Module documentation is [published on Pursuit](http://pursuit.purescript.org/packages/purescript-quickcheck).
