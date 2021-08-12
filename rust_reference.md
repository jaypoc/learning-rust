# Learning RUST (Quick Reference)

Notes from following tutorials at https://learning-rust.github.io/docs/index.html


---
## Rust Playground

Try out rust online at https://play.rust-lang.org/

---
## Installing

Windows: https://www.rust-lang.org/tools/install

---
## Command Line

### RUST Updater (rustup)

|Command                |Description
|-                      |-
|rustup update          |Updates Rust
|rustup self uninstall  |Removes Rust from System

### Rust Compiler (rustc)

|Command                |Description
|-                      |-
|rustc --version        |Check version of Rust Compiler
|rustc &lt;file.rs&gt;  |Compile .rs file into executable

### Cargo (Bundler/Build Tool)

|Command                |Description
|-                      |-          
|cargo new              |Start a new cargo project
|cargo check            |Check a project without building executables
|cargo build            |Build executable in ./target/debug
|cargo build --release  |Build optimized executable in ./target/release


