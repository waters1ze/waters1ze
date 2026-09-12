<div align="center">

<img src="assets/terminal.svg?v=4" width="100%" alt="waters1ze Terminal" />

<br/><br/>

<p align="center">
  <a href="https://github.com/datara-lang/datara"><img src="https://img.shields.io/badge/Language-Datara-E3B341?style=for-the-badge&logo=codeforces&logoColor=white" alt="Datara Language" /></a>
  <a href="https://github.com/datara-lang"><img src="https://img.shields.io/badge/Organization-datara--lang-181717?style=for-the-badge&logo=github&logoColor=white" alt="Datara Organization" /></a>
  <a href="https://github.com/datara-lang/sparks"><img src="https://img.shields.io/badge/Registry-Sparks-2563EB?style=for-the-badge&logo=box&logoColor=white" alt="Sparks Package Registry" /></a>
  <a href="https://github.com/github-linguist/linguist/pull/8189"><img src="https://img.shields.io/badge/Linguist-PR_%238189-F59E0B?style=for-the-badge&logo=git&logoColor=white" alt="Linguist PR" /></a>
</p>

</div>

---

### Systems Architecture & Computer Science

Systems programmer and compiler engineer focused on programming language semantics, intermediate representations, low-latency execution runtimes, and compile-time memory safety without garbage collection.

* **Language Design & Semantics**: Creator and lead architect of **[Datara](https://github.com/datara-lang/datara)** (`.dtr`). Developed an affine ownership model that eliminates runtime GC pauses and manual lifetime annotations through lexical scoping and formal static proofs.
* **Compiler Pipelines & SSA IR**: Architected the `forgen` multi-backend compiler pipeline. Built SSA-based intermediate representations (DMIR) with formal optimization passes including SROA (Scalar Replacement of Aggregates), Mem2Reg, Bound-Check Elimination (BCE), and Common Subexpression Elimination (CSE).
* **Dual Execution Engines**: Integrated **Cranelift** for sub-50ms instant JIT developer feedback alongside **LLVM AOT** (`-O3 -flto`) for peak vectorized machine code execution and **WebAssembly** for sandboxed runtimes.
* **Modern Tooling & Language Infrastructure**: Extensive engineering experience across **TypeScript**, **JavaScript**, and **Node.js** runtimes — authoring language tooling, AST parsers, TextMate grammar specifications, and LSP infrastructure.
* **Cryptographic Security & Package Ecosystems**: Designed **[Sparks](https://github.com/datara-lang/sparks)**, an Ed25519-signed decentralized package manager with capability-guarded sidecars (`.capabilities.json`) preventing supply-chain attacks.

---

### Ecosystem & Projects

| Project | Architecture & Role | Stack | Link |
|:---|:---|:---|:---:|
| **Datara Compiler** | Author & Lead Architect &bull; Deterministic systems language compiler with affine memory model and dual Cranelift/LLVM backends | Rust, Cranelift, LLVM, C++ | [datara-lang/datara](https://github.com/datara-lang/datara) |
| **Sparks Registry** | Author & Architect &bull; Decentralized, Ed25519-signed capability-native package management infrastructure | Python, Cryptography, Rust | [datara-lang/sparks](https://github.com/datara-lang/sparks) |
| **Datara Grammar** | Author & Maintainer &bull; TextMate syntax specification and grammar definitions for VS Code and GitHub Linguist | TypeScript, JSON, TextMate | [datara-lang/datara-grammar](https://github.com/datara-lang/datara-grammar) |

---

### Technical Competencies

#### Core Languages
<p>
  <img src="https://img.shields.io/badge/Datara-E3B341?style=flat-square&logo=codeforces&logoColor=white" alt="Datara" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white" alt="WebAssembly" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
</p>

#### Compilers, IRs & Low-Level Tooling
<p>
  <img src="https://img.shields.io/badge/LLVM_Infrastructure-181717?style=flat-square&logo=llvm&logoColor=white" alt="LLVM" />
  <img src="https://img.shields.io/badge/Cranelift_JIT-2563EB?style=flat-square&logo=fastapi&logoColor=white" alt="Cranelift" />
  <img src="https://img.shields.io/badge/SSA_DMIR-334155?style=flat-square&logo=diagram-next&logoColor=white" alt="SSA IR" />
  <img src="https://img.shields.io/badge/Clang_/_GCC-1E293B?style=flat-square&logo=cplusplus&logoColor=white" alt="Clang" />
  <img src="https://img.shields.io/badge/GDB_/_LLDB-0F172A?style=flat-square&logo=gnubash&logoColor=white" alt="Debuggers" />
</p>

#### Systems & Infrastructure
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Linux_Kernel-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/POSIX_APIs-000000?style=flat-square&logo=gnubash&logoColor=white" alt="POSIX" />
  <img src="https://img.shields.io/badge/Git_VCS-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions" />
</p>

---

<div align="center">
  <sub>Maintained by waters1ze &bull; Creator and Lead Architect of the Datara Language Project</sub>
</div>
