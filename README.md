# sphinx cryptographic packet replay tag writeback cache
[![](https://travis-ci.org/sphinx-cryptography/sphinx_replay_cache.png?branch=master)](https://www.travis-ci.org/sphinx-cryptography/sphinx_replay_cache) [![](https://img.shields.io/crates/v/sphinx_replay_cache.svg)](https://crates.io/crates/sphinx_replay_cache) [![](https://docs.rs/sphinx_replay_cache/badge.svg)](https://docs.rs/sphinx_replay_cache/)


This crate provides a fast replay cache for detecting Sphinx packet replays
and is intended to be used with my Sphinx cryptography crate which you can find here:

* https://crates.io/crates/sphinxcrypto


NOTE: If you are unfamiliar with the Sphinx cryptographic packet format then you can read the Sphinx paper,
**Sphinx: A Compact and Provably Secure Mix Format** by George Danezis and Ian Goldberg.
See https://cypherpunks.ca/~iang/pubs/Sphinx_Oakland09.pdf


# Installation

To import `sphinx_replay_cache`, add the following to the dependencies section of
your project's `Cargo.toml`:
```toml
sphinx_replay_cache = "^0.0.3"
```
Then import the crate as:
```rust,no_run
extern crate sphinx_replay_cache;
```


# acknowledgments

This crate was inspired by the work of Yawning Angel who wrote
the Sphinx packet replay cache for the Katzenpost mix server:

https://github.com/katzenpost/server


# license

GNU AFFERO GENERAL PUBLIC LICENSE
