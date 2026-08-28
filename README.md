# RISC-V Assembly Language Programming — ESP32-C3 & QEMU

Academic course material prepared for teaching **RISC-V assembly programming** using two complementary platforms:

- **ESP32-C3 (RV32IMC)** for embedded, hardware-oriented learning
- **QEMU + Fedora RISC-V (RV64)** for virtualized 64-bit experimentation and debugging

The material was prepared for academic instruction at **Ming Chi University of Technology (MCUT)** under the guidance of **Prof. Yi-Chih Tung**.

## Course Contents

| Module | Topic |
|---|---|
| 00 | Course overview and RISC-V introduction |
| 01 | Introduction to RISC-V assembly |
| 02 | ESP32-C3 and ESP-IDF setup |
| 03 | QEMU RISC-V setup |
| 04 | RISC-V architecture |
| 05 | Getting started: C and assembly integration |
| 06 | Load and store operations |
| 07 | Calling convention |
| 08 | Flow control and branching |
| 09 | Basic opcodes |
| 10 | Multiply and divide operations |

## Repository Structure

```text
course/          Chapter slide decks (00–10)
```

## Recommended Use

1. Start with `course/00_Course_Overview.pptx`.
2. Complete the ESP32-C3 / ESP-IDF and QEMU setup modules.
3. Follow Chapters in sequence for architecture and assembly programming concepts.

## Reference Textbook

This course was developed with reference to Warren Gay, **RISC-V Assembly Language Programming using ESP32-C3 and QEMU**, Elektor.

See `REFERENCES.md` for the source link and attribution.

## Notes

- The original textbook PDF is **not included** in this repository.
- Setup commands and software versions in the slides reflect the course-preparation environment; check current ESP-IDF and QEMU documentation if a command has changed.
- Please verify permission and attribution requirements before redistributing any third-party figures or excerpts contained in teaching slides.
