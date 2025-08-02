# minigrep

A super simple Rust version of `grep`.

This project demonstrates the basics of a command-line tool in Rust, including:

- Command line arguments
- Environment variables
- Standard error output
- Unit tests
- Idiomatic Rust code structure

---

## Usage

```bash
$ cargo run -- <search_string> <text_file>
```
### Example:

```bash
$ cargo run -- to poem.txt
```

### Case Insensitive Search:

```bash
$ IGNORE_CASE=1 cargo run -- to poem.txt
```

### Running tests:

```bash
$ cargo test
```

