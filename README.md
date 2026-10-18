# Eddi Andree Salazar Matos

**Compilers and operating systems, written from scratch. No LLVM, no GCC.**

Lima, Peru · [Portfolio](https://andreesalazar.github.io/Personal-Portafolio/) · [Email](mailto:eddi.salazar.dev@gmail.com) · [LinkedIn](https://linkedin.com/in/andre%C3%A9-salazar-0b1b81304) · [YouTube](https://www.youtube.com/@Qdantex)

---

## [BMO-X](https://github.com/AndreeSalazar/BMO-X-x86-64) — a bare-metal system that runs COBOL, C and Ada on real hardware

My current work. A microkernel with a **frozen surface of three syscalls**, a
capability-based security model, and three native compilers — all written in
Rust from scratch.

It boots on an **AMD Ryzen 5 5600X**, not in an emulator, and occupies
**5.4 MiB of 14.8 GiB of RAM**.

| | |
|---|---|
| **Kernel** | 3 syscalls, capabilities, preemptive scheduling, Ring 0 ↔ Ring 3, demand paging, copy-on-write |
| **Drivers** | USB keyboard (xHCI + HID), AHCI/SATA, GPT, FAT32 — all written from scratch |
| **Compilers** | COBOL, C and Ada, each emitting x86-64 machine code directly to a native binary format |
| **Filesystem** | Content-addressed, copy-on-write, BLAKE3 — writing is committing |

**Exact decimal arithmetic**: `19.99 × 3 = 59.97`, computed in integer scale
and confirmed on silicon. That is the primitive banking software is built on,
and it is why COBOL never died.

Source, docs and build instructions are public under Apache-2.0:
**[github.com/AndreeSalazar/BMO-X-x86-64](https://github.com/AndreeSalazar/BMO-X-x86-64)**

---

## How it is verified

This is the part I care most about, and it is unusual enough to state plainly.

The compilers are tested by a **conformance matrix that executes the emitted
machine code** and checks the real output — not by comparing against
hand-written byte strings. An `IF` that fails to branch looks identical to one
that works in a byte dump; the only way to tell them apart is to run them.

And the order of authority is written down and enforced:

1. **The real CPU**
2. The specification document
3. The emulator

When the emulator and the hardware disagree, *the emulator gets fixed*. That
rule caught a broken `lea [rip+disp]` that passed green in simulation and
would have read garbage on real silicon.

Features that aren't implemented are **rejected with a reason**, never stubbed
to look like they work.

---

## Earlier work

| Project | What it is |
|---|---|
| **[ADead-BIB](https://github.com/AndreeSalazar/ADead-BIB)** | C99 compiler emitting x86-64 directly. Own IR, PE and ELF output, own linker for .dll/.so — no LLVM, GCC or NASM. |
| **[UE5 Fast Startup Accelerator](https://github.com/AndreeSalazar/Proyecto-UE5-Fast-Startup-Accelerator)** | Rust CLI that reads Unreal Engine 5.0–5.8 assets without the editor. 8,865 assets hashed and cached in 813 ms. |
| **[PyDead-BIB](https://github.com/AndreeSalazar/PyDead-BIB)** | Compiles a subset of Python to native x86-64 — no CPython, no LLVM, no runtime in the output binary. |
| **[REACTOR](https://github.com/AndreeSalazar/REACTOR-Framework-for-Vulkan-)** | Vulkan framework with a visual node editor. Small executables, no heap allocation at startup. |
| **[EPICX](https://github.com/AndreeSalazar/EPICX-FRAMEWORK-DirectX12)** | DirectX 12 framework in Rust with React-style components. 446 FPS average on an RTX 3060. |
| **[ASM-BIB](https://github.com/AndreeSalazar/ASM-BIB)** | x86-64 assembler. |

These are research projects, not products. They are public so the code can be
read and judged directly.

---

## What I actually do

- **Compiler backends without LLVM** — lexing, parsing, IR design, instruction
  selection, x86-64 encoding, ABI and calling conventions, binary formats
- **Bare-metal systems** — UEFI boot chains, GDT/IDT, paging, schedulers,
  capability-based security, driver development against real hardware
- **Debugging where there is no debugger** — when a machine boots to a black
  screen, the only tools are serial output, a specification, and reasoning

**Languages**: Rust, C, C++, x86-64 assembly, Python, Java

I also build web apps — React, Next.js, Angular, TypeScript, Spring Boot —
for example **[ORBITA](https://github.com/AndreeSalazar/ORBITA)** (Next.js + Spring Boot gateway + Rust engine).

---

## Background

**Independent systems R&D** — compilers, operating systems and GPU work,
self-directed. Everything above was built alone, and the commit history is
public.

**Universidad Nacional Federico Villarreal** — Computer Engineering, in
progress.

---

## Open to

Compiler engineering · Systems and OS development · Performance engineering ·
Remote work

If you want to check whether any of this is real, the fastest way is to
download a compiler and run it. That's what it's there for.
