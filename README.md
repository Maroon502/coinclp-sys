# Clp-src

[![Package][package-img]][package-url] [![Documentation][documentation-img]][documentation-url] [![License][license-img]][license-url]

coinclp-sys crate is a *-sys crate. The package provides Low-level bindings to the [Clp] library.

By this package, you don't need to worry about installing Clp in the system, and it's a package for **all platforms**.

Clp (Coin-or linear programming) is an open-source linear programming solver. It is primarily meant to be used as a callable library, but a basic, stand-alone executable version is also available.

## Usage
Just add the following to your `Cargo.toml`:

```toml
[dependencies]
coinclp-sys = "0.2"
```

## Library Linking
if you want to know the detail about how it compile or link the Clp, please see [Clp-src].

## Contribution

Your contribution is highly appreciated. Do not hesitate to open an issue or a
pull request. Note that any contribution submitted for inclusion in the project
will be licensed according to the terms given in [LICENSE](license-url).

[Clp]: https://github.com/coin-or/Clp
[Clp-src]: https://github.com/Maroon502/clp-src

[documentation-img]: https://docs.rs/coinclp-sys/badge.svg
[documentation-url]: https://docs.rs/coinclp-sys
[package-img]: https://img.shields.io/crates/v/coinclp-sys.svg
[package-url]: https://crates.io/crates/coinclp-sys
[license-img]: https://img.shields.io/crates/l/coinclp-sys.svg
[license-url]: https://github.com/Maroon502/coinclp-sys/blob/master/LICENSE.md