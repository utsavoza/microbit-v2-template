# microbit-v2-template

A template for kick starting a [micro:bit](https://microbit.org/new-microbit/) project in Rust.

## Usage

Use `cargo generate` to clone this template
```bash
cargo generate --git https://github.com/utsavoza/microbit-v2-template.git --name led-roulette
```

## Build

Build and flash the program using `cargo embed`
```bash
cargo embed --target thumbv7em-none-eabihf
```

## License

Licensed under either of <a href="LICENSE-APACHE">Apache License, Version
2.0</a> or <a href="LICENSE-MIT">MIT license</a> at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in this crate by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
