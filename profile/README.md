# Oxyde

**A web browser written 100% in Rust — built from scratch, for every platform.**

Oxyde is an independent browser engine and application: HTML parsing, DOM, CSS,
layout, text, painting, networking and GPU rendering, all in safe Rust
(`unsafe_code = "forbid"` across the workspace).

## Goals

- 🦀 **Pure Rust** — no C/C++ engine underneath
- 🔒 **Safe by default** — memory safety enforced at the workspace level
- 🌍 **Cross-platform** — desktop first, then mobile and beyond
- 🧩 **Modular** — each engine stage is its own crate

## Architecture

| Crate | Role |
|---|---|
| `oxyde_html` | HTML tokenizer & parser |
| `oxyde_dom` | Document Object Model |
| `oxyde_css` | CSS parsing & cascade |
| `oxyde_layout` | Layout engine |
| `oxyde_text` | Text shaping & fonts |
| `oxyde_paint` | Display lists & painting |
| `oxyde_gpu` | GPU rendering backend |
| `oxyde_net` | Networking |
| `oxyde_ui` | Browser UI |

## Status

🚧 Early development — not usable as a daily browser yet.

## Get involved

Main repository: [oxyde-browser/oxyde](https://github.com/oxyde-browser/oxyde) ·
License: BSD-3-Clause
