# Learning RUST (Quick Reference)

Notes from following tutorials at https://learning-rust.github.io/docs/index.html


---
## Rust Playground

Try out rust online at https://play.rust-lang.org/

---
## Installing

Windows: https://www.rust-lang.org/tools/install

```.cargo/bin``` directory of the home directory is the default location for Rust binaries.

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

|Command                   |Description
|-                         |-          
|cargo new crate_name      |Start a new cargo project (Crate)
|cargo new crate_name --bin|Same as above
|cargo new crate_name --lib|Produces a library instead of an executable.
|cargo init .              |Start a new cargo project in current (.) folder
|cargo check               |Check a project without building executables
|cargo build               |Build executable in ./target/debug
|cargo build --release     |Build optimized executable in ./target/release
|cargo run                 |Run the project
|cargo update              |Update project dependencies
|cargo bench               |Run benchmarks (tests)
|cargo doc                 |Generate project documentation via rustdoc (in target/doc/)
|cargo doc --open          |Opens generated doc in the browser.

## Special FIles

|File/Path   |Description
|-           |-
|Cargo.toml  | Project configuration file (**T**om's **O**bvious **M**inimal **L**anguage format)
|src/        | Folder containing source code
|src/main.rs | crate root for binary/executables
|src/lib.rs  | crate root for libraries

### Project Structure
```
.
├── Cargo.toml
├── Cargo.lock
├── src
│   ├── main.rs
│   ├── lib.rs
│   └── bin
│       └── another_executable.rs
├── tests
│   └── some_integration_tests.rs
├── benches
│   └── simple_bench.rs
└── examples
    └── simple_example.rs
```
