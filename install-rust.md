# Install Rust
One of the things that attracted me to Rust is the rich tooling available out of the box.
Official installation instructions for Rust are available [here](https://rust-lang.org/tools/install)

## Install using rustup
If you are on a unix-like OS (Mac, Linux, BSD, etc.), you can install Rust using the following command:
```bash
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

`rustup` is the tool provided for installing and managing Rust, while `cargo` is there to help you manage dependencies, build your programs, and distribute your work to other Rust developers.

All your goodies for building, testing, and maintaining your Rust code are installed to `$HOME/.cargo/bin`. I highly recommend adding this directory to your path for easy access to your tools! This can be accomplished with the following command:
```bash
$ export PATH=$HOME/.cargo/bin:$PATH
```

You can store your projects however you like, but I use a variant of the old "Go Path" route for my projects, and it means whether I'm working on a fork, or a direct clone of a repo, I can find it easily. I use a path called `code` in my home directory to store all of my projects, including their repository path. I also use this folder to hold my compiled Go binaries, so the full path to the directory containing my projects ends up being `~/code/src/github.com/aftertale`:
```
$ mkdir -p ~/code/src/github.com/<yourGitHubAccount>
```


