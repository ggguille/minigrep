# The Rust Programming Language
## An I/O Project: Building a Command Line Program

### MINIGREP - Project

> We’ll make our own version of the classic command line tool grep (globally search a regular expression and print). 
In the simplest use case, grep searches a specified file for a specified string. 
To do so, grep takes as its arguments a filename and a string. Then it reads the file, finds lines in that file that contain the string argument, and prints those lines.

#### Examples use cases
> Search `frog` into *resources/poeam.txt* file

```
$ cargo run frog resources/poem.txt
   Compiling minigrep v0.1.0 (file:///projects/minigrep)
    Finished dev [unoptimized + debuginfo] target(s) in 0.38s
     Running `target/debug/minigrep frog poem.txt`
How public, like a frog
```

> Search `body` into *resources/poeam.txt* file

```
$ cargo run body poem.txt
   Compiling minigrep v0.1.0 (file:///projects/minigrep)
    Finished dev [unoptimized + debuginfo] target(s) in 0.0s
     Running `target/debug/minigrep body poem.txt`
I’m nobody! Who are you?
Are you nobody, too?
How dreary to be somebody!
```

##### References
- [Rust Doc - chapter 12](https://doc.rust-lang.org/book/ch12-00-an-io-project.html)
