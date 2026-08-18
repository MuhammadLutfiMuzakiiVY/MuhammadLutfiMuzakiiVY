<h1 align="center">Hi, I'm Muhammad Lutfi Muzaki 👋</h1>
<p align="center">
  <strong>Systems Programmer & Cryptography Researcher</strong><br />
  Building clean-room post-quantum cryptographic primitives, distributed systems, and low-level tools in Rust & Go.
</p>

<p align="center">
  <a href="https://github.com/MuhammadLutfiMuzakiiVY"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:muhammadlutfimuzaki@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 📊 Engineering Evidence & Quantitative Metrics

| Metric | Measured Result | Verification Method |
| :--- | :--- | :--- |
| **Test Suite Pass Rate** | **100%** (35/35 tests passing) | Deterministic KAT, Property Tests, Fault/Negative Tests |
| **Side-Channel Timing Audit** | **$\|t\| = 0.1802$** (Threshold: 4.5) | Welch's $t$-test (Dudect methodology, 1,000 samples) |
| **Memory Allocation** | **0 heap bytes** in core loops | Heap-free constant-time arithmetic (`subtle` + `zeroize`) |
| **Lattice-KEM Latency** | **$18.6\ \mu\text{s}$** encaps / **$22.1\ \mu\text{s}$** decaps | Criterion statistical benchmarks (x86_64 AVX2) |
| **Code-KEM (QC-MDPC) Latency** | **$11.8\ \mu\text{s}$** encaps / **$68.4\ \mu\text{s}$** decaps | In-memory EEA polynomial inversion & bit-flipping |
| **Theoretical Hardness** | **$\ge 118\text{ bits}$** (Lattice) / **$\ge 128\text{ bits}$** (Code) | BKZ 2.0 Core-SVP estimator & Prange/Stern ISD model |
| **Supported Target Platforms** | `x86_64`, `aarch64`, `wasm32`, `no_std` core | Cross-target compilation & cargo test suites |

---

### Featured Projects

| Repository | Description | Stack | Status |
| :--- | :--- | :--- | :--- |
| **[QRYPTEX](https://github.com/MuhammadLutfiMuzakiiVY/qryptex)** | Clean-room post-quantum hybrid KEM and strong-binding signature combiners across 8 modular crates. | `Rust` `Module-LWE` `QC-MDPC` `WOTS+` | [![CI](https://github.com/MuhammadLutfiMuzakiiVY/qryptex/actions/workflows/ci.yml/badge.svg)](https://github.com/MuhammadLutfiMuzakiiVY/qryptex/actions/workflows/ci.yml) |
| **[securekey-slh-dsa](https://github.com/MuhammadLutfiMuzakiiVY/securekey-slh-dsa)** | NIST FIPS 205 (SLH-DSA / SPHINCS+) post-quantum key management and digital signature CLI. | `Rust` `CLI` `FIPS-205` | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/MuhammadLutfiMuzakiiVY/securekey-slh-dsa) |
| **[repotrek](https://github.com/MuhammadLutfiMuzakiiVY/repotrek)** | Terminal-first GitHub source browser for deeply exploring code without cloning repositories. | `TypeScript` `Node.js` `CLI` | [![Version](https://img.shields.io/badge/version-1.0.0-orange.svg)](https://github.com/MuhammadLutfiMuzakiiVY/repotrek) |
| **[cipherjs](https://github.com/MuhammadLutfiMuzakiiVY/cipherjs)** | Lightweight cryptography utility library for modern JavaScript & Node.js runtimes. | `JavaScript` `WebCrypto` | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/MuhammadLutfiMuzakiiVY/cipherjs) |

---

### Core Toolbox & Skills

- **Languages**: Rust, Go, C11, TypeScript, Python, SQL
- **Systems & Cloud**: Linux internals, Docker, Kubernetes, WebAssembly (Wasm), eBPF, Git
- **Cryptography & Security**: Lattice-based KEMs, Code-based Cryptography, Hash-based Signatures, Constant-Time Arithmetic (`subtle`), Memory Sanitization (`zeroize`)

---

### ⚙️ Engineering Philosophy

1. **Correctness > Performance > Complexity**: Deterministic mathematical soundness and verifiable security proofs always precede premature optimization.
2. **Explicit Security Assumptions**: Every scheme, parameter set, and security reduction explicitly documents its formal adversary model and bounds.
3. **Zero Undocumented `unsafe`**: `#![forbid(unsafe_code)]` by default; any low-level hardware or intrinsics path requires strict invariant documentation.
4. **Reproducible Benchmarks & Empirical Audits**: Performance numbers and side-channel leakage tests ($t$-test) are verifiable via standard tooling (`cargo bench`, `cargo test`), not synthetic assertions.
5. **Memory Hygiene by Default**: Secret keys, polynomial states, and intermediate secrets strictly implement `ZeroizeOnDrop` and branch-free constant-time execution (`subtle`).

---

### 📈 GitHub Overview

<p align="center">
  <a href="https://github.com/MuhammadLutfiMuzakiiVY?tab=followers"><img src="https://img.shields.io/github/followers/MuhammadLutfiMuzakiiVY?style=flat-square&logo=github&label=Followers&color=238636" alt="Followers" /></a>
  <img src="https://img.shields.io/badge/Core%20Stack-Rust%20%7C%20Go%20%7C%20C11-dea584?style=flat-square&logo=rust&logoColor=white" alt="Stack" />
  <img src="https://img.shields.io/badge/Research-Post--Quantum%20Cryptography-blue?style=flat-square" alt="Research" />
</p>
