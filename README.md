A Nix Tutorial for Beginners
---

# Disclaimer

This tutorial isn't finished...

# Prerequisites

The command `nix` should be installed on your system. If you do not have Nix
installed, visit [quickstart].

# Goals

This series of tutorials should get you to understand the basics of Nix. I want
you to understand how to find and use packages, read and write nix files,
understand the point of various files, and know where to look when this
tutorial isn't enough. Along the way, I will introduce you to the syntax and
terminology and provide additional links to explore the concepts in depth.

# Format

The format will be process oriented. I will introduce a concept and then ask
you questions regarding that concept. Here is a **very** simple example to
illustrate the point:

## Addition in Nix

In the Nix REPL (Read-Evaluate-Print-Loop), you can add numbers. When you enter
the Nix REPL (via `nix repl`) your prompt will change to `nix-repl>`. You only
need to type the arguments on the right of the `>`. Below, I will add one and
one using the addition operator `+`,

```
nix-repl> 1 + 1
2
```

### Tasks

- Add four and five in the Nix repl

<details>
```
nix-repl> 4 + 5
9
```
</details>

- The multiplication operator is `*`, try multiplying four and five

<details>
```
nix-repl> 4 * 5
20
```
</details>

- What do you think will happen if you write `"hello" + "world"`? Did your answer match the result?

<details>
```
nix-repl> "hello" + "world"
"helloworld"
```
</details>

# Available Tutorials

So empty here :sad:

# TODO

- [ ] Tutorial: Getting used to `nix repl`
- [ ] Tutorial: Getting used to `nix shell`
- [ ] Tutorial: Getting used to `nix build`
- [ ] Tutorial: _Pinning_ your Nix packages
- [ ] Tutorial: Generate your first Nix shell
- [ ] Tutorial: Generate your first Nix build

[quickstart]: https://nixos.org/manual/nix/stable/#chap-quick-start
