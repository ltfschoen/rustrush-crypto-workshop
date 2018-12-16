# [RustRush](https://rustrush.ru/):  Applied pure-Rust cryptography workshop

[Presentation](https://docs.google.com/presentation/d/13ccjfT_4LELv8FY7v692XVDEx2fC-0pyyA1N0U2isyI/edit?usp=sharing)

Your task is to fill TODOs in the master branch for crates in the following
order: hash, pwhash, ciphers. Inside each crate follow order of sub-commands
in `cli.rs` files.

Solutions will be published after workshop in the `solution` branch.

# Usage

* Switch to nightly instead of stable to avoid error `error: Edition 2018 is unstable and only available for nightly builds of rustc.`
```
rustup update;
rustup default nightly
```

* Run examples:
```
cargo run --bin rustrush-hash;
cargo run --bin rustrush-pwhash;
cargo run --bin rustrush-ciphers
```

* Output:
```
rustrush-hash 0.1.0
newpavlov <newpavlov@gmail.com>
Computes hash sum using selected algorithm

USAGE:
    rustrush-hash <SUBCOMMAND>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

SUBCOMMANDS:
    blake2b        
    blake2s        
    help           Prints this message or the help of the given subcommand(s)
    sha256         
    shake256       
    var_blake2b    
    var_blake2s
```

## Additional Resources

* [Cryptography 1](https://www.coursera.org/learn/crypto)

## License

Code in this repository licensed under either of

 * [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
 * [MIT license](http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
