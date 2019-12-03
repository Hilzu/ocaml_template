# Ocaml template

Template for new Ocaml projects.

## Requirements

* [opam 2](https://opam.ocaml.org/doc/Install.html)

## Usage

```bash
# Create local switch
opam switch create . --deps-only

# Build
dune build

# Run app
./_build/default/bin/main.exe

# Run tests
dune runtest

# Automatically format code
dune build @fmt --auto-promote
```
