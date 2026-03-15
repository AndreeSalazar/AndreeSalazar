<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&pause=1000&color=00D9FF&center=true&vCenter=true&width=900&lines=Compiler+Developer+%26+OS+Architect;Creator+of+FastOS+%7C+ADead-BIB+%7C+PyDead-BIB;Python+→+x86-64+Native+%7C+0.305ms+%7C+No+Runtime;No+LLVM.+No+GCC.+No+Runtime.+No+GIL.;1M%2B+Entities+%40+75+FPS+GPU+Simulation;Rust+%7C+C%2B%2B+%7C+ASM+%7C+CUDA+%7C+Vulkan;Binary+Is+Binary+💀🦈" alt="Typing SVG" />
</div>

<h1 align="center">👋 Eddi Andreé Salazar Matos</h1>

<p align="center">
  <strong>Compiler Developer & OS Architect</strong>
  <br/>
  <em>Building compilers, operating systems, and GPU engines from scratch — no LLVM, no GCC, no frameworks</em>
  <br/>
  <sub>Lima, Perú 🇵🇪 | 6+ years Systems R&D | Binary Is Binary 💀🦈</sub>
</p>

<p align="center">
  <a href="https://andreesalazar.github.io/PersonalPortafolio">
    <img src="https://img.shields.io/badge/🌐_Portfolio-Live_Demos-00D9FF?style=for-the-badge&labelColor=000000" alt="Portfolio"/>
  </a>
  <a href="mailto:eddi.salazar.dev@gmail.com">
    <img src="https://img.shields.io/badge/📧_Email-Contact-FF6B6B?style=for-the-badge&labelColor=000000" alt="Email"/>
  </a>
  <a href="https://www.youtube.com/@Qdantex">
    <img src="https://img.shields.io/badge/▶️_YouTube-Tech_Demos-FF0000?style=for-the-badge&labelColor=000000" alt="YouTube"/>
  </a>
  <a href="https://linkedin.com/in/andreé-salazar-0b1b81304">
    <img src="https://img.shields.io/badge/💼_LinkedIn-Connect-0077B5?style=for-the-badge&labelColor=000000" alt="LinkedIn"/>
  </a>
</p>

---

## 💀 The Ecosystem — Dead-BIB Family

> *"Binary Is Binary — no runtime, no intermediaries, no excuses"*

| Project | Language | Output | Key Achievement |
|---------|----------|--------|-----------------|
| **ADead-BIB v8.0** | C / C++ | x86-64 native | 354,134 lines proven IR |
| **PyDead-BIB v4.0** | Python | x86-64 native | 0.305ms · no CPython · no GIL |
| **FastOS v4.0** | C / ASM | Bare metal | 89KB kernel · boots in QEMU |
| **Metal-Dead** | Python | Native AI | 0.60MB AI · no PyTorch |

---

## 🆕 PyDead-BIB v4.0 — JIT Killer

> **Python → x86-64 native. No CPython. No LLVM. No GCC. No runtime. No GIL.**

```
pyb run archivo.py    # compile → RAM → execute → 0.305ms
```

| | CPython 3.13 | PyPy 7.3 | Nuitka | **PyDead-BIB** |
|---|---|---|---|---|
| Runtime | ❌ 30MB | ❌ 200MB | ❌ 8MB | ✅ **0 bytes** |
| GIL | ❌ | ❌ | ❌ | ✅ **eliminated** |
| No LLVM/GCC | ✅ | ✅ | ❌ | ✅ |
| AVX2 SIMD | ❌ | ❌ | ❌ | ✅ **auto** |
| UB compile-time | ❌ | ❌ | ❌ | ✅ **13+ types** |
| Hello World | 30MB | 200MB | 8MB | **~2KB** |
| Startup | ~50ms | ~2000ms | ~10ms | **0.305ms** |

**JIT Killer v2.0:**
```
"The CPU doesn't think — it already knows.
 The RAM doesn't wait — it already receives."

Pre-resolved dispatch table → instant image → VirtualAlloc → JMP
CPU features: AVX2 ✓ SSE4.2 ✓ BMI2 ✓
GPU: RTX 3060 → 24,119 GFLOPS from compiled Python
86/86 tests PASS
```

→ **[github.com/AndreeSalazar/PyDead-BIB](https://github.com/AndreeSalazar/PyDead-BIB)**

---

## 🖥️ FastOS — OS from Scratch

```
FastOS v4.0 — QEMU boot:

CPU: AuthenticAMD ✅
BG:  KERNEL Ring0 APPROVE ✅
AVX2 SSE4.2 AES ✅
PIC OK  PIT 100hz ✅

MBR:    512 bytes (FASM)
Kernel: 65,536 bytes (C99) ← 64KB kernel
Image:  10,485,760 bytes
```

16→256 bit gradual CPU wake — no Linux, no Windows — bare metal.

---

## 🚀 What I Build

<table>
<tr>
<td width="50%">

### ⚡ Compilers & Toolchains
- **ADead-BIB** — C/C++ → x86-64 native
- **PyDead-BIB** — Python → x86-64 native
- No LLVM. No GCC. No linker. No runtime.
- IR ADeadOp SSA — own design
- PE / ELF / FastOS .po output

</td>
<td width="50%">

### 🖥️ Operating Systems
- **FastOS** (2019-2026) — complete OS
- Custom bootloader (FASM)
- 64KB C99 kernel
- Memory, scheduling, interrupts
- Boots in QEMU ✅

</td>
</tr>
<tr>
<td width="50%">

### 🎮 GPU Computing & Graphics
- **GPU-Driven Sim**: 1M entities @ 75 FPS
- **REACTOR**: Vulkan (98% less boilerplate)
- **EPICX**: DirectX 12 framework
- CUDA kernels, compute shaders
- RTX 3060: 24,119 GFLOPS

</td>
<td width="50%">

### 🔥 Performance Engineering
- SIMD AVX2 auto-vectorization
- JIT Killer v2.0 — 0.305ms
- UB detection at compile time
- No GC, no runtime overhead
- Branchless, cache-friendly, deterministic

</td>
</tr>
</table>

---

## 💼 Professional Experience

```rust
struct EddI {
    title:  "Compiler Developer & OS Architect",
    years:  "6+ years (2019-2026)",
    location: "Lima, Perú 🇵🇪",
    
    compilers_built: vec![
        "ADead-BIB v8.0 — C/C++ → x86-64 (354K lines)",
        "PyDead-BIB v4.0 — Python → x86-64 (0.305ms)",
        "ADead-GPU — GPU deterministic compiler",
        "Zom — ADead-BIB + ROCm/HIP",
    ],
    
    os_built: vec![
        "FastOS v4.0 — complete OS, boots in QEMU",
        "Custom bootloader (FASM, 512 bytes MBR)",
        "64KB C99 kernel — memory, scheduler, IRQ",
    ],
    
    gpu_achievements: vec![
        "1,000,000 entities @ 75 FPS (RTX 3060)",
        "24,119 GFLOPS from compiled Python",
        "REACTOR: Vulkan 98% less boilerplate",
        "EPICX: DirectX 12 framework",
    ],
    
    philosophy: "Binary Is Binary — no intermediaries",
}
```

---

## 🛠️ Technical Arsenal

<div align="center">

### 🔧 Compilers & Low-Level
```
Rust (Advanced) • C / C++ • Assembly x86-64
Lexer / Parser / AST / IR / Codegen
PE / ELF binary generation — no linker
ISA x86-64 encoding • FASM • NASM
```

### 🖥️ Operating Systems
```
Bootloaders (FASM) • Kernels (C99)
Memory Management • Scheduling • Interrupts
x86-64 Long Mode • CPUID • APIC • PIT
Bare metal — no Linux — no Windows dependency
```

### 🎮 GPU & Graphics
```
Vulkan API • DirectX 12 • CUDA • wgpu
Compute Shaders • SPIR-V • HLSL • GLSL
GPU-Driven Architecture • Real-time Simulation
```

### ⚡ Performance
```
SIMD (AVX2 / SSE4.2 / BMI2)
JIT Killer v2.0 — VirtualAlloc executor
UB Detection — compile time
Deterministic execution • Cache optimization
```

</div>

---

## 🏆 Featured Projects

### 💀 Dead-BIB Compiler Family

<details>
<summary><b>PyDead-BIB v4.0 — Python Native Compiler</b> 🆕</summary>

**[github.com/AndreeSalazar/PyDead-BIB](https://github.com/AndreeSalazar/PyDead-BIB)**

First Python compiler generating native x86-64 without CPython, LLVM, GCC, or any runtime.

- **0.305ms** startup vs CPython's 50ms
- **2KB** Hello World vs 30MB CPython runtime  
- **JIT Killer v2.0**: pre-resolved dispatch, instant image, VirtualAlloc executor
- **13+ UB types** detected at compile time
- **AVX2 SIMD** auto-vectorization
- **CUDA + Vulkan** GPU dispatch from Python
- **24,119 GFLOPS** RTX 3060 from compiled Python
- **86/86 tests** PASS
- **Techne License v1.0** — free personal/OSS, 10% royalty commercial

```
"The CPU doesn't think — it already knows.
 The RAM doesn't wait — it already receives."
```

</details>

<details>
<summary><b>ADead-BIB v8.0 — C/C++ Native Compiler</b></summary>

**[github.com/AndreeSalazar/ADead-BIB](https://github.com/AndreeSalazar/ADead-BIB)**

Complete C/C++ compiler generating machine code without GCC, LLVM, or external linkers.

- **354,134 lines** of proven compiler infrastructure
- **IR ADeadOp SSA** — own design
- PE (Windows) + ELF (Linux) + FastOS .po output
- Full OOP: classes, inheritance, polymorphism, vtables
- UB detector: 21+ types
- 16 → 256 bit targets (SSE → AVX2)
- Binary Guardian stamp

</details>

<details>
<summary><b>FastOS v4.0 — Complete OS from Scratch</b></summary>

OS built from zero — boots in QEMU.

- Custom bootloader (FASM, 512 bytes MBR)
- 64KB C99 kernel
- Memory management, scheduler, interrupts
- AVX2 SSE4.2 AES detection at boot
- 16→256 bit gradual CPU wake
- Target: bare metal without Linux or Windows

</details>

---

### 🚀 GPU Computing

<details>
<summary><b>GPU-Driven Massive Simulation — 1M Entities @ 75 FPS</b></summary>

**[github.com/AndreeSalazar/GPU-Driven](https://github.com/AndreeSalazar/GPU-Driven)**

| Entities | Sim Time | FPS |
|----------|----------|-----|
| 100,000 | ~0.05ms | 120+ |
| 500,000 | ~0.10ms | 100 |
| **1,000,000** | **~0.14ms** | **75** |

Deterministic: same input → same output guaranteed.

</details>

<details>
<summary><b>REACTOR — Vulkan Framework (98% less boilerplate)</b></summary>

**[github.com/AndreeSalazar/REACTOR-Framework-for-Vulkan-](https://github.com/AndreeSalazar/REACTOR-Framework-for-Vulkan-)**

- Visual node editor (Blender-style)
- 150-330KB executables
- 0.36s load time
- Zero heap allocations at startup
- Hot-reload SPIR-V shaders

</details>

---

## 📊 GitHub Statistics

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=AndreeSalazar&show_icons=true&theme=react&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=C9D1D9&count_private=true" alt="GitHub Stats"/>
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=AndreeSalazar&theme=react&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF" alt="GitHub Streak"/>
</p>

<p align="center">
  <img width="70%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AndreeSalazar&layout=compact&theme=react&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=C9D1D9&langs_count=10&hide=jupyter%20notebook" alt="Top Languages"/>
</p>

---

## 🎓 Background

**Self-Directed Systems R&D (2019-2026)**
- 6+ years intensive compiler + OS + GPU development
- 50+ public repositories
- Production-quality deliverables

**Universidad Nacional Federico Villarreal**
- Computer Engineering (In Progress)
- Admission: Special modality (Law 29973)

---

## 💡 What Makes Me Different

```
Everyone uses LLVM.        I don't.
Everyone uses GCC.         I don't.
Everyone uses runtimes.    I don't.
Everyone keeps the GIL.    I removed it.
Everyone uses JIT to learn. Mine already knows.

354,134 lines of proven compiler infrastructure.
89KB OS kernel that boots.
Python executing in 0.305ms.
1M entities at 75 FPS.

1 developer. Lima, Perú. 🇵🇪
Binary Is Binary. 💀🦈
```

---

## 📫 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Live_Demos-00D9FF?style=for-the-badge&labelColor=000000)](https://andreesalazar.github.io/PersonalPortafolio)
[![Email](https://img.shields.io/badge/📧_Email-eddi.salazar.dev@gmail.com-FF6B6B?style=for-the-badge&labelColor=000000)](mailto:eddi.salazar.dev@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-Connect-0077B5?style=for-the-badge&labelColor=000000)](https://linkedin.com/in/andreé-salazar-0b1b81304)
[![YouTube](https://img.shields.io/badge/▶️_YouTube-Tech_Demos-FF0000?style=for-the-badge&labelColor=000000)](https://www.youtube.com/@Qdantex)

**💼 Open to: Compiler Engineering · OS Development · GPU Computing · Performance Engineering**

</div>

---

<div align="center">

```
ADead-BIB 💀 C/C++  →  PyDead-BIB 💀 Python  →  FastOS 💀 Bare Metal
                    IR ADeadOp SSA
                   Binary Is Binary
              Eddi Andreé Salazar Matos
                   Lima, Perú 🇵🇪
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=00D9FF&height=100&section=footer" alt="Footer"/>

</div>
