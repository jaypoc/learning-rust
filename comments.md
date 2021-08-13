# Rust Syntax

## Comments/Documenting Code

```rust
// Line comments

/* Block comments (not recommended. Use line comments instead) */
```

## Commenting for rustdoc:
```rust
/// Line comments; document the next item
mod tests {

}
```
```rust
mod tests {
    //! Line COmmentsl document the enclosing item
}
```
### Doc Attributes

```rust
#[doc = "Outer Comment"]

#![doc = "Inner Comment"]
```
