# Kyle

Rust, real-time audio, and electronics. Mostly tools I needed and couldn't
find.

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
