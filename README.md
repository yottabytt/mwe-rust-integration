when `cargo test` is run, it creates three binaries as we can see in [target/debug/deps](https://github.com/yottabytt/mwe-rust-integration/tree/main/meow/target/debug/deps) directory. 

In addition to the src binary [target/debug/deps/meow](https://github.com/yottabytt/mwe-rust-integration/blob/main/meow/target/debug/deps/meow), we can see four more binaries, which are test binaries:
 -  unit tests [target/debug/deps/meow-ea5c5b8b2cf3b544](https://github.com/yottabytt/mwe-rust-integration/blob/main/meow/target/debug/deps/meow-ea5c5b8b2cf3b544)
 -  `tests/foo.rs` [target/debug/deps/foo-8706df6ba36b6e2f](https://github.com/yottabytt/mwe-rust-integration/blob/main/meow/target/debug/deps/foo-8706df6ba36b6e2f)
 -  `tests/bar` (has a test in `main.rs`) [target/debug/deps/bar-451c26b8c157da73](https://github.com/yottabytt/mwe-rust-integration/blob/main/meow/target/debug/deps/bar-451c26b8c157da73)
 -  `tests/baz` (a test in `main.rs` + another one in a module `mod qux`) [target/debug/deps/baz-8a90dc53bdc638c1](https://github.com/yottabytt/mwe-rust-integration/blob/main/meow/target/debug/deps/baz-8a90dc53bdc638c1)


