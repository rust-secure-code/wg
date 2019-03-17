# Rust Secure Code Working Group

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
  
## Work Items

Our mission objectives are divided in several work items:

**Reduce the amount of ```unsafe``` code**
- [Build-time sandboxing](https://github.com/rust-secure-code/wg/issues/29)
- [Improve Clippy Security Lints](https://github.com/rust-secure-code/wg/issues/27)
- [Improve dynamic analysis tooling](https://github.com/rust-secure-code/wg/issues/26)
- [Improving static analysis tooling](https://github.com/rust-secure-code/wg/issues/22)
- [Propose safe abstractions replacing unsafe code without performance loss.](https://github.com/rust-secure-code/wg/issues/19)
- [Improve discoverability of tools](https://github.com/rust-secure-code/wg/issues/25)
- [Improving the Memory Sanitizer](https://github.com/rust-secure-code/wg/issues/21)

**Distribution of security updates**
- [Reproducable Build Tooling](https://github.com/rust-secure-code/wg/issues/28)
- [Integrating Rustsec in DevOps workflow](https://github.com/rust-secure-code/wg/issues/15)
- [Make production binaries auditible](https://github.com/rust-secure-code/wg/issues/14)

**Code Authentication and Trust**
- [Improve code authentication on crates.io](https://github.com/rust-secure-code/wg/issues/18)

**Verification of the Standard Library**
- [Continuous verification of the standard library](https://github.com/rust-secure-code/wg/issues/23)

## Contact

- **Zulip**: Our official chat is the [#wg-secure-code Zulip stream].
- **Twitter**: Follow us at [@rustsecurecode].

[issue tracker]: https://github.com/rust-secure-code/wg/issues
[#wg-secure-code Zulip stream]: https://rust-lang.zulipchat.com/#narrow/stream/146229-wg-secure-code
[@rustsecurecode]: https://twitter.com/rustsecurecode
