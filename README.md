# Serge Rabyking

Open silicon, built new in the open: imaging hardware from NumPy models, raw sensor transport over HDMI, and one engine for the file formats every EDA tool re-implements.

**Speaking at [ORConf 2026](https://orconf.org/)** — Ghent, September 11–13.

## Building

- **[np2hw](https://github.com/lanserge/np2hw)** — NumPy image-processing
  models compiled to synthesisable, readable Verilog, held bit-exact
  against the model by an example suite that proves every capability.
  Ships as a FuseSoC generator — cores generate inside the consuming
  SoC's own build.
- **[bayerlink](https://github.com/bayerlink/bayerlink)** — raw sensor
  data over any HDMI/DVI link: a self-describing protocol with conformance
  vectors, and tooling that closes the loop on a $10 capture stick.
- **[rawast](https://github.com/edacommons/rawast)** — one bidirectional,
  grammar-driven engine for the file formats every EDA tool re-implements:
  GDSII, LEF/DEF, Tcl, SystemVerilog. Grammars are data; the PoC parses
  100% of a 3,132-file production corpus.
- **Setun-HDL** — the Setun-1958, history's only production ternary computer,
  reimplemented in Amaranth: CPU, ternary ALU, full toolchain, verified on a
  Tang Nano 9K. A book is in preparation; the source opens with it.

## Background

Thirty-plus years of software coupled tightly to hardware. Twelve years at
Apical (acquired by Arm) working on image signal processing IP that shipped
in production cameras — patent
[US10063787B2](https://patents.google.com/patent/US10063787B2). Doctoral
research in logic optimisation (SAT) at Loughborough; applied mathematics at
MIPT. Merged upstream patches in open EDA tools.

## Working with me

Consulting — ISP bring-up, imaging pipelines, EDA tooling — and
[GitHub Sponsors](https://github.com/sponsors/lanserge), where sponsorship
funds named capability targets that land open, with your name on the
release. **s.rabykin@gmail.com** · [serge.rabyking.com](https://serge.rabyking.com)
