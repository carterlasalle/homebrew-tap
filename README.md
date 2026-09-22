# homebrew-tap

Personal Homebrew tap.

```bash
brew install carterlasalle/tap/tracelayer
```

Formula source lives in the tracelayer repo (`contrib/brew/tracelayer.rb`, bump via `contrib/brew/bump.sh`).

## system-context-compiler

[System Context Compiler](https://github.com/carterlasalle/scc) — compile
repositories into evidence-backed system context for coding agents.

```bash
brew install carterlasalle/tap/system-context-compiler
scc --version
```

The formula is named `system-context-compiler` because `scc` in homebrew-core is
[boyter/scc](https://github.com/boyter/scc), a Go line counter — `brew install scc`
installs that, not this. The binary it installs is `scc`.

Formula source lives in the scc repo (`contrib/brew/system-context-compiler.rb`,
bump via `contrib/brew/bump.sh`).
