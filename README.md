# Hey, I'm Kyle 👋

I build open tools for DJs and audio hackers — hardware and software.

## 🎛️ Current project — [openDVS](https://github.com/fobiat/openDVS)

An **open-source Digital Vinyl System**: control digital decks with real
turntables and timecode vinyl, without the locked-down hardware.

- 🦀 Clean-room **timecode engine in Rust** — no_std, allocation-free,
  real-time safe; locks absolute position ~33 ms after a needle drop
- 📀 An **open, freely-pressable timecode format** — the spec is
  CC-BY-SA with a royalty-free implementation grant, so anyone can press
  or decode it. No vendor offers that.
- 🔌 **Open hardware** (CERN-OHL-S) that doubles as a generic
  class-compliant USB audio interface
- ⚖️ GPL-3.0 · CERN-OHL-S-2.0 · CC-BY-SA-4.0

Status: `v0.1.0-alpha` — engine + CLI working, validated against a
synthetic signal corpus; real-vinyl testing and custom hardware are next.
Try it: [releases](https://github.com/fobiat/openDVS/releases) ·
[the spec](https://github.com/fobiat/openDVS/blob/main/spec/odvs-timecode-v1.md)

## 🔬 Ohmic Labs — the hardware bench

My label for handmade test & measurement gear and electronics projects:

- 🌡️ **PT100 Simulator** — handheld RTD temperature simulator:
  ESP32 + OLED + rotary encoder, precision film resistors, −200 °C to
  +200 °C per IEC 60751, 18650-powered with USB-C charging. Built by
  hand, firmware in C++ (PlatformIO). *(repo going public once it's
  polished)*
- More on the bench: embedded builds around ESP32/Arduino, a vinyl BPM
  counter, and the analog front ends feeding into openDVS Rev A

## 🏠 Also running

- [k3s-homelab](https://github.com/fobiat/k3s-homelab) — home Kubernetes
  on k3s + Flux GitOps, deployed via GitHub Actions

## 🔧 Things I care about

- Real-time audio and DSP (the fun kind of hard)
- Vinyl and turntablism — keeping the feel, opening the tech
- Electronics: phono stages, converters, PCBs that hum only when they should
- Test gear you can trust because you built and calibrated it yourself
- Open licensing done properly — copyleft + open hardware + open formats

## 📫 Contact

**kyle@ohmic-labs.co.uk**

---
<sub>🐧 Arch Linux, naturally.</sub>
