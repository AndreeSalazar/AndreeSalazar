<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00D9FF&center=true&vCenter=true&width=800&lines=Systems+Software+Engineer;OS+%26+Compiler+Developer;6%2B+Years+Building+Low-Level+Systems;Rust+%7C+C%2B%2B+%7C+ASM+%7C+CUDA+%7C+Vulkan;Creator+of+FastOS+%26+ADead-BIB+Compiler;1M%2B+Entities+%40+75+FPS+GPU+Simulation" alt="Typing SVG" />
</div>

<h1 align="center">👋 Eddi Andreé Salazar Matos</h1>

<p align="center">
  <strong>Systems Software Engineer | OS & Compiler Developer</strong>
  <br/>
  <em>Building operating systems, compilers, and high-performance GPU engines from scratch</em>
  <br/>
  <sub>Lima, Perú 🇵🇪 | 6+ years in Systems R&D (2019-2025)</sub>
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

## 🚀 What I Build

<table>
<tr>
<td width="50%">

### 🖥️ **Operating Systems**
- **FastOS** (2019-2026) - Complete OS from scratch
- Custom bootloader (GPU-First, Binary-First)
- Kernel: memory management, scheduling, interrupts
- Full stack: ADead-BIB + Rust + wgpu

</td>
<td width="50%">

### ⚡ **Compilers & Toolchains**
- **ADead-BIB** - x86-64 native code compiler
- **ADead-GPU** - GPU-focused deterministic compiler
- **Zom** - ADead-BIB + ROCm/HIP integration
- PE/ELF generation, FFI, deterministic runtimes

</td>
</tr>
<tr>
<td width="50%">

### 🎮 **GPU Computing & Graphics**
- **GPU-Driven Sim**: 1M entities @ 75 FPS
- **REACTOR**: Vulkan framework (98% less boilerplate)
- **EPICX**: DirectX 12 framework
- **Game Engine X**: Full DX12 game engine
- CUDA kernels, compute shaders, deterministic simulation

</td>
<td width="50%">

### 🔥 **Performance Engineering**
- **PyASM Trace Engine**: 40x Python speedups
- SIMD (AVX2), RDTSC timing (nanosecond precision)
- Branchless optimization, cache-friendly layouts
- Game engines (4 games: platformer, raycaster, fighter)
- Structure of Arrays, memory coalescing

</td>
</tr>
</table>

---

## 💼 Professional Experience

```rust
struct Career {
    role: "Systems Software Engineer (Independent R&D)",
    period: "2019 - 2025 (6 years)",
    focus: vec![
        "Operating Systems Development",
        "Compiler & Toolchain Engineering", 
        "GPU Computing & Graphics",
        "Performance Optimization",
    ],
    achievements: vec![
        "Built complete OS (FastOS) with custom bootloader + kernel",
        "Created production compiler generating x86-64 machine code",
        "1M+ entity GPU simulation @ 75 FPS deterministic",
        "40x Python speedups with Rust+ASM hybrid engine",
        "36+ public repositories spanning systems → full-stack",
    ],
}
```

**+ 6 years** as Office Assistant at EXTRA GAS S.A. (2018-2024) - Demonstrated professionalism and work ethic

---

## 🛠️ Technical Arsenal

<div align="center">

### 🔧 **Systems & Low-Level**
```
Rust (Advanced) • C/C++ • Assembly x86-64 • LLVM IR
Operating Systems • Bootloaders • Kernels • Memory Management
Compilers (Lexer/Parser/Codegen) • PE/ELF Binaries • Linking
```

### 🎮 **GPU & Graphics**
```
Vulkan API • DirectX 12 • wgpu • CUDA
Compute Shaders • SPIR-V • Pipelines • Instanced Rendering
Real-time Procedural Generation • GPU-Driven Architecture
```

### ⚡ **Performance & Optimization**
```
SIMD (SSE/AVX/AVX2) • RDTSC Profiling • Branchless Programming
Cache Optimization • Memory Alignment • Vectorization
Structure of Arrays • Memory Coalescing • Deterministic Computing
```

### 💻 **Full-Stack Development**
```
TypeScript • Python (pandas/PyO3) • JavaScript • Java
Angular • React • Vue • Node.js • PostgreSQL
Data Analysis • ETL Pipelines • E-commerce • Observability Systems
```

### 🔨 **DevOps & Tools**
```
Git • Cargo • CMake • Docker • CI/CD • NASM
Makefile • pnpm • Jupyter • Build Systems
```

</div>

---

## 🏆 Featured Projects

### 🖥️ **Operating System Development**

<details>
<summary><b>FastOS - Complete OS from Scratch (2019-2026)</b></summary>

**The Main Achievement** - A fully functional operating system built from zero

**Stack:** Rust, Assembly x86-64, wgpu, ADead-BIB, QEMU

**What it includes:**
- ✅ Custom bootloader (GPU-First, Binary-First OS)
- ✅ Complete kernel: paging, heap allocation, scheduling
- ✅ Interrupt handling (IDT, ISRs, IRQ)
- ✅ Process management (multitasking, context switching)
- ✅ System calls interface
- ✅ Graphics stack (wgpu integrated from kernel)
- ✅ Full development stack: ADead-BIB language + Rust runtime

**Why it matters:** Demonstrates deep understanding of computer architecture, hardware control, and systems programming at the most fundamental level.

</details>

---

### ⚡ **Compiler Engineering**

<details>
<summary><b>ADead-BIB - x86-64 Native Code Compiler (2023-Present)</b> ⭐ 1 star</summary>

**Repository:** [github.com/AndreeSalazar/ADead-BIB](https://github.com/AndreeSalazar/ADead-BIB)

Complete compiler generating machine code directly without external assemblers/linkers

**Features:**
- Direct PE (Windows) and ELF (Linux) binary generation
- Full OOP support (classes, inheritance, polymorphism, vtables)
- Python FFI for seamless interop with Python ecosystem  
- Deterministic runtime for perfect synchronization
- 70+ built-in functions, module system
- Minimal executables: 1.5 KB (Hello World) to 350 KB (full apps)
- 8-10x performance improvements

**Tech:** Rust, LLVM IR, x86-64 Assembly

</details>

<details>
<summary><b>ADead-GPU - GPU-Focused Deterministic Compiler (2024-2025)</b> ⭐ 1 star</summary>

**Repository:** [github.com/AndreeSalazar/ADead-GPU](https://github.com/AndreeSalazar/ADead-GPU)

Specialized compiler for deterministic GPU code generation with noise reduction

**Tech:** C++, Rust, CUDA

</details>

<details>
<summary><b>Zom - ADead-BIB + ROCm Integration (2024-2025)</b> ⭐ 1 star</summary>

**Repository:** [github.com/AndreeSalazar/Zom](https://github.com/AndreeSalazar/Zom)

ADead-BIB compiler with AMD GPU computing (ROCm/HIP)

**Tech:** Rust, HIP, ROCm

</details>

---

### 🚀 **GPU Computing & Massive Simulation**

<details>
<summary><b>GPU-Driven Massive Simulation Engine (2024-2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/GPU-Driven](https://github.com/AndreeSalazar/GPU-Driven)

Simulate **millions of entities in real-time** with deterministic behavior

**Achievements:**
- 🔥 **1,000,000 entities @ 75 FPS** on RTX 3060
- ⚡ Simulation time: 0.14ms (GPU compute)
- ✅ Deterministic: same input → same output guaranteed
- 🎯 GPU-driven architecture: GPU thinks, CPU orchestrates

**Performance Benchmarks:**
| Entities | Sim Time (GPU) | Frame Time | FPS |
|----------|----------------|------------|-----|
| 100,000  | ~0.05ms       | ~8ms       | 120+|
| 500,000  | ~0.10ms       | ~10ms      | 100 |
| 1,000,000| ~0.14ms       | ~13ms      | 75  |

**Tech:** Rust, CUDA, wgpu, Assembly (timing), real-time profiling

</details>

<details>
<summary><b>PyASM Trace Engine - Python Acceleration (2024-2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/Tracer_para_Python](https://github.com/AndreeSalazar/Tracer_para_Python)

Hybrid Python-Rust-ASM engine achieving **20-40x speedups**

**Features:**
- Automatic offloading of Python hot paths to native code
- SIMD (AVX2) vectorized operations
- RDTSC cycle-accurate timing (nanosecond precision)
- PyO3 bindings with decorator API (@offload, @trace)

**Real Benchmarks (100K elements, 100 iterations):**
- Python: 915.9 ms
- Rust: 22.6 ms → **40.5x speedup**
- ASM SIMD: 44.1 ms → **20.8x speedup**

**Tech:** Rust, Python (PyO3), Assembly (NASM), AVX2

</details>

---

### 🎮 **Graphics Frameworks & Game Engines**

<details>
<summary><b>REACTOR - Vulkan Framework (2024-2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/REACTOR-Framework-for-Vulkan-](https://github.com/AndreeSalazar/REACTOR-Framework-for-Vulkan-)

Ultra-lightweight Vulkan framework reducing boilerplate by **98%**

**Features:**
- Visual node editor (Blender Geometry Nodes style)
- Real-time procedural generation (Perlin noise, mesh extrusion, materials)
- Ultra-optimized: 150-330 KB executables, 0.36s load time
- Zero heap allocations during startup
- Hot-reload shaders (SPIR-V compilation)

**Tech:** Rust, Vulkan API, SPIR-V, Qt

</details>

<details>
<summary><b>EPICX - DirectX 12 Framework (2024-2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/EPICX-FRAMEWORK-DirectX12](https://github.com/AndreeSalazar/EPICX-FRAMEWORK-DirectX12)

High-level abstractions for DirectX 12 on Windows

**Tech:** C++, DirectX 12, HLSL

</details>

<details>
<summary><b>Game Engine X - Full DX12 Engine (2023-2024)</b></summary>

**Repository:** [github.com/AndreeSalazar/Game_Engine_X](https://github.com/AndreeSalazar/Game_Engine_X)

Complete game engine built with DirectX 12 for Windows

**Tech:** C++, DirectX 12, HLSL, CMake

</details>

<details>
<summary><b>VULKAN-FULL - Cross-Platform Engine (2024-2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/VULKAN-FULL](https://github.com/AndreeSalazar/VULKAN-FULL)

Multi-platform graphics engine using Vulkan for any OS

**Tech:** C++, Vulkan API, GLSL, CMake

</details>

<details>
<summary><b>Minimalist Vulkan Render Engine (2024-Present)</b></summary>

**Repository:** [github.com/AndreeSalazar/Motor-de-Render-Minimalista](https://github.com/AndreeSalazar/Motor-de-Render-Minimalista)

3D rendering engine built from scratch with C++ and Vulkan

**Features:**
- Complete graphics pipeline
- Real-time rendering capabilities
- Low-level GPU programming mastery

**Tech:** C++, Vulkan API, GLSL, CMake

</details>

<details>
<summary><b>Game-Rust-ASM - Deterministic 2D Game Engine (2023-2024)</b></summary>

**Repository:** [github.com/AndreeSalazar/Game-Rust-ASM](https://github.com/AndreeSalazar/Game-Rust-ASM)

**4 complete games** demonstrating different techniques:

1. **Physics 2D** - Platformer with custom physics
2. **Raycaster** - DOOM-style engine with DDA algorithm
3. **Massive Sim** - 5,000+ entities @ 60 FPS
4. **Fighting** - Frame-perfect input, hitbox system

**Architecture:**
- Rust orchestrates, ASM executes hot paths
- RDTSC timing (nanosecond precision)
- SIMD collision detection
- Custom ECS (Entity Component System)
- Fixed timestep deterministic @ 60 FPS
- Software rendering (no GPU dependency)

**Tech:** Rust, NASM x86-64, hecs, winit, softbuffer

</details>

---

### 💻 **Full-Stack & Data Engineering**

<details>
<summary><b>Portfolio Java - Full-Stack Hybrid (2024-2025)</b> ⭐ 1 star</summary>

**Repository:** [github.com/AndreeSalazar/Portfolio_Java](https://github.com/AndreeSalazar/Portfolio_Java)

Full-stack architecture combining Python + Java + Rust

**Tech:** Java, Python, Rust, PostgreSQL

</details>

<details>
<summary><b>Portfolio Python - Data Analyst Stack (2024-2025)</b> ⭐ 1 star</summary>

**Repository:** [github.com/AndreeSalazar/Portfolio_Python](https://github.com/AndreeSalazar/Portfolio_Python)

Complete data analysis portfolio with ETL pipelines and visualization

**Tech:** Python, pandas, numpy, Jupyter, matplotlib

</details>

<details>
<summary><b>Observabilidad-desde-Cero (2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/Observabilidad-desde-Cero](https://github.com/AndreeSalazar/Observabilidad-desde-Cero)

Complete observability system built from scratch with Rust + Java

**Tech:** Rust, Java, HTML

</details>

<details>
<summary><b>E-commerce pnpm (2024-2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/ecommerce-pnpm](https://github.com/AndreeSalazar/ecommerce-pnpm)

Full e-commerce application with modern monorepo structure

**Tech:** TypeScript, pnpm, Node.js, React

</details>

---

### 🔧 **Developer Tools**

<details>
<summary><b>Visual Editor - Node-Based Development (2024-2025)</b> ⭐ 1 star</summary>

**Repository:** [github.com/AndreeSalazar/visual-editor](https://github.com/AndreeSalazar/visual-editor)

Visual code editor for DEV and UI generalists

**Tech:** JavaScript, Node.js

</details>

<details>
<summary><b>Ultra-C++ - Code Generator (2024-2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/Ultra-C-](https://github.com/AndreeSalazar/Ultra-C-)

Automatic C++ file generator (cpp + header) for simplified development

**Tech:** C++

</details>

<details>
<summary><b>Navegador-GPU - GPU-First Browser (2024-2025)</b></summary>

**Repository:** [github.com/AndreeSalazar/Navegador-GPU](https://github.com/AndreeSalazar/Navegador-GPU)

Experimental browser with GPU-first rendering acceleration

**Tech:** Rust, GPU rendering

</details>

<details>
<summary><b>Omega Visual Editor (2024)</b></summary>

**Repository:** [github.com/AndreeSalazar/Omega-Visual-Semantic-Node-Based-Code-Editor](https://github.com/AndreeSalazar/Omega-Visual-Semantic-Node-Based-Code-Editor)

Node-based visual code editor with semantic understanding

**Tech:** Python, Qt, Node System

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

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=AndreeSalazar&theme=react-dark&hide_border=true&area=true&bg_color=0D1117&color=00D9FF&line=00D9FF&point=C9D1D9" alt="Activity Graph"/>
</p>

---

## 🎓 Education & Background

**🎓 Universidad Nacional Federico Villarreal** (Currently studying)
- 3rd Cycle - Computer Engineering (Ingeniería Informática)
- Faculty of Electronic and Computer Engineering
- Admission: Special modality (Law 29973) - Resolution Nº 1701-2023-UNFV (May 16, 2023)

**📚 Self-Directed Systems Programming (2019-2025)**
- 6+ years intensive R&D in operating systems, compilers, GPU computing
- Validated through 36+ production-quality open source projects
- Equivalent to senior-level professional experience

**📜 Technical Certifications**
- Graphic Design - Computer Science Specialization (CETPRO Márquez, 600 hours)
- Basic Electronics (ITEG, 120 hours)  
- Computer Assembly (ACRESOFT, 24 hours)

---

## 💡 What Makes Me Different

```typescript
const unique_value = {
  depth: "Not just frameworks - built an OS, compiler, and GPU engines from scratch",
  breadth: "36+ repos spanning systems programming → full-stack development",
  proven: "6 years of consistent R&D with production-quality deliverables",
  results: [
    "1M entities @ 75 FPS GPU simulation",
    "40x Python speedups with hybrid Rust-ASM",
    "Complete OS with custom bootloader + kernel",
    "Production compiler generating native x86-64 code"
  ],
  mindset: "Solve problems at the root level, optimize for both humans and machines"
};
```

---

## 🌱 Currently

- 🔭 Actively developing FastOS and ADead-BIB compiler ecosystem
- 🌐 Exploring WebAssembly for high-performance web applications
- 📚 Deepening expertise in GPU architecture and parallel computing
- 💼 **Open to full-time opportunities** in Systems Engineering, Compiler Development, Graphics Programming, or Performance-Critical Applications

---

## 📫 Let's Connect

<div align="center">

[![Portfolio Website](https://img.shields.io/badge/🌐_Portfolio-Visit_Live_Demos-00D9FF?style=for-the-badge&labelColor=000000)](https://andreesalazar.github.io/PersonalPortafolio)
[![Email](https://img.shields.io/badge/📧_Email-eddi.salazar.dev@gmail.com-FF6B6B?style=for-the-badge&labelColor=000000)](mailto:eddi.salazar.dev@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-Connect-0077B5?style=for-the-badge&labelColor=000000)](https://linkedin.com/in/andreé-salazar-0b1b81304)
[![YouTube](https://img.shields.io/badge/▶️_YouTube-Tech_Demos-FF0000?style=for-the-badge&labelColor=000000)](https://www.youtube.com/@Qdantex)
[![Instagram](https://img.shields.io/badge/📸_Instagram-qmachus-E4405F?style=for-the-badge&labelColor=000000)](https://www.instagram.com/qmachus/)

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=AndreeSalazar&color=00D9FF&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views"/>
  
  <br/><br/>
  
  **💼 Available for Full-Time Positions & Technical Collaborations**
  
  <br/>
  
  <sub>⭐ If you find my work interesting, star some repos and let's build something amazing together!</sub>
  
  <br/><br/>
  
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00D9FF&height=100&section=footer" alt="Footer Wave"/>
</div>
