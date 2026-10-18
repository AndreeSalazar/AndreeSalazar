<div align="center">

# Eddi Andree Salazar Matos

**Operating systems, firmware and compilers — built from the boot sector up.**

Lima, Peru · [Portfolio](https://andreesalazar.github.io/Personal-Portafolio/) · [Email](mailto:eddi.salazar.dev@gmail.com) · [LinkedIn](https://linkedin.com/in/andre%C3%A9-salazar-0b1b81304) · [YouTube](https://www.youtube.com/@Qdantex)

</div>

---

## Featured

| | Project | What it proves |
|---|---|---|
| **1** | **[BMO-X](https://github.com/AndreeSalazar/BMO-X-x86-64)** | A whole machine of my own: UEFI boot, kernel, drivers, desktop, filesystem and six language paths — running on a real Ryzen |
| **2** | **[TALK-CPU](https://github.com/AndreeSalazar/TALK-CPU-x86-64)** | x86-64 machine code written by hand, byte by byte, booted on my own PC |

---

## [BMO-X](https://github.com/AndreeSalazar/BMO-X-x86-64) — an independent x86-64 system, from the firmware to its own languages

<p align="center">
  <img src="https://raw.githubusercontent.com/AndreeSalazar/BMO-X-x86-64/main/docs/evidencia/23-globo-del-puntero.png" alt="BMO-X desktop running on the Ryzen, with its RTX 3060 status bubble" width="100%">
  <br><sub>BMO-X's own desktop, on the real machine.</sub>
</p>

My current work. Its design is **Bare Metal Orquestal**: programs declare what
they need, the system grants capabilities, and the kernel only checks.
It runs on an **AMD Ryzen 5 5600X with an RTX 3060**, not in an emulator.

| Part | What it does |
|---|---|
| **Kernel** | Capability-based isolation behind **two frozen syscalls** (`INVOKE`, `WAIT`); UEFI → Ring 0 → Ring 3 |
| **Languages** | **Six native paths** — C, C++, COBOL, Ada, and two of my own: **TITAN++** and **INTI** — emitting x86-64 without LLVM or GCC backends |
| **Graphics** | **VERRANO**, its own drawing API, with a CPU reference path and an RTX 3060 driver written in-house |
| **Storage** | **ESTRATOS**, a versioned filesystem; branch and merge compare nodes by BLAKE3 |
| **Desktop** | Windows, tools, PNG capture, and **MUNDO** — a native block game written in TITAN++, played on the Ryzen |
| **Compatibility** | **PROTON-X** loads Windows PE programs; it displayed the Cyberpunk 2077 intro on BMO-X (CPU-rendered, not playable) |

Source, documentation and hardware evidence are public under Apache-2.0.
Open limits are stated, not hidden: GPU firmware startup on the RTX
(**case 0x15**) is still under investigation.

---

## [TALK-CPU](https://github.com/AndreeSalazar/TALK-CPU-x86-64) — hand-written x86-64, booted on real hardware

No compiler, no assembler: the instructions are written byte by byte in `.hex`.
A minimal UEFI bridge loads them from FAT32, calls `ExitBootServices` and jumps
into my own 64-bit code, which draws straight to the framebuffer.

On **October 18, 2026** it booted on the target machine — an **MSI A320M-A PRO MAX
with a Ryzen 5 5600X** — on the first physical attempt:

<img src="https://raw.githubusercontent.com/AndreeSalazar/TALK-CPU-x86-64/main/EVIDENCIAS/PC_REAL/PRIMER_ARRANQUE/02-saludo-metal64.png" alt="Hand-written x86-64 code printing on the real Ryzen machine" width="480">

It also ships **Flappy Metal**, a playable game (gravity, pipes, collisions,
score) in **4,088 bytes** of hand-written machine code, running in QEMU.

---

## Polyglot by necessity

I didn't collect languages; BMO-X demanded them. Building a machine end to end
means meeting each layer in the language it actually speaks — and for most of
them, **writing the compiler, not just the code**.

| Language | Where it was forced on me |
|---|---|
| **Rust** | The kernel, drivers, filesystem and every compiler in BMO-X |
| **x86-64 machine code** | Instruction encoders for every backend; TALK-CPU written directly in `.hex` |
| **C** | A native C path in BMO-X, and [ADead-BIB](https://github.com/AndreeSalazar/ADead-BIB), a C99 compiler with its own PE/ELF linker |
| **C++** | A native C++ path in BMO-X |
| **COBOL** | Exact decimal arithmetic — the primitive banking software is built on |
| **Ada** | Strict typing and checked contracts as a native path |
| **TITAN++ · INTI** | Languages I designed for BMO-X; MUNDO is written in TITAN++ |
| **GPU / shaders** | VERRANO, the BSF shader format, Vulkan, DirectX 12 |
| **PowerShell** | The build and deployment pipeline |
| **TypeScript · Java · Python** | Web and tooling: React, Next.js, Angular, Spring Boot |

---

## How it is verified

This is the part I care most about.

The compilers are tested by **executing the emitted machine code** and checking
the real output — not by comparing against hand-written byte strings. An `IF`
that fails to branch looks identical to one that works in a byte dump; the only
way to tell them apart is to run them.

The order of authority is written down and enforced:

1. **The real CPU**
2. The specification document
3. The emulator

When the emulator and the hardware disagree, *the emulator gets fixed*.
Every claim in BMO-X is labeled **METAL** (seen on the Ryzen), **HOST**
(checked on the development machine) or **OPEN** (not solved yet).
Features that aren't implemented are **rejected with a reason**, never stubbed
to look like they work.

---

## Earlier work

| Project | What it is |
|---|---|
| **[ADead-BIB](https://github.com/AndreeSalazar/ADead-BIB)** | C99 compiler emitting x86-64 directly. Own IR, PE and ELF output, own linker for .dll/.so — no LLVM, GCC or NASM. |
| **[UE5 Fast Startup Accelerator](https://github.com/AndreeSalazar/Proyecto-UE5-Fast-Startup-Accelerator)** | Rust CLI that reads Unreal Engine 5.0–5.8 assets without the editor. 8,865 assets hashed and cached in 813 ms. |
| **[REACTOR](https://github.com/AndreeSalazar/REACTOR-Framework-for-Vulkan-)** | Experimental game engine in Rust on Vulkan, with an asset CLI and Blender bridge. |
| **[EPICX](https://github.com/AndreeSalazar/EPICX-FRAMEWORK-DirectX12)** | DirectX 12 framework for Rust with React-style components. 446 FPS average on an RTX 3060. |
| **[PyDead-BIB](https://github.com/AndreeSalazar/PyDead-BIB)** | Python frontend with a Vulkan compute backend for AI workloads. |
| **[ORBITA](https://github.com/AndreeSalazar/ORBITA)** | Web platform for running and monitoring jobs: Next.js, Spring Boot gateway, Rust engine. |

These are research projects, not products. They are public so the code can be
read and judged directly.

---

## Background

**Independent systems R&D** — compilers, operating systems and GPU work,
self-directed and built alone. The commit history is public.

## Open to

Compiler engineering · Systems and OS development · Graphics and GPU ·
Performance engineering · Remote work

If you want to check whether any of this is real, the fastest way is to
read the evidence and run the code. That's what it's there for.
