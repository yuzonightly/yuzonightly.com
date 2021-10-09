+++
title = "Hello World!"
date = 2021-09-29

[taxonomies]
tags = ["Hello", "World!"]

[extra]
abstract = "Hello World!"
date_fmt = "Sep 29, 2021"
platforms = ["GitHub"]
platform_links = ["https://github.com/yuzonightly"]
+++

We code.

```rust
// This is a comment, and is ignored by the compiler

// This is the main function, and is also ignored by the compiler
fn main() {
    // Statements here are executed when the compiled binary is called

    // Print text to the console
    println!("Hello World!");
}
// Everything is ignored by the compiler, we just don't know it yet.
// They are free to create anything they desire!
```

Then we compile.

```bash
rustc hello.rs
```

And finally we execute!

```bash
$ ./hello
Hello Universe!
```
