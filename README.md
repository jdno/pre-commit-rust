# Rust hooks for pre-commit

[Rust](https://www.rust-lang.org) tools package for [pre-commit](https://pre-commit.com).

## Using rust tools with pre-commit

```yaml
-   repo: https://github.com/jdno/pre-commit-rust
    rev: v1.1.0
    hooks:
    -   id: fmt
    -   id: cargo-check
```
