# wsl
Experiences with setting up Windows Subsystem for Linux to try out Rust

First of all, the [Hello world! program](https://doc.rust-lang.org/book/ch01-02-hello-world.html) did not compile for me. The WSL needed a compiler.
`sudo apt-get update` and `sudo apt-get install build-essential` (as in <https://stackoverflow.com/questions/52445961/how-do-i-fix-the-rust-error-linker-cc-not-found-for-debian-on-windows-10>) fixed that for me.

I find it fun to use Linux shell commands while working in Windows.

Moreover, just start the terminal/PowerShell(?) in Windows, then type `wsl` to start the "bash terminal"
