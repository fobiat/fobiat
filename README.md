# Kyle

Rust, real-time audio, and electronics. Mostly tools I needed and couldn't
find.

## Applejack

A ground-up C# rewrite of a Garry's Mod roleplay gamemode for
[S&box](https://sbox.game) — scarcity-driven city RP, not a
jobs-and-printers moneymaker. The original ships as a behavioural
reference only; nothing of its implementation survives into the
rewrite.

- Architecture-first: 14 design documents and 6 ADRs written and
  reviewed before a line of gameplay code
- Host-authoritative networking, one inventory model with real item
  identity, data-driven content that needs no compiler to extend
- Documents its own predecessor's defects — SQL built by string
  concatenation, a monkey-patched global hook dispatcher — so none
  of them get reproduced in the name of authenticity

C#. Private while the framework takes shape.

## Rivet — rebuild your workstation from a commit

**[rivet.fobiat.workers.dev](https://rivet.fobiat.workers.dev)**

A Git-native snapshot tool for Linux and macOS workstations. It records the
explicit packages and the configuration you approve — not a disk image, not
your whole home folder.

- Arch, Debian/Ubuntu, Fedora/RHEL, openSUSE, NixOS, Void, and macOS on Apple
  Silicon and Intel
- Restores across distro families: native packages resolve through a
  cross-distro package map instead of being guessed at
- Snapshots to Git, a local/NAS path, an rclone remote, or restic — encrypted
  at rest with `age`
- Secrets are excluded by default; anything you do want carried goes through an
  explicit vault whose private key never leaves the machine
- Terminal UI over drift, history, per-file diffs, and the restore plan

Rust, dual-licensed MIT OR Apache-2.0. Currently `v1.0.1`.

```sh
curl -sSf https://rivet.fobiat.workers.dev/install | sh
```

## rivet-workstation — an AI-first developer workstation

A daemon-driven workspace tool, separate from the snapshot tool above but
built to hand off to it: `ws up` turns a `workstation.yaml` into a
reproducible, running project workspace — terminals, build watchers,
services, databases, logs, and AI coding assistant panes — restorable onto
a fresh machine via Rivet.

- A daemon supervises and observes; thin clients (a CLI and a Ratatui TUI)
  drive it, so state survives a daemon restart without duplicating sessions
- Service dependency ordering, health checks, and restart policy
- Two interchangeable session backends — tmux, and a native terminal core
  (PTY supervision, VT parsing, its own grid and scrollback)
- A plugin SDK with capability-gated subprocess RPC, and AI provider panes
  with context injection

Rust. Private while the milestones land.

## Ohmic Labs

A side bench for handmade test gear and embedded work: a PT100 RTD temperature
simulator (ESP32, precision film resistors, IEC 60751, USB-C charging), a
tap-tempo BPM counter for vinyl DJing, and assorted ESP32 builds. Repos go
public as they get finished.

Also in progress: an open-source Digital Vinyl System — a clean-room `no_std`
timecode engine in Rust and a freely pressable timecode vinyl format. Private
while the format settles.

## Elsewhere

- [k3s-homelab](https://github.com/fobiat/k3s-homelab) — home Kubernetes on k3s
  and Flux, deployed with GitHub Actions
- [openBPM](https://github.com/fobiat/openBPM) — ESP32 beatmatch assistant for
  vinyl DJing

## Contact

kyle@ohmic-labs.co.uk
