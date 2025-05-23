```rust
fn main() {
    println!("Hello, world!")
}
```

---

The first part is the `main` function :

```rust
fn main() {

}
```

This function is special, it is the entry point of every
executable (compiled) Rust program.

- `fn` is the Rust syntax to declare a *function*.
- `main` is the *name* of the function (reserved name).
- `()` is the place parameter(s) are mentioned (if there is).
- `{}` set the scope of the function, where it begins and ends.

---

The second part is the content of the main function :

```rust
fn main() {
    println!("Hello, world!"); // Content
}
```

It prints some text to the screen. Important details are :
  - The function content is indented using 4 spaces, not a tab.
  - `println!` calls a Rust *macro*, `!` indicates that it is a macro (special function) instead of a user-created function.
  - `"Hello, world!"` is the string (chain of character) that will be printed.
  - The `;` indicates that the expression ends here.
