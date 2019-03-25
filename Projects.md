# List of security-related projects
---
# Fuzzers
|     Name     |                Repository               |                               Description                              |
|:------------:|:---------------------------------------:|:----------------------------------------------------------------------:|
|  Cargo Fuzz  |  https://github.com/rust-fuzz/cargo-fuzz  | Command-line wrapper for using libFuzzer. Easy to use, no need to recompile LLVM! |
|  Libdiffuzz  |   https://github.com/Shnatsel/libdiffuzz  | This is a drop-in replacement for OS memory allocator that can be used to detect uses of uninitialized memory. It is designed to be used in case Memory Sanitizer is not applicable for some reason. |
|    Angora    |   https://github.com/AngoraFuzzer/Angora  | Angora is a mutation-based coverage guided fuzzer. The main goal of Angora is to increase branch coverage by solving path constraints without symbolic execution. |
| honggfuzz-rs | https://github.com/rust-fuzz/honggfuzz-rs | A fuzzer developed by Google. |
| afl.rs       | https://github.com/rust-fuzz/afl.rs       | Allows one to run the AFL fuzzer on code written in the Rust programming language.                                                                                                                   |
| QuickCheck   | https://github.com/BurntSushi/quickcheck  | QuickCheck is a way to do property based testing using randomly generated input.                                                                                                                     |
| Proptest     | https://github.com/altsysrq/proptest      | Proptest is a property testing framework (i.e., the QuickCheck family) inspired by the Hypothesis framework for Python.                                                                              |
---
# Model Checkers

|     Name     |                Repository               |                               Description                              |
|:------------:|:---------------------------------------:|:----------------------------------------------------------------------:|
|     Loom     |    https://github.com/carllerche/loom   | Loom is a model checker for concurrent Rust code. It exhaustively explores the behaviors of code under the C11 memory model, which Rust inherits. |
| BugHunt-Rust |   https://github.com/blt/bughunt-rust   | This project is aiming to provide "stateful" QuickCheck models for Rust's standard library. |
---
# Linters
|     Name     |                Repository                |                               Description                              |
|:------------:|:----------------------------------------:|:----------------------------------------------------------------------:|
| Cargo Clippy | https://github.com/rust-lang/rust-clippy | A collection of lints to catch common mistakes and improve your Rust code. |
---
# Input Sanitizing
|     Name     |                Repository               |                               Description                              |
|:------------:|:---------------------------------------:|:----------------------------------------------------------------------:|
| untrusted.rs | https://github.com/briansmith/untrusted | Allows for reliable and efficient parsing of untrusted inputs in Rust. |
---
# Vulnerability Disclosure

|           Name            |                Repository                |                      Description                       |
|:-------------------------:|:---------------------------------------------:|:------------------------------------------------------:|
| RustSec Advisory Database |    https://github.com/RustSec/advisory-db/    | The RustSec Advisory Database is a repository of security advisories filed against Rust crates published via https://crates.io. Works closely with Cargo Audit. |
|  RustSec Advisory Client  |    https://github.com/RustSec/rustsec-crate   | Client library for accessing the RustSec Security Advisory Database: fetches the advisory-db (or other compatible) git repository and audits Cargo.lock files against it. It is mainly used by   Cargo Audit but may be useful if you would like to consume the RustSec advisory database in other capacities. |
|        Cargo Audit        |     https://github.com/RustSec/cargo-audit    | Audit Cargo.lock for crates with security vulnerabilities reported to the RustSec Advisory Database. |
|        Crates Audit       | https://gitlab.com/zachreizner/crates-audit/ | A tool to cross-reference the crates.io index with the RustSec Advisory database. |

---
# Dependency Checker
|           Name            |                Repository                     |                      Description                       |
|:-------------------------:|:---------------------------------------------:|:------------------------------------------------------:|
|        Cargo Geiger       |    https://github.com/anderejd/cargo-geiger   | A program that list statistics related to usage of unsafe Rust code in a Rust crate and all its dependencies. |
---
# Static and Dynamic Analyzers
|     Name     |                Repository               |                               Description                              |
|:------------:|:---------------------------------------:|:----------------------------------------------------------------------:|
| MIRAI | https://github.com/facebookexperimental/MIRAI | Mirai is an abstract interpreter for the Rust compiler's mid-level intermediate representation (MIR). It is intended to become a widely used static analysis tool for Rust.                 |
| MIRI  | https://github.com/rust-lang/miri             | An experimental interpreter for Rust's mid-level intermediate representation (MIR). It can run binaries and test suites of cargo projects and detect certain classes of undefined behavior. |
---
# Code Review
|     Name     |                Repository               |                               Description                              |
|:------------:|:---------------------------------------:|:----------------------------------------------------------------------:|
| Cargo Crev | https://github.com/dpc/crev | crev is an code review system as opposed to typically practiced code-change review system. |
---
# Security Maintainance
|     Name     |                Repository               |                               Description                              |
|:------------:|:---------------------------------------:|:----------------------------------------------------------------------:|
| The Update Framework in Rust | https://github.com/heartsucker/rust-tuf | A Rust implementation of  The Update Framework. |

