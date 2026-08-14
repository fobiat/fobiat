# Kyle

Rust, real-time audio, and electronics. Mostly tools I needed and couldn't
find. The short versions are below; the long ones live at
**[fobiat.dev](https://fobiat.dev)**.

## Rivet

Git-native workstation snapshots for Linux and macOS: rebuild your machine
from a commit. Rivet records the packages you installed on purpose and the
config you approve, not a disk image. Restores work across distro families,
and secrets stay out unless you explicitly vault them.

Not out yet. The site and [docs](https://fobiat.dev/rivet/docs/introduction/)
are already live at **[fobiat.dev/rivet](https://fobiat.dev/rivet)**, and
that's where the release will land.

Rust, MIT OR Apache-2.0.

## Applejack

A scarcity-driven city roleplay gamemode for [S&box](https://sbox.game),
rebuilt from scratch in C# on Source 2, against a live editor from the first
commit. The Garry's Mod original survives as a behavioural reference only:
its gameplay values are canon, its implementation is not.

The repo stays private while the framework takes shape, but the design docs,
wireframes, and hosting guides are already public at
**[fobiat.dev/applejack](https://fobiat.dev/applejack)**.

## Everything else

| Project | What it is |
| --- | --- |
| **[rivet-workstation](https://fobiat.dev/rivet-workstation)** | An AI-first workstation: `ws up` turns a YAML file into a running project workspace (terminals, services, logs, AI assistant panes), owned by a daemon and restorable onto a fresh machine via Rivet. Rust, private while the milestones land. |
| **[openBPM](https://fobiat.dev/openbpm)** | Tap-tempo BPM counter and beatmatch assistant for vinyl DJing on an ESP32: booth-legible digits, pitch %, and a drift timer so you know how long before your decks fall apart. [Source](https://github.com/fobiat/openBPM) is public. |
| **openDVS** | An open Digital Vinyl System: a clean-room `no_std` timecode engine in Rust, a freely pressable timecode vinyl format, and open hardware that doubles as a USB audio interface. Private while the format settles. |
| **Ohmic Labs** | A modular handheld instrument platform on one ESP32 + OLED + encoder core: a PT100 RTD simulator first, a 4-20 mA loop calibrator next. |
| **[k3s-homelab](https://github.com/fobiat/k3s-homelab)** | The home cluster: k3s and Flux, deployed from GitHub Actions. |

---

[kyle@ohmic-labs.co.uk](mailto:kyle@ohmic-labs.co.uk)
