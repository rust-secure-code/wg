# Rust Secure Code Working Group

![Hermit Ferris](https://avatars2.githubusercontent.com/u/44121472?s=230)

This repository is the central [issue tracker] used by the Secure Code WG to
coordinate efforts towards promoting secure code development in Rust.

## Mission

Our mission is to make it easy to write secure code in Rust.

We have the following goals for the Rust language and ecosystem:
- Most tasks shouldn't require dangerous features such as `unsafe`. This includes FFI.
- Mistakes in security code should be easily caught by machines or, failing
  that, humans aided by machines.
- It should be clear to programmers how to perform security-sensitive tasks.
- Security-critical code which is relied on by Rust programmers should be bug
  free.
  
## Projects

- [cargo-audit]: Audit Rust projects for vulnerable dependencies sourced from the [RustSec Advisory Database][rustsec].
- [cargo-repro]: Build and verify byte-for-byte reproducible Rust packages using a Cargo-based workflow.
- [cargo-sandbox]: Perform Cargo builds inside of a sandboxed environment.
- [safety-dance]: Auditing crates for unsafe code which can be safely replaced.
- We also maintain a [list of security-related projects][projects].

## Contact

- **Zulip**: Our official chat is the [#wg-secure-code Zulip stream].
- **Twitter**: Follow us at [@rustsecurecode].

[issue tracker]: https://github.com/rust-secure-code/wg/issues
[cargo-audit]: https://github.com/rustsec/cargo-audit
[cargo-repro]: https://github.com/rust-secure-code/cargo-repro
[cargo-sandbox]: https://github.com/rust-secure-code/cargo-sandbox
[rustsec]: https://rustsec.org
[projects]: https://github.com/rust-secure-code/projects
[#wg-secure-code Zulip stream]: https://rust-lang.zulipchat.com/#narrow/stream/146229-wg-secure-code
[@rustsecurecode]: https://twitter.com/rustsecurecode
