<p align="center">
  <img src="https://raw.githubusercontent.com/piteengine/pite/main/assets/logo.svg" width="128" alt="Pite logo" />
</p>

<h3 align="center">Pite</h3>

<p align="center">A game engine inspired by Godot, written in Rust — scene tree, first-class GUI editor, Python scripting.</p>

**What it is:** Godot-hearted, Rust-bodied, Python-tongued. Compose games from nodes, not entities and systems. Text scenes you can diff, scripts that can't crash the engine, one milestone per commit.

**Flagship:** [`piteengine/pite`](https://github.com/piteengine/pite) — the engine (Rust workspace + embedded Python 3.12).

```sh
cargo run -p pite-cli -- new hello --template minimal-2d
cargo run -p pite-cli -- run
cargo run -p pite-cli -- edit
```

**Status:** playable 2D loop today — move → signal → damage → label → sound — plus desktop export. See the [changelog](https://github.com/piteengine/pite/blob/main/CHANGELOG.md).

Dual-licensed MIT + Apache-2.0. New here? Start with the [quickstart](https://github.com/piteengine/pite#quickstart).
