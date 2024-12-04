# Multiple Mutable References in Rust
This repository demonstrates a common error in Rust: creating multiple mutable references to the same variable.  Rust's borrow checker prevents this to avoid data races and ensure memory safety. The example shows how to modify the code to correctly handle mutable references.

## Bug
The `bug.rs` file contains code that attempts to create two mutable references (`y` and `z`) to the same variable (`x`). This results in a compile-time error.