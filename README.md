# Flox Demo

A tiny repo to demo usage of flox for an internal knowledge sharing session.

## TLDR;

- flox search <package>    <- Search for a package
- flox install <package>   <- Install a package into an environment
- flox activate            <- Enter the environment

## Commands used to demo
```
flox init

export MY_ENV="testing flox"

flox search scc
flox install scc
flox activate

flox search elixir
flox install elixir_1_15
flox activate
elixir hello.exs

flox search ocaml
flox install ocaml
flox activate
ocaml hello.ml

flox search python3
flox install python3
flox activate
python3 hello.py

flox push
```

## Links
- https://github.com/flox/flox
- https://flox.dev/docs/
- https://search.nixos.org/packages
